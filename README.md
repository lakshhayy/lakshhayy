# 👋 Lakshay Kaushik

**ECE @ DTU '27 · Full-Stack + AI Systems**

I build production systems, not side-project demos. My projects run on real infrastructure, serve real users, and have bugs I actually had to debug at 2am.

Strong on fundamentals — DSA, system design, clean APIs. AI tools are a force multiplier for me because I can already reason through problems on a whiteboard first.

---

## 🚀 What I've Shipped

### 🤖 [AI Meeting Co-pilot](https://github.com/lakshhayy/ai-meeting-copilot) · `Live` · React · Node.js · PostgreSQL · Redis · Docker
Full-stack SaaS that transcribes meeting recordings and generates AI-powered summaries with semantic search.

**⚙️ The hard parts I actually solved:**
- Async processing pipeline with **Bull + Redis** queues — 60min+ recordings process without blocking the main thread or timing out
- **pgvector RAG pipeline** with OpenAI embeddings for semantic search across entire meeting history
- Multi-tenant RBAC via Clerk + Drizzle ORM — proper data isolation, not just auth guards
- Multi-stage **Docker** build + Docker Compose; structured logging across all async jobs
- Groq Whisper API for transcription (~10–20x faster than OpenAI Whisper)

**💡 Why it's not just a weekend project:** Deployed on Render with a Chrome Extension using `tabCapture` for real-time audio — the extension, WebSocket pipeline, transcription, and RAG all work end-to-end.

---

### 🏫 [Automated Subject Allocation System](https://github.com/lakshhayy/subject-allocation) · `Production @ NIT Bhopal` · React · Node.js · PostgreSQL

Actually used by faculty every semester at NIT Bhopal's CSE department.

- 📋 Allocates 50+ courses automatically based on seniority + workload constraints
- 🔒 **Atomic PostgreSQL transactions** to prevent race conditions — 100% allocation integrity guaranteed
- 🛡️ RBAC, Zod validation, rate limiting, bcrypt, XSS + session fixation prevention baked in
- 📊 Real-time faculty preference tracking dashboard

---

### 🎬 [Video Platform Backend](https://github.com/lakshhayy/video-platform) · Node.js · Express · MongoDB · JWT · Cloudinary

- ⚡ RESTful API handling 100+ concurrent connections
- 📤 Async media upload pipeline with Multer + Cloudinary
- 🔐 Custom JWT middleware, role-based access control, NoSQL schemas with Mongoose

---

## 💼 Work Experience

**🔧 Full Stack & Cybersecurity Intern** — ISEA Phase-III, MANIT Bhopal `Dec 2025 – Jan 2026`
- Automated a **3-day manual forensic workflow to under 5 minutes** (99% reduction) with Node.js + PostgreSQL
- Applied OWASP Top 10 practices: rate limiting, ClamAV/YARA-based malware detection
- Digital forensic acquisition using FTK, Oxygen Forensics, Tableau TX1

**🎮 Frontend Developer Intern** — Clarityze, Health-Tech Startup `Oct 2024 – Mar 2025`
- Built 3D browser-based therapy games with **Three.js at 60+ FPS** for real-time patient interaction
- Gamified 15+ medical exercises to improve engagement and compliance

---

## 🧠 DSA & Problem Solving

- 💪 **180+ LeetCode problems** — skewed toward Mediums and Hards, regular contest participant
- 🗂️ Strong on: DP patterns (Grid, Knapsack, String, Interval), Graphs (Dijkstra, topological sort), Sliding Window, Trees
- 🏆 Competed in SIH 2024 and Execute 5.0 alongside 1000+ developers

If you want to know how I think through problems, look at my commit history — not just the final code.

---

## 🛠️ Tech Stack

```
Languages     C/C++  JavaScript  TypeScript  Python  SQL
Frontend      React  Tailwind CSS  Three.js  Zod  Recharts
Backend       Node.js  Express  FastAPI
Databases     PostgreSQL  MongoDB  Redis
ORM           Drizzle ORM  Mongoose
Auth          Clerk  JWT  RBAC  OAuth
DevOps        Docker  Docker Compose  Git/GitHub
AI / LLM      Groq Whisper  OpenAI API  pgvector  RAG pipelines
Security      OWASP Top 10  TLS  ClamAV/YARA  Digital Forensics
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

---

> 🐛 *"The most interesting bug I've fixed: a race condition in atomic PostgreSQL transactions where two faculty simultaneously claimed the same course slot — solved by upgrading to SERIALIZABLE isolation and retrying at the application layer."*
