# Bedru Mekiyu

**Full-Stack Engineer · DevOps & Cloud** — Addis Ababa, Ethiopia

I build production-grade full-stack systems and ship them on AWS. My work focuses on offline-first government applications, multi-tenant SaaS with role-based access, and real-time operational dashboards. Currently a Software Engineering undergraduate at Addis Ababa University, available for full-stack roles, DevOps/cloud engineering, and remote contracts.

> Full-stack systems. Cloud infrastructure. Production-grade delivery.

---

## About

I design and ship software that operates under real conditions — offline environments, government infrastructure, enterprise workflows. My background spans full-stack TypeScript product engineering and AWS-based DevOps, with a track record of multiple production systems serving real users. I work in async-first distributed teams and treat engineering as a systems discipline: every application I build is designed to operate reliably, scale predictably, and be maintainable long-term.

---

## Current Focus

- **Building:** A distributed task queue system on Redis + BullMQ, and expanding the `ethio-tech-platform` event-driven stack.
- **Learning:** AWS Solutions Architect — Associate (SAA-C03). *Designing Data-Intensive Applications* — Kleppmann.
- **Maintaining:** Four deployed production applications (CivicVoice, Rental, Vital Registration, Inventory) and an active set of TypeScript services.

---

## Projects

### CivicVoice — Government Citizen Feedback Platform

- **Problem:** Citizens had no structured channel to submit feedback to government departments — submissions were lost, undirected, and unmeasurable.
- **Solution:** Multi-channel platform accepting submissions via SMS, WhatsApp, and web, with automatic routing to the correct department plus tracking and analytics. Deployed on AWS (ECS Fargate, CloudFront, RDS Aurora).
- **Impact:** 500+ submissions processed, 40% faster department response time, 3 input channels, live production deployment.
- **Stack:** React · Express · MongoDB · AWS ECS · CloudFront · RDS

