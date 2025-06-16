# HealNext – AI-Powered Healthcare Assistant

🚀 Built for **GenAI Hackathon by Jazzee Edtech**

📄 **[Project Document (PDF)](./BycrptX_AniketSubudhi_Jazzee2025.pdf)**  
🎥 **[Video Pitch (2-min YouTube)](https://youtu.be/SQrBRzwpMa8)**

---

## 📌 Overview

**HealNext** is not just a project—it's a mission to revolutionize Indian healthcare using Generative AI. From rural clinics to urban hospitals, we aim to reduce inefficiencies, automate administrative overload, and empower both patients and healthcare providers with AI-driven tools.

---

## 🧠 Problem Statement

India’s healthcare system is burdened by manual paperwork, delayed diagnosis, disconnected records, and inaccessibility in rural areas. Doctors spend more time writing than treating, and patients often don’t understand when a condition is urgent or whom to consult.

---

## 💡 Solution Summary

HealNext uses Generative AI to:

- Scan reports, prescriptions, and X-rays for critical insights
- Convert voice to structured medical records
- Alert patients about urgent health flags in real-time
- Match patients with nearby specialists and hospitals
- Provide regional language voice-entry support for rural workers
- Enable direct doctor calls and emergency response

---

## 🛠️ Tech Stack

- **Frontend (Web):** React + Tailwind (Admin & Doctor Dashboard)
- **Mobile App:** React Native (Patient & Hospital Interface)
- **Backend:** Node.js + Express
- **Database:** MongoDB
- **AI Layer:** Fine-tuned LLMs, OCR (Tesseract), ChatGPT API, X-ray vision model

---

## 📊 Architecture

```text
Patient App ←→ Node.js API ←→ MongoDB
        ↑            ↓
  OCR / LLMs / GPT APIs ←→ Admin Web Panel
        ↑
 X-ray / Lab Report / Voice-to-Text AI
