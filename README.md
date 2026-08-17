<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=280&color=0:020617,100:1E293B&text=Aravindan%20Singaram&fontColor=ffffff&fontSize=42&fontAlignY=40&desc=Cloud%20%26%20Data%20Engineering%20%E2%80%A2%20Backend%20Engineering%20%E2%80%A2%20AI%20%26%20Agent%20Engineering&descAlignY=62&descColor=CBD5E1"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=950&lines=Building+Production-Ready+Backend+Systems;Designing+Data+Pipelines+and+RAG+Systems;Engineering+AI+Agents+with+LangGraph;Deploying+Containerised+Applications;Exploring+Cloud%2C+Data+and+Distributed+Systems"/>

<br/>

<a href="https://github.com/Aravindan-001">
<img src="https://komarev.com/ghpvc/?username=Aravindan-001&style=for-the-badge&color=0ea5e9"/>
</a>

<a href="https://github.com/Aravindan-001?tab=followers">
<img src="https://img.shields.io/github/followers/Aravindan-001?style=for-the-badge&logo=github"/>
</a>

<a href="https://www.linkedin.com/in/aravindansingaram">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="mailto:aravindansingaram@gmail.com">
<img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

</div>

---

# 👋 About Me

I'm **Aravindan Singaram**, a 5th-semester **B.Tech Information Technology** student focused on building backend systems, data pipelines, AI agents, and cloud-deployed applications.

My current engineering focus sits at the intersection of **Data Engineering + Backend Engineering + Cloud/DevOps + AI/Agent Engineering**.

I enjoy taking a system from **data ingestion and database design → APIs → AI workflows → testing → containerisation → production deployment**.

name: Aravindan Singaram

education:
  degree: B.Tech Information Technology
  institution: NPR College of Engineering and Technology
  duration: 2024 - 2028

focus:
  - Data Engineering
  - Backend Engineering
  - Cloud & DevOps
  - AI & Agent Engineering

currently_building:
  - NORA — Agency Operations, Knowledge Graph & AI Agent Platform
  - Data pipelines
  - AI-integrated backend systems

certifications:
  - Neo4j Certified Professional
  - MongoDB Basics for Students
  - Prompt Engineering with GitHub Copilot
````
 🧠 What I Build

* **Backend systems** with FastAPI, Laravel, Node.js and layered architectures
* **Data platforms** using PostgreSQL, pgvector, MongoDB, Neo4j and Redis
* **ETL / ELT pipelines** with webhook ingestion, validation, transformation and AI classification
* **RAG systems** with vector retrieval, context construction and grounded LLM responses
* **AI agents** using LangGraph, tool execution, intent routing and confirmation-gated actions
* **Production applications** containerised with Docker and deployed using Nginx, Render, AWS S3 and Cloudflare
* **Cross-platform applications** using SvelteKit, React Native and Flutter

---

# 🛠 Tech Stack

### Languages

<p>
<img src="https://skillicons.dev/icons?i=python,ts,js,php,dart,c"/>
</p>

Python • SQL • TypeScript • JavaScript • PHP 8.2+ • Dart • C

### Backend

<p>
<img src="https://skillicons.dev/icons?i=fastapi,laravel,nodejs,express,flask"/>
</p>

FastAPI • Laravel 12 • Node.js • Express.js • Flask • REST APIs • SQLAlchemy 2.x • Pydantic • Pydantic Settings

Router → Service → Repository Architecture • RBAC • Supervisor Queue Processing

### Data & Databases

<p>
<img src="https://skillicons.dev/icons?i=postgresql,mysql,mongodb,redis,neo4j"/>
</p>

PostgreSQL • pgvector • MySQL 8 • MongoDB Atlas • Neo4j • Redis • Supabase • Firebase

### Data Engineering

ETL / ELT • Data Ingestion • Data Transformation & Validation • Data Modelling

API-based Ingestion • Webhook-driven Workflows • Knowledge Indexing Pipelines • Vector Embeddings

### AI & Agents

LangGraph • LangChain / LCEL • RAG • pgvector Retrieval • OpenAI • Gemini

Prompt Engineering • Agentic Tool Layer • Structured Generation

