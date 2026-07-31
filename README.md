# 👨‍💻 Parks RPK

**Software Engineer · QA & Evals · AI-Powered Products**

📍 Binghamton, NY &nbsp;|&nbsp; 📞 +1 (607) 343 8233 &nbsp;|&nbsp; 📧 rpkparks@gmail.com &nbsp;|&nbsp; 🌐 [LinkedIn](https://www.linkedin.com/in/parks-rpk-8479a3350) &nbsp;|&nbsp; 🐙 [GitHub](https://github.com/parks3131) &nbsp;|&nbsp; 🔗 [Portfolio](https://www.parkstechusa.com/)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=anthropic&logoColor=white)

---

## 🧭 Summary

Software Engineer focused on QA, evals, and AI-powered products built and shipped end to end. At **Acarin Inc**, built a real-time observability and load-testing pipeline (k6, Docker, InfluxDB, Grafana) simulating **20,000 concurrent users** and isolating bottlenecks across auth, LLM, and rendering layers for an AI HR platform **shipped to the US Army**, and replaced manual regression testing with a Playwright/Cucumber automation suite. Independently designed and shipped **full-stack products in real use**: **ClubChat**, a team-coordination app now run by **100+ member university clubs**; a RAG chatbot with prompt-injection guardrails; **Interstellar**, a developer-intelligence platform detecting drift between planned and shipped code; and a fully autonomous AI news pipeline. Works fluently with modern AI dev tooling (Claude Code, Cursor, LangChain, MCP), with strong CS fundamentals and a consistent record of **owning projects from idea to production, not just closing tickets**.

---

## 🎓 Education

**Binghamton University, SUNY** &nbsp;|&nbsp; *B.S. in Computer Science* &nbsp;|&nbsp; May 2026

- **GPA:** 3.80 / 4.00 &nbsp;·&nbsp; Dean's List
- **Relevant Coursework:** Data Structures & Algorithms, Machine Learning, Operating Systems, Database Systems, Computer Architecture, Computer Networks, Cloud Computing, Artificial Intelligence, Natural Language Processing (NLP)

---

## 🛠️ Technical Skills

- **Languages:** Python, TypeScript, JavaScript, C++, C, Java, SQL, Bash, HTML/CSS
- **AI, Agentic Systems & Data:** LangChain, Model Context Protocol (MCP), Retrieval-Augmented Generation (RAG), AI Evals, Semantic / Knowledge Graphs, Hugging Face, Scikit-learn, OpenCV, NumPy, Pandas
- **Web & Frameworks:** Node.js, Fastify, Express.js, React, React Native / Expo, Next.js, FastAPI, Flask, WebSockets, REST APIs, MongoDB (MERN), Drizzle, JSON Schema
- **DevOps, Cloud & Infrastructure:** Docker, CI/CD Pipelines, GitHub Actions, Linux/Unix, AWS (EC2, RDS, DynamoDB, Aurora), Azure, Databricks, Kafka, Kubernetes, InfluxDB, Fly.io
- **Testing & Observability:** Playwright, Cucumber, k6 (Load Testing), Testcontainers, Grafana, Jupyter Notebooks
- **Collaboration & Developer Tools:** Jira API, GitHub Enterprise, Git, PostgreSQL, Cursor, Claude Code, VS Code

---

## 📜 Certifications

- **Claude** &nbsp;·&nbsp; Claude 101, Claude Code 101, Building with the Claude API, Advanced Model Context Protocol
- **OpenCV** &nbsp;·&nbsp; University at Buffalo
- **Google Data Analytics Professional Certificate** &nbsp;·&nbsp; Coursera
- **Python, C & C++ Core Programming** &nbsp;·&nbsp; IIT Bombay

---

## 💼 Professional Experience

### Acarin Inc. &nbsp;|&nbsp; Software Engineer (QA & Evals) &nbsp;|&nbsp; Baltimore, MD &nbsp;|&nbsp; Jan 2025 – Present

Owned quality, evals, and observability for **Mission Mind HR Worker**, an AI HR platform **shipped to the US Army**, and took it from manual testing to a fully automated, load-verified release pipeline.

- Built a **k6 + Chromium load-testing suite** simulating **20,000 concurrent users** through Keycloak SSO and multi-step AI chat flows, exposing LLM timeouts and permission gaps before they ever reached production.
- Designed a **Docker-containerized Grafana + InfluxDB** observability pipeline surfacing p95/p99 latency, error rates, and throughput on a live dashboard used daily by an **8-person DevOps team**.
- Engineered **per-user logging pipelines** that isolate failures to the exact workflow stage (auth → bot response → UI render), turning vague bug reports into precise, one-line fixes and cutting debug time dramatically.
- Architected a **Playwright + Cucumber + TypeScript E2E framework** (3-layer: page objects → step definitions → Gherkin), refactoring a monolith into 21 files across 8 feature areas so non-technical QA can write tests in plain English.
- **Integrated Playwright MCP with Claude Code** to auto-discover and patch broken UI selectors on a live browser, cutting new-workflow creation from days to hours.
- Mapped every UI test **1:1 to a k6 load-test workflow**, so the same user journeys are verified both functionally and under load, and drove backend fixes off documented failure patterns.

`k6 · Playwright · Cucumber · TypeScript · Docker · Grafana · InfluxDB · Keycloak · Claude Code (MCP)`

---

## 🚀 Projects

### 🏃 ClubChat &nbsp;|&nbsp; *Team Coordination App for University Clubs · Shipped & in daily use*

A full-stack mobile app that **100+ member clubs now use to run everything they used to juggle in a group chat**: workout plans, race sign-ups, rosters, and a shared calendar.

- **Shipped a full-stack app** (iOS, Android, and web from one Expo codebase) that turns the messy club group chat into a real product, with every workout, race, and roster becoming a permissioned object with its own history.
- **Real-time backend** on Fastify + Postgres + Redis + WebSockets: a durable per-channel message log with gapless sequence numbers that keeps every device in sync and never loses or double-posts a message.
- **Push notifications suppressed by read cursor**, not socket liveness, so members are only pinged for messages they genuinely haven't seen yet.
- **Built solo, spec to store:** 116 REST routes, a 39-table schema, and 631 automated tests running against real Postgres/Redis via Testcontainers.

`TypeScript · Node 24 · Fastify · Postgres 17 · Redis · WebSockets · React Native / Expo · Drizzle · S3 · APNs/FCM`

**Repo:** [github.com/parks3131/ClubChat-Remastered](https://github.com/parks3131/ClubChat-Remastered)

---

### 🌌 Interstellar &nbsp;|&nbsp; *Developer Intelligence Platform (Y Combinator)*

Building a unified intelligence layer to detect drift between what was scoped and what is actually being built.

| Focus Area | Engineering Impact |
| :--- | :--- |
| **The Core Engine** | Holds simultaneous context pictures (Intent vs. Reality) across Jira, Slack, Figma, & GitHub to surface misalignments in real time. |
| **Contextual Guardrails** | Replaced noisy alerts with scoped, artifact-linked notifications when code execution strays from the spec boundary. |
| **AI Agent Ingestion** | Synthesizes codebase context and constraints into pristine, agent-executable specification files. |
| **System Architecture** | Built for both vendor-backed MCP deployment (Glean/Onyx) and full-stack semantic-graph connectors. |

`Python · LLM Reasoning · MCP · Semantic Graph · Jira / Slack / GitHub / Figma`

**Repo:** [github.com/parks3131/Interstellar](https://github.com/parks3131/Interstellar)

---

### 💬 Parks Portfolio AI Chat &nbsp;|&nbsp; *RAG-Powered Assistant with Guardrails* &nbsp;·&nbsp; Jul 2026

- Replaced a static system prompt with a retrieval pipeline: embedded a content corpus using OpenAI `text-embedding-3-small` into **Neon Postgres (pgvector, HNSW cosine index)**, retrieving top-k chunks per query to ground every reply.
- Built an idempotent reindex script that embeds, upserts by ID, and prunes stale vectors, keeping the vector store reproducible from a single JSON corpus file.
- Implemented **input/output guardrails** (regex-based jailbreak & prompt-leak detection, message-length caps) and **Upstash Redis** sliding-window rate limiting to protect the public chat API from abuse and prompt injection.
- Kept the LLM provider swappable via **OpenRouter**, isolating retrieval, guardrail, and generation logic into independent modules.

`Next.js · TypeScript · OpenAI Embeddings · Neon (pgvector) · Upstash Redis · OpenRouter`

**Live:** [parkstechusa.com](https://www.parkstechusa.com/)

---

### 📰 Parks's News &nbsp;|&nbsp; *Autonomous AI News Aggregation & Newsletter*

- Shipped an **end-to-end AI news platform** (a real-time web app plus an autonomous daily email newsletter) aggregating **70+ sources** (RSS, Reddit, Hacker News, arXiv, NewsAPI) and using LLM agents to read, rank, and summarize with zero manual curation.
- Designed an agentic tool-call loop that scores articles by impact, novelty, and recency, streaming ranked results live to the UI via Server-Sent Events instead of a blocking wait.
- Ran it as a **serverless, self-healing pipeline** (GitHub Actions cron, no server to maintain) with graceful fallbacks at every failure point; batched LLM calls and 15-minute caching cut multi-source fetch time from ~15s to ~3s.

`Next.js · TypeScript · Python · OpenRouter · LangChain · GitHub Actions`

**Live:** [parks-s-news.vercel.app](https://parks-s-news.vercel.app/) &nbsp;·&nbsp; **Newsletter:** [github.com/parks3131/parks-news-letter](https://github.com/parks3131/parks-news-letter)

---

### 🏡 B-Roommates Housing Portal &nbsp;|&nbsp; *ACM Project* &nbsp;·&nbsp; Oct 2024 – Apr 2025

- Built a Tinder-style roommate-matching platform (React + MERN) with auth, preference filtering, and messaging; UX-tested with 10+ users.

`React · Node.js · Express · MongoDB · Docker`

---

### 🏆 MICASA UX Hackathon &nbsp;|&nbsp; *Runner-up* &nbsp;·&nbsp; May 2025

- Redesigned full guest onboarding for MICASA (third spaces for artists); built lo-fi → hi-fi in Figma with invite-code entry, deferred signup, and dashboard-first navigation.

---

### ⚛️ Quantum Computing Research &nbsp;|&nbsp; *Prof. Yiming Zheng* &nbsp;·&nbsp; Jan 2025 – May 2026

- Researching quantum error correction and algorithm optimization using Qiskit; preparing for conference submission.

---

### 🚲 NYC CitiBike Data Analysis

- Processed millions of ride records to surface peak demand, seasonal trends, and station utilization; built Tableau + Matplotlib dashboards for station-optimization insights.

`Python · Pandas · SQL · Tableau`

---

## 🌱 Leadership

- 👨‍🏫 **Course Assistant · DSA** &nbsp;|&nbsp; Binghamton &nbsp;|&nbsp; Jan 2025 – Present &nbsp;·&nbsp; problem design, debugging support, lab facilitation
- 💻 **ACM Member** &nbsp;|&nbsp; Binghamton &nbsp;|&nbsp; Oct 2024 – Present &nbsp;·&nbsp; weekly tech events, competitive coding
- 🌍 **Google DSC Core Member** &nbsp;|&nbsp; VIT Chennai &nbsp;|&nbsp; Aug 2022 – Jul 2024 &nbsp;·&nbsp; organized hackathons incl. a 72-hr zonal event with **1,500+ participants**
- 🎤 **Toastmasters VPP** &nbsp;|&nbsp; VIT Chennai &nbsp;|&nbsp; Nov 2023 – Aug 2024 &nbsp;·&nbsp; guided members across speech pathways, ran 30+ meets
