# Hi, I'm Akkeem 👋

**Computer Science student at CUNY** building production software, multi-tenant SaaS, AI systems, and full-stack apps.

Most of my work lives at the intersection of **backend engineering, applied AI, and security**. I care about the parts that don't demo well: tenant isolation, migration safety, request-boundary validation, and accessibility.

---

## 🚀 Featured Projects

### 🚚 [AsheFlow](https://github.com/adonisja/AsheFlow): Crew Management & Intelligent Dispatch
Multi-tenant SaaS for Amazon DSP delivery operations. Replaces spreadsheets and verbal coordination with a role-aware platform covering the full shift lifecycle.

- **Scale:** 688 commits · 582 backend tests · 41 API routers · 136 migrations · 8 roles
- **Stack:** FastAPI · PostgreSQL · SQLAlchemy 2.0 · Redis · Celery · React 19 · React Native · Docker · AWS (EC2, Cognito, Textract)
- **Highlights:** weighted dispatch algorithm (preferences, PTO, trainer–trainee pairing, crew balance) · two-tier package routing · Discord bot integration · SSE live updates · ADP payroll reconciliation · strict `company_id` tenant isolation on every query
- **Status:** deployed to staging on AWS with CI/CD via GitHub Actions

### 🔍 [Angel Filter](https://github.com/adonisja/NLIP-Project): Multi-Provider AI Proxy *(CUNY Capstone)*
Fans a query out to multiple LLM and search providers in parallel, then ranks results with semantic embeddings and three-axis scoring (price · distance · rating) — and demotes sponsored content instead of rewarding it.

- **Stack:** Python · NLIP protocol · OpenAI · Gemini · Ollama · WatsonX · Brave Search · Google Places · Prometheus
- **Highlights:** parallel fan-out with failure isolation · constraint extraction from natural language · fuzzy consensus clustering · sponsored-content penalty · 277 passing tests

### 🔬 [Lumina](https://github.com/adonisja/LesionRec): AI Skin Analysis & Recommendations
Full-stack app that analyzes skin conditions and generates personalized, budget-aware skincare routines.

- **Stack:** React · FastAPI · Gemini 2.0 Flash · privacy-focused image pipeline

### 🎓 [Project DJA](https://github.com/Sawyer0/ai-innovation-challenge_software-track): Compliance-Aware AI Advising
Agentic AI academic advisor built for the AI Innovation Challenge. Checks visa status, financial aid eligibility, and graduation timeline *before* recommending a course — the constraints DegreeWorks doesn't model.

### 📊 [TikTok Review Sentiment Analysis](https://github.com/adonisja/TikTok-Reviews-Sentiment-Analysis)
Tracked how Google Play review sentiment shifted in response to real-world events affecting TikTok. Python · Pandas · Matplotlib.

---

## 🔧 Tech

**Languages**: Python · TypeScript · JavaScript · SQL · Kotlin

**Backend**: FastAPI · SQLAlchemy 2.0 · Pydantic · PostgreSQL · Redis · Celery · Alembic · REST · SSE

**Frontend & Mobile**: React 19 · React Native · Tailwind CSS · Vite · Jetpack Compose

**Cloud & DevOps**: AWS (EC2, Cognito, Lambda, Textract, SSM) · Docker · GitHub Actions · Caddy

**AI / ML**: LLM orchestration · semantic embeddings · RAG patterns · prompt engineering · OCR pipelines

**Security**: multi-tenant isolation · JWT/JWKS auth · role-based access control · OWASP Top 10 · PII retention & privacy review

---

## 🔐 On Security

Security on my projects isn't a separate hobby — it's the audit I run before calling anything done. On AsheFlow that means a documented nine-dimension review of every change: tenant scoping on every query, role gates on every endpoint, no unvalidated `Any` at the request boundary, no exception text leaking to clients, and no PII in logs or response schemas. I'm extending that instinct toward penetration testing and offensive security.

---

## 🌱 Currently

- Shipping AsheFlow toward production launch
- Building Angel Filter for a May 2026 capstone demo
- Going deeper on distributed systems, system design, and offensive security

---

## 📫 Reach Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akkeem-tyrell)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:tyrellakkeem@gmail.com)

Open to **software engineering and security internships/roles**, and to collaborating on ambitious projects. If you're working on something hard, I'd like to hear about it.

---

<sub>Thanks for visiting 👍🏾 — let's build something.</sub>
