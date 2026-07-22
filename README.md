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

## Installation

1. Install n8n
2. Import `workflows/jarvis_public.json`
3. Create your credentials
   - OpenAI
   - Telegram
   - Gmail
   - Google Calendar
   - Tavily
4. Replace placeholder values
5. Activate the workflow

---

## Notes

Credentials are not included.

API keys have been removed for security.

---

## Future Plans

Jarvis v2

- PostgreSQL Memory
- Long-term Memory
- FastAPI Backend
- Docker Deployment
- Multi-user Support
