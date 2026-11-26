<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b27,50:414868,100:7aa2f7&height=190&section=header&text=Muhammad%20Abdullah&fontSize=46&fontColor=c0caf5&fontAlignY=34&desc=AI%20Engineer%20%C2%B7%20RAG%20%C2%B7%20LLMs%20%C2%B7%20Agents&descSize=18&descAlignY=54" width="100%" alt="Muhammad Abdullah — AI Engineer · RAG · LLMs · Agents" />

<h3 align="center">LLM systems that are grounded, measured and shipped</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/muhammad-abdullah-53b843248/" target="_blank">
    <img src="https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=Linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:muhammad.abdullahds1@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/-Email-D14836?style=for-the-badge&logo=Gmail&logoColor=white" alt="Email">
  </a>
  <a href="https://twitter.com/abdulah_xx" target="_blank">
    <img src="https://img.shields.io/badge/-Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter">
  </a>
  <a href="https://kaggle.com/abddullah" target="_blank">
    <img src="https://img.shields.io/badge/-Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle">
  </a>
  <img src="https://komarev.com/ghpvc/?username=abdulah-x&style=for-the-badge&color=2C3E50" alt="Profile Views">
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=7AA2F7&center=true&vCenter=true&width=640&lines=Shipped+a+RAG+relevancy+evaluator+to+production;Built+a+ReAct+agent+on+LangGraph+from+scratch;Every+agent+call+graded+against+baselines" alt="Typing SVG" />
</p>

---

### Introduction

I'm an AI Engineer focused on **RAG, LLM applications and AI agents**. I care about the parts that decide whether an LLM system works in practice: what gets retrieved, which decisions stay in code instead of the model, hard limits on agent loops, and measuring results against simple baselines instead of trusting a demo.

I've shipped a RAG-based relevancy evaluator to production, built a hand-written ReAct agent that runs 24/7 and grades its own calls in a live forward test, and run LLM automations in live business operations.

Open to **AI Engineer / LLM Engineer roles**, remote or Pakistan-based, full-time or contract.

## 🧠 What I Work On

- **RAG:** chunking and embeddings, vector search (ChromaDB, Pinecone), two-stage retrieve-then-score pipelines, relevancy evaluation
- **AI agents:** LangGraph state graphs, tool-calling loops, human-in-the-loop pauses, guardrails, tool/time/round caps
- **LLM engineering:** structured outputs with Pydantic, prompt-injection defences, rate-limit fallbacks, streaming (SSE), tracing with Langfuse
- **Evaluation:** golden-set trajectory tests, forward testing, calibration reports against naive baselines

## ⚡ Currently

- 📈 **Running** FinSight's live forward test: 1,400+ graded calls so far, full results in January
- 🔬 **Going deeper** into agent evaluation and retrieval quality
- 💼 **Open to** AI Engineer roles

---

## 🏗️ Featured Work

### 📊 [FinSight](https://github.com/abdulah-x/FinSight) — ReAct Market-Bias Agent
Hand-written ReAct agent on LangGraph (no prebuilt agents) that gives a Bullish / Bearish / Neutral bias for BTC, ETH and gold. Guardrail model, parallel evidence tool, `interrupt()` for missing input and hard caps on every loop. The LLM never decides the score: it is computed in code, and every call is graded in a live forward test against simple baselines. Runs 24/7 at $0 on Groq and Oracle Cloud.
`LangGraph` · `Groq` · `FastAPI` · `PostgreSQL` · `Docker` · `Langfuse`

### 🤖 RAG-Based Relevancy Evaluator *(Paramount Intelligence)*
LLM pipeline evaluating content relevance with retrieval-augmented generation. Shipped to production.
`Python` · `LLMs` · `Vector Search` · `RAG`

### 🎯 [JobRadar](https://github.com/abdulah-x/JobRadar) — RAG Job Matching
Two-stage pipeline: embeddings + ChromaDB filter jobs against resume chunks at no LLM cost, then Gemini scores the survivors with the top-3 retrieved chunks and returns structured output (score, matching / missing skills, seniority). Groq fallback on rate limits.
`RAG` · `ChromaDB` · `Gemini` · `Pydantic` · `Docker`

