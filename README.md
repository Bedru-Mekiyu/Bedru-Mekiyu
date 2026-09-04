# Bedru Mekiyu

**Full-Stack Engineer · Cloud & DevOps** — Addis Ababa, Ethiopia

I build production-grade full-stack systems and deploy reliable AWS infrastructure. My work focuses on offline-first civic platforms, multi-tenant SaaS with fine-grained role-based access control (RBAC), and real-time operational dashboards. Software Engineering undergraduate at Addis Ababa University, available for full-stack, DevOps/cloud engineering, and distributed engineering roles.

> **Engineering Philosophy:** Systems discipline first. Reliable offline execution, zero-downtime scaling, and production-ready operational maintainability.

---

## 🛠️ Technical Capabilities

- **Frontend:** TypeScript, React, Next.js, TailwindCSS, Flutter
- **Backend & APIs:** Node.js, Express, REST APIs, WebSockets, Redis, BullMQ
- **Databases & ORM:** PostgreSQL, MongoDB, Prisma ORM, Supabase
- **Cloud & DevOps:** AWS (ECS Fargate, RDS Aurora, CloudFront, S3, EC2, VPC, IAM, CloudWatch), Docker, Terraform, GitHub Actions, Nginx, Linux/Bash
- **Mobile Engineering:** Flutter, Dart, Kotlin, Android SDK
- **Architecture Patterns:** Offline-First PWA, Role-Based Access Control (RBAC), JWT Authentication, Event-Driven Task Queues, Sync Architectures

---

## 🚀 Featured Portfolio Repositories

### 🏛️ CivicVoice — Government Citizen Feedback Platform
> Multi-channel feedback platform accepting submissions via SMS, WhatsApp, and Web, automatically routing issues to government departments with real-time analytics.

- **Architecture Highlights:** Containerized services on AWS ECS Fargate, CloudFront CDN edge distribution, and RDS Aurora storage.
- **Impact & Scale:** 500+ submissions processed, 40% reduction in response time, 3 active input channels.
- **Tech Stack:** `React` · `Express` · `MongoDB` · `AWS ECS` · `CloudFront` · `RDS`
- 🔗 **Repository:** [Bedru-Mekiyu/civicVoice-app](https://github.com/Bedru-Mekiyu/civicVoice-app)
- 🌐 **Live Demo:** [civicVoice-app-1.onrender.com](https://civicvoice-app-1.onrender.com)

---

### 🏢 Rental Management System
> Enterprise multi-tenant rental management platform replacing spreadsheet workflows with structured lease lifecycles and complete audit trails.

- **Architecture Highlights:** End-to-end Role-Based Access Control (RBAC) across Admin, Manager, and Agent roles with JWT security.
- **Impact & Scale:** Manages thousands of rental units, maintaining accurate historical payment and lease logs.
- **Tech Stack:** `React` · `Express` · `MongoDB` · `JWT` · `RBAC` · `TailwindCSS`
- 🔗 **Repository:** [Bedru-Mekiyu/rentalapp](https://github.com/Bedru-Mekiyu/rentalapp)

---

### 📜 Vital Registration System
> Offline-first registration system for low-connectivity regions that queues birth and death records locally and syncs to central PostgreSQL on reconnect.

- **Architecture Highlights:** Service Worker caching, IndexedDB local persistence, and background sync engines.
- **Impact & Scale:** Reduced registration turnaround from weeks to under 24 hours in low-bandwidth municipal offices.
- **Tech Stack:** `React` · `Node.js` · `PostgreSQL` · `Prisma` · `Service Worker` · `Background Sync`
- 🔗 **Repository:** [Bedru-Mekiyu/vital-registration-app](https://github.com/Bedru-Mekiyu/vital-registration-app)
- 🌐 **Live Demo:** [vital-registration-app.onrender.com](https://vital-registration-app.onrender.com)

---

### 📦 Multi-Location Inventory Dashboard
> Real-time inventory tracking dashboard with automated reconciliation workflows and low-stock alerting across multiple distribution nodes.

- **Architecture Highlights:** Event-driven WebSocket status broadcasts paired with typed Prisma relational queries.
- **Impact & Scale:** 85% reduction in inventory reconciliation discrepancies across registered stock locations.
- **Tech Stack:** `Next.js` · `Prisma` · `TypeScript` · `PostgreSQL` · `WebSockets`
- 🔗 **Repository:** [Bedru-Mekiyu/Inventory-app](https://github.com/Bedru-Mekiyu/Inventory-app)

---

### 🎯 Typed Issue Tracker
> Role-aware task management system with state-machine workflow state transitions and strict per-role view filtering.

- **Architecture Highlights:** Typed Next.js API routes with JWT authentication guards and strict Prisma relational model validation.
- **Tech Stack:** `Next.js` · `Prisma` · `TypeScript` · `JWT` · `PostgreSQL`
- 🔗 **Repository:** [Bedru-Mekiyu/Issue-Tracker](https://github.com/Bedru-Mekiyu/Issue-Tracker)

---

### 📚 BookSwap — Mobile Exchange Network
> Cross-platform mobile application enabling peer-to-peer book discovery, listing management, and swap requests.

- **Architecture Highlights:** Clean architectural separation built for cross-platform iOS and Android deployments.
- **Tech Stack:** `Flutter` · `Dart` · `Kotlin` · `REST API`
- 🔗 **Repository:** [bethelihemw/BookSwap](https://github.com/bethelihemw/BookSwap)

---

## 🏗️ Systems Engineering & AWS Case Study

### CivicVoice Production Infrastructure (AWS)
- **ECS Fargate Scaling:** Auto-scales 2 → 20 containers under load spikes within 60 seconds. Eliminated early OOM application crashes.
- **CloudFront Asset Delivery:** Edge caching reduced TTFB from ~2.4s to ~180ms for regional users (80% load time optimization).
- **RDS Aurora Reliability:** Configured point-in-time recovery with 35-day retention, 5-minute RPO target, and zero manual snapshot management overhead.

---

## 📌 Specialized Repositories & Modules

- [`ethio-tech-platform`](https://github.com/Bedru-Mekiyu/ethio-tech-platform) — Event-driven backend stack & Redis queue workflows.
- [`game-finder--app`](https://github.com/Bedru-Mekiyu/game-finder--app) — Rawg API integration built with React & TypeScript.
- [`events-nextjs`](https://github.com/Bedru-Mekiyu/events-nextjs) — Serverless Next.js event management platform.
- [`first-CI-CD`](https://github.com/Bedru-Mekiyu/first-CI-CD) — Automated deployment workflows using GitHub Actions.
- [`fastapi-issue-tracker`](https://github.com/Bedru-Mekiyu/fastapi-issue-tracker) — Lightweight Python/FastAPI backend service.

---

## 📖 Ongoing Technical Focus

- **AWS Certified Solutions Architect — Associate (SAA-C03)** preparation.
- **Distributed Systems Architecture:** Active study of *Designing Data-Intensive Applications* (Kleppmann) with focus on eventual consistency, idempotent API design, and distributed transaction boundaries.

---

## 📬 Connect & Collaborate

- **GitHub:** [@Bedru-Mekiyu](https://github.com/Bedru-Mekiyu)
- **LinkedIn:** [linkedin.com/in/bedru-mekiyu](https://linkedin.com/in/bedru-mekiyu)
- **Email:** [bedru.mekiyu-ug@aau.edu.et](mailto:bedru.mekiyu-ug@aau.edu.et)

*Open for software engineering opportunities, contract work, and technical collaborations.*
