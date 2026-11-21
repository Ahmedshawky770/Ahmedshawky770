# Ahmed Shawky

**Full-Stack Developer | TypeScript & Rust**

I build web products and systems software, with an interest in clear domain boundaries, reliable data flows, and practical testing. My work spans product features, backend APIs, databases, deployment tooling, and native desktop software.

## Selected projects

### HAKAWI — Arabic storytelling platform
My current main product project: a bilingual Arabic/English platform for stories, readers, and publishers.

- **Stack:** Next.js App Router, NestJS, TypeScript, PostgreSQL, Drizzle ORM, Valkey
- **Includes:** authentication and MFA, publishing and social features, moderation, messaging, books, payments, rentals, and administration
- **Engineering:** modular backend, shared TypeScript contracts, SQL migration runner, automated tests, observability, Docker, and infrastructure-as-code
- **Status:** Pre-release development. Reliability and deployment checks are still in progress; the repository's CI status is the source of truth.

[Repository](https://github.com/Ahmedshawky770/HAKAWI)

### herafinho — location-aware service marketplace
A marketplace concept connecting clients with local craftspeople, including service requests and order workflows.

- **Stack:** Next.js, TypeScript, PostgreSQL/PostGIS, Drizzle ORM, Valkey
- **Architecture:** npm-workspaces monorepo with a web app, shared packages, background workers, and a WebSocket service
- **Engineering:** geospatial search, real-time location features, background jobs, event outbox, tests, and CI/CD
- **Status:** Separate project repository; its latest checked CI runs were not green, so deployment readiness should not be assumed.

[Repository](https://github.com/Ahmedshawky770/herafinho)

### FrameForge — Linux-first video tooling
An experimental desktop video player and editing project, with a Rust core and a Tauri interface.

- **Stack:** Rust, Tauri 2, libmpv, FFmpeg, HTML, and TypeScript
- **Focus:** media playback, frame scrubbing, cut/merge planning, and video export
- **Also includes:** a CLI, reusable Rust crates, and an early playback-only web component
- **Status:** Experimental; export correctness, platform behavior, and CI still need further validation.

[Repository](https://github.com/Ahmedshawky770/FrameForge)

### Earlier HAKAWI implementation
I previously built HAKAWI as a Next.js-centered application with PostgreSQL, Drizzle, Sanity, Valkey, authentication, and a broad set of product features. I stopped that iteration after the feature scope and architecture became too coupled, then began the current HAKAWI implementation with clearer frontend/backend boundaries. It is a **legacy project**, not a companion to the current app.

## Areas I work with

- **Frontend:** TypeScript, React, Next.js, accessible interfaces, Arabic/English localization, RTL
- **Backend:** NestJS, REST APIs, WebSockets, authentication/authorization, background jobs, event-driven workflows
- **Data:** PostgreSQL, Drizzle ORM, SQL migrations, PostGIS, Valkey
- **Systems:** Rust, Tauri, FFmpeg, libmpv
- **Delivery and operations:** Docker, GitHub Actions, GitLab CI, Terraform, Helm, AWS, structured logging and monitoring
- **Testing:** Vitest, Playwright, integration tests, migration checks, and load-test tooling

## How I approach engineering

I value explicit trade-offs, maintainable boundaries, and tests for important user and business flows. I also treat project status honestly: a documented architecture or CI workflow is not, by itself, proof that a feature is production-ready.

## Contact

- [GitHub](https://github.com/Ahmedshawky770)
- [LinkedIn](https://www.linkedin.com/in/Ahmedshawky770)

---

*This profile describes work in progress as well as completed experiments; project status is noted where relevant.*
