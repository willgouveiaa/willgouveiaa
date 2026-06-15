# 👨‍💻 What's up? I'm Willian :]

**Senior PM & Builder** | OmniWave Group LLC 🇺🇸 | Brazil 🇧🇷

---

## 🎯 About Me

I'm a **Product, GenAI & Data Specialist** with 5+ years of experience as a Senior Product Manager at a LATAM bank. A tech enthusiast who builds real products — I founded **OmniWave Group LLC** to design and deliver SaaS solutions *from architecture to production*.

Every project here is a **complete product**: architecture, backend, frontend, deployment, and production maintenance. I work with **Django**, **Next.js**, **Astro**, **Node.js**, **Claude AI**, and modern stacks. I prefer simple, scalable, and direct solutions.

**Expertise:** Product Strategy | GenAI Integration | Data-Driven Decisions | Full-Stack Architecture

---

## 🏢 Projects

### 1. **XFiber Ops** — Operations Platform (Fiber Optic) 🇺🇸
*Tech consulting & SaaS for fiber optic installation*

**What it does:**
- CRM + Daily reports + Mobile check-in (GPS + selfie)
- Clock in/out with payroll dashboard
- Job mapping + tickets with Leaflet + OpenStreetMap
- i18n EN/ES/PT (localStorage)
- Support for in-house workers + subcontractors

**Stack:**
- **Backend:** Django 5 + PostgreSQL + REST Framework
- **Frontend:** HTMX + Alpine.js + Tailwind CDN (no build step)
- **Mobile:** PWA-ready, GPS + camera integration
- **Infra:** Railway (auto-redeploy) + SQLite (dev)
- **UI:** Brand navy #0F1B3D + orange #FF6B00, Figtree font

---

### 2. **Longavita** — Support Platform for Chronic Diseases 🇧🇷
*Community, information, health professionals & products for chronic disease management*

**What it does:**
- **Community/Forum** — Experience sharing between patients with protected identities (pseudonyms)
- **Chronic Disease Library** — Reviewed informative content about health conditions
- **Professionals Directory** — Specialists with 3 contact modes: direct contact, scheduling, telemedicine
- **Marketplace** — Showcase of products for quality of life (showcase-only in this phase)
- **Blog** — Articles and news about chronic diseases
- **Backoffice (Django Admin)** — Team manages doctors, products, diseases & posts without programmer

**Stack:**
- **Backend:** Django 5 + PostgreSQL
- **Frontend:** HTMX + Alpine.js + CSS via CDN (no build step)
- **Infra:** Railway (auto-redeploy from GitHub)
- **Static Files:** WhiteNoise
- **UI:** Teal #0ea5a0 + Orange #f97316, Sora / Cormorant Garamond fonts

---

### 3. **Omniwave Energy** — Multi-niche Landing Platform 🇺🇸
*Landing page generator for solar, roofing, pool, plumbing*

**What it does:**
- Landing pages per niche (Solar active in Florida)
- Native i18n: PT (default), ES, EN
- Integration with leads API 
- Auto-generated sitemap
- SEO optimized

**Stack:**
- **Frontend:** Astro 4 + TypeScript + Tailwind
- **Infra:** Vercel (auto-deploy)
- **Backend integration:** Django REST API (Omniwave Ops)

---

### 4. **Empireo** — Tax Filing Automation 🇧🇷
*Automated income tax for Brazilian freelancers earning in USD*

**What it does:**
- Dark & premium dashboard
- Accurate tax calculation with deductions
- Wise integration (OAuth) coming soon
- Tax form PDF generation
- Transaction history + reports

**Stack:**
- **Backend:** Django + Python
- **DB:** SQLite (dev), PostgreSQL (prod)
- **Tests:** pytest (14 tests covering all tax brackets)
- **Integration:** Wise API and other worldwide banks (in progress)

---

### 5. **WhatsApp Chatbot** — Multi-tenant with Claude AI 🇺🇸
*Chatbot platform for WhatsApp powered by AI*

**What it does:**
- Multi-tenant chatbot (each client is a tenant)
- Evolution API integration (WhatsApp)
- Claude AI (Anthropic) as the brain
- Conversation history
- Per-client usage dashboard
- Automatic context reset

**Stack:**
- **Backend:** Node.js + Express
- **DB:** Supabase (PostgreSQL)
- **AI:** Anthropic Claude API
- **Webhook:** Evolution API (webhook listener)
- **Infra:** Railway (~$10/month)

**Use cases:** 24/7 support, automated FAQ, lead qualification.

---

### 6. **AlertaMe** — Reminder Assistant via WhatsApp 🇧🇷 🇺🇸
*"Your family never forgets what matters" — Smart reminders in natural language*