Conversational Memory • Intent Routing • Confirmation-gated AI Actions • n8n

### Frontend & Mobile

<p>
<img src="https://skillicons.dev/icons?i=svelte,nextjs,react,ts,tailwind,vite,flutter"/>
</p>

SvelteKit • Svelte 5 • Next.js 15 • React 19 • React Native Expo

Flutter • Tailwind CSS • shadcn/ui • Framer Motion • Vite

### Cloud & DevOps

<p>
<img src="https://skillicons.dev/icons?i=docker,nginx,aws,cloudflare,git,github"/>
</p>

Docker • Render • AWS S3 • Cloudflare DNS/CDN/Proxy

Nginx • Supervisor • Git/GitHub • Deployment Verification • Security Headers/CSP

### Testing

Pytest • HTTPX • Integration Testing • API Testing

npm run check • npm run build

---

# 🚀 Featured Projects

## 🤖 NORA — Agency Operations, Knowledge Graph & AI Agent Platform

**2026 · FastAPI + PostgreSQL + pgvector + LangGraph + SvelteKit**

A full-stack agency operations platform connecting structured business data with conversational AI and semantic knowledge retrieval.

### Engineering Highlights

* Modelled **Clients → Leads → Projects → Tasks** as PostgreSQL relational entities with foreign keys, cascading deletion and Alembic migrations.
* Built a layered **Router → Service → Repository** backend using FastAPI, SQLAlchemy and Pydantic.
* Expanded the integration test suite from **134 to 303 passing Pytest/HTTPX tests**.
* Integrated **pgvector** for entity-aware semantic retrieval, relevance scoring and idempotent knowledge re-indexing.
* Implemented a complete **RAG pipeline**:

```text
Knowledge Retrieval
        ↓
Entity-aware Context Construction
        ↓
Structured LLM Generation
        ↓
Grounded Response
        ↓
Source Metadata
```

* Built a **LangGraph StateGraph** with three major branches:

  * Knowledge / RAG
  * Action / Tool
  * General LLM
* Implemented AI-driven CRUD tools with **confirmation-gated mutations**.
* Implemented bounded multi-turn conversational memory.
* Added persistent **PostgreSQL-backed session storage** with an in-memory fallback.
* Implemented entity-aware follow-up resolution for references such as:

  * "second project"
  * "that client"
* Built the ORBIT conversational interface using **SvelteKit + Svelte 5**.
* Optimised graph rendering using O(1) Map-based edge lookups.

---

## 💎 Svaraa Jewels — Production E-commerce Platform

**2025 · Laravel 12 + MySQL 8 + Redis + Docker + Nginx + Render**

Production-oriented jewellery e-commerce platform with payment processing, background jobs, administration, search and cloud deployment.

### Engineering Highlights

* Built product catalogue, cart, order management, inventory, coupons and reviews.
* Implemented **Razorpay webhook-based payment confirmation**.
* Added invoice generation and background order processing.
* Used **Redis + Supervisor** for queue-based background processing.
* Containerised the application stack using **Docker**.
* Configured **Nginx** for production deployment.
* Deployed the application to **Render**.
* Integrated **AWS S3** for file storage.
* Integrated **Cloudflare** for DNS, CDN, proxy and web security.
* Implemented **Security Headers and CSP**.
* Debugged production environment and filesystem/storage issues.
* Built a **Filament 5** administration system.
* Added bulk upload and PDF catalogue import workflows.
* Implemented full-text search using **Laravel Scout + Meilisearch**.
* Designed and optimised MySQL database queries.

Repository:

`github.com/nexoralabs-website/svaraa-jewels`

---

## 📊 WhatsApp Lead Engagement & CRM Data Pipeline

**2025 · n8n + Supabase/PostgreSQL + WhatsApp API + Gemini + React**

An event-driven ETL and AI classification pipeline for automated lead engagement and CRM management.

### Architecture

```text
Lead Capture
     ↓
Webhook Ingestion
     ↓
Data Normalisation
     ↓
Validation
     ↓
PostgreSQL / Supabase
     ↓
Gemini AI Classification
     ↓
Lead Scoring
     ↓
CRM Update
     ↓
React Dashboard
```

### Highlights

