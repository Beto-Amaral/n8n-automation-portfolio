# Project 04 — Weekly IT Ticket Report (Jira + Gmail)

## Overview
Automated workflow that runs every Monday at 8:00 AM, fetches all tickets 
from Jira, processes the data and sends a formatted HTML report via Gmail 
to the IT manager.

## What the Report Shows
- 📦 Total number of tickets
- 🔴 Open / Reopened tickets
- 🟡 In Progress tickets
- ⏳ Pending tickets
- ✅ Resolved tickets
- 👤 Unassigned tickets (with ticket list)

## Nodes Used
- **Schedule Trigger** — fires every Monday at 8:00 AM
- **Jira Software (Get Many Issues)** — fetches all tickets from the project
- **Code (JavaScript)** — processes and categorizes tickets by status
- **Gmail (Send Message)** — sends a formatted HTML report via email

## How It Works
1. Every Monday at 8:00 AM the workflow runs automatically
2. Jira node fetches all tickets from the IT Team project
3. Code node categorizes tickets by status and identifies unassigned ones
4. Gmail sends a formatted HTML email report to the manager

## Business Value
- ✅ Eliminates manual ticket status reporting
- ✅ Gives management full visibility of IT team workload
- ✅ Automatically flags unassigned tickets
- ✅ Saves ~30 minutes of manual work every week

## Tools & Platforms
- n8n Cloud (app.n8n.cloud)
- Jira Cloud (atlassian.net)
- Gmail API (OAuth2)

## Status
✅ Published and active — runs automatically every Monday at 8:00 AM
