# Resume

**The document is based on machine translation. In case of conflict between the translation and the original Japanese version, the Japanese version will prevail.**

As of June 2026

![ikuwow](ikuwow.webp)

Ikuo Degawa (@ikuwow)

SRE / Platform Engineer

Born in 1990, lives in Kanagawa, Japan

* X: https://x.com/ikuwow
* GitHub: https://github.com/ikuwow
* Blog: https://queryok.ikuwow.com
* Email: ikuwow(at)gmail.com

The latest version of this resume is available on GitHub: https://github.com/ikuwow/resume

## Summary

I have worked for many years as an SRE and platform engineer at web companies, building the reliability and delivery foundations of services.
I specialize in SLO/SLI operations on AWS, GitOps and progressive delivery, and the design, construction, and operation of microservice platforms with Kubernetes and Istio.
Working across job roles and technical domains, I pursue holistic problem-solving that factors in technical, organizational, and cost trade-offs.
I always act with the goals of the project or service and the value to users in mind.

## Skills

### Core (Reliability & Delivery Platform)

* SRE / DevOps practice (building and operating CI/CD environments, leadership in incident response, practices such as postmortems and the 50% rule, Enabling SRE)
* Establishing and operating SLO/SLI and error budget policies
* Designing and building observability tooling (Datadog, etc.)
* Designing and operating GitOps and progressive delivery (PipeCD, Flagger, Flux, etc.)
* Designing, building, and operating microservice architectures with Kubernetes and Istio
* Building and operating AWS-centered cloud infrastructure
* Developing and operating backend applications in Golang
* Hands-on technical validation and PoC
* Utilizing AI coding agents, and designing and introducing development processes premised on AI agents

### Experience

* Languages & frameworks: PHP, Ruby on Rails, Java/Spring, JavaScript, Golang, CakePHP
* Cloud & infrastructure: AWS, GCP, Terraform, Ansible, Chef, Docker, Kubernetes, ECS
* Datastores & analytics: PostgreSQL, MySQL, Elasticsearch, Redshift, BigQuery, Tableau
* Frontend: HTML/CSS/JavaScript, Sass, Webpack, observability and performance improvement with RUM
* Other: fundamentals of networking and infrastructure, office network setup, reading/writing/listening in English

### Background

* Image and audio processing programming with MATLAB and C
* iOS app development with Swift
* Customizing CMS such as WordPress

<div class="page-break"></div>

## Work Experience

### tacoms Inc.

Worked as a contractor from June 2024 to July 2025, then as a full-time employee from August 2025 to present

As the SRE tech lead, driving the reliability, delivery, and cost of the restaurant order management SaaS "Camel" across the board

#### SRE Member / Tech Lead

* Operating AWS service infrastructure using ECS Fargate, Aurora, SQS/SNS, Lambda, etc.
* Performance optimization of Aurora MySQL
* Designing and building the data aggregation infrastructure using BigQuery, etc.
* Building and operating infrastructure for new services
* Designing and implementing migration from CIOps (GitHub Actions → ECR → ECS) to GitOps (PipeCD)
* Building and promoting observability tooling using Datadog
* Evaluating TiDB migration
* Introducing canary release / progressive delivery using PipeCD
* Designing and building infrastructure for detecting integration errors with external services (Lambda, EventBridge, Datadog)
* Handling traffic spikes from customer campaigns
* Building infrastructure for AI utilization
* Various incident response and on-call

#### Development and operation of "Camel", a restaurant order management SaaS

* Designing SLO/SLI, building and operating measurement infrastructure (Datadog, AWS)
* Developing and operating Golang backend applications
* Building monitoring tooling for external integration availability
* Optimizing infrastructure costs
* Promoting migration from other products
* Feature improvements for large enterprise adoption

#### Cross-functional

* Administrator of internal infrastructure systems like GitHub, Datadog

### ZOZO, Inc.

Worked as a full-time employee from December 2021 to April 2024 in a fully remote capacity

Served as a platform SRE for a large-scale EC service, and as the lead SRE for a core system replacement

#### Platform Services SRE Block, Front SRE Block

* Designing, building, and operating Kubernetes infrastructure
* Operating microservice applications on a service mesh using Istio
* Operating MySQL and SQL Server
* Operating Java and NodeJS applications
* Managing SaaS like Sentry, Datadog, PagerDuty using Terraform
* Ensuring service reliability based on SLOs
* Building workflows to achieve parallel pipelines for monorepo using GitHub Actions
* Expanding the use of Flagger, Flux
* Adopting GitHub Projects
* On-call duties, incident response
* Mentoring new employees

#### Lead SRE for Core System Replacement

* Catching up on domain knowledge and translating it into requirements
* Conducting PoC, designing, and building data integration methods using Kafka (Amazon MSK, etc.)
* Task and schedule management
* Logical design of RDBs
* Building release flows and lecturing development teams
* Adhering to various guidelines including security
* Lecturing SRE and development teams on post-replacement technologies
* Conducting pre-release load testing

