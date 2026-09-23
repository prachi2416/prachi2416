<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2E86AB,100:1B4965&height=180&section=header&text=Prachi%20Tripathi&fontSize=42&fontColor=ffffff&animation=fadeIn&desc=Software%20Engineer%20%E2%80%94%20Full-Stack%20%26%20Applied%20ML&descAlignY=62&descSize=18" alt="Header banner" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=3000&pause=1200&color=2E86AB&center=true&vCenter=true&width=650&lines=Full-Stack+Developer+%7C+Applied+ML;Building+production-grade+software;React+%7C+Node.js+%7C+Python+%7C+PostgreSQL" alt="Typing SVG" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/prachi-tripathi-24r16)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/prachi2416)

</div>

<br>

## About

I build products end-to-end — schema design, backend, frontend, and deployment — with a growing focus on applying machine learning to real workflows. My recent projects dig into the kind of engineering that's easy to skip in a portfolio: concurrency-safe rate limiting, locally-run RAG pipelines, and role-based multi-tenant systems.

Currently deepening my foundation in applied ML and system design through an M.S. in Data Science.

<br>

## Flagship Projects

### GateKeeper — Redis-Backed API Gateway & Rate Limiter
Implements three rate-limiting algorithms from first principles as atomic Lua scripts, eliminating the read-check-write race condition that lets concurrent requests bypass a naive limiter.
- Token Bucket, Sliding Window Log, and Sliding Window Counter — algorithm selectable per client
- Every state transition is a single atomic Lua script executed inside Redis — no TOCTOU races under concurrent load
- Fails closed (503) if Redis is unreachable, instead of silently letting all traffic through
- 11/11 tests passing; k6 burst/sustained-load scripts validate correctness under real concurrency, not just sequential calls

**Stack:** Node.js · Express · Redis · Lua · React · TypeScript · Docker

### DocMind — Fully Local RAG Platform for Document Intelligence
A two-tier Retrieval-Augmented Generation system where embeddings and inference run entirely on local infrastructure — no document content ever leaves the machine.
- Full ingestion → chunk → embed → store → retrieve → generate pipeline via ChromaDB (vector store) and Ollama (local LLM)
- Node.js serverless API layer separated from a stateful Python/FastAPI RAG engine — the same app/inference split used in production ML systems
- Dedicated Evaluation and Monitoring pages, so retrieval quality and system health are visible, not just assumed

**Stack:** Python · FastAPI · ChromaDB · Ollama · React · TypeScript · Supabase · Docker · Vercel

### LedgerBox — Multi-Tenant Financial Management Platform
A SaaS-style platform for expense, invoice, and team management with role-based access control enforced across owner/admin/member roles.
- Multi-organization support with org switching and persisted active-org state
- RBAC permission logic isolated into reusable helpers rather than scattered across UI components
- Type-safe throughout; data layer explicitly architected to swap local storage for Supabase/PostgreSQL with minimal changes

**Stack:** React 18 · TypeScript · Vite · Zustand · TanStack Query · Tailwind CSS · Recharts

<br>

## Tech Stack

**Languages**
<p><img src="https://skillicons.dev/icons?i=js,ts,python,java,kotlin,html,css" /></p>

**Frontend**
<p><img src="https://skillicons.dev/icons?i=react,tailwind,bootstrap,vite" /></p>

**Backend & Data**
<p><img src="https://skillicons.dev/icons?i=nodejs,postgres,redis,firebase,supabase" /></p>

**Tools & Platforms**
<p><img src="https://skillicons.dev/icons?i=git,github,docker,vscode,postman,vercel" /></p>

<br>

## Other Projects

| Project | What it does | Stack |
|---|---|---|
| **Real Estate Platform** | Property marketplace with buy/rent listings, an approval workflow, and status tracking across buyer, seller, and admin roles. | React.js · HTML · CSS |
| **Finance AI Application** | Personal finance app for expense tracking, budgeting, and investment monitoring, backed by an analytics dashboard. | React.js · JavaScript · Supabase |
| **ALT Life Foundation Website** | Production NGO platform: PostgreSQL on Supabase, Row-Level Security for data access control, and a CI/CD pipeline to cloud deployment. | React · TypeScript · PostgreSQL · Supabase |
| **LocalServe** | Three-sided service marketplace (customers, vendors, admins) with full request-lifecycle management and workflow automation. | React · Bootstrap |

<br>

## Certifications

- JavaScript Full Stack Developer Certification
- DSA Mastery with Java
- JPMorgan Chase Software Engineering Virtual Experience Program

<br>

## Education

**M.S., Data Science** — Thakur College of Science and Commerce · Expected 2028

**B.Sc., Computer Science** — Thakur College of Science and Commerce · CGPA 8.91 / 10

<br>

## Currently Exploring

```yaml
focus:
  - Machine Learning & Applied AI
  - System Design
  - Advanced SQL
  - Cloud Deployment & SaaS Architecture
```

<br>

<div align="center">

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/prachi-tripathi-24r16)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/prachi2416)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1B4965,100:2E86AB&height=100&section=footer" alt="Footer banner" />
