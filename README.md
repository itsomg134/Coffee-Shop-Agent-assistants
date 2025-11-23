# Coffee-Shop-Agent-assistants
This repository contains the Barista Voice Agent, a conversational assistant built using LangChain as part of the Murf AI Voice Agent Challenge. The agent simulates a friendly barista at a virtual café, guiding users through a structured drink-ordering process via voice interaction.

# ☕ Coffee Shop Agent — Barista Voice Assistant

<div align="center">

![Version](https://img.shields.io/badge/Version-1.0.0-blue)
![Python](https://img.shields.io/badge/Python-3.11-yellow?logo=python)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?logo=typescript)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript)
![Shell](https://img.shields.io/badge/Shell-Bash-121011?logo=gnu-bash)
![Dockerfile](https://img.shields.io/badge/Dockerfile-Ready-0db7ed?logo=docker)
![License](https://img.shields.io/badge/License-MIT-green)

**A friendly AI Barista that takes your drink order through real-time voice interaction.
Built for the #MurfAIALAgentsChallenge.**

[Features](#-features) • [Project-Structure](#️-project-structure) • [Quick-Start](#-quick-start) • [Demo-Video](#-demo-video) • [Author](#-author)

</div>

---

## 📋 Description

**Coffee Shop Agent** is a fully interactive **voice-based barista assistant** built using **LangChain**, **Python**, **TypeScript**, and **Docker**.
It guides users through a structured drink-ordering conversation — just like talking to a real barista.

This project is part of the **Murf AI Voice Agent Challenge**.

👉 *Currently supports English only.*

---

## 🚀 Features

* 🤖 **LangChain Agent** + Task-based workflow
* 🎙️ **Voice interface** via browser (mic input + TTS output)
* ☕ **Structured coffee order flow**:

  * Drink type
  * Size
  * Temperature
  * Milk type
  * Sweetener
  * Added flavors
* 🔊 **Murf Falcon TTS** for super fast and natural audio
* 🐳 **Fully Dockerized** (backend, frontend, worker services)
* 🌐 **Full stack setup**: Python backend + TypeScript/JS frontend
* 🧩 **Modular folder structure** for easy extension

---

## 🗂️ Project Structure

```
/src
  ├── agent/        # Barista agent logic
  ├── transcriber/  # Whisper STT module
  ├── tts/          # Murf Falcon TTS integration
  ├── browser/      # Frontend UI (TypeScript + JS)
  ├── farg/         # Agent orchestration layer
  ├── scripts/      # Shell scripts for automation
  ├── Dockerfile    # Docker build setup
```

---


## ⚡ Quick Start

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/neuro-ai-assist-barista.git
cd neuro-ai-assist-barista
```

### 2. Start with Docker Compose

```bash
docker-compose up --build
```

### 3. Open in browser

```
http://localhost:3000
```

### 4. Start speaking!

☕🎙️ *“Hi there! What kind of coffee would you like today?”*

---

## 🎥 Demo Video

▶ **Day 2 Barista Agent Demo:**
[https://drive.google.com/file/d/1LYFJ1MkRbBn5kc87Zs8EnOmmTPYra1Ek/view?usp=drive_link](https://drive.google.com/file/d/1LYFJ1MkRbBn5kc87Zs8EnOmmTPYra1Ek/view?usp=drive_link)

---

## 📹 Challenge Context

Created for **Day 2** of the **#MurfAIALAgentsChallenge** as part of the
**#10DaysofAIVoiceAgents** series.

Goal:
Build a guided, step-by-step voice barista capable of taking complete beverage orders.

---
<img width="1889" height="1079" alt="Screenshot 2025-11-22 172437" src="https://github.com/user-attachments/assets/34b7cd56-ee3f-4dbb-b545-6fe763183f39" />

## 🔖 Tags

`#MurfAIALAgentsChallenge`
`#10DaysofAIVoiceAgents`
`#LangChain`
`#Python`
`#TypeScript`
`#JavaScript`
`#AI`
`#VoiceTech`
`#Docker`
`#BaristaAgent`
`#NeuroAIAssist`

---

## 👨‍💻 Author

**Om Gedam**

* GitHub: [@itsomg134](https://github.com/itsomg134)
* Email: **[omgedam123098@gmail.com](mailto:omgedam123098@gmail.com)**
* Twitter: [@omgedam](https://x.com/its_om_g_143)
* LinkedIn: [Om Gedam](https://www.linkedin.com/in/om-gedam-39686432a)
* Portfolio: **ogworks.lovable.app**

**Made with ❤️ using Python, TypeScript, JavaScript, Shell, and Docker.**


<img width="1920" height="1080" alt="Screenshot (131)" src="https://github.com/user-attachments/assets/424cbc7e-b284-4bc2-8d62-89886f1ce88a" />
