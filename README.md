# Parks RPK
Binghamton, NY | +1 (607) 343 8233 | prpk@binghamton.edu | [LinkedIn](https://www.linkedin.com/in/parks-rpk-8479a3350) | [GitHub]([NEW GITHUB URL])

---

## Education

**Binghamton University, State University of New York**
Bachelor of Science in Computer Science — May 2026
Cumulative GPA: 3.80 / 4.00 | Dean's List: Present

Relevant Coursework: Data Structures & Algorithms, Object-Oriented Programming, Machine Learning, Operating Systems, Computer Architecture, Database Systems, Computer Networks, Theory of Computation, Cloud Computing, AI, NLP

---

## Technical Skills

**Programming Languages:** Python, C++, C, Java, JavaScript, TypeScript, SQL, Bash, Linux, ROS

**AI & Data Science:** Scikit-learn, NumPy, Pandas, OpenCV, Hugging Face, LangChain, AI API, Microsoft Excel, RAG, MCP

**Web Development:** MERN Stack (MongoDB, Express, React, Node.js), HTML, CSS, REST APIs, WordPress, Flask, Docker, k6, Playwright, Cucumber, Grafana, InfluxDB, Integration Testing, CI/CD

**Tools & Platforms:** Jira, Git, GitHub, Jupyter, VS Code, Cursor, Navicat, PostgreSQL, Azure, Databricks, AI/BI Genie

**Certifications:** Python, C, C++ (IIT Bombay) | OpenCV (University at Buffalo) | Google Data Analytics

---

## Professional Experience

**Acarin Inc. — Software Engineer** | Baltimore, MD | Jan 2026 – Present
- Built a k6 + Chromium browser-based load testing suite simulating up to 20,000 concurrent users through full login, Keycloak SSO, and AI chat workflows for Mission Mind AI's HR Worker, a production system shipped to the US Army.
- Designed a Docker-containerized Grafana + InfluxDB pipeline that exports k6 run metrics in real time, surfacing p95/p99 latency, error rates, and per-endpoint throughput on a live dashboard the 8-person Agile/DevOps team uses to triage regressions.
- Engineered per-user logging pipelines capturing step-by-step latency and error data across thousands of virtual users, reducing debug time by isolating failures to specific workflow stages (auth, bot response, UI render).
- Analyzed failure patterns across runs to identify missing role permissions, bot response timeouts under load, and UI rendering delays; documented findings in structured reports that drove backend fixes.

**Acarin Inc. — Software Engineer Intern** | Baltimore, MD | Oct 2025 – Jan 2026
- Architected a Playwright + Cucumber + TypeScript end-to-end test framework following a strict three-layer pattern (page objects → step definitions → Gherkin features), refactoring a monolithic codebase into 21 files across 8 feature areas (Login, Navigation, Chat, Create Job, Jobs Dashboard, Employees, Settings, Document Review).
- Built a shared step-definition layer (auth.steps.ts) eliminating duplicated login/navigation glue code across feature files, and configured the Cucumber glob loader to auto-discover new *.steps.ts files without manual config edits.
- Authored a custom TypeScript HTML reporter (generate-report.ts) that produces per-scenario reports with embedded screenshots and video artifacts on failure, chained resiliently so reports generate even when tests fail.
- Mapped each UI test scenario 1:1 to the corresponding k6 API load-test workflow, ensuring functional and performance suites validate the same user journeys end-to-end.

**State University of New York Research Foundation — Web Developer** | Binghamton, NY | Feb 2025 – June 2026
- Designed and built the Failure in Making website with hands-on WordPress development, cPanel customization, and content structuring.
- Collaborated with U.S. museum partners in weekly Zoom syncs to align site features with stakeholder and project requirements.

---

## Research & Project Experience

**Interstellar — Developer Intelligence Platform** | Jan 2026 – Present
- Building a unified intelligence layer that ingests context across Jira, Slack, GitHub, Figma, and Docs, then reasons across all signals to detect drift between engineering intent and what is actually being built.
- Designed a reasoning architecture that holds two simultaneous context pictures — what was scoped (tickets, PRDs, Slack decisions, Figma specs) and what is being built (commits, PR diffs, codebase state) — and compares them to proactively surface misalignments before sprint completion.
- Implemented a flagging layer that generates structured, scoped alerts tied to specific engineering artifacts (e.g., identifying when a PR touches modules outside the scoped service boundary) rather than generic alerts.
- Engineered a spec generation module that produces agent-executable files containing build rationale, relevant codebase context, acceptance criteria, prior decisions, and explicit constraints — enabling AI agents to execute without ambiguity.
- Designed two deployment scenarios: vendor-backed (Glean/Onyx via MCP for ingestion, Interstellar adds reasoning) and full-stack (direct API connectors, semantic graph context engine, custom ingestion pipeline).

**Tech:** Python, LLM Reasoning, MCP, REST APIs, Semantic Graph, Jira/Slack/GitHub/Figma Integrations

---

**AI-Powered Candidate-to-Job Matching Platform** | March 2026 – May 2026
- Built a full-stack resume parsing and candidate ranking system using FastAPI, PostgreSQL with pgvector, and OpenAI embeddings, processing PDF resumes into structured JSON via LLM-based extraction.
- Designed REST APIs for resume ingestion (/parse) and semantic job matching (/match), ranking 100+ candidate profiles against job descriptions using cosine similarity over 1536-dimensional embeddings.
- Containerized the application with Docker and deployed to AWS (EC2 + RDS) with automated CI/CD via GitHub Actions, including linting, pytest test suites, and image builds on every push.
- Achieved sub-500ms match latency by indexing embeddings with pgvector's IVFFlat and caching frequent job-description queries in Redis.

**Tech:** FastAPI, PostgreSQL, pgvector, OpenAI API, Docker, AWS EC2/RDS, GitHub Actions, Redis

---

**Runner-up, MICASA UX Hackathon** | May 2025
- Redesigned the complete guest onboarding experience for MICASA, a platform reimagining third spaces for artists and creatives.
- Designed lo-fi and hi-fi prototypes in Figma, introducing invite-code entry, deferred signup, and dashboard-first navigation.
- Improved event discoverability and first-time guest engagement, aligning flows with user mental models.

---

**B-Roommates Housing Portal — ACM Club Project** | Binghamton University | Oct 2024 – April 2025
- Developed React frontend with authentication and REST API integration for a Tinder-style roommate-matching platform.
- Built profile creation, roommate preference filtering, and messaging integration; dockerized the application for team collaboration.
- Conducted UX tests with 10+ engineers and end users; collaborated across a 5-member team in an agile workflow.

**Tech:** React, Node.js, Express, MongoDB, HTML, CSS, REST APIs, Docker, Git

---

**Quantum Computing Research — Under Prof. Yiming Zheng** | Binghamton, NY | Jan 2025 – May 2026
- Conducting research on quantum algorithms and error correction techniques to optimize computational efficiency and reliability.
- Implementing quantum circuits using Qiskit to explore applications in secure computing and cryptography.
- Preparing findings for conference submission and assisting with lab publications.

**Tech:** Python, Qiskit, Quantum Algorithms

---

**NYC CitiBike Data Analysis**
- Cleaned and processed millions of ride records using Pandas, NumPy, and SQL to analyze peak demand, seasonal trends, and station utilization.
- Built interactive dashboards using Tableau and Matplotlib; generated insights for optimizing station placement and rush-hour load balancing.

**Tech:** Python, Pandas, NumPy, SQL, Tableau, Matplotlib

---

## Leadership & Extracurricular Experience

**Course Assistant — Data Structures & Algorithms** | Binghamton University | Jan 2025 – Present
- Designed coding problems and test cases; supported students with debugging during labs and office hours.
- Collaborated with the professor to monitor course progress and improve coding project quality.

**Association for Computing Machinery (ACM), Member** | Binghamton University | Oct 2024 – Present
- Conducted weekly events on data structures and emerging technologies; collaborated on competitive coding challenges.

**Google Developer Student Club, Core Member** | VIT Chennai | Aug 2022 – July 2024
- Organized and managed numerous hackathons including a 72-hour zonal hackathon with 1,500+ participants.

**Toastmasters Club, VPP** | VIT Chennai | Nov 2023 – Aug 2024
- Tracked and guided club members' progress across educational speech pathways; conducted 30+ club meets.