#### Frontend Replacement Project

* Designing, building, and operating NodeJS applications on microservice infrastructure
* Designing WAF and routing on Akamai
* Building release flows and lecturing development teams
* Adhering to various guidelines including security
* Lecturing SRE and development teams on post-replacement technologies
* Conducting pre-release load testing

### SMS Co., Ltd.

Worked as a full-time employee from October 2017 to November 2021
(Worked fully remotely from 2020)

As the SRE for the elderly care management support SaaS "Kaipoke" and other services

#### Development and support for an internal LP hosting service, and others

August 2020 - November 2021

* Improving features of Ruby on Rails applications
* Rebuilding and maintaining the environment for Serverless applications
* Improving development structure by setting up CI and workflows
* Reducing cost and improving management by rebuilding AWS environment
* Code review and release management
* Consulting for users (marketers, designers, etc.)
* Defining the service's positioning and deciding future directions

#### SRE for elderly care management support service (SaaS) Kaipoke

October 2017 - July 2020

* Improving performance across multiple Spring and SAStruts applications
* Performance tuning of applications and DBs
* Maintaining AWS environment in cooperation with partner companies
* Building and maintaining development environments with AWS and Terraform
* Handling EoL of dependent frameworks and packages
* Maintaining batch jobs
* Designing SLIs, implementing and visualizing them using AWS, deciding SLOs
* Optimizing the cost of the entire infrastructure
* Supporting each development team with release schedule adjustments, etc.
* Triaging system requirements from internal stakeholders and supporting problem solving

### TeamUp Inc.

Worked as a freelance engineer from April 2018 to June 2021 in a fully remote capacity

#### Infrastructure setup and support for establishing development systems for 1-on-1 tool TeamUp

April 2018 - June 2021

* Converting AWS environment to IaC using Terraform/Ansible
* Setting up development systems using documentation management tools like esa.io, GitHub
* Streamlining development flow using CircleCI, etc.
* Replacing and maintaining AWS environment where the service runs
* Deciding and implementing security requirements using AWS services
* Supporting performance improvement of Ruby on Rails applications
* Developing management features for Ruby on Rails applications

<div class="page-break"></div>

### Leverages, Inc.

Worked as a full-time employee from April 2015 to September 2017

#### Development of engineer-oriented Q&A service "teratail" and others

April 2015 - September 2017

* Developing and maintaining CakePHP applications
* Designing and building public REST APIs
* Developing the entire frontend for campaign pages
* Setting up CI environment
* Considering measures to achieve business goals
* Building analysis infrastructure using Elasticsearch, Redshift, BigQuery, etc.
* Migrating from VPC to GKE (Kubernetes) environment
* Improving application performance overall
* Introducing and connecting Mailchimp system with the application for newsletters
* Introducing and managing Google's advertising system (Google Adwords)
* Others
  * Designing, building, and managing internal networks
  * Writing content articles
  * Building and directing newsletter content
  * Participating in recruitment activities
  * Awarded Excellent Hacker Award in 2015

### Slogan, Inc.

Worked as an intern from September 2013 to March 2015

#### Maintenance of "Goodfind" related media and setting up internal networks

* Developing user-facing CakePHP applications
* Developing admin-facing CakePHP applications
* Replacing VPC environments using Chef, etc.
* Building and maintaining office/office-to-office networks
* Developing new iOS applications
* Conducting seminars for student engineers

## Writing

* [tacoms tech blog](https://tacoms-inc.hatenablog.com/archive/author/ikuwow) Tech blog articles, 2024–
* [Former tacoms tech blog](https://zenn.dev/p/tacoms) Tech blog articles
* O'Reilly [進化的アーキテクチャ (Building Evolutionary Architectures)](https://www.oreilly.co.jp/books/9784873118567/) translation review, 2019
* SoftwareDesign series "アプリエンジニアのための［インフラ］入門 (Infrastructure Basics for Application Engineers)", all 6 parts, 2016
* gihyo.jp [あとはコードを書くだけ，はじめに作る開発環境構築ベストプラクティス (Development Environment Setup Best Practices)](https://gihyo.jp/dev/serial/01/howto-env-conf), 2016
* gihyo.jp [聞いたら一生の宝，プログラミングの基礎の基礎 (Programming Fundamentals)](https://gihyo.jp/dev/serial/01/js-foundation), (3rd, 5th, 7th parts), 2015

## Certifications

* [LPIC-3 305 (Virtualization and Containerization)](https://people.lpi.org/m/LPI000286814), 2024
* 日商簿記 (The Japan Chamber of Commerce and Industry Bookkeeping) Level 2, 2016
* 情報処理技術者試験 ネットワークスペシャリスト (Network Specialist Examination), 2015
* TOEIC Score 860, 2013

## Education

* Graduated from Keio University Graduate School of Science and Technology, Department of Integrated Design Engineering, March 2015
* Graduated from Keio University Faculty of Science and Technology, Department of Electronics and Electrical Engineering, March 2013
