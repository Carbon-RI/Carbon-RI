# Ray(Ryo) Ito | Full-Stack Developer & Project Architect

## From Physical Infrastructure to Digital Solutions
With **15 years of experience in Construction Project Management**, I have specialized in the delivery of critical infrastructure, including **large-scale data centers** in Japan and Singapore.

This background defines my approach to software engineering: I don't just write code; I architect systems with the same precision and commitment to reliability required for physical mission-critical facilities.

* **Engineering Focus**: Deeply committed to **Next.js**, **TypeScript**, and **Node.js**.
* **Strategic Mindset**: Leveraging over a decade of leading multinational teams to deliver high-performance software with absolute technical integrity.
* **Value**: Bridging the gap between complex project oversight and modern full-stack development.

[Portfolio](https://www.ryoito.dev/) | [LinkedIn](https://www.linkedin.com/in/ryo-ito46/)

---

## Technical Strategy & Stack

### Core Expertise
> **Building robust, high-performance web applications through type-safe architecture and Next.js optimization.**
![](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=next.js&logoColor=white) ![](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white) ![](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

### Engineering Ecosystem
* **Frontend & Mobile:** React, Tailwind CSS, Vite, React Native (Expo)
* **Backend & Data:** Supabase (RPC/Realtime), Express, MongoDB, Firebase, **Zod**
* **Infrastructure:** Docker, AWS (S3/EC2), Vercel (CI/CD), GitHub Actions
* **Governance:** Strategic Architecture Design, Agile (Jira), Python

---

### Engineering Meets Minimalism: Personal Portfolio
[Live Demo](https://www.ryoito.dev) | [Source Code](https://github.com/Carbon-RI/Portfolio-2026)

A performance-driven portfolio embodying **"Strategic Minimalism"**—designed to solve the trade-off between high-end visual aesthetics and peak engineering performance.

* **RSC-Centric Architecture**: Shifted all data-fetching to the server-side and restricted use client to leaf nodes, resolving initial hydration bottlenecks caused by heavy SDKs.
* **Performance Optimization**: Substituted JS-heavy animation libraries with native **Tailwind CSS** optimizations and aggressive **tree-shaking** of the Firebase SDK to minimize bundle size.
* **Schema-Driven Development**: Implemented a type-safe content pipeline using **Zod** and Firebase, bridging dynamic CMS flexibility with strict **runtime data integrity**.
* **Lighthouse 100**: Achieved perfect scores as a direct result of this "Strategic Minimalism" and intentional architectural decisions.

---

### Architecture & Data Integrity: Impacto (Rebuild)
[Live Demo](https://impacto-live-chat.vercel.app/) | [Source Code](https://github.com/Carbon-RI/Impacto-live-chat) | [Full Case Studies in Portfolio](https://www.ryoito.dev/projects/impacto-chat-redesign)

Performed a fundamental architectural redesign of a real-time chat module to transition from a "feature-first" prototype to a **"consistency-first"** production system.

* **Database as SSoT**: Migrated from client-side state management to a **Single Source of Truth (SSoT)** model, restricting all data mutations to **Supabase RPCs** to eliminate multi-client state drift.
* **Atomic Transaction Design**: Resolved **TOCTOU (race condition)** vulnerabilities by unifying authorization checks and data writes within single database transactions using INSERT ... SELECT logic.
* **WAL-based Real-time Sync**: Replaced traditional WebSocket events with **PostgreSQL Write-Ahead Log (WAL)** subscriptions, ensuring the UI reflects only "committed facts" rather than unverified client events.
* **Type-Safe Contract**: Established end-to-end type safety by synchronizing the database schema with the TypeScript frontend via Supabase CLI, ensuring high refactoring resilience.

---

### Technical Leadership & Team Projects
While these repositories are private due to team development, they demonstrate my ability to lead technical strategy and solve complex domain challenges.

Dosis (MedTech) | FullStack Dev

[Full Case Studies in Portfolio](https://www.ryoito.dev/projects/dosis)
* **Strategic Pivot**: Engineered a **"Two-Step Validation"** architecture using Drug Identification Numbers (DIN) to resolve data inconsistencies inherent in raw OCR, prioritizing **medical data integrity**.
* **Reliable Scheduling**: Architected a lifestyle-linked notification system using **Agenda and Expo**, ensuring precise medication logging and automated safety-guard checks against interaction databases.

Cubie (EdTech) | Technical Lead

[Full Case Studies in Portfolio](https://www.ryoito.dev/projects/cubie)
* **Tech Strategy**: Prioritized team velocity and maintainability by selecting a **Vanilla React (Vite)** stack over high-level frameworks, building core infrastructure from scratch for full transparency.
* **Secure Infrastructure**: Designed a multi-layered security model including **HttpOnly Cookies** and **AWS S3 Presigned URLs**, ensuring **FIPPA compliance** for educational data.
* **Adaptive Governance**: Established a **monorepo structure** and standardized directory patterns to eliminate development ambiguity for a distributed team.
