<!-- Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:7F5AF0,50:2CB1BC,100:2CB67D&height=210&section=header&text=Phan%20Ho%C3%A0ng%20Quang%20Ngh%E1%BB%8B&fontSize=44&fontColor=ffffff&fontAlignY=36&desc=AI%20Engineer%20%C2%B7%20Agent%20Systems%20%C2%B7%20Computer%20Vision&descSize=18&descAlignY=58&animation=twinkling" width="100%" alt="header" />
</p>

<p align="center">
  <a href="https://github.com/qnghi13">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=7F5AF0&center=true&vCenter=true&width=620&lines=AI+Engineer+Intern+candidate;Building+Verified+Data+Agents;Building+RAG+%26+Agentic+Systems;Real-time+Computer+Vision;Data+Science+%40+VNUHCM+%E2%80%93+University+of+Science" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="mailto:phqnghi23@clc.fitus.edu.vn"><img src="https://img.shields.io/badge/Email-7F5AF0?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/qnghi13"><img src="https://img.shields.io/badge/GitHub-2CB1BC?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <img src="https://komarev.com/ghpvc/?username=qnghi13&style=for-the-badge&color=2CB67D&label=PROFILE+VIEWS" alt="Profile views" />
</p>

## 🧠 About Me

- 🎓 Final-year **Data Science** student at **VNUHCM – University of Science**
- 🛠️ Building **DA-Agent**, a sandboxed data-analyst agent with verified answers and a measured eval harness
- 🤖 Focus: **AI Engineering**, **Agent Systems** and **Computer Vision**
- 🌱 Currently learning: **production-grade agentic systems**

## 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,opencv,sklearn,fastapi,docker,mysql,git,github,linux,vscode&perline=11" alt="Tech stack icons" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" />
  <img src="https://img.shields.io/badge/ChromaDB-FF6446?style=for-the-badge" alt="ChromaDB" />
  <img src="https://img.shields.io/badge/Neo4j-4581C3?style=for-the-badge&logo=neo4j&logoColor=white" alt="Neo4j" />
  <img src="https://img.shields.io/badge/Ultralytics%20YOLO-111F68?style=for-the-badge&logo=ultralytics&logoColor=white" alt="Ultralytics YOLO" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit" />
</p>

## 🚀 Featured Projects

### 🤖 [DA-Agent](https://github.com/qnghi13/DA-Agent): Data Analyst Agent for Messy Files

> Upload CSV, Excel or SQLite files and ask questions in plain language. Every answer traces back to the SQL that produced it, and code checks it before you see it.

<p align="center">
  <img src="https://img.shields.io/badge/Holdout%20correct-60%25-2CB67D?style=for-the-badge" alt="Holdout correct 60%" />
  <img src="https://img.shields.io/badge/Abstained-9%25-7F5AF0?style=for-the-badge" alt="Abstained 9%" />
  <img src="https://img.shields.io/badge/Cost-%240.30%20%2F%20150%20questions-2CB1BC?style=for-the-badge" alt="Cost $0.30 per 150 questions" />
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qnghi13/DA-Agent/main/docs/images/architecture-dark.svg" />
  <img src="https://raw.githubusercontent.com/qnghi13/DA-Agent/main/docs/images/architecture-light.svg" width="100%" alt="DA-Agent architecture drawn as one bench: browser, API, Postgres, worker, LLM client, runner and a sealed sandbox" />
</picture>

- **LangGraph agent** that plans, writes SQL, and submits answers that code verifies: numbers must come from query results, otherwise it repairs twice, then abstains.
- **Sandboxed execution:** a read-only SQL guard, one dataset per container, no network and no secrets.
- **Messy files become a reviewable spec** (types, formats, rows to exclude) that the user approves before any query runs.
- **Operable and measured:** Postgres job queue with crash-safe checkpoints, token and money budgets, OpenTelemetry traces, and an evaluation harness with fixed dev and holdout splits. 33 architecture decision records.
- Holdout scores come from the DataMate benchmark of messy Vietnamese retail data, 150 unseen questions, using Groq `gpt-oss-20b`.

<p align="center">
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white" alt="LangGraph" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black" alt="DuckDB" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white" alt="OpenTelemetry" />
</p>

### ⚖️ [Legal RAG Bot](https://github.com/qnghi13/legal-rag-bot): Vietnamese Labor Law Assistant

> Answers only from retrieved legal text, and every citation is verified before the answer is returned.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/legal-rag-architecture-dark.svg" />
  <img src="assets/legal-rag-architecture-light.svg" width="100%" alt="Legal RAG Bot architecture drawn as one bench: ingest, BM25, Chroma, Neo4j graph, reranker, Groq LLM, citation verifier and Streamlit UI" />
</picture>

<p align="center">
  <img src="https://raw.githubusercontent.com/qnghi13/legal-rag-bot/main/image/QA.png" width="60%" alt="Legal RAG Bot chat interface" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square" alt="ChromaDB" />
  <img src="https://img.shields.io/badge/BM25-3B82F6?style=flat-square" alt="BM25" />
  <img src="https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white" alt="Neo4j" />
  <img src="https://img.shields.io/badge/Ragas-8B5CF6?style=flat-square" alt="Ragas" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit" />
</p>

### 🧍 [Fall Detection System](https://github.com/qnghi13/Fall-Detection-System): Real-time Monitoring & Alerts

> Team of 3. **My role:** model selection & training, detector logic, deployment environment.

<p align="center">
  <img src="https://img.shields.io/badge/mAP%4050-0.854-2CB67D?style=for-the-badge" alt="mAP@50 0.854" />
  <img src="https://img.shields.io/badge/Fall%20Recall-93%25-7F5AF0?style=for-the-badge" alt="Fall recall 93%" />
  <img src="https://img.shields.io/badge/Inference-4.6%20ms-2CB1BC?style=for-the-badge" alt="Inference 4.6 ms" />
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/fall-detection-architecture-dark.svg" />
  <img src="assets/fall-detection-architecture-light.svg" width="100%" alt="Fall Detection System architecture drawn as one bench: camera, YOLOv8n detector, fall timer, FastAPI backend, SQLite storage, Telegram notifier and React dashboard" />
</picture>

| Model | Params | Inference | mAP@50 | Fall Recall |
| :--- | ---: | ---: | ---: | ---: |
| 🏆 **YOLOv8n** | 3.0 M | 4.6 ms | **0.854** | **0.930** |
| YOLOv10n | 2.7 M | 3.4 ms | 0.803 | 0.803 |
| RT-DETR | 32.8 M | 17.9 ms | 0.805 | 0.915 |

<p align="center">
  <img src="https://img.shields.io/badge/Ultralytics-111F68?style=flat-square&logo=ultralytics&logoColor=white" alt="Ultralytics" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white" alt="Socket.IO" />
  <img src="https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram" />
</p>

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=qnghi13&theme=tokyonight" width="95%" alt="Profile details" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=qnghi13&theme=tokyonight" height="170" alt="Stats" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=qnghi13&theme=tokyonight" height="170" alt="Repos per language" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=qnghi13&theme=tokyonight&hide_border=true&border_radius=10" alt="GitHub streak" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qnghi13/qnghi13/output/github-snake-dark.svg" />
    <img src="https://raw.githubusercontent.com/qnghi13/qnghi13/output/github-snake.svg" alt="Snake eating contributions" width="100%" />
  </picture>
</p>

<!-- Footer -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2CB67D,50:2CB1BC,100:7F5AF0&height=120&section=footer" width="100%" alt="footer" />
</p>
