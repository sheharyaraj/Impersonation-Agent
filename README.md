---
title: Impersonation Agent
emoji: 🤖
colorFrom: blue
colorTo: indigo
sdk: gradio
sdk_version: 5.49.1
app_file: main.py
pinned: false
short_description: AI chatbot that answers questions as Sheharyar Ajmal
---

# Impersonation Agent

A Gradio chatbot that role-plays as Muhammad Sheharyar Ajmal, answering visitor
questions about his career, background, skills, and experience. It is embedded
in his portfolio site.

## Stack

- Gradio `ChatInterface`
- OpenAI `gpt-4o-mini`
- Pushover notifications for lead capture

## Environment variables

Set these as **Space secrets** (Settings -> Variables and secrets), or in a
local `.env` file for development:

- `OPENAI_API_KEY`
- `PUSHOVER_TOKEN`
- `PUSHOVER_USER`

## Run locally

```bash
pip install -r requirements.txt
python main.py
```
