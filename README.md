# 👨‍💻 Parks RPK
📍 Binghamton, NY | 📞 +1 (607) 343 8233 | 📧 rpkparks@gmail.com | 🌐 [LinkedIn](https://www.linkedin.com/in/parks-rpk-8479a3350) | 🐙 [GitHub](https://github.com/parks3131) | [Portfolio](https://www.parkstechusa.com/)

---

## 🧭 Summary

QA & Evals Intern of experience building and testing AI-powered products end-to-end. At Acarin Inc, built a real-time observability pipeline (Docker, InfluxDB, Grafana) that isolated performance bottlenecks across auth, LLM, and rendering layers for an AI HR platform under 20,000 concurrent users, and replaced manual regression testing with a Playwright/Cucumber automation suite. Independently designed and shipped full-stack AI projects, a RAG-based chatbot with prompt-injection guardrails, a developer intelligence platform detecting drift between planned and shipped code, and a fully automated AI news pipeline, using modern AI dev tools (Claude Code, Cursor, Langchain, Agentic Executor and Curator etc… ) throughout. Strong CS fundamentals with a consistent track record of owning projects from idea to production, not just closing tickets.

---

## 🎓 Education
**Binghamton University, SUNY** — *B.S. in Computer Science* | May 2026
- **GPA:** 3.80 / 4.00 | Dean's List
- **Relevant Coursework:** Data Structures & Algorithms, Machine Learning, Operating Systems, Database Systems, Computer Architecture, Computer Networks, Cloud Computing, Artificial Intelligence, Natural Language Processing (NLP)

---

## 🛠️ Technical Skills

- **Languages:** Python, TypeScript, JavaScript, C++, C, Java, SQL, Bash, HTML/CSS
- **AI, Agentic Systems & Data:** LangChain, Model Context Protocol (MCP), Retrieval-Augmented Generation (RAG), Semantic Graphs / Knowledge Graphs, Hugging Face, Scikit-learn, OpenCV, NumPy, Pandas
- **Web & Frameworks:** Node.js, Express.js, React, MongoDB (MERN Stack), Next.js, FastAPI, Flask, REST APIs, JSON Schema
- **DevOps, Cloud & Infrastructure:** Docker, CI/CD Pipelines, Linux/Unix, Azure, Databricks, InfluxDB, Kafka, AWS (EC2, RDS, DynamoDB, Aurora), Kubernetes, ROS (Robot Operating System)
- **Testing & Observability:** Playwright, Cucumber, k6 (Load Testing), Grafana, Jupyter Notebooks
- **Collaboration & Developer Tools:** Jira API, GitHub Enterprise, Git, PostgreSQL, Cursor, VS Code

---

## 📜 Certifications
- **OpenCV** – University at Buffalo
- **Google Data Analytics Professional Certificate** – Coursera
- **Python, C, & C++ Core Programming** – IIT Bombay

---

## 💼 Professional Experience

**Acarin Inc. — Software Engineer** | Baltimore, MD | Mar 2026 – Present
- Built k6 + Chromium load testing suite simulating **20,000 concurrent users** through Keycloak SSO & AI chat flows for Mission Mind HR Worker, shipped to the **US Army**
- Designed Docker-containerized **Grafana + InfluxDB** pipeline surfacing p95/p99 latency, error rates & throughput on a live dashboard used by the 8-person DevOps team
- Engineered per-user logging pipelines isolating failures to exact workflow stages (auth → bot response → UI render), cutting debug time significantly
- Analyzed failure patterns (missing permissions, bot timeouts, render delays) and documented findings that drove backend fixes

**Acarin Inc. — Software Engineer Intern** | Baltimore, MD | Jan 2025 – Ma 2026
- Architected Playwright + Cucumber + TypeScript E2E framework (3-layer: page objects → step definitions → Gherkin), refactoring a monolith into 21 files across 8 feature areas
- Built shared auth step layer eliminating duplicated login glue code; configured Cucumber glob loader to auto-discover new `*.steps.ts` files
- Authored custom TypeScript HTML reporter generating per-scenario reports with screenshots & video on failure
- Mapped UI tests 1:1 to k6 load-test workflows — same user journeys covered functionally and under load

**🌐 SUNY Research Foundation — Back End Developer** | Binghamton, NY | Feb 2025 – Jun 2026

*Served as backend developer on a federally funded digital exhibit platform, designing and deploying RESTful APIs using Python and FastAPI with Pydantic-validated schemas, managing relational data in Amazon RDS (PostgreSQL) and document data in Amazon DynamoDB, building GitHub Actions CI/CD pipelines, and collaborating within a 5-person Agile team tracked in Jira to ship a nationally distributed platform now serving museum partners across the United States.*

- Developed backend services using Python and FastAPI, building RESTful API endpoints with Pydantic-validated schemas to support structured research data ingestion and retrieval workflows
- Managed relational data in Amazon RDS (PostgreSQL), designing normalized schemas and writing optimized SQL queries for content management and multi-stakeholder data access
- Stored and queried flexible document data in Amazon DynamoDB, leveraging its serverless NoSQL model for high-throughput, low-latency reads across research modules
- Set up and maintained a CI/CD pipeline using GitHub Actions, automating build, test, and deployment stages to streamline releases and reduce manual overhead
- Participated in Agile/Scrum ceremonies including sprint planning, daily standups, and retrospectives, tracking tasks and progress in Jira as part of a 5-person development team
- Shipped a nationally distributed digital exhibit platform now serving museum partners across the United States

`Python · FastAPI · Pydantic · Amazon RDS · DynamoDB · GitHub Actions · Jira`

---

## 🚀 Projects

#### 🌌 Interstellar | *Developer Intelligence Platform (Y Combinator)*
Building a unified intelligence layer to detect drift between what was scoped and what is actually being built.

| Focus Area | Engineering Impact |
| :--- | :--- |
| **The Core Engine** | Holds simultaneous context pictures (Intent vs. Reality) across Jira, Slack, Figma, & GitHub to surface misalignments in real-time. |
| **Contextual Guardrails** | Replaced noisy alerts with scoped, artifact-linked notifications when code execution strays from the spec boundary. |
| **AI Agent Ingestion** | Synthesizes codebase context and constraints into pristine, agent-executable specification files. |
| **System Architecture** | Built for both vendor-backed MCP deployment (Glean/Onyx) and full-stack semantic graph connectors. |

`Python · LLM Reasoning · MCP · Semantic Graph · Jira/Slack/GitHub/Figma`

---


**💬 Parks Portfolio AI Chat — RAG-Powered Assistant with Guardrails** | Jul 2026
- Replaced a static system prompt with a retrieval pipeline: embedded a content corpus using OpenAI `text-embedding-3-small` into **Neon Postgres (pgvector, HNSW cosine index)**, retrieving top-k chunks per query to ground every reply
- Built an idempotent reindex script (`scripts/reindex.ts`) that embeds, upserts by ID, and prunes stale vectors — keeping the vector store reproducible from a single JSON corpus file
- Implemented input/output guardrails (regex-based jailbreak & prompt-leak detection, message-length caps) and **Upstash Redis** sliding-window rate limiting to protect the public chat API from abuse and prompt injection
- Kept the LLM provider swappable via **OpenRouter**'s OpenAI-compatible API, isolating retrieval, guardrail, and generation logic into independent modules

`Next.js · TypeScript · OpenAI Embeddings · Neon (pgvector) · Upstash Redis · OpenRouter`

---

**🏆 Runner-up — MICASA UX Hackathon** | May 2025
- Redesigned full guest onboarding for MICASA (third spaces for artists); built lo-fi → hi-fi in Figma with invite-code entry, deferred signup & dashboard-first nav

---

**🏡 B-Roommates Housing Portal — ACM Project** | Oct 2024 – Apr 2025
- Built Tinder-style roommate matching platform (React + MERN) with auth, preference filtering & messaging; UX-tested with 10+ users

`React · Node.js · Express · MongoDB · Docker`

---

**⚛️ Quantum Computing Research — Prof. Yiming Zheng** | Jan 2025 – May 2026
- Researching quantum error correction & algorithm optimization using Qiskit; preparing for conference submission

---

**🚲 NYC CitiBike Data Analysis**
- Processed millions of ride records to surface peak demand, seasonal trends & station utilization; built Tableau + Matplotlib dashboards for station optimization insights

`Python · Pandas · SQL · Tableau`

---

## 🌱 Leadership

- 👨‍🏫 **Course Assistant — DSA** | Binghamton | Jan 2025 – Present — problem design, debugging support, lab facilitation
- 💻 **ACM Member** | Binghamton | Oct 2024 – Present — weekly tech events, competitive coding
- 🌍 **Google DSC Core Member** | VIT Chennai | Aug 2022 – Jul 2024 — organized hackathons incl. 72-hr zonal event with **1,500+ participants**
- 🎤 **Toastmasters VPP** | VIT Chennai | Nov 2023 – Aug 2024 — guided members across speech pathways, ran 30+ meets
