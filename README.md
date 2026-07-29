# 👋 Lakshay Kaushik

**ECE @ DTU '27 · Full-Stack + AI Systems**

I build production systems, not side-project demos. My projects run on real infrastructure, serve real users, and have bugs I actually had to debug at 2am.

Strong on fundamentals — DSA, system design, clean APIs. AI tools are a force multiplier for me because I can already reason through problems on a whiteboard first.

---

## 🚀 What I've Shipped

### 🤖 [AI Meeting Co-pilot](https://github.com/lakshhayy/meeting-ai-copilot) · `Live` · React · Node.js · PostgreSQL · Redis · Docker
Full-stack SaaS that transcribes meeting recordings and generates AI-powered summaries with semantic search.

**⚙️ The hard parts I actually solved:**
- Async processing pipeline with **BullMQ + Redis** queues — 60min+ recordings process without blocking the main thread or timing out.
- **pgvector RAG pipeline** with Gemini embeddings for semantic search across entire meeting history.
- Built a custom **Chrome Extension** for live tab audio capture and processed recordings through the Groq Whisper API (under 60s for 30min audio).
- Multi-stage **Docker** CI/CD pipeline via GitHub Actions.

---

### 🔬 [ResearchForge](https://github.com/lakshhayy/research-ai) · `Live` · Python · LangGraph · FastAPI · React
A multi-agent AI research platform that automates deep web research and report generation.

- 🧠 Coordinated agent workflows (Planner, Researcher, Synthesizer) using **LangGraph** and the Tavily Search API.
- 🛡️ Implemented an automated **Critic and Grader** workflow to evaluate search results and actively reduce low-confidence/hallucinated responses.
- ⚡ Real-time streaming UI using React and Server-Sent Events (SSE).

---

### 📧 [Email-to-Sheets API Automation](https://github.com/lakshhayy/gmailtosheets) · Python · GCP · OAuth 2.0
An automated data extraction pipeline connecting Google Cloud services.

- 🔄 Integrated **Gmail and Google Sheets APIs** to extract, parse, and log unread emails into a structured spreadsheet.
- 🔐 Implemented **OAuth 2.0** for secure desktop authentication, avoiding hardcoded credentials.
- 🧹 Utilized **BeautifulSoup** to parse complex MIME structures and convert raw HTML emails into clean text.
- 🗂️ Designed a local JSON-based state management system to eliminate duplicate data processing.

---

## 💼 Work Experience

**🔧 Full Stack & Cybersecurity Intern** — ISEA Phase-III, MANIT Bhopal `Dec 2025 – Feb 2026`
- Developed the **Subject Allocator** for the CSE department, automating semester-wise allocation for 75+ subjects and 20+ faculty, reducing allocation time from **3 days to 5 minutes**.
- Engineered secure **JWT authentication** with RBAC, bcrypt hashing, and session fixation protection.
- Hardened API endpoints with rate limiting and httpOnly to effectively mitigate SQL injection and XSS attacks.

**📈 Growth & Analytics Intern** — The Political Architects `Apr 2025 – May 2025`
- Managed Meta ad campaigns, allocating budgets and monitoring key metrics (**ROI, CTR, CPL, CPA**) to maximize performance.
- Applied statistical **A/B testing** on ad creatives to identify high-performing variants and reduce cost per conversion.
- Delivered bi-weekly data-driven reports, enabling the strategy team to make faster, informed budget decisions.

**🎮 SDE Intern** — Clarityze, Health-Tech Startup `Sep 2024 – Mar 2025`
- Built interactive Vision therapy games using **HTML, CSS, JavaScript**, achieving **60+ FPS** for real-time patient interaction.
- Collaborated with therapists to convert 15+ medical exercises into gamified web experiences, improving patient therapy engagement.

---

## 🧠 DSA & Problem Solving

- 💪 **450+ LeetCode problems solved** — Strong grasp on Arrays, Trees, Graphs, DP, and Heaps. Contest rating: **1630+**.
- 🏅 Achieved the **Top 50 SQL Badge** on LeetCode.
- 🏆 Participated in top-tier hackathons like **SIH 2024** and **Execute 5.0**, competing alongside 1000+ developers.

If you want to know how I think through problems, look at my commit history — not just the final code.

---

## 🛠️ Tech Stack

```
Languages     C/C++  Python  JavaScript  TypeScript  HTML/CSS  SQL
Frontend      React  Tailwind CSS  Recharts  Zod
Backend       Node.js  Express  FastAPI  PostgreSQL  MongoDB  Redis  BullMQ
AI / LLM      LangGraph  Groq  OpenAI  pgvector  RAG  Prompt Engineering
Cloud/DevOps  AWS (S3)  GCP  Docker  GitHub Actions  CI/CD
Security      OAuth 2.0  RBAC  JWT  OWASP Principles
```

---

## 📍 Currently

- 🎓 B.Tech ECE @ Delhi Technological University — Class of 2027
- ⚡ Sharpening DSA + contest rating, targeting 1700+ on Codeforces
- 🤖 Building AI annotation and agentic tooling projects on the side

---

## 📫 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/lakshay-kaushik-b9b40a284)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/lakshhayy)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lakshaykaushik2059@gmail.com)
