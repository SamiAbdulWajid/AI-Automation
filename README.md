[README (3).md](https://github.com/user-attachments/files/27239366/README.3.md)
# 🤖 AI Email Automation & Follow-Up System

## 📌 Overview
An intelligent email automation system that uses AI agents to classify incoming emails, generate context-aware replies, and schedule follow-ups automatically.

---

## 🚀 Problem
Handling emails manually is time-consuming and inconsistent, especially when managing multiple conversations.

---

## 💡 Solution
Built a multi-agent AI system that:
- Classifies emails based on intent and urgency  
- Decides whether to reply, follow-up, or ignore  
- Generates contextual replies using LLM  
- Automates follow-up using Calendar and Tasks  

---

## 🎯 Impact
- Reduces manual effort  
- Improves response consistency  
- Automates communication workflow  

---

## 🧠 Architecture
Gmail Trigger → AI Agent 1 (Classification) → AI Agent 2 (Decision) → Switch →  
AI Agent 3 → (Reply / Follow-up) → Gmail + Calendar + Tasks

---

## ✨ Features
- AI email classification  
- Tone-based reply generation  
- Automatic follow-up scheduling  
- Multi-agent decision system  

---

## 🛠 Tech Stack
- n8n (Workflow Automation)  
- Groq API (LLaMA 3.1)  
- Gmail API  
- Google Calendar API  
- Google Tasks API  

---

## 📂 Workflow
Check the workflow file inside the `workflow/` folder.

---

## 👨‍💻 Author
Sami Abdul Wajid
