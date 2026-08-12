# 👋 Hello, I'm Ahmed Shawky

> **Frontend Developer | Next.js Specialist | Aspiring Full-Stack Engineer**  
> Building scalable, performant web experiences with clean architecture and pragmatic engineering principles.

---

## 🚀 About Me

I'm a passionate web developer focused on crafting **fast, responsive, and maintainable** applications. Currently working on **"Hakawi"** – a modular monolith platform built with **Next.js 15 App Router**, where I apply **SOLID**, **DDD**, and **RBAC** patterns to solve real-world complexity.

I believe in **simplicity over cleverness**, **documentation over assumptions**, and **architecture before code**. My goal is to bridge the gap between frontend polish and backend robustness – one commit at a time.

---

## 🛠️ My Tech Stack

[![My Skills](https://skillicons.dev/icons?i=nextjs,typescript,react,nodejs,postgresql,redis,docker,git,github,linux,tailwind,vscode,vercel)](https://skillicons.dev)

### 🔹 Core Development
- **Next.js 15** (App Router, Server Actions, Middleware, Edge Runtime)
- **TypeScript** (strict mode, unified typing, no `any`)
- **React** (React Hook Form, TanStack Query, shadcn/ui)
- **Internationalization**: next-intl

### 🔹 Backend & Data
- **Drizzle ORM** – type-safe database access
- **PostgreSQL** – relational data modeling
- **Valkey (Redis-compatible)** – caching & distributed locks via Docker
- **Sanity CMS** – headless content management

### 🔹 DevOps & Observability
- **Docker** – local development & service isolation
- **Sentry** – error tracking & performance monitoring
- **Winston** – structured logging (never `console.log` in prod 😉)
- **GitHub Actions** – CI/CD foundations

### 🔹 Architecture & Patterns
- Modular Monolith design
- Loose Coupling + Open/Closed Principle
- SSOT (Single Source of Truth) mindset
- RBAC (Role-Based Access Control)
- Distributed sync patterns with retry & failover

---

## 💡 My Engineering Principles (The Realistic 12)

These aren't just buzzwords – they're daily practices I follow before writing any major feature:

1. 🚫 **No `any` / `as any`** in TypeScript – type safety is non-negotiable  
2. 🪵 **Logger over `console`** – structured, level-based logging always  
3. 🔢 **IDs as strings** – avoid integer leakage & ease future migrations  
4. 📝 **Document problems & solutions** – future-me will thank present-me  
5. 🗺️ **Draw architecture before coding** – clarity beats speed in the long run  
6. 🔄 **Minimize DB migrations** – plan schema changes thoughtfully  
7. 🔗 **Loose Coupling** – modules communicate, but don't depend  
8. 🔓 **Open/Closed** – extend behavior, don't modify core  
9. ✅ **SSOT (Single Source of Truth)** – one canonical data flow  
10. 🧩 **Unified Typing** – shared types across frontend/backend  
11. ⚡ **Valkey + Docker for caching** – predictable, portable performance  
12. 🛑 **Avoid cascade failures** – isolate sync, retry smartly, fail gracefully  

---
## 🏗️ Architecture Philosophy
📦 Hakawi – Monolith (Next.js 15)
│
├── 🎨 Frontend: React UI + RHF + TanStack Query + next-intl
├── 🔄 Next.js Layer: App Router + Middleware + Server Actions
├── 🌐 API Layer: auth / user / admin / sync / webhooks
├── ⚙️ Business Logic: Services + Domain Entities + RBAC
├── 🛡️ Resilience: Circuit Breaker + Health Checks + Failover
├── 🔁 Sync Unit: Queue + Retry + Distributed Lock
├── 🗄️ Data Access: Repositories + Drizzle + Sanity + Valkey
├── 🌍 External: PostgreSQL, Sanity, Sentry, Paymob, Google OAuth
└── 🔔 Webhooks: Sanity → API → Sync Engine


I prioritize **maintainability**, **observability**, and **gradual evolution** – because great systems are built, not born.

---

## 🎯 Currently Focusing On

- ✅ Deepening **Domain-Driven Design** patterns in practice  
- ✅ Refining **ID Unification Strategy** (moving from `googleId` PK → serial `id` + auth fields)  
- ✅ Exploring **lightweight alternatives** (HTMX, Alpine.js) for specific use-cases  
- ✅ Writing more **technical content** about architecture decisions & trade-offs  
- ✅ Contributing to **open-source tools** that solve real developer pain points  

---

## 📫 Let's Connect

I'm always open to discussing:
- 🤝 Collaborations with startups & product teams  
- 💬 Architecture reviews or technical mentorship  
- 🌱 Growth-oriented projects that value clean code & user experience  

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ahmedshawky770/Ahmedshawky770) [![GitLab](https://shields.io)](https://gitlab.com/aahmedshawkyy77) [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmed-shawky-116766262/) [![Email](https://shields.io)](mailto:aahmedshawkyy77@gmail.com)

---

> *"Code is like humor. When you have to explain it, it's bad."*  
> But when architecture is clear, even complex systems feel simple. 🏗️✨

---

*🔧 This profile is kept realistic, updated with actual tools I use daily – no hype, just craft.*  
*Last updated: May 2026*
