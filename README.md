# Hi, I'm Carlos Mendoza

### Full-stack developer building AI agents and web platforms that run in production

I design the whole system: database, backend, agent, UI and deployment. Then I keep it running.

I founded **Zaqi Solutions**, a small software studio. There I build **Onix**, a multi-tenant WhatsApp AI sales agent, and a **real-time voice agent** for incident reporting at an enterprise client. I also built and maintain **[Lingolandias Academy](https://lingolandias.com)** solo. It is a language-learning platform with **500+ active users**.

🌐 **Portfolio:** [koatth60.github.io](https://koatth60.github.io) · 📍 Bogotá, Colombia · Open to remote roles worldwide

---

## 🤖 AI agents

| Project | What it does | How it's built |
|---|---|---|
| **Onix** — WhatsApp AI sales agent | Answers catalog questions, recognizes products from customer photos, takes the order, collects delivery data and guides the payment. Multi-tenant SaaS with a React panel and a CRM. | Python, FastAPI, **LangGraph**, PostgreSQL 16 + **pgvector** with row-level security. The model is routed per conversation stage (Claude / Gemini / DeepSeek, with fallback). Tools own the facts; a grounding check rewrites any price that no tool returned. |
| **Voice agent** for Major Incident reporting | Takes phone reports in natural Colombian Spanish, runs the triage and leaves the ticket ready for the incident bridge. Keeps working when the caller goes off-script. | Python, **Pipecat** + Pipecat Flows, **Deepgram** STT, Silero VAD + smart-turn, **Claude Haiku**, TTS with fallback, WebRTC / Twilio. A field is stored only if the caller's own words back it. Strict mypy, ruff and pytest. |

Both agents follow one rule: **the model drives the conversation, and the code owns the facts.**

Both repositories are private. I'm happy to walk through the code in an interview.

## 🚀 Web platforms

| Project | Description | Stack |
|---|---|---|
| [Lingolandias Academy](https://lingolandias.com) | Learning platform with 500+ users, built solo. Live video classes, real-time chat, calendar and role-based access. | React, NestJS, PostgreSQL, Socket.IO, Jitsi, AWS S3, Docker, Nginx |
| [Grillr](https://grillr-seven.vercel.app) · [front](https://github.com/koatth60/grillr) · [API](https://github.com/koatth60/grillr-back) | AI mock interviews: Claude writes questions tailored to the job and scores each answer. Stripe billing. | Next.js, TypeScript, NestJS, Prisma, PostgreSQL, Claude API, Stripe |
| [Lingolandias Website](https://lingolandias.net) · [code](https://github.com/koatth60/lingolandias) | Marketing site in 3 languages with a language-level quiz | React, Tailwind, i18next, Express |
| Handy Pro · [API](https://github.com/koatth60/handypro-back) · [front](https://github.com/koatth60/handypro-frontend) | Services marketplace built by a team of 6. I built the real-time chat, the Stripe payments and the data preload. | NestJS, TypeORM, PostgreSQL, Socket.IO, Stripe, Next.js |

---

## 🛠️ Tech stack

**AI & agents**
![Claude](https://img.shields.io/badge/Claude_API-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Pipecat](https://img.shields.io/badge/Pipecat-111111?style=for-the-badge&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![Deepgram](https://img.shields.io/badge/Deepgram-13EF93?style=for-the-badge&logoColor=black)
![WhatsApp](https://img.shields.io/badge/WhatsApp_Cloud_API-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Backend**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

**Data**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)

**DevOps**
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_S3-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![DigitalOcean](https://img.shields.io/badge/DigitalOcean-0080FF?style=for-the-badge&logo=digitalocean&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

---

## 🧭 How I work

- **The model drafts, and the code decides.** Prices, totals and state changes go through validated tools and database constraints.
- **I measure on real conversations.** Every agent turn writes a trace with its tools, model, tokens and latency.
- **Tests run in a second.** Decision logic is pure and runs without network, database or model calls.
- **I own the product end to end.** That covers the schema, the Nginx config and the fix at 2 a.m.

---

## 📍 Contact

📧 koatth60@gmail.com · 💼 [LinkedIn](https://www.linkedin.com/in/carlos-mendoza-060097225/) · 🌐 [koatth60.github.io](https://koatth60.github.io)
