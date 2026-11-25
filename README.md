## Hi, I'm Susano Kevin

AI engineer and IT support specialist in Milwaukee, WI. I build LLM-powered tools with Python, test them with Playwright, and bring three years of university help desk and desktop support experience to every project. M.S. in IT Management (AI & Data Analytics), UW-Milwaukee.

Looking for AI engineer, AI automation, and IT support / help desk roles in Wisconsin, open to relocation, or remote. I'm especially interested in AI for IT service management: ticket triage, knowledge base search, and self-service assistants.

### What I've built

- **[Customer Support AI Agent](https://github.com/SusanoKevin/customer-support-ai-agent) ([live demo](https://customer-support-ai-agent-nine.vercel.app)):** a billing support agent with streaming chat and live two-way voice (Gemini Live, with barge-in) over one shared agent session. It retrieves policy documents with RAG (Gemini embeddings, Postgres pgvector) and only answers above a measured similarity threshold. Routing, identity checks, and refund rules run in server code instead of trusting the model, and a citation check runs before any answer streams. FastAPI backend with a typed SSE event contract, Next.js frontend, per-step latency, token, and cost tracing, rate limits, 145 pytest tests (93% coverage), deployed on Render and Vercel.
- **AI data analyst prototype (Excellerate Education Solutions, private):** shows dashboards and predicts student attendance rates and exam scores from PostgreSQL and SQL Server data. Full stack in Python and TypeScript: a 13-tool LangGraph ReAct agent with RAG over ChromaDB (Ollama embeddings and LLMs), an SSE-streaming FastAPI backend (Pydantic, Uvicorn) with JWT auth, rate limiting, and Redis, a React + Tailwind frontend, and an MCP server exposing its tools to Claude Code, all run in Docker and Docker Compose. I also set up role-based access control and monitored API and token usage in Grafana and Prometheus.
- **Playwright test suites (Excellerate, private):** TypeScript end-to-end tests for an ERP and an applicant tracking web app.
- **[Churn-Predictor](https://github.com/SusanoKevin/Churn-Predictor):** Random Forest churn classifier with SMOTE on the Kaggle Telco dataset, served through a Streamlit app.
- **[LangrisserBot](https://github.com/SusanoKevin/LangrisserBot):** Discord slash-command bot (discord.py) with game data that auto-refreshes every 4 hours.

### IT support experience

- Tier 1 and Tier 2 help desk and desktop support for faculty, staff, and students at two Wisconsin universities
- 8 to 15 tickets a day, 20 to 30+ at semester start, tracked in TeamDynamix and Track-IT within response targets
- Windows imaging and deployment, hardware repair (RAM, SSDs), printers, classroom AV, Wi-Fi and VPN troubleshooting
- Knowledge base guides, user training, and supervising student workers

### Skills

- **AI & LLM:** LangGraph, RAG, ChromaDB, embeddings, Ollama, Model Context Protocol (MCP), prompt engineering, Claude Code
- **Code & APIs:** Python, TypeScript (Playwright), SQL (PostgreSQL, SQL Server), Redis, FastAPI, Pydantic, Uvicorn, REST APIs, SSE streaming, JWT auth, role-based access control, React, Tailwind CSS
- **IT support & ITSM:** TeamDynamix (TDX), Track-IT, Jira, ticket triage, escalation, knowledge base articles, Windows imaging and deployment, Active Directory (fundamentals)
- **DevOps, testing & monitoring:** Docker, Docker Compose, Git, CI/CD, Playwright, Grafana, Prometheus
- **ML & data:** pandas, scikit-learn, Streamlit, SnowPro Associate: Platform Certification
- **Platforms:** Windows, macOS, Linux (Ubuntu, Arch), VMware and Hyper-V (familiarity)

### Experience

- **Software Engineer Intern**, Excellerate Education Solutions (Jan 2026 - present)
- **Help Desk Technician (Tier 1)**, Carroll University (Sept 2023 - May 2024)
- **Help Desk & Desktop Support Technician (Tier 2)**, Cardinal Stritch University (May 2021 - May 2023)

### Contact

[LinkedIn](https://www.linkedin.com/in/susano-kevin/) · susanokevin29@gmail.com · Milwaukee, WI
