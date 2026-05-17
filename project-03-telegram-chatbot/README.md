# Project 03 — Aquino Assistant Chatbot

## Overview
A Telegram chatbot that responds to user commands automatically. 
Users can type commands and receive instant responses with real data.

## Available Commands
- **hello** / **hi** — Welcome message with available commands
- **weather** — Current weather forecast for Berlin
- **time** — Current time in Berlin
- **help** — List of all available commands

## Nodes Used
- **Telegram Trigger (On message)** — listens for incoming messages
- **Switch** — routes the message to the correct response based on command
- **HTTP Request** — fetches live weather data from wttr.in API
- **Code (JavaScript)** — processes and extracts weather data
- **Telegram (Send message)** — sends the response back to the user

## How It Works
1. User sends a message to @assistant_2u_Bot on Telegram
2. Telegram Trigger captures the message
3. Switch node checks what command was typed
4. Workflow routes to the correct response
5. Bot replies instantly with the right information

## Tools & Platforms
- n8n Cloud (app.n8n.cloud)
- Telegram Bot API (@BotFather)
- wttr.in (free public weather API)

## Status
✅ Published and active
