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

- `resume.ja.md` - Japanese resume source
- `resume.en.md` - English resume source
- `style.css` - Custom styling for PDF generation
- `md-to-pdf.json` - PDF generation configuration
- `.textlintrc` - Japanese text linting rules configuration

## Development Workflow

1. Edit the appropriate Markdown file (resume.ja.md or resume.en.md)
2. Use watch commands during editing for live preview
3. Run `npm run lint` before committing to ensure text quality
4. Generate final PDFs with `npm run pdf` and `npm run pdf-en`

## GitHub Actions

The repository uses GitHub Actions for:
- Automatic PDF generation on push
- Linting checks
- Creating releases with PDF artifacts