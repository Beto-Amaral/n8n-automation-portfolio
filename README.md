# n8n Automation Portfolio

Hi! I'm Roberto de Aquino, a Data Analyst and IT Support Specialist. I bridge the gap between IT operations, Finance, and Business Intelligence by building high-impact automation workflows with n8n.

Rather than just connecting tools, I focus on building automations that save time, reduce manual errors, ensure SLA compliance, and support internal financial controls.

---

## 🛠️ Featured Projects

### 🚀 01. Automated Lead Management & Ingestion
* **Problem:** Marketing/Sales teams losing track of new leads due to manual data entry from webhooks, creating delays in follow-ups.
* **Automation:** Captures incoming lead data instantly via Webhook and structures it into a centralized spreadsheet.
* **Tools Used:** Webhook, Google Sheets.
* **Output:** A clean, automated Google Sheets database updated in real-time.
* **Business Value / Time Saved:** Eliminates 100% of manual data entry errors and ensures sales operations can contact leads within minutes, increasing conversion rates.

---

### 📅 02. Scheduled Internal Alerts System (Berlin Weather)
* **Problem:** Field teams or operations managers needing external localized data daily before starting shifts without checking multiple apps.
* **Automation:** A scheduled worker that fetches live data from weather APIs every morning at 7:00 AM, parses the JSON payload, and formats it for communication channels.
* **Tools Used:** Schedule, HTTP Request, Code (JavaScript), Telegram.
* **Output:** A clean, automated notification delivered to a Telegram broadcast channel every morning.
* **Business Value / Time Saved:** Demonstrates infrastructure readiness for automated routine team briefings, shift alerts, or daily operations scheduling.

---

### 🤖 03. Aquino Assistant Chatbot (On-Demand Operations Support)
* **Problem:** Internal staff or users needing quick, on-demand status or external data updates without opening multiple corporate dashboards.
* **Automation:** An interactive Telegram chatbot that triggers based on user commands, processes variables using conditional routing (Switch), and fetches live external data.
* **Tools Used:** Telegram Trigger, Switch, HTTP Request, Code, Telegram.
* **Output:** A responsive, interactive chat interface providing real-time data on demand.
* **Business Value / Time Saved:** Boosts operational efficiency by decentralizing data access, acting as a prototype for automated IT Help Desk or FAQ routing.

---

### 📊 04. Weekly IT Ticket & SLA Compliance Report
* **Problem:** IT Management and Finance lack visibility into overdue IT tickets, leading to breached SLAs, contractual penalties, and month-end operational delays.
* **Automation:** A weekly workflow that fetches pending tickets from Jira Cloud, analyzes SLA statuses, generates an aggregated HTML summary report, and emails it to stakeholders.
* **Tools Used:** Schedule, Jira Cloud API, Code (JavaScript), Gmail API.
* **Output:** A highly formatted, professional HTML executive summary sent every Monday morning to management.
* **Business Value / Internal Controls:** *Critical for Finance & Audit.* Ensures full visibility over delays affecting critical accounting/ERP systems. Prevents financial losses from SLA breaches and automates internal compliance evidence.

---

## 🧰 Tools & Tech Stack

* **Automation Engine:** n8n Cloud / Self-Hosted Workflow Engineering
* **ITSM & Ticket Management:** Jira Cloud API
* **Communication & Alerts:** Telegram Bot API, Gmail API
* **Data Management:** Google Sheets API, JSON & Data Parsing (JavaScript/Code node)
* **External Integrations:** Webhooks & REST APIs (HTTP Request)