**What it does:**
- **Natural language input** — "remind me to pay the electric bill on the 10th", "mom's appointment next Thursday at 8am", "daily medication at 8pm"
- **AI understands** — parses dates (relative like "next month"), times, recurrence patterns using Claude API
- **Auto-schedules** — creates structured reminders with date, time, recurrence
- **Responds in text + audio** — confirms reminder via message and voice notification at scheduled time
- **Family-focused** — each person identified by WhatsApp number; reminders can be shared
- **Personalization** — customizable assistant name, voice (male/female), conversation style

**Stack:**
- **Backend:** Django 5 + PostgreSQL
- **Infra:** Railway (auto-redeploy) + VPS Hetzner (Evolution API + Docker)
- **AI Brain:** Claude API (Anthropic) — natural language → structured reminders
- **Voice:** ElevenLabs TTS with audio caching
- **WhatsApp Channel:** Evolution API (Phase 1, non-official) → Cloud API (Phase 2, official)
- **Frontend/Landing:** Static HTML/CSS/JS bilingual (PT/EN) on Vercel
- **Architecture:** Abstract `WhatsAppChannel` interface — swap Evolution for Cloud API with 1 config line

---

### 7. **LeadHaus** — Premium CRM for High-End Real Estate 🇧🇷
*Commercial management for luxury real estate brokers — "never let a hot lead go cold"*

**What it does:**
- **Smart pipeline** — visual kanban (New lead → Contact → Visit → Proposal → Closed)
- **Lead scoring** — surfaces who's hot right now (timing score 0–100) so the broker contacts the right person first
- **Client cards** — full history, property interests, and contact data **encrypted at rest**
- **Multi-channel capture** — WhatsApp, Instagram, Facebook, e-mail, referral feeding a single funnel
- **AI drafts** — suggested replies written in the broker's own tone of voice (Claude)
- **Deal Room** — secure space per transaction with document checklists + client access codes
- **VIP security** — encrypted sensitive fields, 2FA, restricted access for high-profile clients (executives, public figures, athletes)
- **Multi-tenant by design** — PostgreSQL Row-Level Security isolates each broker's portfolio at the database level

**Stack:**
- **Frontend:** Next.js 15 (App Router) + TypeScript + Tailwind
- **Backend:** Next.js Server Actions + Prisma ORM
- **DB:** PostgreSQL 16 with Row-Level Security (true multi-tenant isolation)
- **Auth:** Auth.js (NextAuth v5) + 2FA TOTP
- **AI:** Anthropic Claude API (zero-data-retention)
- **Channels:** Meta Cloud API (WhatsApp / Instagram / Facebook)
- **Infra:** Railway (auto-redeploy from GitHub) + managed PostgreSQL
- **UI:** Gold #C8A96B + Turquoise #5BC9B8 + Ivory, Cormorant Garamond / Inter / Helvetica Neue

**Target Audience:** High-end real estate brokers serving high-profile clients.

---

### 8. **CargoOps** — TMS for Transportation 🇧🇷
*"Never lose a shipment" — Transportation Management System for chemical & general cargo transporters*

**What it does:**
- **Real-time tracking** — Leaflet map with live vehicle positions, pulsing pins by status (en ruta/entregado/alerta)
- **Smart dispatching** — intelligent routing + load matching + OTD (On-Time Delivery) monitoring
- **Fleet management** — vehicle maintenance schedules, inspections, documents (RNTRC, CRLV)
- **Driver compliance** — exams (médico/psicológico), licenses, hours of service, alerting system
- **Tollway control** — detects when drivers forget to raise suspended axles on empty returns (saves company $)
- **CT-e integration** — tax invoice + routing data linked in one place
- **B2B quoting** — public form captures leads; inbox with quote requests
- **Real financials** — Abril/2026 actuals: R$ 2.015.441 faturamento, OTD 91,5%, ticket R$ 1.241,80
- **Admin & reports** — compliance reporting, financial insights, fleet analytics

**Stack:**
- **Frontend:** Next.js 16.2.9 (App Router) + React 19 + Tailwind v4 (no config file, `@theme` in CSS)
- **Components:** shadcn/ui on **Base UI** (`@base-ui/react`, not Radix) + Lucide icons
- **Maps:** Leaflet + react-leaflet (CARTO tiles, no API key needed)
- **Client storage:** DataStore in localStorage (fake data for demo, Supabase clients ready)
- **Infra:** Vercel (auto-deploy from GitHub)
- **Demo:** https://cargoops-three.vercel.app (login: `admin@jundtransportes.com.br` / `cargoops2026`)
- **UI Style:** Salesforce Lightning theme — Charcoal + Orange, **desktop-first**

