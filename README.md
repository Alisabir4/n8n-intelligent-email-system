# 🤖 n8n AI Agent Workflow

This project is an AI-powered automation agent built using **n8n** and **LangChain nodes**.

## 🚀 Features

- Chat-based AI agent using Google Gemini (gemini-2.5-flash)
- Email sending automation via Gmail
- Customer database lookup using Google Sheets
- Memory support for conversation context
- Tool-based AI decision making (sendEmail + database lookup)

## 🧠 How it works

1. User sends a message via chat trigger
2. AI Agent processes the request
3. If email is needed:
   - It first searches customer database (Google Sheets)
   - Then sends email using Gmail tool
4. AI remembers conversation using buffer memory

## 🛠️ Tools Used

- n8n workflow automation
- Google Gemini API
- Gmail API
- Google Sheets API
- LangChain AI Agent

## 📂 File Included

- `AI agent.json` → n8n workflow export file

## ⚙️ Use Case

- AI email assistant
- Business automation
- Customer communication automation

## 👤 Author

Built by Ali
