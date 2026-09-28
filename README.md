<div align="center">

<br />

# 🤖 PrimeChat (AIRA V1)
### *Personal AI Conversational Agent & Autonomous Assistant Archetype*

<p align="center">
  <strong>The original python-based foundation and journey from V1 onwards that evolved into AIRA OS.</strong>
</p>

[![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com)
[![Render](https://img.shields.io/badge/Render-Hosted-46E3B7?style=for-the-badge&logo=render&logoColor=white)](https://render.com)
[![SQLite](https://img.shields.io/badge/SQLite-Database-003B57?style=for-the-badge&logo=sqlite&logoColor=white)](https://sqlite.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

<br/>

</div>

---

## 🌟 Overview

**PrimeChat** is the foundational AI assistant prototype engineered from scratch by **Shaik Shadik**. It was designed to test real-time AI reasoning, conversation memory persistence, and dynamic tool orchestration before migrating to the full mobile-native [AIRA OS](https://github.com/Shaikshadik03/AIRA-OS).

Built with an ultra-responsive Python backend and modern glassmorphic web frontend, PrimeChat served as the pilot architecture for autonomous personal assistants.

---

## ✨ Key Features

- ⚡ **Real-Time Streaming Responses**: Instant token generation for seamless natural conversation.
- 💾 **Session & Context Persistence**: Stateful conversation memory powered by SQLite database storage.
- ☁️ **Cloud Native**: Pre-configured with `render.yaml` for instant zero-downtime deployment on Render.
- 🎨 **Minimalist Frontend Client**: Clean, dark-mode user interface connecting over REST & WebSockets.
- 🛡️ **Modular Backend Pipeline**: Decoupled `cloud_main.py` routing with centralized `database.py` operations.

---

## 🏗️ Architecture Flow

```
┌──────────────────────────────────────────────────┐
│             Web Client Frontend UI               │
│         (HTML5 / Modern JavaScript / CSS)        │
└───────────────────────┬──────────────────────────┘
                        │ HTTP / JSON API
┌───────────────────────▼──────────────────────────┐
│          PrimeChat Backend (cloud_main.py)       │
│   • Request Validation & Session Handler         │
│   • LLM Prompt Engineering & Context Assembly    │
│   • Asynchronous Response Streamer               │
└───────────────┬──────────────────────────┬───────┘
                │                          │
┌───────────────▼───────────┐   ┌──────────▼───────────┐
│     SQLite Database       │   │    LLM Inference     │
│   • User Sessions         │   │    • Cloud LLM       │
│   • Message History       │   │    • Dynamic Prompts │
└───────────────────────────┘   └──────────────────────┘
```

---

## 🛠️ Tech Stack

| Component | Technology |
|---|---|
| **Language** | Python 3.11+ |
| **Backend Framework** | FastAPI / Python Standard Async |
| **Database** | SQLite3 (`database.py`) |
| **Deployment** | Render Cloud (`render.yaml`) |
| **Frontend** | Vanilla JS / CSS3 Dark Mode Interface |

---

## 🚀 Quickstart Guide

### 1. Clone the repository
```bash
git clone https://github.com/Shaikshadik03/CHAT-BOT.git
cd CHAT-BOT
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run locally
```bash
python cloud_main.py
```
Open `front_end_app/index.html` or navigate to `http://localhost:8000` in your browser!

---

## 📈 Evolution Timeline

* 🐣 **PrimeChat (V1)**: The core Python + SQLite prototype in this repository.
* 🚀 **AIRA OS (V2 - V4)**: Re-architected into a full mobile operating system with **Flutter**, **Groq (Llama 3.3)**, **Supabase pgvector**, and **Google Workspace Integrations**.

---

## 📬 Connect & Author

**Built with ❤️ by [Shaik Shadik](https://github.com/Shaikshadik03)**  
*Founder, BuildWithShadik • 1st Year B.Tech CSE at Malla Reddy University*

[![Portfolio](https://img.shields.io/badge/Portfolio-shadik.lovable.app-black?style=for-the-badge&logo=vercel)](https://shadik.lovable.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-shxdik03-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/shxdik03)
[![GitHub](https://img.shields.io/badge/GitHub-Shaikshadik03-181717?style=for-the-badge&logo=github)](https://github.com/Shaikshadik03)
