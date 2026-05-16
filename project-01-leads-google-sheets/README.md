# Project 01 — Leads to Google Sheets

## Overview
Automation workflow that captures lead data (name and email) sent via HTTP POST request and automatically saves it to a Google Sheets spreadsheet.

## Nodes Used
- **Webhook** — receives incoming data
- **Google Sheets (Append Row)** — saves data to the spreadsheet

## How It Works
1. External system sends a POST request with `{ nome, email }` to the Webhook URL
2. Webhook receives the data and passes it to the next node
3. Google Sheets saves name and email as a new row automatically

## Tools & Platforms
- n8n Cloud (app.n8n.cloud)
- Google Sheets API (OAuth2)

## Example Payload
```json
{
  "nome": "Roberto",
  "email": "roberto@email.com"
}
```

## Status
✅ Published and active
