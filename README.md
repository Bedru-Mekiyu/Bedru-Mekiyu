<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:1d4ed8&height=160&section=header&text=Bedru%20Mekiyu&fontSize=48&fontColor=ffffff&fontAlignY=42&animation=fadeIn" width="100%"/>

<br/>

**Software Engineer · Addis Ababa, Ethiopia**

Full-stack engineer focused on systems that work under real-world conditions —
offline environments, government infrastructure, and enterprise workflows.

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/bedru-mekiyu)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:bedru.mekiyu-ug@aau.edu.et)
[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/bedru_mekiyu)
[![Portfolio](https://img.shields.io/badge/bedru.dev-000000?style=flat-square&logo=vercel&logoColor=white)](https://bedru.dev)
[![Open to Work](https://img.shields.io/badge/Open%20to%20Work-22C55E?style=flat-square)](https://linkedin.com/in/bedru-mekiyu)

</div>

---

## About

CS / Software Engineering student at **Addis Ababa University**. I build production systems that reach real users — not demos. My work spans full-stack development, AWS infrastructure, and offline-first mobile and web applications.

I treat engineering as a systems discipline: reliability, predictability, and maintainability are not optional.

**Currently:** Building a Redis + BullMQ distributed task queue · Studying for AWS SAA-C03 · Reading *Designing Data-Intensive Applications*

---

## Skills

**Languages**
TypeScript · JavaScript · Python · Dart · Kotlin · SQL

**Frontend**
React · Next.js · Tailwind CSS · shadcn/ui · Vite · TanStack Query

**Backend**
Node.js · Express · Prisma · REST APIs · JWT · BullMQ

**Databases**
PostgreSQL · MongoDB · MySQL · Redis · Supabase

**Cloud & DevOps**
AWS (ECS Fargate · RDS Aurora · CloudFront · S3) · Docker · Terraform · GitHub Actions · Nginx

**Mobile**
Flutter · Kotlin

**Patterns**
Offline-First · RBAC · Event-Driven · Background Sync

---

## Projects

### Rental Management System
`Enterprise SaaS` · Express 5 · MongoDB · React 19 · [GitHub](https://github.com/Bedru-Mekiyu/rentalapp)

Property managers were tracking thousands of units in spreadsheets with no audit trail. I built a full SaaS platform with 5-role RBAC, two-factor authentication (TOTP + email OTP), lease lifecycle management, multi-gateway payments (Chapa · Telebirr · Stripe), and AES-256-GCM field encryption.

`134 commits` · `Team of 4`

---

### CivicVoice
`Government Platform` · React · Express · MongoDB · [GitHub](https://github.com/Bedru-Mekiyu/civicVoice-app) · [Live](https://civicvoice-app-1.onrender.com)

Citizens had no structured feedback channel — submissions were lost and unmeasurable. I built a multi-channel submission platform (SMS · WhatsApp · Web) with auto-routing to government departments, support for 7 Ethiopian languages, anonymous submissions, and an admin analytics dashboard.

`500+ submissions` · `40% faster response time` · `66 commits` · `Team of 4`

---

### Vital Registration System
`Offline-First Government` · React · Node.js · PostgreSQL · Prisma · [GitHub](https://github.com/Bedru-Mekiyu/vital-registration-app) · [Live](https://vital-registration-app.onrender.com)

Civil registration in rural Ethiopia took weeks because field workers lacked reliable connectivity. I built an offline-first system with local storage and background sync. Certificates are generated as QR-verifiable PDFs with blockchain anchoring for tamper-proof verification.

`Weeks → 24 hours`

---

### Inventory Dashboard
`Operations Tool` · Next.js · Prisma · PostgreSQL · [GitHub](https://github.com/Bedru-Mekiyu/Inventory-app) · [Live](https://inventory-app-5kb4.onrender.com)

Multi-location inventory had no real-time visibility or alerting. Built a multi-tenant dashboard with server-side pagination, full-text search, low-stock alerts, and 12-week trend charts.

`85% reduction in stock discrepancies`

---

### Issue Tracker
`Developer Tool` · Next.js · Prisma · MySQL · [GitHub](https://github.com/Bedru-Mekiyu/Issue-Tracker)

A lightweight alternative to Jira — 3-state workflow, Google SSO, markdown support, trend charts, and Zod-validated APIs.

`85 commits` · `Solo`

---

### BookSwap
`Consumer Mobile` · Flutter · Dart · Kotlin · [GitHub](https://github.com/bethelihemw/BookSwap)

Cross-platform mobile app for peer-to-peer book exchange with listing, discovery, and user profiles.

`47 commits` · `Team of 5`

---

## Infrastructure Decisions

Real choices made on government and enterprise projects.

| Decision | Problem | Outcome |
|---|---|---|
| ECS Fargate over EC2 | Traffic spikes during government announcements — needed 2 → 20 containers in under 60s | Eliminated OOM crashes at peak load |
| CloudFront + S3 | Users in regional offices experienced 800ms+ TTFB from origin | 80% reduction in frontend load time |
| RDS Aurora | Government required 35-day backup retention and point-in-time recovery | Zero backup overhead · 5-minute RPO |
| Offline-First + background sync | Registration in rural areas with no signal | Civil registration cut from weeks to 24 hours |
| AES-256-GCM field encryption | Multi-tenant SaaS needed data isolation at rest, not just at the access layer | Compliance-grade storage-level isolation |

---

## Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Bedru-Mekiyu&show_icons=true&count_private=true&hide_border=true&theme=transparent&icon_color=3B82F6&text_color=c9d1d9&title_color=3B82F6&include_all_commits=true" height="160"/>
&nbsp;
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Bedru-Mekiyu&hide_border=true&theme=transparent&ring=3B82F6&fire=3B82F6&currStreakNum=c9d1d9&sideNums=c9d1d9&currStreakLabel=3B82F6&sideLabels=3B82F6&dates=8b949e" height="160"/>

<br/><br/>

<img src="https://github-profile-trophy.vercel.app/?username=Bedru-Mekiyu&theme=onedark&no-frame=true&no-bg=true&row=1&column=7&margin-w=10" width="100%"/>

</div>

---

## Contact

Open to full-stack, DevOps, and remote roles — especially systems that need to operate under real-world constraints.

[bedru.mekiyu-ug@aau.edu.et](mailto:bedru.mekiyu-ug@aau.edu.et) · [LinkedIn](https://linkedin.com/in/bedru-mekiyu) · [Telegram](https://t.me/bedru_mekiyu) · [bedru.dev](https://bedru.dev)

<div align="center">
<br/>
<img src="https://raw.githubusercontent.com/Bedru-Mekiyu/Bedru-Mekiyu/output/github-contribution-grid-snake-dark.svg" width="100%" alt="Contributions"/>
<br/>
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1d4ed8,100:0f172a&height=100&section=footer" width="100%"/>
</div>
