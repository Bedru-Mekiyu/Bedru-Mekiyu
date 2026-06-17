<div align="center">

# Bedru Mekiyu

**Software Engineer · Addis Ababa, Ethiopia**

Full-stack engineer focused on systems that reach real users under real constraints — government infrastructure, enterprise SaaS, and education platforms.

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/bedru-mekiyu)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:bedru.mekiyu-ug@aau.edu.et)
[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/bedru_mekiyu)
[![Portfolio](https://img.shields.io/badge/bedru.dev-000000?style=flat-square&logo=vercel&logoColor=white)](https://bedru.dev)
[![Open to Work](https://img.shields.io/badge/Open%20to%20Work-22C55E?style=flat-square)](https://linkedin.com/in/bedru-mekiyu)

</div>

---

## About

CS / Software Engineering student at **Addis Ababa University**. I build production systems — government platforms, enterprise SaaS, edtech — not demos. My work spans full-stack development, AWS infrastructure, and offline-capable applications designed for environments where connectivity is unreliable.

I treat engineering as a systems discipline: reliability, predictability, and maintainability are not optional.

**Currently:** Building a Redis + BullMQ distributed task queue · Studying for AWS SAA-C03 · Reading *Designing Data-Intensive Applications*

---

## Flagship — EthioTech Platform

`Education · Open Source · MIT` · React 19 · TypeScript · Vite · Tailwind 4 · Three.js · Konva · Socket.io · Node 22 · Express 4 · MongoDB · Redis · Jitsi · [GitHub](https://github.com/Bedru-Mekiyu/ethio-tech-platform)

Ethiopia has the talent but lacks access to job-ready tech education outside Addis Ababa. EthioTech is a hands-on learning platform with live mentorship, real-time classrooms, and a structured curriculum — built to fix the country's tech education gap.

The platform is a 49-model MongoDB architecture with 46 controllers, 7 RBAC roles (30+ granular permissions), realtime classrooms via Socket.io + Jitsi, a Konva-based collaborative whiteboard, breakout rooms, hand-raise queues, live polls, Q&A, presence tracking, engagement scoring, and a 50-level XP/achievements system.

`622 commits` · `2 contributors` · `MIT licensed`

---

## Featured Projects

### Rental Management System
`Enterprise SaaS` · Express 5 · Mongoose · React 19 · [GitHub](https://github.com/Bedru-Mekiyu/rentalapp)

Property companies were tracking thousands of units in spreadsheets with no audit trail. I built a multi-role SaaS platform with TOTP + email-OTP + backup-code 2FA, AES-256-GCM field encryption for PII, RBAC with session management, lease lifecycle workflows, multi-gateway payment processing (Chapa · Telebirr · Stripe · Flutterwave), CSRF + rate-limiting + DOMPurify sanitization, Sentry observability, and AWS S3/SES integration.

`152 commits` · `4 contributors`

---

### CivicVoice
`Government Platform` · React · Express · MongoDB · [GitHub](https://github.com/Bedru-Mekiyu/civicVoice-app) · [Live](https://civicvoice-app-1.onrender.com)

Citizens had no structured feedback channel — submissions to government departments were lost and unmeasurable. I built a multi-sector civic engagement platform supporting 7 Ethiopian languages (Amharic, Oromo, Tigrinya, Somali, Afar, Gurage, English), anonymous submissions, and an admin analytics dashboard with CSV export.

`66 commits` · `4 contributors`

---

### Vital Registration System
`Government · PWA` · React · Node.js · PostgreSQL · Prisma · [GitHub](https://github.com/Bedru-Mekiyu/vital-registration-app) · [Live](https://vital-registration-app.onrender.com)

Civil registration in rural Ethiopia is slow and unreliable. The platform digitalizes birth, death, marriage, divorce, and adoption records with 7 database models, 6 user roles, audit logging, and gamification. Certificates are generated as QR-verifiable PDFs. PWA install + planned service-worker offline support for low-connectivity field work.

`20 commits` · `Solo`

---

### Issue Tracker
`Developer Tool` · Next.js · Prisma · MySQL · [GitHub](https://github.com/Bedru-Mekiyu/Issue-Tracker)

A lightweight Jira alternative — 3-state workflow, Google SSO, markdown descriptions, trend charts, Zod-validated APIs, and a Docker Compose setup for local MySQL.

`79 commits` · `Solo`

---

### Inventory Dashboard
`Operations Tool` · Next.js · Prisma · PostgreSQL · [GitHub](https://github.com/Bedru-Mekiyu/Inventory-app) · [Live](https://inventory-app-5kb4.onrender.com)

Multi-location inventory with server-side pagination, full-text search, low-stock alerts, and 12-week trend charts.

`28 commits` · `Solo`

---

## Open Source

**[BookSwap](https://github.com/bethelihemw/BookSwap)** — Cross-platform mobile app for peer-to-peer book exchange, built with Flutter/Dart and Kotlin. Contributed as part of a 5-person team (12 of ~37 commits).

---

## Architecture Decisions

Real choices made on government, enterprise, and edtech projects.

| Decision | Problem | Outcome |
|---|---|---|
| Redis adapter for Socket.io | Need horizontal scale for realtime classrooms across multiple Node instances | Single pub/sub channel across the cluster; no sticky sessions |
| 7-role RBAC with 30+ granular permissions | Edtech platform serves students, mentors, parents, schools, and admins with very different access patterns | One permission model; no role-explosion hacks |
| Konva + Socket.io whiteboard | Live classrooms need collaborative drawing with undo history | Concurrent multi-user sessions with optimistic local state |
| ECS Fargate over EC2 | Traffic spikes during government announcements — needed 2 → 20 containers in under 60s | Eliminated OOM crashes at peak load |
| CloudFront + S3 | Users in regional offices experienced 800ms+ TTFB from origin | 80% reduction in frontend load time |
| RDS Aurora | Government required 35-day backup retention and point-in-time recovery | Zero backup overhead · 5-minute RPO |
| Offline-first + background sync | Registration in rural areas with no signal | Civil registration cut from weeks to 24 hours |
| AES-256-GCM field encryption | Multi-tenant SaaS needed data isolation at rest, not just at the access layer | Compliance-grade storage-level isolation |

---

## Skills

**Languages**
TypeScript · JavaScript · Python · SQL · Kotlin · Dart

**Frontend**
React · Next.js · Tailwind CSS · shadcn/ui · Vite · TanStack Query · Zustand

**Backend**
Node.js · Express · Prisma · REST APIs · JWT · Socket.io · BullMQ

**Databases**
PostgreSQL · MongoDB · MySQL · Redis · Supabase

**Cloud & DevOps**
AWS (ECS Fargate · RDS Aurora · CloudFront · S3 · SES) · Docker · Terraform · GitHub Actions · Nginx · Render · Vercel · Railway

**Mobile**
Flutter · Kotlin

**Patterns**
Offline-First · RBAC · Event-Driven · Realtime Systems · Background Sync · Multi-Tenant Architecture

---

## What I'm Working Toward

Distributed systems, real-time infrastructure, and platforms that work in low-connectivity environments. Short-term: AWS SAA-C03 certification, shipping the EthioTech realtime classroom to production, and a Redis-backed task queue for background processing. Long-term: leading systems work on platforms that matter at a national scale — edtech, govtech, public infrastructure.

---

## Contact

Open to full-stack, platform, and DevOps roles — especially systems that need to operate under real-world constraints.

[bedru.mekiyu-ug@aau.edu.et](mailto:bedru.mekiyu-ug@aau.edu.et) · [LinkedIn](https://linkedin.com/in/bedru-mekiyu) · [Telegram](https://t.me/bedru_mekiyu) · [bedru.dev](https://bedru.dev)