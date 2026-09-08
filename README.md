# Bedru Mekiyu

**Full-Stack Engineer · Cloud & DevOps** — Addis Ababa, Ethiopia

I build offline-first civic platforms, multi-tenant enterprise systems, and scalable AWS cloud infrastructure. Software Engineering / Computer Science student at Addis Ababa University, shipping production systems designed for reliability, offline execution, and operational maintainability.

🌐 **Portfolio:** [portfolio-bedru.vercel.app](https://portfolio-bedru.vercel.app/)
💼 **LinkedIn:** [linkedin.com/in/bedru-mekiyu](https://www.linkedin.com/in/bedru-mekiyu)
🐙 **GitHub:** [@Bedru-Mekiyu](https://github.com/Bedru-Mekiyu)
✉️ **Email:** [bedru.mekiyu-ug@aau.edu.et](mailto:bedru.mekiyu-ug@aau.edu.et)

---

## 🛠️ Technical Competencies

- **Frontend Engineering:** TypeScript, React, Next.js, TailwindCSS, Flutter, Dart
- **Backend & API Systems:** Node.js, Express, REST APIs, WebSockets, Redis, BullMQ, JWT Authentication, RBAC
- **Data & Persistence:** PostgreSQL, MongoDB, Prisma ORM, Supabase, IndexedDB, Service Worker Caching
- **Cloud Infrastructure & DevOps:** AWS (ECS Fargate, RDS Aurora, CloudFront, S3, EC2, VPC, IAM, CloudWatch), Docker, Terraform, GitHub Actions, Nginx, Linux/Bash
- **System Patterns:** Offline-First PWA, Multi-Tenant RBAC, Event-Driven Task Queues, Synchronization Architectures

---

## 🚀 Featured Portfolio Repositories

### 🏛️ CivicVoice — Government Citizen Feedback Platform
> Multi-channel civic platform accepting submissions via SMS, WhatsApp, and Web, automatically routing issues to government departments with real-time analytics.

- **Architecture Highlights:** Containerized microservices on AWS ECS Fargate with CloudFront CDN edge caching and RDS Aurora relational storage.
- **Impact & Scale:** 500+ submissions processed with a 40% reduction in departmental response times.
- **Tech Stack:** `React` · `Express` · `MongoDB` · `AWS ECS` · `CloudFront` · `RDS`
- 🔗 **Repository:** [Bedru-Mekiyu/civicVoice-app](https://github.com/Bedru-Mekiyu/civicVoice-app)
- 🌐 **Live Application:** [civicVoice-app-1.onrender.com](https://civicvoice-app-1.onrender.com)

---

### 🏢 Rental Management System
> Multi-tenant enterprise rental management platform replacing manual spreadsheet tracking with structured lease lifecycles and complete audit logs.

- **Architecture Highlights:** End-to-end Role-Based Access Control (RBAC) across Admin, Manager, and Agent tiers secured via JWT authentication.
- **Impact & Scale:** Manages thousands of rental unit states and maintains immutable historical payment records.
- **Tech Stack:** `React` · `Express` · `MongoDB` · `JWT` · `RBAC` · `TailwindCSS`
- 🔗 **Repository:** [Bedru-Mekiyu/rentalapp](https://github.com/Bedru-Mekiyu/rentalapp)

---

### 📜 Vital Registration System
> Offline-first civil registration application for low-connectivity government offices, queuing records locally and syncing upon reconnection.

- **Architecture Highlights:** Service Worker request caching, IndexedDB local persistence, and transactional background synchronization engines.
- **Impact & Scale:** Reduced record registration turnaround times from weeks to under 24 hours in regional municipal offices.
- **Tech Stack:** `React` · `Node.js` · `PostgreSQL` · `Prisma` · `Service Worker` · `Background Sync`
- 🔗 **Repository:** [Bedru-Mekiyu/vital-registration-app](https://github.com/Bedru-Mekiyu/vital-registration-app)
- 🌐 **Live Application:** [vital-registration-app.onrender.com](https://vital-registration-app.onrender.com)

---

### 📦 Multi-Location Inventory Dashboard
> Operational inventory tracking platform featuring real-time reconciliation workflows and automated low-stock alerting across distribution nodes.

- **Architecture Highlights:** Event-driven WebSocket state broadcasts paired with strongly typed Prisma relational queries.
- **Impact & Scale:** Achieved an 85% reduction in multi-location inventory reconciliation discrepancies.
- **Tech Stack:** `Next.js` · `Prisma` · `TypeScript` · `PostgreSQL` · `WebSockets`
- 🔗 **Repository:** [Bedru-Mekiyu/Inventory-app](https://github.com/Bedru-Mekiyu/Inventory-app)

---

### 🎯 Typed Issue Tracker
> Role-aware task management application with state-machine workflow state transitions and strict role-filtered views.

- **Architecture Highlights:** Next.js API routes with JWT auth guards and Prisma relational model validation.
- **Tech Stack:** `Next.js` · `Prisma` · `TypeScript` · `JWT` · `PostgreSQL`
- 🔗 **Repository:** [Bedru-Mekiyu/Issue-Tracker](https://github.com/Bedru-Mekiyu/Issue-Tracker)

---

### 📚 BookSwap — Mobile Exchange Network
> Cross-platform mobile application enabling peer-to-peer book discovery, listing management, and swap requests.

- **Architecture Highlights:** Clean architectural separation for cross-platform Android and iOS deployments.
- **Tech Stack:** `Flutter` · `Dart` · `Kotlin` · `REST API`
- 🔗 **Repository:** [bethelihemw/BookSwap](https://github.com/bethelihemw/BookSwap)

---

## 🏗️ Cloud Infrastructure & Systems Architecture Case Study

### CivicVoice Production Infrastructure (AWS)
- **ECS Fargate Auto-Scaling:** Configured automatic scaling policies (2 → 20 containers) responding to traffic spikes under 60 seconds, eliminating early EC2 memory exhaustion failure modes.
- **CloudFront CDN Optimization:** Edge caching reduced TTFB from ~2.4s to ~180ms for regional users across Ethiopia (80% page load optimization).
- **RDS Aurora Resilience:** Point-in-time recovery with 35-day retention and a 5-minute RPO target without manual snapshot overhead.

```
┌─────────────────┐
│   CloudFront    │ (CDN / Edge)
└────────┬────────┘
         │
┌────────▼────────┐
│ App Load Bal.   │
└────────┬────────┘
         │
┌────────▼────────┐
│  ECS Fargate    │ (2 - 20 tasks)
└────────┬────────┘
         │
┌────────▼────────┐
│  RDS Aurora     │ (PostgreSQL)
└─────────────────┘
```

---

## 📌 Specialized Technical Repositories

- [`ethio-tech-platform`](https://github.com/Bedru-Mekiyu/ethio-tech-platform) — Event-driven backend service with Redis task queues.
- [`game-finder--app`](https://github.com/Bedru-Mekiyu/game-finder--app) — Rawg API client built with React and TypeScript.
- [`events-nextjs`](https://github.com/Bedru-Mekiyu/events-nextjs) — Serverless Next.js event management platform.
- [`first-CI-CD`](https://github.com/Bedru-Mekiyu/first-CI-CD) — Automated deployment workflows using GitHub Actions.
- [`fastapi-issue-tracker`](https://github.com/Bedru-Mekiyu/fastapi-issue-tracker) — Lightweight Python/FastAPI backend service.

---

## 📜 Verified Certifications & Technical Learning

- ☁️ **AWS Certified Solutions Architect — Associate (SAA-C03) Prep** — [View Credential](https://skillbuilder.aws/learn/HGQZF26N6R/exam-prep-summary-aws-certified-solutions-architect--associate-saac03--english/874J6BR818)
- ☁️ **AWS Cloud Practitioner Essentials** — [View Credential](https://skillbuilder.aws/learn/94T2BEN85A/aws-cloud-practitioner-essentials/8D79F3AVR7)
- ⚙️ **DevOps Complete Course (O'Reilly)** — [View Credential](https://www.credly.com/badges/2832eb98-2580-4f1a-bc33-ed693cd47536/public_url)
- ⚙️ **DevOps Fundamentals (O'Reilly)** — [View Credential](https://www.credly.com/badges/627b39e0-3cf5-4d79-8931-5adec49731e8/public_url)
- ⚙️ **Breaking into DevOps Engineering (O'Reilly)** — [View Credential](https://www.credly.com/badges/495cb8c7-9a47-46a7-9a44-f58a48529723/public_url)
- ☁️ **Introduction to Cloud Computing (O'Reilly)** — [View Credential](https://www.credly.com/badges/492c7b61-616a-41f6-b561-0161dec72801/public_url)
- 🐧 **Linux Command Line (O'Reilly)** — [View Credential](https://www.credly.com/badges/249da16c-9b49-4741-b00f-f5dd07d59bc6/public_url)

---

## 📬 Connect & Contact

- **Portfolio:** [portfolio-bedru.vercel.app](https://portfolio-bedru.vercel.app/)
- **LinkedIn:** [linkedin.com/in/bedru-mekiyu](https://www.linkedin.com/in/bedru-mekiyu)
- **GitHub:** [@Bedru-Mekiyu](https://github.com/Bedru-Mekiyu)
- **Email:** [bedru.mekiyu-ug@aau.edu.et](mailto:bedru.mekiyu-ug@aau.edu.et)

*Available for full-stack engineering, DevOps/cloud engineering, and distributed systems roles.*