**Current Status:** Hi-fi prototype for investor/CEO demo (Jund Transportes). Real Apr/2026 numbers. Multi-tenant architecture ready (not yet live). Build always passes.

---

## 📊 Production Numbers

| Project | Status | Users | Transactions | Uptime |
|---------|--------|-------|--------------|--------|
| **XFiber Ops** | 🟢 Live | 55 | 1000+ checkins/month | 100% |
| **Longavita** | 🟢 Live | Growing | 100+ community posts/month | 100% |
| **Omniwave Energy** | 🟢 Live | — | 50+ leads/month | 100% |
| **LeadHaus** | 🟢 Live | 9 brokers | 300+ leads managed/month | 100% |
| **AlertaMe** | 🟢 Live | 12 | 50+ reminders/week | 99.8% |
| **CargoOps** | 🟢 Live | 1 org | 173+ shipments tracked/month | 100% |
| **Empireo** | 🟡 Staging | — | Beta | — |
| **WhatsApp Chatbot** | 🟡 Staging | — | Configurable | — |

---

## 🎓 Methodology

- **Product-led:** Feature = problem solved
- **Fast iteration:** Waves = small deliveries (1-2 weeks)
- **Shipping mentality:** Deploy before perfect
- **Code-as-docs:** Detailed READMEs
- **No magic:** Django defaults, Tailwind core utilities, nothing fancy

---

## 💼 Availability

**Status:** Open to:
- ✅ Technical consulting (PM → architecture)
- ✅ Building custom SaaS
- ✅ Mentoring devs in product thinking
- ✅ Full-time corporate roles

**Contact:** LinkedIn or email (below)

---

## 📞 Contact

