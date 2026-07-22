# Jarvis v1

Jarvis v1 is an AI-powered personal assistant built entirely in n8n.

It integrates multiple AI and productivity services into a single Telegram interface.

---

## Features

- 🤖 AI Chatbot
- 📄 PDF Resume & Document Analyzer
- 🔍 Research Assistant (Tavily)
- 📧 Gmail Assistant
- 📅 Google Calendar Viewer
- ➕ Google Calendar Event Scheduler
- 📝 Text Summarizer
- 🧠 AI Intent Router

---

## Tech Stack

- n8n
- OpenAI API
- Telegram Bot API
- Gmail API
- Google Calendar API
- Tavily Search API

---

## Architecture

![Architecture](architecture/jarvis-architecture.png)

---

## Workflow

User
↓

Telegram Bot
↓

AI Intent Router

↓

Switch Node

├── Chatbot
├── PDF Assistant
├── Research Assistant
├── Email Assistant
├── Calendar Viewer
└── Event Scheduler

↓

Telegram Response

---