🔗 [civicVoice-app](https://github.com/Bedru-Mekiyu/civicVoice-app) · [Live Demo](https://civicvoice-app-1.onrender.com)

### Rental Management System

- **Problem:** Property managers were tracking thousands of rental units across spreadsheets — no audit trail, no real-time state, error-prone workflows.
- **Solution:** Role-based access platform with lease lifecycle management, payment tracking, and multi-tenant workflows replacing the spreadsheet-based process.
- **Impact:** Manages thousands of units, 4-person team, full RBAC (admin / manager / agent), full payment and lease history.
- **Stack:** React · Express · MongoDB · JWT · RBAC · TailwindCSS

🔗 [rentalapp](https://github.com/Bedru-Mekiyu/rentalapp) · 134 commits

### Vital Registration System

- **Problem:** Birth and death registration in low-connectivity regions took weeks because the system depended on a live internet connection — critical records were delayed or lost.
- **Solution:** Offline-first registration system that stores records locally, continues working without internet, and syncs to the central database on reconnect via service workers and background sync.
- **Impact:** Registration time reduced from weeks to 24 hours. Fully functional offline. Deployed for government registration offices.
- **Stack:** React · Node.js · PostgreSQL · Prisma · Service Worker · Background Sync

🔗 [vital-registration-app](https://github.com/Bedru-Mekiyu/vital-registration-app) · [Live Demo](https://vital-registration-app.onrender.com)

### Inventory Dashboard

- **Problem:** Inventory discrepancies across multiple locations due to no real-time visibility and manual count reconciliation.
- **Solution:** Real-time multi-location inventory dashboard with low-stock alerting and automated reconciliation workflows.
- **Impact:** 85% reduction in inventory discrepancies, multi-location support, automated low-stock alerts, full audit history.
- **Stack:** Next.js · Prisma · TypeScript · PostgreSQL · WebSockets

🔗 [Inventory-app](https://github.com/Bedru-Mekiyu/Inventory-app) · [Live Demo](https://inventory-app-5kb4.onrender.com)

### Issue Tracker

- **Problem:** Engineering teams needed structured task tracking with role differentiation (developer / manager / admin) without enterprise-tool overhead.
- **Solution:** Typed role-aware task management system with JWT-secured API routes, workflow state machines, and per-role filtered views.
- **Impact:** Production-quality code path — role-based workflows, full TypeScript codebase, state machine-based task transitions.
- **Stack:** Next.js · Prisma · TypeScript · JWT · PostgreSQL

🔗 [Issue-Tracker](https://github.com/Bedru-Mekiyu/Issue-Tracker) · 79 commits

### BookSwap — Mobile Book Exchange

- **Problem:** Students and readers had no dedicated platform for book exchange — discovery was informal, trust low.
- **Solution:** Cross-platform mobile app for book listing, discovery, and peer-to-peer swap requests with user profiles and transaction history.
- **Impact:** Cross-platform iOS & Android build, 5-person collaborative build.
- **Stack:** Flutter · Dart · Kotlin · REST

🔗 [BookSwap](https://github.com/bethelihemw/BookSwap)

---

## Also Building

[`ethio-tech-platform`](https://github.com/Bedru-Mekiyu/ethio-tech-platform) ·
[`game-finder--app`](https://github.com/Bedru-Mekiyu/game-finder--app) ·
[`events-nextjs`](https://github.com/Bedru-Mekiyu/events-nextjs) ·
[`first-CI-CD`](https://github.com/Bedru-Mekiyu/first-CI-CD) ·
[`Internship`](https://github.com/Bedru-Mekiyu/Internship) ·
[`amazon`](https://github.com/Bedru-Mekiyu/amazon)

---

## Architecture & Systems Experience

- **Offline-first systems** — local persistence, conflict resolution, background sync (Vital Registration, CivicVoice offline mode).
- **Role-based access control (RBAC)** — admin / manager / agent, and developer / manager / admin role differentiation (Rental, Issue Tracker).
- **Authentication** — JWT, OAuth, session-based auth.
- **Realtime systems** — WebSockets, server-sent updates, event-driven ingestion (Inventory, CivicVoice).
- **API design** — REST, structured error handling, role-aware route guards.
- **Database design** — relational schemas (Prisma + PostgreSQL), document models (MongoDB), Redis-backed task queues.
- **Scalable architectures** — containerised services on AWS ECS Fargate, edge-cached static delivery via CloudFront, managed PostgreSQL via RDS Aurora.

---

## Technical Skills

- **Frontend:** TypeScript, React, Next.js, TailwindCSS, Flutter
- **Backend:** Node.js, Express, REST APIs, WebSockets, BullMQ, Redis
- **Data:** PostgreSQL, MongoDB, Prisma ORM, Supabase
- **Cloud & DevOps:** AWS (EC2, ECS, S3, RDS, Lambda, CloudFront, VPC, IAM, Route 53, CloudWatch, CodePipeline, ECR), Docker, Terraform, GitHub Actions, Nginx, Linux/Bash
- **Mobile:** Flutter, Dart, Kotlin, Jetpack Compose, Android
- **Tools:** Git, GitHub, Postman, Vercel, Render
- **Patterns:** Offline-first, RBAC, JWT auth, event-driven, sync architectures

---

## AWS & DevOps Highlight — CivicVoice Production

The CivicVoice deployment is the concrete evidence behind my AWS/DevOps capability:

- **ECS over EC2** — Fargate scales 2 → 20 containers in under 60 seconds for traffic spikes. Eliminated 3 OOM crashes in the first month.
- **CloudFront + S3 for static assets** — edge nodes cut TTFB from ~2.4s to ~180ms outside Addis. 80% frontend load-time reduction.
- **RDS Aurora over self-managed PostgreSQL** — built-in point-in-time recovery with 35-day retention, RPO of 5 minutes, zero backup-management overhead.

Full architecture decision log and diagram: [bedru.dev/#aws-case-study](https://bedru.dev/#aws-case-study)

---

---

## Learning

- **AWS Certified Solutions Architect — Associate (SAA-C03)** — in progress.
- **Designing Data-Intensive Applications** — Kleppmann (active reading).
- **Distributed systems patterns** — task queues, eventual consistency, idempotent operations.

---

## Open Source & Collaboration

I am interested in collaborating on:

- Offline-first web applications and PWA architecture.
- Government / civic-tech platforms that need real engineering discipline.
- TypeScript tooling — typed API layers, Prisma schema design, RBAC patterns.

Open to issues, PRs, and design discussions on any of the featured repositories.

---

## Connect

- GitHub: [@Bedru-Mekiyu](https://github.com/Bedru-Mekiyu)
- LinkedIn: [linkedin.com/in/bedru-mekiyu](https://linkedin.com/in/bedru-mekiyu)
- Email: [bedru.mekiyu-ug@aau.edu.et](mailto:bedru.mekiyu-ug@aau.edu.et)
- Portfolio: [bedru.dev](https://bedru.dev)

Open to full-stack roles, DevOps/cloud engineering, and remote work.
