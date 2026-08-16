# Rufus Nomah Emare

**Backend · AI/ML · Full-Stack · Android**  
Lagos, Nigeria → Open to relocation worldwide  
Open to full-time roles in backend engineering, AI engineering, and full-stack development

---

I build production software that connects systems and AI to real problems — APIs, async pipelines, web apps, and Android — end-to-end from architecture to deployment.

I co-founded an edtech product that scaled to **2,000+ users**, ship production AI systems, and independently build [ReliabilityIQ](https://reliabilityiq.com) (AI predictive maintenance SaaS). Recent work includes a production Django/Celery task queue API and an open-source contribution to [cookiecutter-django](https://github.com/cookiecutter/cookiecutter-django).

---

## What I Build With

**Backend**  
`Python` `Django` `Django REST Framework` `Celery` `Redis` `PostgreSQL` `FastAPI` `Flask` `JWT` `OpenAPI`

**AI / ML**  
`RAG / V-RAG` `LLM Integration` `Agentic Workflows` `Tool Calling` `Prompt Engineering` `OpenAI` `Gemini` `Anthropic` `Computer Vision` `NLP`

**Frontend & Mobile**  
`TypeScript` `React` `Next.js` `Tailwind CSS` `Kotlin` `Jetpack Compose` `Android SDK` `ML Kit`

**Infrastructure**  
`Docker` `GitHub Actions` `CI/CD` `AWS` `Kubernetes` `Railway` `Linux`

---

## Featured Projects

### [Django Task Queue API](https://github.com/Africanus12/django-task-queue-api) — *Live*
Production-oriented async job API: submit tasks, track lifecycle, retry/cancel, and get webhook callbacks on completion. Built for real ownership isolation, idempotency, and safe AI credential handling.

- **Stack:** Django 5.1 · DRF · Celery · Redis · PostgreSQL · JWT · Gunicorn  
- **Highlights:** Task states (`pending` → `running` → `success` / retry / fail / cancel), per-owner idempotency keys, independent webhook delivery, Fernet-encrypted short-lived AI credentials, rate limits, OpenAPI/Swagger, health/readiness probes  
- **Ops:** Docker Compose, GitHub Actions CI, deployed on Railway  
→ [Repo](https://github.com/Africanus12/django-task-queue-api) · [API](https://web-production-0d58f.up.railway.app) · [Docs](https://web-production-0d58f.up.railway.app/api/docs/) · [Health](https://web-production-0d58f.up.railway.app/health/)

---

### [Generative Storyboard Consultant (GSC)](https://v0-generative-storyboard-consultant-three.vercel.app/)
V-RAG platform for multimodal video analysis and storyboard generation: motion features, semantic embedding, vector retrieval, and LLM-augmented output in one pipeline.

`Next.js` `React` `TypeScript` `Tailwind` `Vercel`  
→ [Repo](https://github.com/Africanus12/v0-generative-storyboard-consultant) · [Live demo](https://v0-generative-storyboard-consultant-three.vercel.app/)

---

### [TrackIt – AI Expense Tracker](https://github.com/Africanus12/TrackIt) *(in development)*
Android app for Nigerian SMEs: ML Kit OCR receipt scanning, voice entry, Gemini categorisation, Supabase backend, QR flows.

`Kotlin` `Jetpack Compose` `Gemini` `Supabase` `ML Kit`

---

### [ReliabilityIQ](https://reliabilityiq.com)
Independent AI predictive and corrective maintenance SaaS — product design through implementation.

---

## Open Source

### [cookiecutter-django](https://github.com/cookiecutter/cookiecutter-django) — [PR #6817](https://github.com/cookiecutter/cookiecutter-django/pull/6817)
Fixed GitHub Actions failures when generated projects use Docker but do not keep local env files in VCS. Made Compose `env_file` entries optional (`required: false`) and added a CI step that creates minimal dummy env files so Postgres/Django still receive required variables.

`Docker Compose` `GitHub Actions` `Django` `CI/CD`  
Upstream CI on the PR: **all checks green**

---

## Certifications

- **AWS Certified Solutions Architect** — Amazon Web Services  
- **Google Site Reliability Engineering (SRE)** — Uplimit × Google  
- **Google Analytics Certified** — Google

---

## Currently

- Shipping and hardening the [Django Task Queue API](https://github.com/Africanus12/django-task-queue-api)  
- Building [ReliabilityIQ](https://reliabilityiq.com)  
- Developing TrackIt for SME expense workflows  
- Contributing to open-source Django tooling ([cookiecutter-django #6817](https://github.com/cookiecutter/cookiecutter-django/pull/6817))  
- Open to full-time **backend**, **AI/ML**, and **full-stack** roles (relocation welcome)

---

## Find Me

[![Email](https://img.shields.io/badge/Email-rufusemare%40gmail.com-blue?style=flat-square&logo=gmail)](mailto:rufusemare@gmail.com)
[![X](https://img.shields.io/badge/X-%40Rufus87078959-black?style=flat-square&logo=x)](https://x.com/Rufus87078959)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Emare%20Rufus-blue?style=flat-square&logo=linkedin)](https://ng.linkedin.com/in/emare-rufus-33974812b)
[![Portfolio](https://img.shields.io/badge/Portfolio-cutjamm.com-orange?style=flat-square)](https://cutjamm.com/africanus)
[![ReliabilityIQ](https://img.shields.io/badge/ReliabilityIQ-reliabilityiq.com-green?style=flat-square)](https://reliabilityiq.com)

---

*"The best systems are the ones that keep working when you are not watching."*
