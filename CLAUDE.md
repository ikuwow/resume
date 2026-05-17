# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is ikuwow's resume repository that generates both Japanese and English resume PDFs from Markdown files using md-to-pdf.

## Common Development Commands

### Build Commands
- `npm run pdf` - Generate Japanese PDF (creates ikuwow_resume.ja.pdf)
- `npm run pdf-en` - Generate English PDF (creates ikuwow_resume.en.pdf)

### Watch Commands (for development)
- `npm run pdf-watch` - Watch and rebuild Japanese PDF on changes
- `npm run pdf-en-watch` - Watch and rebuild English PDF on changes

### Linting
- `npm run lint` - Run textlint for Japanese text quality checks

## Repository Structure

- `resume.ja.md` - Japanese resume source (master)
- `resume.en.md` - English resume source (machine-translated from `resume.ja.md`)
- `style.css` - Custom styling for PDF generation
- `md-to-pdf.json` - PDF generation configuration
- `.textlintrc` - Japanese text linting rules configuration

## Authoring Rules

These constraints exist in the content itself or in the publishing flow. Follow them when editing the resume Markdown.

- `resume.ja.md` is the source of truth. `resume.en.md` declares near the top that in case of conflict the Japanese version prevails.
- Any change to `resume.ja.md` must include the corresponding update to `resume.en.md` in the same PR.
- The "as of" date at the top of each file must be updated to today's date whenever the body is changed:
  - `resume.ja.md` — the `YYYY年MM月DD日現在` line near the top
  - `resume.en.md` — the `As of Month DD, YYYY` line near the top
- The email address is intentionally obfuscated as `ikuwow(at)gmail.com` in both files. Do not change `(at)` to `@`.
- Do not commit generated PDFs or local build artifacts. They are covered by `.gitignore` (`*.pdf`).
- `.textlintrc` sets `sentence-length.max` to 201; the value is intentional. Do not lower it to "fix" long-sentence warnings — rewrite the sentence instead.

## Development Workflow

1. Edit `resume.ja.md` first, then mirror the change into `resume.en.md`.
2. Update the "as of" date in both files.
3. Run `npm run lint` before committing. Watch-mode commands (`pdf-watch`, `pdf-en-watch`) are long-running processes; do not invoke them from an automated agent — they are for humans editing locally.
4. PDF generation is normally handled by CI (see below). Run `npm run pdf` / `npm run pdf-en` locally only when you need to verify the rendered output yourself.

## Release Process

Pushing a tag matching `v*` (e.g., `v2026.05.17`) triggers `.github/workflows/release.yml`, which builds both PDFs and attaches them to a GitHub Release. The README links (`releases/latest/download/...`) point at the latest release, so tagging is the publishing step.

## GitHub Actions

- `.github/workflows/main.yml` — On every push: builds both PDFs (macOS runner, required for the Hiragino Sans font selected in `style.css`) and uploads them as artifacts; runs textlint on a Linux runner.
- `.github/workflows/release.yml` — On `v*` tag push: builds both PDFs and attaches them to a GitHub Release.
- `.github/workflows/dependabot-auto-merge.yml` — Auto-merges Dependabot PRs for `semver-patch` and `semver-minor` updates. Major updates still require manual review.
- `.github/dependabot.yml` — Monthly schedule for npm and GitHub Actions ecosystems.
