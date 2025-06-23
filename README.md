# DeployLite – GenAI-Powered DevOps Automation Platform

🚀 Built for **GenAI Hackathon by Jazzee Edtech**

📄 **[BycrptX_AniketSubudhi_Jazzee2025_Document](./BycrptX_AniketSubudhi_Jazzee2025_Document.pdf)**  
🎥 **[BycrptX_AniketSubudhi_Jazzee2025_PitchVideo](https://youtu.be/SQrBRzwpMa8)**

---

## 📌 Overview

**DeployLite** is an AI-powered cloud platform that automates the complete DevOps lifecycle. From code to production, it simplifies deployment, infrastructure management, and scaling for full-stack and ML apps. At its core is **CodeOps AI**, a GenAI agent that acts as a junior DevOps engineer—writing Dockerfiles, fixing errors, scaling infra, and deploying with just voice or prompt.

---

## 🧠 Problem Statement

Developers waste hours on CI/CD setup, Docker configuration, debugging, and scaling. Platforms like Vercel and Heroku lack true AI-driven infrastructure automation. There's no easy way to go from code to cloud for complex stacks—until now.

---

## 💡 Solution Summary

DeployLite automates:

- 1-click deployment for full-stack & ML apps  
- Stack detection & Dockerfile generation  
- GitHub-integrated CI/CD  
- AI-based error fixes and auto-commit  
- Natural language and voice-based deployment  
- Infra scaling via AI traffic analysis  
- Self-hosted AI-managed databases (e.g., MongoDB)  
- AI code verification before pushing to production

---

## 🛠️ Tech Stack

- **Frontend (Web):** Next.js + Tailwind (Dashboard)
- **Backend:** Node.js + Express
- **Database:** MongoDB
- **AI Layer:** GenAI (GPT APIs), Model Context Protocol (MCP), Custom Stack Detector, Auto Debugger
- **DevOps:** Docker, Webhooks, Self-healing Infra, GitHub Actions

---

## 📊 Architecture

```text
User (Chat / Voice / UI) → CodeOps AI
     → MCP Context Engine → AI Stack Analyzer
     → DockerGen / CI/CD Generator → Auto Debugger
     → Infra Manager (Scaling, DB, Traffic)
     → Continuous Deployment Pipeline