* Designed the ingestion and normalisation layer between webhooks and PostgreSQL.
* Implemented schema validation before database writes.
* Integrated Gemini for automated reply analysis and lead classification.
* Implemented lead scoring workflows.
* Built event-triggered CRM updates and alerts.
* Built a React dashboard for monitoring lead activity.

---

## 📱 Shri Vishwakarma Matrimony — Flutter Mobile App

**2025 · Flutter + Dart + PHP + MySQL + REST APIs**

Production-oriented matrimonial application featuring:

* Profile management
* Search and filtering
* Membership tiers
* Premium workflows
* Chat restrictions
* Interest workflows
* Tamil / English bilingual UI

### Engineering

* Applied **Provider + Repository Pattern**.
* Built PHP/MySQL REST APIs.
* Implemented JWT authentication.
* Implemented business logic and RBAC.
* Built Material 3 based UI.

---

## 🎓 CampusIQ — AI-Powered Placement Readiness System

**2024 · React Native Expo + Supabase + PostgreSQL**

An AI-assisted placement readiness platform.

### Features

* NLP-based Placement Readiness Score **0–100**
* Resume skill extraction
* Skill-gap detection
* Company eligibility prediction
* Admin analytics dashboard
* Supabase Authentication
* PostgreSQL Row Level Security
* Supabase Storage
* Realtime synchronisation

---

## 📈 SkillMarket AI — Skill Intelligence Platform

**2024 · React Native Expo + Supabase/PostgreSQL**

A mobile platform focused on personalised job-market skill recommendations.

### Engineering

* Designed a **15-table PostgreSQL schema**.
* Implemented Row Level Security.
* Enforced user-level data isolation.
* Built personalised skill recommendation workflows.

---

## 📊 Firebase / GA4 / Google Ads Analytics Integration

**2024 · Firebase Analytics + Crashlytics + GA4 + Google Ads**

Implemented mobile analytics and conversion tracking workflows.

Tracked events including:

`first_open` • `session_start` • `view_item` • `generate_lead` • `post_property` • `plan_purchase`

Analysed conversion funnels for marketing optimisation.

---

# 🏆 Achievements & Leadership

* **Smart India Hackathon** — selected project; developed an AI and automation-based solution addressing a real-world problem statement.
* Participated in multiple hackathons involving AI classification, mobile application development, backend API engineering and workflow automation.
* Mentored junior students on **React Native, Laravel and Supabase** integration.
* **Neo4j Certified Professional**.
* Active GitHub developer maintaining project repositories, technical documentation and collaborative development workflows.

---

# 🎯 Current Focus

```yaml
learning:
  - Advanced Data Engineering
  - Cloud Infrastructure
  - Distributed Systems
  - Advanced Backend Architecture
  - AI Agent Systems

building:
  - NORA
  - Data Pipelines
  - AI-integrated Backend Systems
  - Cloud-deployed Applications

exploring:
  - Vector Databases
  - Knowledge Graphs
  - Event-driven Architecture
  - Workflow Automation
  - Observability
  - Production Infrastructure

target_roles:
  - Data Engineering
  - Backend Engineering
  - Cloud / DevOps
  - AI Engineering
```

---

# 📊 GitHub Analytics

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Aravindan-001&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github"/>

<img height="170" src="https://streak-stats.demolab.com?user=Aravindan-001&theme=tokyonight&hide_border=true"/>

</div>

<br>

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Aravindan-001&layout=compact&theme=tokyonight&hide_border=true"/>

</div>

---

# 🏆 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=Aravindan-001&theme=tokyonight&no-frame=true&no-bg=true&margin-w=10&row=1"/>

</div>

---

# 📈 Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Aravindan-001&theme=tokyo-night&hide_border=true"/>

</div>

---

# 🌐 Connect With Me

<div align="center">

<a href="mailto:aravindansingaram@gmail.com">
<img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<a href="https://www.linkedin.com/in/aravindansingaram">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://github.com/Aravindan-001">
<img src="https://img.shields.io/badge/GitHub-111827?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</div>

---

# 🐍 Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg"/>

</div>

---

<div align="center">

### Building scalable data, backend and AI systems — one production-ready component at a time.

</div>
```
