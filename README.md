# Marcel R. G. Berger

**AI builds MVPs. I build stable apps.**

Indie App Developer · Software Architect · Author. Development and operations from a single owner.

I build and ship my own software products — from idea to App Store. Mobile apps, microservice backends, Kubernetes infrastructure, and AI-powered automation. Everything designed, built, and operated by me.

20+ years in software engineering. Currently building and operating production products as a solo founder.

---

## Live in the App Store

### DokuAI
AI-powered reporting and documentation for construction and field service. Upload photos or voice recordings — DokuAI transcribes, analyzes, and compiles structured reports automatically. 5 microservices, Kafka, OpenAI Whisper & Vision, PostgreSQL. Flutter app for iOS and Android.
[dokuai.app](https://dokuai.app) · [App Store](https://apps.apple.com/app/id6749177847)

### SnapShots — Photo Speed Quiz
AI-generated word puzzle game. Every hour, the backend creates new puzzles — GPT-4o picks words, DALL-E 3 generates visual clues, everything translated into 8 languages. Global leaderboard, streak system, offline play. Quarkus backend, PostgreSQL. Flutter app.
[snapshots-quiz.app](https://snapshots-quiz.app) · [App Store](https://apps.apple.com/app/id6759857715)

### CivoCloudManager
Native macOS app for Civo Cloud — full CRUD, Kubernetes deep integration (live metrics, pods, logs), S3 file browser, firewall management, 8 languages. Swift 6, SwiftUI, zero dependencies.
[civo-cloud-manager.app.website](https://civo-cloud-manager.app.website) · [App Store](https://apps.apple.com/app/id6760776010) · [Source](https://github.com/marcelrgberger/civo-cloud-manager)

More on [marcelrgberger.com](https://marcelrgberger.com) — including products currently in development.

---

## Open Source

### [auto-brew](https://github.com/marcelrgberger/auto-brew)
Native macOS app for Homebrew: background auto-updates, a full Brew GUI for browsing and installing casks, and an AppSnapshot engine for backing up and migrating app data across Macs. Swift.

### [pages-cli](https://github.com/marcelrgberger/pages-cli)
Claude Code plugin: control Apple Pages from Claude — create, edit, format and export documents via `/pages`. 100+ templates, PDF/Word/EPUB export, tables, images. Python.

### [numbers-cli](https://github.com/marcelrgberger/numbers-cli)
Claude Code plugin for full Apple Numbers control via AppleScript — create spreadsheets, manage data, format cells, export to PDF/Excel/CSV.

### [whatsapp-cli](https://github.com/marcelrgberger/whatsapp-cli)
Claude Code plugin: control WhatsApp from Claude — read chats, send messages, search, auto-reply, export conversations, monitor in real-time. macOS only. Python.

### [xcode-cli](https://github.com/marcelrgberger/xcode-cli)
Claude Code plugin: control Xcode from Claude — build, test, run, clean, manage simulators, schemes, projects, and devices. 30+ commands via AppleScript + xcodebuild + xcrun. Python.

### [jira-cli](https://github.com/marcelrgberger/jira-cli)
Single-file Python CLI for Atlassian Jira Cloud — read and edit issues, comments, transitions, attachments, links, agile boards, and bulk operations. Standard library only, no dependencies.

### [inwx-dns](https://github.com/marcelrgberger/inwx-dns)
Claude Code plugin for managing domains and DNS records via the INWX API. Python.

### [askapro-cli](https://github.com/marcelrgberger/askapro-cli)
Ask a Pro — AI-powered document analysis with 85+ expert consultation roles for legal, medical, tax, and professional advice. TypeScript.

---

## The Platform Behind It

All products run on my own Kubernetes cluster with GitOps (ArgoCD), Helm-based deployments, and full observability via Prometheus and Grafana. CI/CD pipelines from commit to App Store release via GitHub Actions — no manual deploys.

The cluster is monitored and maintained by AI agents I built myself. A Claude-powered ops agent runs every hour — detecting problems, restarting services, optimizing resources, and applying fixes autonomously. A second agent runs daily to analyze infrastructure, improve Helm charts, and tune security policies. No human in the loop.

---

## Background

Before going indie, I spent 20 years building software in enterprise environments — microservice architectures for banks, IAM systems for regulated industries, instant payment platforms, and digital transformation in critical infrastructure (KRITIS). That experience shapes how I build today: production-first, secure by default, designed to last.

---

## Book

### [Solopreneur — The Art of Working Alone](https://amzn.eu/d/06PCcWKD)
What it takes to build, ship, and operate products without a team. Decision-making under uncertainty, systems thinking, and the structural realities of working independently. Written from within the journey, not after it.

---

## Core Technologies

### Languages & Mobile
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-FA7343?style=for-the-badge&logo=swift&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

### Backend & Architecture
![Quarkus](https://img.shields.io/badge/Quarkus-4695EB?style=for-the-badge&logo=quarkus&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![REST](https://img.shields.io/badge/REST-005571?style=for-the-badge)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)

### Cloud, DevOps & Infrastructure
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo%20CD-FE5400?style=for-the-badge&logo=argo&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![OpenShift](https://img.shields.io/badge/OpenShift-EE0000?style=for-the-badge&logo=redhatopenshift&logoColor=white)

### Data & Messaging
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Liquibase](https://img.shields.io/badge/Liquibase-2962FF?style=for-the-badge&logo=liquibase&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![CloudKit](https://img.shields.io/badge/CloudKit-000000?style=for-the-badge&logo=icloud&logoColor=white)
![S3](https://img.shields.io/badge/S3_Object_Storage-569A31?style=for-the-badge&logo=amazons3&logoColor=white)

### Monitoring & Observability
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

### Security & Identity
![Keycloak](https://img.shields.io/badge/Keycloak-4B6C9E?style=for-the-badge&logo=keycloak&logoColor=white)
![OAuth2](https://img.shields.io/badge/OAuth2-6A6A6A?style=for-the-badge)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Let's Encrypt](https://img.shields.io/badge/Let's%20Encrypt-003A70?style=for-the-badge&logo=letsencrypt&logoColor=white)

### AI & Automation
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_AI-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![DALL·E](https://img.shields.io/badge/DALL·E-412991?style=for-the-badge&logo=openai&logoColor=white)
![Apple Vision](https://img.shields.io/badge/Apple_Vision-000000?style=for-the-badge&logo=apple&logoColor=white)

### App Distribution
![App Store](https://img.shields.io/badge/App_Store-0D96F6?style=for-the-badge&logo=appstore&logoColor=white)
![Google Play](https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=googleplay&logoColor=white)
![RevenueCat](https://img.shields.io/badge/RevenueCat-F25A5A?style=for-the-badge)

---

## How I work

I don't outsource. I don't subcontract. I don't pitch what I haven't shipped myself.

Short cycles, written summaries, direct trade-off conversations.

---

## Work together

Two ways to engage — pick the one that matches the scope.

### Build a project — [theapparchitect.com](https://theapparchitect.com)

**Code is cheap. Architecture is the moat.** One architect, end-to-end, accountable for the outcome. Plan, build, hand over — no agency layers between you and the work.

| Engagement | Scope |
|------------|-------|
| **Full Build** | From whiteboard to App Store. Planning, architecture, UX and delivery. You receive source code, build pipelines and a written handover. Fixed scope, fixed price. |
| **Architecture Review** | Two focused weeks looking at the system you already have. Written report with prioritised actions and risk ratings — practical findings, not academic. |
| **Embedded Architect** | Part-time inside your team. I own the system-design calls and keep your engineers unblocked. Months, not days. |

→ [Start a project on theapparchitect.com](https://theapparchitect.com)

### Book a session

Hour-shaped engagements for one specific question — all billed by invoice (no Stripe in Cal.com). Alternatively: pay via [GitHub Sponsors](https://github.com/sponsors/marcelrgberger) — same delivery.

| Session | Duration · Fee | Scope |
|---------|----------------|-------|
| [Initial Consultation](https://cal.com/marcelrgberger/consultation) | 30 min · free | Honest take on your app idea before you sink time and money into it |
| [Pair Programming](https://cal.com/marcelrgberger/pair-programming) | 60 min · €200 | Live coding on your stack — Swift/SwiftUI, Flutter, Java/JVM, Claude Code plugins, CI/CD |
| [App Review for Vibe Coders](https://cal.com/marcelrgberger/app-review) | 60 min · €250 | Code, architecture, and operations review for AI-built apps that need hardening |
| [Problem Solver](https://cal.com/marcelrgberger/problem-solver) | 60 min · €300 | One concrete problem you describe upfront — I prepare, we solve it together |
| [Consulting](https://cal.com/marcelrgberger/consulting) | 60 min · €350 | Architecture / decision support with a written summary delivered within 3 business days |
| [Conference Talk](https://cal.com/marcelrgberger/conference-talk) | by request · €2.000 | Native macOS/iOS · AI in production at scale · indie Kubernetes & GitOps · Apache Kafka & Quarkus · solo software business · Claude Code plugins |

For conference talks, travel, accommodation, and meals are arranged and paid by the booking organization.

---

## Sponsor this work

[![Sponsor marcelrgberger](https://img.shields.io/badge/Sponsor%20on%20GitHub-EA4AAA?style=for-the-badge&logo=githubsponsors&logoColor=white)](https://github.com/sponsors/marcelrgberger)

If you find any of the public plugins, write-ups, or products useful, consider sponsoring. It directly funds hosting, code signing, infrastructure, and the time I put into open-source.

## Contact

Personal site: [marcelrgberger.com](https://marcelrgberger.com)
Studio: [theapparchitect.com](https://theapparchitect.com)
Book a call: [cal.com/marcelrgberger](https://cal.com/marcelrgberger)
LinkedIn: [linkedin.com/in/marcel-r-g-berger](https://www.linkedin.com/in/marcel-r-g-berger)
Reddit: [reddit.com/user/Constant-Chemical23](https://www.reddit.com/user/Constant-Chemical23/)

---

Imprint: [marcelrgberger.com/imprint](https://marcelrgberger.com/imprint/)
Privacy: [marcelrgberger.com/privacy](https://marcelrgberger.com/privacy/)