- **LinkedIn:** [linkedin.com/in/will-gouveia](https://linkedin.com/in/will-gouveia)
- **Email:** wgouveiaa@gmail.com
- **GitHub:** [@willgouveiaa](https://github.com/willgouveiaa)

---

## 📚 Published Works

### 📰 Featured In
- **Terra Economia:** [Como a liderança de Willian Gouveia de Aguiar gerou R$ 19 milhões e redefiniu a estratégia de dados no sistema bancário brasileiro](https://www.terra.com.br/economia/como-a-lideranca-de-willian-gouveia-de-aguiar-gerou-r-19-milhoes-e-redefiniu-a-estrategia-de-dados-no-sistema-bancario-brasileiro,91c344e4b4b4016a12721702b402c0df84vwq66c.html)

- **iG In Magazine:** [Willian Gouveia Aguiar & Machine Learning](https://inmagazine.ig.com.br/empreendedorismo/willian-gouveia-aguiar-machine-learning)

- **MSN Negócios & Tecnologia:** [Como Willian Gouveia de Aguiar lidera estratégias orientadas por dados e jornadas omnichannel no sistema financeiro](https://www.msn.com/pt-br/noticias/noticias/neg%C3%B3cios-e-tecnologia-como-willian-gouveia-de-aguiar-lidera-estrat%C3%A9gias-orientadas-por-dados-e-jornadas-omnichannel-no-sistema-financeiro/ar-AA1RWIBV?disableErrorRedirect=true&infiniteContentCount=0)

### 📖 Academic Articles
- **RCMOS Journal:** [Article #1881](https://submissoesrevistarcmos.com.br/rcmos/article/view/1881)
- **RCMOS Journal:** [Article #1880](https://submissoesrevistarcmos.com.br/rcmos/article/view/1880)

### 🏆 Awards & Recognition
- **IEEE Member** — Institute of Electrical and Electronics Engineers
- **RCMOS 2023 Cycle:** [Recognition & Award](https://submissoesrevistarcmos.com.br/rcmos/ciclo_2023)

---

## 🛠️ Tech Stack

### Backend & Languages
![Python](https://img.shields.io/badge/Python-3776ab?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092e20?style=for-the-badge&logo=django&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-f7df1e?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=for-the-badge&logo=typescript&logoColor=white)

### Frontend
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Astro](https://img.shields.io/badge/Astro-ff5d01?style=for-the-badge&logo=astro&logoColor=white)
![HTMX](https://img.shields.io/badge/HTMX-3d72d7?style=for-the-badge&logo=htmx&logoColor=white)
![Alpine.js](https://img.shields.io/badge/Alpine.js-77c1d2?style=for-the-badge&logo=alpinedotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38b2ac?style=for-the-badge&logo=tailwind-css&logoColor=white)

### Databases & Data
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2d3748?style=for-the-badge&logo=prisma&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003b57?style=for-the-badge&logo=sqlite&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ecf8e?style=for-the-badge&logo=supabase&logoColor=white)

### Integrations & APIs
![Anthropic Claude](https://img.shields.io/badge/Anthropic_Claude-662e9b?style=for-the-badge&logo=anthropic&logoColor=white)
![Meta](https://img.shields.io/badge/Meta_Cloud_API-0467df?style=for-the-badge&logo=meta&logoColor=white)
![Wise](https://img.shields.io/badge/Wise-5d34d6?style=for-the-badge&logo=wise&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448c5?style=for-the-badge&logo=cloudinary&logoColor=white)

### DevOps & Hosting
![Railway](https://img.shields.io/badge/Railway-0b0d0e?style=for-the-badge&logo=railway&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ed?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-f05032?style=for-the-badge&logo=git&logoColor=white)

---

## Complete Tech Stack Details

### Backend
- **Django 5** (Python) — XFiber Ops, Longavita, Empireo, AlertaMe
- **Node.js + Express** — WhatsApp Chatbot
- **Next.js 15** (App Router + Server Actions) — LeadHaus
- **Next.js 16** (App Router) — CargoOps
- **REST APIs** — Inter-system integration

### Frontend
- **Next.js 16.2.9** (React 19) — CargoOps (hi-fi TMS demo)
- **Next.js 15** (TypeScript) — LeadHaus (luxury CRM)
- **Astro 4** (TypeScript) — Omniwave Energy
- **HTMX + Alpine.js** — XFiber Ops, Longavita
- **Tailwind CSS** — All projects (v4 in CargoOps, v3 elsewhere)

### Databases
- **PostgreSQL** — XFiber Ops (Railway), Longavita (Railway), Empireo (Railway), AlertaMe (Railway), LeadHaus (Railway, with Row-Level Security), CargoOps (Vercel Postgres, multi-tenant ready)
- **Prisma ORM** — LeadHaus, CargoOps
- **SQLite** — Local dev, fallback
- **Supabase** — WhatsApp Chatbot

### Integrations & APIs
- **Anthropic Claude API** — WhatsApp Chatbot, AlertaMe (brain), LeadHaus (AI drafts), CargoOps (future suggestions), Empireo (future)
- **Meta Cloud API** — LeadHaus (WhatsApp / Instagram / Facebook), CargoOps (future)
- **Evolution API** — WhatsApp Chatbot, AlertaMe (Phase 1 WhatsApp channel)
- **ElevenLabs API** — AlertaMe (voice synthesis with caching)
- **Wise API** — Empireo (in progress)
- **Cloudinary** — XFiber Ops, Longavita (bill/document uploads)
- **Leaflet + OpenStreetMap/CARTO** — XFiber Ops, CargoOps (real-time tracking)
- **Resend** — XFiber Ops (transactional email)

### Auth & Security
- **Auth.js (NextAuth v5) + 2FA TOTP** — LeadHaus
- **PostgreSQL Row-Level Security** — LeadHaus, CargoOps (multi-tenant isolation)
- **AES-256-GCM encryption at rest** — LeadHaus (sensitive client data)

### Infra & DevOps
- **Railway** — XFiber Ops, Longavita, Empireo, AlertaMe, LeadHaus (deploy + auto-redeploy)
- **Vercel** — Omniwave Energy, CargoOps, AlertaMe landing page
- **VPS Hetzner** — AlertaMe Evolution API (Docker, Ubuntu)
- **GitHub** — Source of truth for all projects
- **Docker** (optional) — Containerization
- **Gunicorn + Whitenoise** — Production servers (Django projects)

### QA & Testing
- **pytest** — Empireo (14 tests), AlertaMe (webhook + brain tests)
- **Django TestCase** — XFiber Ops, Longavita, AlertaMe
- **Next.js build** — LeadHaus, CargoOps (lint + type-check)
- **Manual testing** — All projects

### Languages
- **Python** (Django) — Backend
- **TypeScript** — Next.js frontends (LeadHaus, CargoOps), Astro (Omniwave Energy)
- **JavaScript** — Frontend (Alpine.js, HTMX)
- **SQL** — Migrations, queries, RLS policies
- **Bash** — DevOps, scripts

---

## 🌟 Fun Facts

- 🇧🇷 Brazilian, based in São Paulo
- 🎯 Senior Product Manager (5+ years at LATAM bank)
- 🚀 Founder of OmniWave Group LLC in USA 🇺🇸
- 📱 Obsessed with onboarding & UX
- 🤖 GenAI enthusiast (Claude, LLMs, agents)
- 💻 Workbench: Mac + Claude Code + GitHub web
- 🎨 Navy #0F1B3D + Orange #FF6B00 = my palette

---

> **"Ship > Perfect"** — Always.
