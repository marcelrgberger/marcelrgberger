# Marcel R. G. Berger

**Indie App Developer | Software Architect | Author | Building AI-Powered Products**

I design, build, and operate software products end-to-end — from mobile apps and microservice backends to Kubernetes infrastructure and AI-powered autonomous operations. With 20+ years in software engineering, I've built systems across banking, finance, identity management, and critical infrastructure. Today, I channel that experience into building and shipping my own products as an independent developer.

I'm the author of [Solopreneur — The Art of Working Alone](https://amzn.eu/d/06PCcWKD), a book about the structural realities of building products independently — covering decision-making under uncertainty, systems thinking, and working without a team.

Currently building and operating five production products as a solo founder.

---

## What I Build

### Production-Grade Backend Systems
Microservice architectures with Java, Quarkus, and Spring Boot. Event-driven systems with Apache Kafka, asynchronous processing pipelines, and horizontal autoscaling. I've designed and operated systems with 30+ microservices in high-availability environments for enterprise clients including Union Investment and DZ Bank.

### Cross-Platform Mobile Applications
Native-quality apps with Flutter and Swift, deployed to App Store and Google Play. Offline-first architectures with local persistence (Drift/SwiftData), state management via Riverpod, and full CI/CD pipelines from commit to store release via GitHub Actions. Every app I build goes through automated build, test, and release — no manual deploys.

### Cloud-Native Infrastructure
Kubernetes clusters with GitOps (ArgoCD), cluster autoscaling with per-pool configuration, Helm-based deployments, and full observability stacks (Prometheus, Grafana, custom dashboards). I don't just deploy to the cloud — I build and operate the entire platform, including DNS automation, certificate management, and automated app onboarding.

### AI-Driven Autonomous Operations
Production systems managed by AI agents that monitor, diagnose, and remediate cluster issues autonomously. Claude-powered DevOps agents that run every hour, detect problems, restart failing services, optimize resource allocation, sync node labels, and generate infrastructure improvements — all without human intervention. A separate daily improvement agent analyzes Helm charts, security policies, and cost efficiency across the entire platform.

### Identity & Security Architecture
IAM solutions with SailPoint IdentityIQ, Keycloak, OAuth2/OIDC, and Azure Entra ID. Compliance-first architectures for regulated industries (EU DAC6, banking security, KRITIS). Enterprise-grade identity governance for major German banks.

---

## Products

I build and operate my own products under real production constraints — running on my own Kubernetes cluster with GitOps, automated monitoring, and AI-powered operations. No staging-only demos, no toy projects.

### DokuAI
AI-powered mobile reporting and documentation for construction and field service. Upload photos, voice recordings, or documents — and DokuAI automatically transcribes audio via OpenAI Whisper, analyzes images with GPT Vision, extracts location metadata, and compiles everything into structured reports. Built as 5 Quarkus microservices (API, Transcription, Image Analysis, Location, Report Generation) connected through Apache Kafka, with PostgreSQL for persistence and Civo S3 for file storage. The image and report services autoscale up to 12 replicas under load. Flutter app for iOS and Android.
[dokuai.app](https://dokuai.app)

### Sommelio
AI wine recommendations based on taste, context, and personal preference. Snap a photo of a wine bottle or label — Sommelio extracts the wine's characteristics using OpenAI Vision, matches them against your taste profile and favorites, and delivers personalized recommendations via Server-Sent Events in real time. Built as 3 Quarkus microservices (API, Extractor, Matching) with Kafka-driven pipeline processing, PostgreSQL, and Civo S3 for image storage. Flutter app with RevenueCat for monetization, Drift for offline persistence, and support for 8 languages.
[sommelio.app](https://sommelio.app)

### PaperlessIQ
Intelligent document management with structured data extraction and workflow automation. Import documents via camera scan, file picker, or share sheet — PaperlessIQ runs on-device OCR using Apple's Vision framework, extracts metadata (dates, amounts, IBANs, invoice numbers), and organizes everything into a deterministic folder structure synced via iCloud. Optional AI-powered classification and summarization through OpenAI. Built as a native iOS app with SwiftUI, SwiftData, CloudKit, and Core Spotlight for full-text search. Offline-first architecture with no document content leaving the device unless explicitly configured.
[paperlessiq.app](https://paperlessiq.app)

### Pourenzo
AI bartender that crafts cocktail recommendations from your available ingredients and personal taste. Photograph your bottles — Pourenzo identifies spirits and ingredients via OpenAI Vision, then generates cocktail recipes you can actually make with what you have at home. Seasonal recommendations, home bar inventory tracking, and personalized suggestions that improve over time. Built as 3 Quarkus microservices (API, Extractor, Matching) with the same Kafka-driven architecture as Sommelio. Flutter app with RevenueCat, Drift, and multi-language support.
[pourenzo.app](https://pourenzo.app)

### SnapShots
A dynamic word-guessing puzzle game with AI-generated images. Every hour, the backend automatically generates new puzzles — GPT-4o creates words, DALL-E 3 generates three visual clues per puzzle, and all content is translated into 8 languages. Players guess the word from the images, earning points through streak multipliers, time bonuses, and hint strategies. Features a global leaderboard, offline play with incremental sync, sound effects, particle animations, and haptic feedback. Built as a single Quarkus service with PostgreSQL, Liquibase migrations, and a caching layer for image delivery. Flutter app with Riverpod, Drift, and audioplayers.
[snapshots-quiz.app](https://snapshots-quiz.app)

---

## Book

### [Solopreneur — The Art of Working Alone](https://amzn.eu/d/06PCcWKD)
A real-world reflection on building and sustaining products as a solo founder. Written from within the journey — covering decision-making under uncertainty, systems thinking, and the structural realities of working independently. Not a success story, but an honest account of what it takes to build, ship, and operate products without a team.

---

## Industries & Domains

- **SaaS & Product Development** — End-to-end product lifecycle as indie developer and sole engineer, from idea to App Store
- **Banking & Finance** — Microservice architectures, instant payment systems, regulatory compliance (EU DAC6)
- **Identity & Access Management** — Enterprise IAM for major German banks with SailPoint and Keycloak
- **Critical Infrastructure (KRITIS)** — Secure cloud architectures, digital transformation, process automation

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
![REST](https://img.shields.io/badge/REST-005571?style=for-the-badge)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)

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

### Monitoring & Observability
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

### Security & Identity
![Keycloak](https://img.shields.io/badge/Keycloak-4B6C9E?style=for-the-badge&logo=keycloak&logoColor=white)
![OAuth2](https://img.shields.io/badge/OAuth2-6A6A6A?style=for-the-badge)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

### AI & Automation
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_AI-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Camunda](https://img.shields.io/badge/Camunda-FC5D0D?style=for-the-badge&logo=camunda&logoColor=white)

---

## Contact

Website: [marcelrgberger.com](https://marcelrgberger.com)
LinkedIn: [linkedin.com/in/marcel-r-g-berger](https://www.linkedin.com/in/marcel-r-g-berger)
GitHub: [github.com/marcelrgberger](https://github.com/marcelrgberger)

---

Imprint: [berger-rosenstock.de/imprint](https://berger-rosenstock.de/imprint)
Privacy: [berger-rosenstock.de/data-protection](https://berger-rosenstock.de/data-protection)
