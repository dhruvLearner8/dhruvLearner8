<h1 align="center">Hey, I'm Dhruv Patel</h1>
<p align="center">
  <b>AI Engineer</b> &nbsp;|&nbsp; MS in Computer Science &nbsp;|&nbsp; Building intelligent systems that solve real problems
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/dhruv-patel-083740209/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:dhruvmpatel096@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/dhruvLearner8">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

### About Me

- Recently completed my **Master's in Computer Science**
- Research paper accepted and upcoming publication
- Focused on **Agentic AI, RAG, LLM tool orchestration, and MCP**
- Background in **Data Science** and **Full-Stack Software Engineering**
- I build end-to-end AI products — not just notebooks, but deployed systems with real UIs

---

### Experience

- **Data Scientist** @ Tundra Technologies
- **Software Engineer** @ RapidOps
- **Junior Software Developer** @ BAISCO

---

### Tech Stack

**AI & ML**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Gemini_2.0-8E75B2?style=flat-square&logo=google&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![MCP](https://img.shields.io/badge/MCP_Protocol-FF6F00?style=flat-square&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)

**Backend & APIs**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-FF6C37?style=flat-square&logo=postman&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

**Tools & Infra**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Chrome Extensions](https://img.shields.io/badge/Chrome_Extensions-4285F4?style=flat-square&logo=googlechrome&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)

---

### Featured AI Projects

<table>
<tr>
<td width="50%" valign="top">

#### [Arc Reactor — Multi-Tool AI Agent with MCP & Telegram](https://github.com/dhruvLearner8/Arc-Reactor-Agent-for-Browser)
A reasoning-driven AI agent that receives queries via Telegram, autonomously orchestrates multiple MCP tool servers (web search, RAG, math, code execution), and returns answers — all through an LLM-powered Perception → Memory → Decision → Action loop.

`MCP` `Gemini 2.0 Flash` `FAISS` `Ollama` `Telegram Bot` `stdio + SSE Transport`

**What it does:**
- Telegram bot as the agent's input interface — send a message, get an AI-powered answer
- 30+ MCP tools across 3 servers (math/code, document RAG, web search via DuckDuckGo)
- In-RAM semantic memory using FAISS + Ollama embeddings for multi-step reasoning
- Supports both stdio and SSE (Server-Sent Events) MCP transport protocols
- Configurable agent strategy, persona, and tool routing via YAML

</td>
<td width="50%" valign="top">

#### [RAG-Based Chrome Plugin](https://github.com/dhruvLearner8/RAG-Based-Chrome-Plugin)
A Chrome extension that indexes any webpage you visit into a local FAISS vector database and lets you semantically search across all indexed pages. Click a result to open the page with matching text highlighted.

`FAISS` `Ollama` `nomic-embed-text` `FastAPI` `Chrome Manifest V3`

**What it does:**
- One-click page indexing with text chunking (512 words, 40-word overlap)
- Local embeddings via Ollama — no data leaves your machine
- Semantic search with top-k retrieval
- Auto-navigate and highlight matching paragraphs on the source page

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [LunarAgent — DQN for Procedural Crater-Field Navigation](https://github.com/dhruvLearner8/LunarAgent-using-DQN)
A Deep Q-Network agent that learns to navigate a lunar rover across procedurally generated crater fields from raw terrain patches, with a full debugging log of the reward-shaping, loss, and architecture bugs found and fixed along the way.

`PyTorch` `Deep Q-Learning` `Dueling DQN` `GroupNorm` `Huber Loss` `Apple MPS`

**What it does:**
- 4-layer conv + dueling value/advantage head (110K params, 21.6x smaller than baseline) reading local terrain patches
- Potential-based reward shaping so distance-to-goal never makes early death the optimal policy
- Randomized crater placement per episode to force generalization over route memorization
- BFS-verified map solvability; MPS-accelerated training (~2.3x over CPU) with a 100K-transition replay buffer

</td>
<td width="50%" valign="top">

#### [ATS Resume Analyzer Chrome Extension](https://github.com/dhruvLearner8/Resume-Analyzer-Chrome-Extension)
A Chrome Extension that scans job postings from any site and analyzes your resume against the job description using Gemini. Returns an ATS score, strengths, weaknesses, missing keywords, and improvement suggestions.

`Gemini REST API` `Chrome MV3` `Vanilla JS` `No dependencies`

**What it does:**
- Upload PDF/TXT resume, scan any job posting page
- Gemini analyzes resume vs. job description
- Returns ATS score (0-100), strengths, gaps, and keyword suggestions
- Zero build step — pure browser APIs + fetch

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [Viewport Calculator](https://github.com/dhruvLearner8/Viewport-Calculator-Home-Team-AI)
A video processing pipeline using Python multiprocessing with motion detection, viewport tracking, and smoothing. Containerized with Docker and deployable to AWS EC2.

`Python` `Multiprocessing` `Docker` `AWS EC2` `OpenCV`

**What it does:**
- 4-process pipeline with shared queues (reader, detector, viewport, writer)
- Motion-based state machine (STEADY / TRACKING)
- Smoothing buffer for stable viewport output
- Docker Compose for local/cloud deployment

</td>
<td width="50%" valign="top">

#### [Personal AI Agent for Gmail & Calendar](https://github.com/dhruvLearner8/Personal-AI-Agent-for-GMail-and-Calendar-Assistant)
A full-stack agentic AI assistant that manages Gmail and Google Calendar through natural language. The LLM autonomously decides which tools to call, chains them across multiple iterations, and returns structured results.

`Gemini 2.0 Flash` `MCP` `FastAPI` `React` `Gmail API` `Calendar API` `OAuth 2.0`

**What it does:**
- Read, search, and send emails via chat
- Summarize email threads and extract document attachments (PDF/DOCX)
- View schedule, check free slots, create events with attendees
- 10 MCP tools orchestrated by an agentic loop (up to 5 iterations)

</td>
</tr>
</table>

---

### GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=dhruvLearner8&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dhruvLearner8&layout=compact&theme=tokyonight&hide_border=true" height="165" />
</p>

---

<p align="center">
  <i>I build AI systems that actually work — not just demos, but full-stack products with real APIs, real auth, and real users in mind.</i>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/dhruv-patel-083740209/">Let's connect</a>
</p>
