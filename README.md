# Hi, I'm Radhika Tenali 👋

**Associate Software Engineer and MCA (Artificial Intelligence) student** based in Bengaluru, India. I build full-stack applications, backend APIs and applied-AI systems, with about 1 year 10 months of professional experience across enterprise SaaS, AI-powered applications and mobile.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-radhika--t-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/radhika-t-266b85209)

---

## What I work on

- **Full-stack and backend/API:** React, Next.js, Node.js, FastAPI. Multi-tenant REST APIs, JWT and role-based access, WebSockets, background job queues.
- **Applied AI/LLM:** RAG with hybrid vector + keyword retrieval, multi-agent workflows (LangGraph, Google ADK), OCR and computer vision, voice agents, embedding-based matching.
- **Enterprise SaaS:** tenant isolation, security hardening, cloud deployment (AWS, Docker, GitHub Actions).
- **Mobile and automation:** Ionic/Capacitor and Android (Java) apps, offline sync, workflow automation.

My day job is proprietary enterprise work, so nothing from it appears here. Everything below is my own hackathon, competition or independent work.

---

## Hackathon finalist projects

| Project | Event | What it is | Repo |
|---|---|---|---|
| **Sahayak** | Paytm Build for India AI Hackathon 2026, **Finalist** | Voice-first autonomous AI teammate for merchant support and sales. Sarvam AI speech (Hindi, Kannada, English), a 6-state agent loop, a guardrail layer (₹50,000 action cap, confidence gate, SHA-256-chained audit trail) and human escalation. Built with a teammate, Lankipalli Tharun. Evaluated on 20 scripted scenarios against **mock** Paytm services, not live Paytm systems. | [sahayak](https://github.com/Tenali-Radhika/sahayak) |
| **AI CFO Agent** | SuperHack 2025, **Finalist** | Multi-agent financial decision-support tool for MSPs: profitability analysis, software-license optimization, upsell detection and scenario simulation. FastAPI + React on AWS Bedrock. Runs on **mock data** when AWS credentials are absent. | [SuperHack2025-AICFOAgent](https://github.com/Tenali-Radhika/SuperHack2025-AICFOAgent) |
| **MedReg AI** | Build and Blog Marathon 2025, **Finalist** | Turns healthcare regulatory requirements (PDF, Word, XML) into draft test cases and traceability matrices. Streamlit UI; Gemini/Vertex AI with OpenAI and Claude as alternatives, plus a rule-based fallback. | [MedReg-AI](https://github.com/Tenali-Radhika/MedReg-AI) |
| **Desi Bhasha Mandi** | AI for Bharat 2026, **Finalist** | Multilingual marketplace for Indian vendors: phone-OTP auth, translation, mandi price discovery, AI negotiation suggestions and vendor verification. Next.js 14, TypeScript, PostgreSQL/Prisma, Redis, PWA, Jest + fast-check. The project's status doc marks the foundation phase (design system, PWA, database, CI) complete, with the language and translation layer next. *Private repo.* | private |

## More projects

Each of these was built under a hackathon or competition deadline, so treat them as **prototypes**. Where a project uses synthetic data, mock APIs or simulated components, the project README says so, and I do too.

| Project | Context | What it is | Repo |
|---|---|---|---|
| **KSP CrimeIQ** | Hackathon prototype | Conversational crime-intelligence assistant over a FIR/accused/victim/network database. A LangGraph multi-agent pipeline (intent → Kannada translation → hybrid RAG → pattern and network analysis), role-based access with PostgreSQL row-level security, a Cytoscape.js criminal-network graph, an explainable-AI reasoning trace per answer, and Kannada voice support. FastAPI + Next.js 14 + pgvector, designed for Zoho Catalyst. Runs on a **synthetic** Karnataka-style dataset. *Private repo.* | private |
| **GramSense AI** | AI for Bharat hackathon, prototype phase | Decision-support platform for small farmers: mandi price dashboard, 7–30 day price forecasts, explainable sell/wait recommendations and weather-aware advice. FastAPI backend with forecasting and recommendation modules; AWS architecture documented. *Private repo.* | private |
| **TrustBridge** | Snowflake hackathon prototype | Privacy-preserving credit check across a bank and a utility company without sharing raw PII, using Snowflake masking and row access policies, a secure-view "clean room" (**simulated**) and Cortex. Streamlit in Snowflake, on **synthetic** data (10,000 rows per side). *Private repo.* | private |
| **Entity Resolution Pipeline** | Amazon ML Challenge | Hybrid matching of business records across 3 data sources: multilingual MiniLM bi-encoder + FAISS and TF-IDF blocking, then a fine-tuned DeBERTa-v3 cross-encoder, with the decision threshold tuned for F₀.₅. *Private repo.* | private |
| **OntologyOne** | Snowflake CoCo CLI Hackathon (team lead) | Governed supply-chain analytics on Snowflake Cortex. A two-tier "truth" design: a certified aggregate mart gives every persona the same KPI, while row-level drill-downs stay governed by row access policies and masking. Streamlit UI, seeded synthetic data, pytest governance suite. | [OntologyOne](https://github.com/Tenali-Radhika/OntologyOne) |
| **Nivorq** | AI Builder Cup 2026 | Enterprise knowledge-and-meetings copilot: multi-agent orchestration on Google ADK/Gemini, hybrid RAG with citations, meeting-intelligence view, Kanban action board with Jira export. FastAPI + React 19, Docker/Cloud Build config. Has a simulation mode when no API key is set. | [Nivorq](https://github.com/Tenali-Radhika/Nivorq) |
| **TigerGraph Agentic Fraud Sentinel** | HHGOA Hackathon | Fraud-investigation agent: a LangGraph state machine over a TigerGraph graph (GSQL schema, multi-hop queries), human-in-the-loop gating and generated SAR reports. Falls back to an embedded graph engine without a TigerGraph instance. All 20 benchmark cases were run. | [TigerGraph-Agentic-Fraud-Investigation](https://github.com/Tenali-Radhika/TigerGraph-Agentic-Fraud-Investigation) |
| **SahyogAI** | BRICS-themed health supply-chain hackathon | Next.js platform for public-health stock visibility, demand forecasting, redistribution matching and multilingual voice field reports (Google Speech + Gemini). Uses **synthetic** data and a federated-learning **simulation**. | [SahyogAi](https://github.com/Tenali-Radhika/SahyogAi) |
| **Pivot Pilot** | Agentic AI Hackathon 2026 | Voice-first career-transition coach: resume vs. job-description skill-gap analysis, a 6-week roadmap and a mock-interview studio scored on four dimensions. React 19 + FastAPI, Gemini/Claude with an offline fallback. | [Pivot_Pilot](https://github.com/Tenali-Radhika/Pivot_Pilot) |
| **Stock Weaves** | AI for Bharat hackathon | Streamlit dashboard testing whether stock returns relate to lunar phases, using permutation tests and bootstrap confidence intervals, with property-based tests. An experiment in rigorous statistical testing rather than a trading tool. *Private repo.* | private |
| **LifeSync Mind** | Dreamflow Buildathon 2025 | Personal productivity and wellness app: tasks, habits, mood tracking and reflections. Next.js 14, TypeScript, Prisma, NextAuth. *Private repo.* | private |

## Tech stack

| | |
|---|---|
| **Languages** | JavaScript, TypeScript, Python, Java, SQL |
| **Frontend** | React 18/19, Next.js, Ionic, Tailwind CSS, Ant Design, Zustand, PWA, Web Workers |
| **Backend** | Node.js, Express, Sails.js, Flask, FastAPI, REST, JWT, RBAC, Socket.IO, Redis, BullMQ |
| **Mobile** | Ionic + Capacitor, Android (Java), Firebase Cloud Messaging, IndexedDB offline sync |
| **Data and cloud** | MongoDB Atlas, PostgreSQL + pgvector, Prisma, AWS (S3, ECS, ECR), Azure OpenAI, Docker, GitHub Actions |
| **AI/ML** | RAG, hybrid vector + keyword search, OpenCV, ONNX (YOLO), Tesseract OCR, Gemini API, Anthropic Claude, Sarvam AI, AWS Bedrock, LangChain, LangGraph, FAISS, Hugging Face Transformers, Streamlit |
| **Testing and tools** | Jest, pytest, Postman, Git |

*I use these in production at work. Most of the AI tooling in the projects above (Bedrock, LangGraph, TigerGraph, Snowflake Cortex, Google ADK, Zoho Catalyst) is prototype-level.*

## Education

- **MCA, Artificial Intelligence**, KL University (online): pursuing, Jul 2025 – Aug 2027, CGPA 9.26/10
- **B.Com, Computer Applications**, Vikram Simhapuri University: graduated Aug 2024

## Get in touch

Open to conversations about full-stack, backend and applied-AI roles. The fastest way to reach me is [LinkedIn](https://linkedin.com/in/radhika-t-266b85209).