<h1 align="center">Hi, I'm Hrishikesh 👋</h1>

<p align="center">
  CS @ UT Dallas '28 · building AI systems that have to work in the real world
</p>

<p align="center">
  <a href="https://linkedin.com/in/hrishikeshnaveenam"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:hrishinave@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://komarev.com/ghpvc/?username=hrishinave&style=flat&color=blue" alt="Profile views">
</p>

---

### About

I'm a Computer Science student at UT Dallas (minor in Math) who spends most of his time on the messy parts of AI systems — the state machines, the crash-safety, the latency budgets, the thing that breaks when a real camera feed hits a model trained on grayscale data.


- 🔬 **Undergraduate Researcher @ UTD URAP** (advised by Prof. Wei Yang) — studying the root causes of non-determinism in LLM inference. Curated 200+ documented cases and built harnesses that replay divergent runs.
- 🌱 **Open source** — contributor to [OpenWorker](https://github.com/andrewyng/openworker) (Andrew Ng), where I added NVIDIA NIM catalog models behind an OpenAI-compatible interface and closed an auth gap that let invalid API keys pass validation.
- 🏆 2nd Place out of 350+ at HackUTD 2025 (PNC Track) · Dean's List
- 💬 Ask me about edge ML, agent orchestration, RAG that actually cites its sources, or why your WebSocket server is leaking hole cards.

---

### What I'm building

**🗣️ [Holler](https://github.com/hrishinave/Holler)** — a multichannel AI agent harness
> Unifies WhatsApp, Telegram, and Twilio into one persistent, event-driven agent runtime with Gmail, Outlook, Drive, and Calendar exposed as callable tools. Hit **91% task completion** on a 100-workflow eval suite while cutting LLM calls 28% and cost 24% vs. a multi-agent baseline. Destructive tool calls are crash-safe: each proposal commits to a single-use pending-action record in WAL-mode SQLite and is consumed atomically, so a replayed turn drops the action instead of double-sending.
> `Python` `FastAPI` `TypeScript` `SQLite` `Twilio` `Composio` `RAG`

**♠️ [Live Multiplayer Poker](https://poka-client.vercel.app)** — authoritative real-time game server
> **360 concurrent players across 60 tables at 1,871 actions/sec** with 0.3 ms p95 action-to-broadcast latency. Deterministic seeded-RNG engine with chip-conservation invariants, proven across 3,000 fuzzed hands and 106 tests. Per-viewer state projection plus a recursive payload scanner in CI asserts zero hole-card leakage across every player, spectator, and history view.
> `React` `TypeScript` `Node.js` `WebSockets` `Supabase` `Vercel`

**📋 AutoPM** — AI product-management copilot · *2nd Place, HackUTD 2025*
> Orchestrates 8 LangGraph agents across a 7-step workflow — research, user stories, RICE prioritization, wireframing, Jira tickets — with Zod-validated structured outputs across 3 third-party APIs. Cuts an estimated 10+ hours of manual PM work per cycle.
> `Next.js` `TypeScript` `LangGraph` `Gemini`

**📚 Research Mate** — RAG over papers that cites its page
> Two-node LangGraph pipeline retrieving the top 10 pages from a hybrid ColQwen2 index over Qdrant and FAISS, answering on Groq Llama 3.3 70B constrained to cite its source page. Ingestion is crash-safe and idempotent via a Postgres state machine and deterministic `sha256(pdf_id | page)` vector IDs.
> `Python` `LangGraph` `ColQwen2` `Qdrant` `PostgreSQL` `Gemini`

**🏀 [NetGainNBA](https://net-gain-nba.vercel.app)** — playoff prediction + GM toolkit
> 88% playoff-prediction accuracy on 2020–2024 data from a 7-model ensemble across 89 features, with live win-probability tracking and K-Means player archetypes.
> `React` `Flask` `XGBoost` `scikit-learn`

---

### Tech

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat&logo=swift&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat&logo=onnx&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![LangChain](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)

**Web & Backend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)

**Cloud, Edge & DevOps**

![NVIDIA Jetson](https://img.shields.io/badge/Jetson-76B900?style=flat&logo=nvidia&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

### Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=hrishinave&show_icons=true&include_all_commits=true&hide_border=true&theme=tokyonight" alt="GitHub stats">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hrishinave&layout=compact&langs_count=8&hide_border=true&theme=tokyonight" alt="Top languages">
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=hrishinave&hide_border=true&theme=tokyonight" alt="Streak">
</p>

---

### Beyond code

Officer at UT Dallas's **Artificial Intelligence Society**, where I help run **HackAI** — the university's annual AI hackathon — and lead technical workshops. Also Product Manager for **TuneTrend** in the UTD AI Mentorship Program, directing a 5-person team building a genre-aware music popularity predictor.

<p align="center"><i>Open to Summer 2027 SWE internships — say hi.</i></p>
