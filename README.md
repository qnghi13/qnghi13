<!-- Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:7F5AF0,50:2CB1BC,100:2CB67D&height=210&section=header&text=Phan%20Ho%C3%A0ng%20Quang%20Ngh%E1%BB%8B&fontSize=44&fontColor=ffffff&fontAlignY=36&desc=AI%20Engineer%20%C2%B7%20Agent%20Systems%20%C2%B7%20Computer%20Vision&descSize=18&descAlignY=58&animation=twinkling" width="100%" alt="header" />
</p>

<p align="center">
  <a href="https://github.com/qnghi13">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=7F5AF0&center=true&vCenter=true&width=620&lines=AI+Engineer+Intern+candidate;Building+RAG+%26+Agentic+Systems;Real-time+Computer+Vision;Data+Science+%40+VNUHCM+%E2%80%93+University+of+Science" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="mailto:phqnghi23@clc.fitus.edu.vn"><img src="https://img.shields.io/badge/Email-7F5AF0?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/qnghi13"><img src="https://img.shields.io/badge/GitHub-2CB1BC?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <img src="https://komarev.com/ghpvc/?username=qnghi13&style=for-the-badge&color=2CB67D&label=PROFILE+VIEWS" alt="Profile views" />
</p>

## 🧠 About Me

- 🎓 Final-year **Data Science** student at **VNUHCM – University of Science**
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

### ⚖️ [Legal RAG Bot](https://github.com/qnghi13/legal-rag-bot): Vietnamese Labor Law Assistant

> Answers only from retrieved legal text, and every citation is verified before the answer is returned.

```mermaid
flowchart LR
    Q([💬 Question]):::input --> R[Query<br/>Rewriter]:::llm
    R --> S[Chroma<br/>Semantic]:::ret
    R --> B[BM25<br/>Keyword]:::ret
    S --> F{Hybrid<br/>Fusion}:::ret
    B --> F
    F --> X[Cross-Encoder<br/>Reranker]:::rank
    X --> G[(Neo4j<br/>Legal Graph)]:::gdb
    G --> L[Groq<br/>LLM]:::llm
    L --> V{Citation<br/>Verifier}:::guard
    V --> A([✅ Answer]):::out

    classDef input fill:#7F5AF0,stroke:#7F5AF0,color:#fff
    classDef llm fill:#2CB1BC,stroke:#2CB1BC,color:#fff
    classDef ret fill:#3B82F6,stroke:#3B82F6,color:#fff
    classDef rank fill:#F59E0B,stroke:#F59E0B,color:#fff
    classDef gdb fill:#4581C3,stroke:#4581C3,color:#fff
    classDef guard fill:#EF4444,stroke:#EF4444,color:#fff
    classDef out fill:#2CB67D,stroke:#2CB67D,color:#fff
```

<p align="center">
  <img src="https://raw.githubusercontent.com/qnghi13/legal-rag-bot/main/image/QA.png" width="70%" alt="Legal RAG Bot chat interface" />
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

```mermaid
flowchart LR
    C([📷 Camera]):::input --> Y[YOLOv8n<br/>Detector]:::model
    Y --> SM{Time-based<br/>State Machine}:::logic
    SM -->|fall confirmed| T([📲 Telegram Alert]):::alert
    SM --> W([🖥️ Live Dashboard]):::out

    classDef input fill:#7F5AF0,stroke:#7F5AF0,color:#fff
    classDef model fill:#111F68,stroke:#111F68,color:#fff
    classDef logic fill:#F59E0B,stroke:#F59E0B,color:#fff
    classDef alert fill:#EF4444,stroke:#EF4444,color:#fff
    classDef out fill:#2CB67D,stroke:#2CB67D,color:#fff
```

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
