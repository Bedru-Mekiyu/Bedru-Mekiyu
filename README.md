# Bedru Mekiyu

**Full-Stack Software Engineer · Cloud & DevOps** — Addis Ababa, Ethiopia  
[LinkedIn](https://www.linkedin.com/in/bedru-mekiyu) · [Portfolio](https://portfolio-bedru.vercel.app/) · [GitHub](https://github.com/Bedru-Mekiyu) · [Email](mailto:bedru.mekiyu-ug@aau.edu.et)

Software Engineering student at Addis Ababa University (2023–2027) building reliable full-stack applications, scalable backend APIs, and automated containerized delivery pipelines. Experienced in translating real-world operational workflows into maintainable software across civic, enterprise, and educational domains.

---

## 🛠️ Technical Capabilities

- **Languages:** TypeScript, JavaScript, Python, PHP, Dart, Kotlin, SQL, HTML/CSS
- **Frontend Engineering:** React (18/19), Next.js (App Router), Tailwind CSS, shadcn/ui, Radix UI, TanStack Query, Zustand, Flutter (Riverpod)
- **Backend & APIs:** Node.js, Express.js (v4/v5), Python (FastAPI, Pydantic), PHP (Laravel 11, Filament v3), RESTful API Design, WebSockets (Socket.IO), JWT Authentication, Multi-Tenant RBAC
- **Databases & ORM:** PostgreSQL, MongoDB (Mongoose), MySQL, Prisma ORM, Supabase (Postgres & Row-Level Security), Redis (Caching & Rate Limiting)
- **DevOps & Cloud:** Docker, Docker Compose, Nginx, GitHub Actions CI/CD, AWS Foundations (EC2, S3, SES, IAM, VPC), Linux/Bash, Render, Vercel
- **Testing & Quality:** Vitest, Playwright (E2E), Jest, PHPUnit, Pytest, Supertest, ESLint

---

## 🚀 Featured Engineering Projects

### 🏢 Rental Management System (RMS)
Full-stack property rental platform developed for the Ethiopian Islamic Affairs Supreme Council to manage leases, tenant records, and payment tracking.
- **Architecture:** React & TypeScript SPA with Zustand state management paired with an Express 5 and MongoDB backend (~80+ REST endpoints, 29 Mongoose schemas).
- **Engineering Highlights:** Multi-tier Role-Based Access Control (Admin, Property Manager, Agent, Tenant), TOTP two-factor authentication, Redis-backed rate limiting, AWS S3 document upload integration, AWS SES email notifications, and automated lease expiration tracking.
- **Tech Stack:** `React` · `TypeScript` · `Express 5` · `MongoDB` · `AWS S3/SES` · `Redis` · `Zustand`
- 🔗 **Repository:** [Bedru-Mekiyu/rentalapp](https://github.com/Bedru-Mekiyu/rentalapp)

---

### 🌐 EthioTech Platform
Collaborative developer education platform combining real-time WebRTC classrooms, regional hub workstation booking, and verified curriculum tracking.
- **Architecture:** Monorepo workspace featuring a React 19 frontend and an event-driven Node.js backend with Socket.IO Redis adapter for distributed socket state.
- **Engineering Highlights:** LiveKit WebRTC SFU integration, Render deployment configuration (`render.yaml`), structured Winston logging, and comprehensive automated testing (50 test suites, 444 unit/integration tests with Vitest, plus Playwright E2E automation).
- **Tech Stack:** `React 19` · `Node.js 22` · `TypeScript` · `WebRTC (LiveKit)` · `Socket.IO` · `Redis` · `MongoDB` · `Vitest` · `Playwright`
- 🔗 **Repository:** [Bedru-Mekiyu/ethio-tech-platform](https://github.com/Bedru-Mekiyu/ethio-tech-platform)

---

### 🤝 Idir Management System
Community mutual aid management system developed for the Ethiopian Muslim Youth Council (EMYC) to digitalize member registries, emergency assistance workflows, and recurring dues collection.
- **Architecture:** Multi-panel architecture built with Laravel 11 and Filament v3, backed by MySQL/PostgreSQL and Redis queue workers.
- **Engineering Highlights:** Multi-tenant organization boundaries, automated SMS notifications via Africa's Talking / AfroMessage, local mobile payment webhook processing (Telebirr, M-Pesa), and automated PHPUnit test pipeline with GitHub Actions.
- **Tech Stack:** `PHP 8.4` · `Laravel 11` · `Filament v3` · `MySQL` · `Redis / Horizon` · `Africa's Talking` · `PHPUnit`
- 🔗 **Repository:** [Bedru-Mekiyu/Idir](https://github.com/Bedru-Mekiyu/Idir)

---

### 📦 Modern Inventory Dashboard
Multi-tenant inventory tracking platform utilizing modern server-first web architecture.
- **Architecture:** Next.js 16 App Router application leveraging React 19 Server Components, Server Actions, and Prisma 7 querying PostgreSQL.
- **Engineering Highlights:** Strict per-user inventory data isolation, modern cookie-based session authentication via Stack Auth, responsive UI with Tailwind CSS v4, and interactive stock trend analytics via Recharts.
- **Tech Stack:** `Next.js 16` · `React 19` · `TypeScript` · `Prisma 7` · `PostgreSQL` · `Stack Auth` · `Recharts`
- 🔗 **Repository:** [Bedru-Mekiyu/Inventory-app](https://github.com/Bedru-Mekiyu/Inventory-app)

---

### ⚡ Automated AWS EC2 Deployment Pipeline
Containerized delivery pipeline demonstrating end-to-end continuous integration and deployment on cloud infrastructure.
- **Architecture:** Multi-container environment running an Express application, MongoDB database, and an Nginx reverse proxy configured with WebSocket upgrade handling.
- **Engineering Highlights:** Automated GitHub Actions workflow building and pushing Docker images to Docker Hub, performing automated SSH deployment to AWS EC2, and managing isolated bridge networks with Docker Compose and container health checks.
- **Tech Stack:** `GitHub Actions` · `Docker` · `Docker Compose` · `Nginx` · `AWS EC2` · `Express.js` · `MongoDB`
- 🔗 **Repository:** [Bedru-Mekiyu/first-CI-CD](https://github.com/Bedru-Mekiyu/first-CI-CD)

---

### 📱 BookSwap — Mobile Exchange Platform
Cross-platform peer-to-peer mobile application for discovering, listing, and exchanging physical and digital books.
- **Architecture:** Cross-platform Flutter mobile client consuming a dedicated Node.js and MongoDB REST API backend service.
- **Engineering Highlights:** State management powered by Flutter Riverpod, clean separation between Dio HTTP interceptors and UI layers, and secure JWT-authenticated swap workflows. Built collaboratively as a team engineering project.
- **Tech Stack:** `Flutter` · `Dart` · `Riverpod` · `Node.js` · `Express` · `MongoDB`
- 🔗 **Repository:** [Bedru-Mekiyu/BookSwap-Flutter](https://github.com/Bedru-Mekiyu/BookSwap-Flutter)

---

## ⚙️ Cloud, DevOps & Systems Practice

- **CI/CD Automation:** Configured automated GitHub Actions workflows enforcing linting, strict TypeScript type checking, PHPUnit/Vitest test suites, and Docker image publishing on push and pull requests (`ethio-tech-platform`, `Idir`, `first-CI-CD`, `events-nextjs`, `fastapi-issue-tracker`).
- **Containerization & Web Servers:** Designed multi-container Docker Compose environments (`first-CI-CD`) with Nginx reverse proxying, connection pooling, and health checks.
- **Cloud Infrastructure:** Hands-on experience provisioning AWS EC2 instances, configuring IAM least-privilege policies, S3 bucket storage, and SES transactional email integrations.
- **Currently Exploring:** Infrastructure as Code (Terraform), Kubernetes cluster orchestration, and advanced observability (Prometheus/Grafana).

---

## 📜 Verified Credentials & Continuing Education

- ☁️ **AWS Cloud Support Associate Professional Certificate** — Verified Training & Assessment
- ☁️ **AWS Certified Solutions Architect — Associate (SAA-C03) Preparation** — [AWS Skill Builder](https://skillbuilder.aws/learn/HGQZF26N6R/exam-prep-summary-aws-certified-solutions-architect--associate-saac03--english/874J6BR818)
- ☁️ **AWS Cloud Practitioner Essentials** — [AWS Skill Builder](https://skillbuilder.aws/learn/94T2BEN85A/aws-cloud-practitioner-essentials/8D79F3AVR7)
- ⚙️ **DevOps Complete Course (O'Reilly)** — [Credly Verification](https://www.credly.com/badges/2832eb98-2580-4f1a-bc33-ed693cd47536/public_url)
- ⚙️ **DevOps Fundamentals (O'Reilly)** — [Credly Verification](https://www.credly.com/badges/627b39e0-3cf5-4d79-8931-5adec49731e8/public_url)
- ⚙️ **Breaking into DevOps Engineering (O'Reilly)** — [Credly Verification](https://www.credly.com/badges/495cb8c7-9a47-46a7-9a44-f58a48529723/public_url)
- ☁️ **Introduction to Cloud Computing (O'Reilly)** — [Credly Verification](https://www.credly.com/badges/492c7b61-616a-41f6-b561-0161dec72801/public_url)
- 🐧 **Linux Command Line (O'Reilly)** — [Credly Verification](https://www.credly.com/badges/249da16c-9b49-4741-b00f-f5dd07d59bc6/public_url)

---

## 📬 Connect

- **Portfolio:** [portfolio-bedru.vercel.app](https://portfolio-bedru.vercel.app/)
- **LinkedIn:** [linkedin.com/in/bedru-mekiyu](https://www.linkedin.com/in/bedru-mekiyu)
- **GitHub:** [@Bedru-Mekiyu](https://github.com/Bedru-Mekiyu)
- **Email:** [bedru.mekiyu-ug@aau.edu.et](mailto:bedru.mekiyu-ug@aau.edu.et)

*Available for Full-Stack Software Engineering, Backend API Development, and Cloud/DevOps opportunities.*
