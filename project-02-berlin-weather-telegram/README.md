# Project 02 — Berlin Weather Notification via Telegram

## Overview
Automation workflow that runs every day at 8:00 AM, fetches the current weather forecast for Berlin from a free public API, and sends a formatted summary message to Telegram automatically.

## Nodes Used
- **Schedule Trigger** — fires the workflow automatically every day at 8:00 AM
- **HTTP Request** — fetches weather data from the wttr.in public API
- **Code (JavaScript)** — processes and extracts the relevant fields
- **Telegram** — sends the formatted message to the user

## How It Works
1. At 8:00 AM, Schedule Trigger fires the workflow automatically
2. HTTP Request fetches Berlin weather data from `https://wttr.in/Berlin?format=j1`
3. Code node parses the JSON string and extracts temperature, humidity, weather description, sunrise and sunset
4. Telegram sends a formatted message with the day's weather data

## Example Telegram Message
