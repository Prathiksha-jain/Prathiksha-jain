[README.md](https://github.com/user-attachments/files/27196545/README.md)
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F0C29,50:302B63,100:24243e&height=280&section=header&text=AI%20Engineer&fontSize=70&fontColor=ffffff&animation=twinkling&fontAlignY=38&desc=Building%20Production-Grade%20GenAI%20Systems%20%7C%20RAG%20%7C%20LLMs%20%7C%20Backend%20Architect&descSize=17&descAlignY=60" />

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=22&duration=2800&pause=900&color=A78BFA&center=true&vCenter=true&width=950&lines=🚀+Building+production-grade+GenAI+systems.;🧠+Hybrid+RAG+%7C+Vector+Search+%7C+Local+LLMs.;⚡+Real-time+AI+Pipelines+%7C+Backend+Systems.;🔥+Offline-first+AI+%E2%80%94+a+rare+skill+in+the+wild.;💡+Not+just+models.+End-to-end+AI+systems." />

<br/>

[![Profile Views](https://komarev.com/ghpvc/?username=YOUR_USERNAME&label=Profile%20Views&color=7C3AED&style=for-the-badge)](https://github.com/YOUR_USERNAME)
[![GitHub followers](https://img.shields.io/github/followers/YOUR_USERNAME?label=Followers&style=for-the-badge&color=A78BFA)](https://github.com/YOUR_USERNAME)

</div>

---

## 🧬 About Me

```yaml
╔══════════════════════════════════════════════════════════════╗
║                     ENGINEER PROFILE                         ║
╠══════════════════════════════════════════════════════════════╣
║  Role        : AI Engineer | GenAI Builder | Backend Arch    ║
║  Focus       : RAG Systems, LLMs, Real-time AI Pipelines     ║
║  Mindset     : Systems thinker. Builder. Solver.             ║
║  Superpower  : Production-grade AI — not just notebooks 🚀   ║
╠══════════════════════════════════════════════════════════════╣
║  Currently   : Designing LLM-augmented pipelines             ║
║  Learning    : Multimodal RAG, Agent frameworks              ║
║  Available   : Collaborations & Open Source                  ║
╚══════════════════════════════════════════════════════════════╝
```

> **One-line summary:** _Building production-grade GenAI systems using RAG, local LLMs, and scalable backend architectures._

---

## 🚀 What I've Built

### 🧠 1. Hybrid RAG Systems — _My Core Strength_

> Production-style Retrieval-Augmented Generation pipelines — not toy projects.

```
┌─────────────────────────────────────────────────────────────┐
│               HYBRID RAG ARCHITECTURE                       │
│                                                             │
│  User Query                                                 │
│      │                                                      │
│      ├──► 🔍 Vector Search (ChromaDB)  ──► VECTOR_TOP_K    │
│      │         sentence-transformers                        │
│      │         all-MiniLM-L6-v2                            │
│      │                                                      │
│      ├──► 🔑 Keyword Search (BM25)     ──► BM25_TOP_K      │
│      │         rank_bm25                                    │
│      │                                                      │
│      └──► 🎯 Hybrid Merge             ──► FINAL_TOP_K      │
│                    │                                        │
│                    ▼                                        │
│              🤖 Local LLM (Ollama)                         │
│              mistral / qwen2.5-coder                        │
│                    │                                        │
│                    ▼                                        │
│              📤 Context-Aware Answer                        │
└─────────────────────────────────────────────────────────────┘
```

**Key features built:**
- ✅ Follow-up query detection & topic anchoring
- ✅ Session-based context memory via **Redis** (`chat:session:{user_id}:{session_id}`)
- ✅ Intelligent routing — Casual vs Technical vs Follow-up queries
- ✅ Multi-stage retrieval pipeline
- ✅ Real-time chat UI with **Streamlit**
- ✅ Automotive domain QA & Policy/Document QA systems
- 🔜 LLM-based query rewriting *(next-level in progress)*

---

### 🌐 2. Safeguard AI — Full-Stack AI Monitoring Dashboard

> Real-world AI-powered safety monitoring system with real-time event pipelines.

```
┌─────────────────────────────────────────────────────────────┐
│                 SAFEGUARD AI ARCHITECTURE                    │
│                                                             │
│  📷 Camera Feed                                             │
│       │                                                     │
│       ▼                                                     │
│  ML Detection Engine  ──►  POST /api/v1/violations          │
│  (PPE / Zone Breach)         │                              │
│                              ▼                              │
│                     🔥 Real-Time Pipeline                   │
│                     Base64 Image Decode                     │
│                     Snapshot Storage                        │
│                     event_id / camera_id / zone_id          │
│                              │                              │
│                              ▼                              │
│                     ⚡ Socket.IO Broadcast                  │
│                              │                              │
│                              ▼                              │
│              🖥️ Next.js Dashboard (Live Alerts)             │
│              Admin / Manager / Supervisor Roles             │
└─────────────────────────────────────────────────────────────┘
```

**Stack:** `Node.js` · `TypeScript` · `Express` · `PostgreSQL` · `Prisma ORM` · `JWT` · `Socket.IO` · `Next.js` · `Tailwind CSS`

---

### 📊 3. ATS — AI Resume Matcher System

> Intelligent hiring system. No hardcoded skill lists. Just LLM-powered understanding.

```
Phase 1: Resume Parsing + Metadata Extraction
    │
    ▼
Phase 2: Fast JD Matching
    ├── Dynamic skill extraction (no hardcoding)
    ├── Context-aware scoring
    └── LLM-based evaluation
    
Optimized for: 150+ resumes | Fast inference
```

---

### ⚡ 4. Scalable AI System Architecture

> Designed for 10–20 concurrent users, offline-first AI, multi-worker queuing.

```
UI → FastAPI → Queue → Workers → Redis → RAG Pipeline → LLM
                                    │
                                    └── Session Memory
                                        context isolation
                                        per-user state
```

**Bottleneck-aware design:** LLM inference = slowest part → Worker scaling strategy applied.

---

## 🛠️ Tech Stack

<div align="center">

### 🧠 AI / ML

![Ollama](https://img.shields.io/badge/Ollama-Local%20LLMs-000000?style=for-the-badge&logo=ollama&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-Vector%20DB-FF6B35?style=for-the-badge)
![HuggingFace](https://img.shields.io/badge/Sentence%20Transformers-Embeddings-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![BM25](https://img.shields.io/badge/BM25-Keyword%20Search-6366F1?style=for-the-badge)

**Models I work with:**
`mistral` · `qwen2.5-coder` · `all-MiniLM-L6-v2`

---

### ⚡ Backend

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

---

### 🌐 Frontend

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socketdotio&logoColor=white)

---

### 🗄️ Databases & ORMs

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=for-the-badge)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

---

### 🧰 Dev Tools & Infra

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Windows](https://img.shields.io/badge/Windows-0078D4?style=for-the-badge&logo=windows&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST%20APIs-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

</div>

---

## 🧠 AI/GenAI Knowledge Depth

```
RAG Architectures
  ├── Naive RAG
  ├── Hybrid RAG (Vector + Keyword + Metadata) ✅ Built
  ├── Tool-Augmented RAG
  └── Multimodal RAG (learning)

Embeddings & Semantic Search ✅
Chunking Strategies ✅
Retrieval Evaluation Challenges ✅
LLM Limitations & Hallucination Control ✅
Context Window Management ✅
Session Memory Design ✅
Offline-first AI Systems ✅ (rare skill 🚀)
```

---

## 🎯 What Makes Me Different

| Trait | Details |
|-------|---------|
| 🏗️ **End-to-end builder** | Not just models — full systems from UI to DB to LLM |
| 🚀 **Offline-first AI** | Local LLMs, no cloud dependency — rare in the field |
| ⚡ **Real-time pipelines** | Socket.IO + async queuing for live AI events |
| 🧩 **System design first** | Think in bottlenecks, scale, and worker architecture |
| 🔍 **Hybrid retrieval** | Vector + BM25 hybrid — not just naive vector search |
| 🛠️ **Production mindset** | Debugged CORS, Prisma, Redis, API failures in real deployments |

---

## 📈 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=midnight-purple&hide_border=true&bg_color=0D0D0D&title_color=A78BFA&icon_color=7C3AED&text_color=E2E8F0" height="160"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=midnight-purple&hide_border=true&bg_color=0D0D0D&title_color=A78BFA&text_color=E2E8F0" height="160"/>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com?user=YOUR_USERNAME&theme=midnight-purple&hide_border=true&background=0D0D0D&ring=7C3AED&fire=A78BFA&currStreakLabel=E2E8F0" />

</div>

---

## 🔮 What's Next

```
🔜 LLM-based query rewriting
🔜 Multimodal RAG (vision + text)
🔜 AI Agent frameworks
🔜 Evaluation pipelines (RAGAs, TRULENS)
🔜 Performance benchmarking dashboards
```

---

## 🤝 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_PROFILE)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YOUR_USERNAME)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:YOUR_EMAIL)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302B63,100:0F0C29&height=120&section=footer" />

**"I don't just use AI. I build the systems that power it."** 🚀

</div>