### ⚙️ [AI Automation Workflows](https://github.com/abdulah-x/n8n) — n8n
Voice AI receptionist backend (Vapi, 9 workflows), a daily AI news digest with Pinecone dedup, and a WhatsApp chatbot running in production at Paramount Intelligence.
`n8n` · `Gemini` · `Pinecone` · `Webhooks`

### 🦅 Hawk-Ear — Audio-Video Surveillance Platform
Dockerized platform with **8 microservices** running real-time audio + video AI analysis. Final Year Project, ~90% solo contribution.
`Python` · `FastAPI` · `Docker` · `Microservices`

---

## 🛠️ Stack

<p align="center">
  <img src="https://img.shields.io/badge/-LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangGraph">
  <img src="https://img.shields.io/badge/-LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain">
  <img src="https://img.shields.io/badge/-Groq-F55036?style=for-the-badge" alt="Groq">
  <img src="https://img.shields.io/badge/-Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Gemini">
  <img src="https://img.shields.io/badge/-Langfuse-0A0A0A?style=for-the-badge" alt="Langfuse">
  <img src="https://img.shields.io/badge/-Tavily-4F46E5?style=for-the-badge" alt="Tavily">
  <img src="https://img.shields.io/badge/-Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white" alt="Pydantic">
  <img src="https://img.shields.io/badge/-ChromaDB-FF6446?style=for-the-badge" alt="ChromaDB">
  <img src="https://img.shields.io/badge/-Pinecone-000000?style=for-the-badge" alt="Pinecone">
  <img src="https://img.shields.io/badge/-Embeddings-414868?style=for-the-badge" alt="Embeddings">
  <img src="https://img.shields.io/badge/-PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/-TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow">
  <img src="https://img.shields.io/badge/-Keras-D00000?style=for-the-badge&logo=keras&logoColor=white" alt="Keras">
  <img src="https://img.shields.io/badge/-Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face">
  <img src="https://img.shields.io/badge/-Whisper-412991?style=for-the-badge" alt="Whisper">
  <img src="https://img.shields.io/badge/-pyannote-5A4FCF?style=for-the-badge" alt="pyannote">
  <img src="https://img.shields.io/badge/-NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/-Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/-FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/-SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white" alt="SQLAlchemy">
  <img src="https://img.shields.io/badge/-WebSockets-010101?style=for-the-badge&logo=socketdotio&logoColor=white" alt="WebSockets">
  <img src="https://img.shields.io/badge/-PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/-TimescaleDB-FDB515?style=for-the-badge" alt="TimescaleDB">
  <img src="https://img.shields.io/badge/-Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis">
  <img src="https://img.shields.io/badge/-MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB">
  <img src="https://img.shields.io/badge/-SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite">
  <img src="https://img.shields.io/badge/-SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/-TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/-React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/-Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js">
  <img src="https://img.shields.io/badge/-Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/-n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n">
  <img src="https://img.shields.io/badge/-Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/-nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" alt="nginx">
  <img src="https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/-Oracle%20Cloud-F80000?style=for-the-badge&logo=oracle&logoColor=white" alt="Oracle Cloud">
  <img src="https://img.shields.io/badge/-AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS">
  <img src="https://img.shields.io/badge/-Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/-Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" alt="Bash">
  <img src="https://img.shields.io/badge/-pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="pytest">
  <img src="https://img.shields.io/badge/-Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
</p>

---

### GitHub

<p align="center">
  <img height="180" src="https://raw.githubusercontent.com/abdulah-x/abdulah-x/profile-summary-card-output/tokyonight/3-stats.svg" alt="Stats" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=abdulah-x&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=abdulah-x&theme=tokyo-night&hide_border=true&area=true" alt="Contribution Activity" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/abdulah-x/abdulah-x/output/github-contribution-grid-snake-dark.svg" alt="Snake animation" />
</p>

---

## 🤝 Let's Build Something

Hiring, collaborating, or just curious about the work? I respond fast.

<p align="center">
  <a href="https://www.linkedin.com/in/muhammad-abdullah-53b843248/" target="_blank">
    <img src="https://img.shields.io/badge/-Message_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:muhammad.abdullahds1@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/-Send_Email-D14836?style=for-the-badge&logo=Gmail&logoColor=white" alt="Email">
  </a>
</p>

<p align="center"><i>Models get the spotlight. Pipelines do the work.</i></p>
