<h1 align="center">Hi, I'm Rohit Mehra 👋</h1>

<h3 align="center">Backend & AI Engineer · Building production-grade LLM systems</h3>

<p align="center">
  <a href="https://linkedin.com/in/rohitmdev">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:rohitmehra29june@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/rohitmdev29">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

---

## 👨‍💻 About Me

I'm a **Backend & AI Engineer** with hands-on experience in **fine-tuning LLMs**, building **async Python backends**, and deploying **quantized models** to production. My work focuses on the intersection of AI research and real-world engineering — taking models from notebooks to systems that hold up under load.

- 🔭 Currently building **QLoRA fine-tuned LLMs** for domain-specific tasks
- 🧠 Deep interest in **parameter-efficient fine-tuning**, **quantization**, and **LLM observability**
- ⚡ Love optimizing databases — a **6× query speedup** is more satisfying than a new framework
- 🎯 Open to **Backend / AI Engineer** roles (Remote / Hybrid / On-site)


---

## 🚀 Featured Projects

### 1. [Text-to-SQL Generator](https://github.com/rohitmdev29/text-to-sql-generator)
> Fine-tuned Gemma-2B with QLoRA to convert natural language into SQL queries

- **0% → 80%** exact match accuracy on held-out test set
- Trained only **0.79%** of parameters (20.77M / 2.63B) on a single T4 GPU
- Quantized to **8-bit GGUF** (2.59 GB) and deployed locally via **Ollama**
- Cloud-ready fallback using **Groq API** for Streamlit Cloud
- Built a **Streamlit UI** with preset queries + CSV export
- Tested on a real SQLite e-commerce database (200 customers, 1000 orders)

`Python` `PyTorch` `Hugging Face` `Unsloth` `QLoRA` `TRL` `Ollama` `Streamlit` `Groq` `SQLite`

**🔗 [Live Demo](https://text-to-sql-generator-fkcx8d53y3ubljuoappxr3h.streamlit.app) · [GitHub Repo](https://github.com/rohitmdev29/text-to-sql-generator)**

---

### 2. Resume–JD Matcher — MCP + LangGraph
> AI-powered candidate screening built on a hybrid LangGraph + deterministic pipeline

- Reduced per-candidate screening cost by **90%** (90 → 9 LLM calls per batch)
- **MCP Architecture** — separated AI capabilities (server) from orchestration (host)
- **Zero crashes** — empty PDFs skipped gracefully, hallucination guards + RFC 3986 URIs
- Custom **LocalConnector** bypasses MCP stdio limitation (zero cold-start)

`Python` `LangGraph` `LangChain` `MCP` `Gemini API` `Streamlit`

**🔗 [Live Demo](https://resume-jd-matcher-e54mueakqtrlhwh62lavmn.streamlit.app/)**

---

### 3. [Real-Time Chat Backend](https://github.com/rohitmdev/chat-backend)
> Production-grade WebSocket chat backend with JWT auth, Redis pub/sub, and Docker

- **Deterministic room_id** (`dm:min:max`) — eliminated `rooms` table, queries 3 → 1 (~67% fewer)
- **Composite index** — ~6× faster than Seq Scan (0.25 ms vs 1.47 ms)
- **JWT verified before `accept()`** — clean 1008 close instead of 1006 abnormal closure
- **25 tests** (pytest + pytest-asyncio) — 100% critical-path coverage
- **Docker Compose** with Postgres 15 + Redis 7 (healthchecks + volumes)

`FastAPI` `SQLAlchemy 2.0 (Async)` `PostgreSQL` `Redis` `WebSockets` `JWT` `Docker` `Alembic` `pytest`

**🔗 [GitHub Repo](https://github.com/rohitmdev/chat-backend)**

---

## 🛠️ Tech Stack

<table>
<tr>
<td valign="top" width="50%">

### 🤖 AI / LLM Engineering
![QLoRA](https://img.shields.io/badge/QLoRA-Fine--Tuning-2563EB?style=flat-square)
![LoRA](https://img.shields.io/badge/LoRA-PEFT-2563EB?style=flat-square)
![Unsloth](https://img.shields.io/badge/Unsloth-2563EB?style=flat-square)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square)

</td>
<td valign="top" width="50%">

### ⚙️ Backend Engineering
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy_2.0-D71F00?style=flat-square)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens)

</td>
</tr>
<tr>
<td valign="top" width="50%">

### 🗄️ Data Layer
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

</td>
<td valign="top" width="50%">

### 🚀 DevOps & Tooling
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

</td>
</tr>
</table>

---

## 🎯 Currently Exploring

- 📚 **Advanced RAG Pipelines** — hybrid search, re-ranking, vector databases
- 🔍 **LLM Observability** — LangSmith tracing, evaluation, production monitoring
- ⚡ **Distributed Systems** — Kafka, event-driven architecture, read replicas

---

## 💬 Let's Connect

<p align="center">
  <a href="https://linkedin.com/in/rohitmdev">
    <img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:rohitmehra29june@gmail.com">
    <img src="https://img.shields.io/badge/Send_an_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

<p align="center">
  <i>"Good backends are invisible. Bad backends are unforgettable."</i>
</p>
