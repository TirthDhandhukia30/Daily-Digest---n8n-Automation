# 📩 AI Daily Digest

## WorkFLow

<img width="650" alt="AI Daily Digest Workflow" src="https://github.com/user-attachments/assets/ecdbc417-32f2-45b4-9a80-107f3d930048" />

AI Daily Digest is an automation workflow built with **n8n**, deployed on **Google Cloud**, that delivers daily news and summarized emails straight to your messaging apps.  

## 🚀 Features
- Fetches the **latest New York Times headlines** via RSS/HTTP request.  
- Summarizes **Gmail & Outlook emails** using **Google Gemini**.  
- Forwards concise digests to **Discord** and **Telegram**.  
- Reduces inbox clutter and keeps you updated with minimal effort.  

## 🛠️ Tech Stack
- **Google Cloud** – Deployment & hosting  
- **n8n** – Workflow automation  
- **Google Gemini API** – AI-based summarization  
- **Discord API** & **Telegram Bot API** – Message delivery  
- **Gmail & Outlook integrations** – Email fetching  

## ⚡ Workflow Overview
1. **Schedule Trigger** runs daily to fetch news from NYT.  
2. **HTTP Request** pulls RSS feed → **Gemini Agent** summarizes top 5 stories.  
3. **Gmail & Outlook Triggers** capture new mails → **Gemini Agent** summarizes key points.  
4. **Discord & Telegram Nodes** send all digests to your chosen channels.  


