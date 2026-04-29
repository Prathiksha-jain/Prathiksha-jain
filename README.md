<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F0C29,50:302B63,100:24243e&height=280&section=header&text=Prathiksha%20Jain&fontSize=65&fontColor=ffffff&animation=twinkling&fontAlignY=38&desc=AI%20Engineer%20%7C%20GenAI%20Builder%20%7C%20Backend%20Architect&descSize=18&descAlignY=60" />

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=22&duration=2800&pause=900&color=A78BFA&center=true&vCenter=true&width=950&lines=🚀+Building+production-grade+GenAI+systems.;🧠+Hybrid+RAG+%7C+Vector+Search+%7C+Local+LLMs.;⚡+Real-time+AI+Pipelines+%7C+Backend+Systems.;🔥+Offline-first+AI+%E2%80%94+a+rare+skill+in+the+wild.;💡+Not+just+models.+End-to-end+AI+systems." />

<br/>

[![Profile Views](https://komarev.com/ghpvc/?username=Prathiksha-jain&label=Profile%20Views&color=7C3AED&style=for-the-badge)](https://github.com/Prathiksha-jain)
[![GitHub followers](https://img.shields.io/github/followers/Prathiksha-jain?label=Followers&style=for-the-badge&color=A78BFA)](https://github.com/Prathiksha-jain)

</div>

---

## 🧬 About Me

<div align="center">

| | |
|:---|:---|
| 🎯 **Role** | AI Engineer · GenAI Builder · Backend Architect |
| 🔍 **Focus** | RAG Systems · LLMs · Real-time AI Pipelines |
| 🧠 **Mindset** | Systems thinker. Builder. Solver. |
| 🚀 **Superpower** | Production-grade AI — not just notebooks |
| ⚙️ **Currently** | Designing LLM-augmented pipelines |
| 📚 **Learning** | Multimodal RAG · Agent Frameworks |
| 🤝 **Available** | Collaborations & Open Source |

</div>

> **One-line summary:** _Building production-grade GenAI systems using RAG, local LLMs, and scalable backend architectures._

---

## 🚀 What I've Built

### 🧠 1. Hybrid RAG Systems — _My Core Strength_

> Production-style Retrieval-Augmented Generation pipelines — not toy projects.

```mermaid
flowchart TD
    A[🧑 User Query] --> B[🔍 Vector Search\nChromaDB · all-MiniLM-L6-v2]
    A --> C[🔑 Keyword Search\nBM25 · rank_bm25]
    A --> D[🗂️ Metadata Filter]
    B --> E[VECTOR_TOP_K]
    C --> F[BM25_TOP_K]
    D --> G[META_FILTER]
    E --> H[🎯 Hybrid Merger\nFINAL_TOP_K]
    F --> H
    G --> H
    H --> I[🤖 Local LLM via Ollama\nmistral · qwen2.5-coder]
    I --> J[📤 Context-Aware Answer]

    style A fill:#1e1b4b,color:#fff,stroke:#7C3AED
    style H fill:#312e81,color:#fff,stroke:#A78BFA
    style I fill:#1e1b4b,color:#fff,stroke:#7C3AED
    style J fill:#14b8a6,color:#fff,stroke:#0d9488
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

```mermaid
flowchart LR
    A[📷 Camera Feed] --> B[🤖 ML Detection Engine\nPPE · Zone Breach]
    B --> C[POST /api/v1/violations]
    C --> D[🔥 Real-Time Pipeline\nBase64 Decode · Snapshot Store]
    D --> E[⚡ Socket.IO Broadcast]
    E --> F[🖥️ Next.js Dashboard\nLive Alerts · Role-based UI]
    F --> G[👤 Admin]
    F --> H[👤 Manager]
    F --> I[👤 Supervisor]

    style A fill:#1e1b4b,color:#fff,stroke:#7C3AED
    style B fill:#312e81,color:#fff,stroke:#A78BFA
    style D fill:#1e1b4b,color:#fff,stroke:#7C3AED
    style F fill:#14b8a6,color:#fff,stroke:#0d9488
```

<div align="center">

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

</div>

---

### 📊 3. ATS — AI Resume Matcher System

> Intelligent hiring system. No hardcoded skill lists. Just LLM-powered understanding.

```mermaid
flowchart TD
    A[📄 Resume Upload\n150+ resumes] --> B[Phase 1: Parsing\nMetadata Extraction]
    B --> C[🧠 Dynamic Skill Extraction\nNo hardcoding — LLM-powered]
    C --> D[Phase 2: JD Matching\nFast Inference]
    D --> E[🎯 Context-Aware Scoring]
    E --> F[📊 LLM-Based Evaluation\nRanked Output]

    style A fill:#1e1b4b,color:#fff,stroke:#7C3AED
    style C fill:#312e81,color:#fff,stroke:#A78BFA
    style F fill:#14b8a6,color:#fff,stroke:#0d9488
```

---

### ⚡ 4. Scalable AI System Architecture

> Designed for 10–20 concurrent users, offline-first AI, multi-worker queuing.

```mermaid
flowchart LR
    A[🖥️ UI] --> B[⚡ FastAPI]
    B --> C[📬 Queue]
    C --> D[👷 Workers]
    D --> E[🔴 Redis\nSession Memory]
    D --> F[🧠 RAG Pipeline]
    F --> G[🤖 LLM]
    E --> F

    style A fill:#1e1b4b,color:#fff,stroke:#7C3AED
    style C fill:#312e81,color:#fff,stroke:#A78BFA
    style F fill:#312e81,color:#fff,stroke:#A78BFA
    style G fill:#14b8a6,color:#fff,stroke:#0d9488
```

> 💡 **Bottleneck-aware:** LLM inference = slowest part → Worker scaling strategy applied.

---

## 🛠️ Tech Stack

<div align="center">

### 🧠 AI / ML

![Ollama](https://img.shields.io/badge/Ollama-Local%20LLMs-000000?style=for-the-badge&logo=ollama&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-Vector%20DB-FF6B35?style=for-the-badge)
![HuggingFace](https://img.shields.io/badge/Sentence%20Transformers-Embeddings-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![BM25](https://img.shields.io/badge/BM25-Keyword%20Search-6366F1?style=for-the-badge)

**Models I work with:** `mistral` · `qwen2.5-coder` · `all-MiniLM-L6-v2`

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

## 🧠 AI / GenAI Knowledge Depth

<div align="center">

| Domain | Topics | Status |
|--------|--------|--------|
| **RAG Architectures** | Naive · Hybrid · Tool-Augmented · Multimodal | ✅ Built + Learning |
| **Embeddings** | Semantic search · Sentence Transformers | ✅ |
| **Chunking Strategies** | Sliding window · Semantic chunking | ✅ |
| **Retrieval Evaluation** | Precision · Recall · MRR challenges | ✅ |
| **LLM Limitations** | Hallucination control · Context limits | ✅ |
| **Session Memory** | Redis-based · Per-user isolation | ✅ Built |
| **Offline-first AI** | Local LLMs · No cloud dependency | 🚀 Rare skill |

</div>

---

## 🎯 What Makes Me Different

<div align="center">

| Trait | Details |
|-------|---------|
| 🏗️ **End-to-end builder** | Not just models — full systems from UI to DB to LLM |
| 🚀 **Offline-first AI** | Local LLMs, no cloud dependency — rare in the field |
| ⚡ **Real-time pipelines** | Socket.IO + async queuing for live AI events |
| 🧩 **System design first** | Think in bottlenecks, scale, and worker architecture |
| 🔍 **Hybrid retrieval** | Vector + BM25 — not just naive vector search |
| 🛠️ **Production mindset** | Debugged CORS, Prisma, Redis, API failures in real deployments |

</div>

---

## 📈 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Prathiksha-jain&show_icons=true&theme=midnight-purple&hide_border=true&bg_color=0D0D0D&title_color=A78BFA&icon_color=7C3AED&text_color=E2E8F0" height="160"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Prathiksha-jain&layout=compact&theme=midnight-purple&hide_border=true&bg_color=0D0D0D&title_color=A78BFA&text_color=E2E8F0" height="160"/>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com?user=Prathiksha-jain&theme=midnight-purple&hide_border=true&background=0D0D0D&ring=7C3AED&fire=A78BFA&currStreakLabel=E2E8F0" />

</div>

---

## 🔮 What's Next

<div align="center">

| 🔜 Upcoming | Details |
|------------|---------|
| 🧠 LLM Query Rewriting | Rewrite ambiguous queries before retrieval |
| 🖼️ Multimodal RAG | Vision + Text retrieval pipelines |
| 🤖 AI Agent Frameworks | Tool-use, planning, memory-augmented agents |
| 📊 Evaluation Pipelines | RAGAs · TruLens benchmarking |
| 🚀 Performance Dashboards | Latency · Throughput · Retrieval quality metrics |

</div>

---

## 🤝 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Prathiksha%20Jain-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/prathiksha-jain-7bb495226/)
[![GitHub](https://img.shields.io/badge/GitHub-YOUR__USERNAME-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Prathiksha-jain)
[![Gmail](https://img.shields.io/badge/Gmail-prathikshajain0007-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:prathikshajain0007@gmail.com)
[![YouTube](https://img.shields.io/badge/YouTube-Before%20I%20Fade-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@beforeifade)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302B63,100:0F0C29&height=120&section=footer" />

**"I don't just use AI. I build the systems that power it."** 🚀

</div>
