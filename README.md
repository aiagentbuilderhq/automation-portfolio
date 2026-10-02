# 🤖 Automation Portfolio — 90-Day Build-in-Public

**Isaac | AI Workflow Automation Specialist | Nigeria 🇳🇬 | Day 30/90**

Every automation below was built, tested, and documented during my 90-day journey from $0 to first USD client. Each project includes: problem → solution → architecture → results → demo video → tools.

**Contact:** Free 20-Min Automation Audit → [Add Your Google Calendar Appointment Link Here] | Upwork | Fiverr | Contra

---

## 📊 Portfolio At A Glance — 5 Live Projects

| # | Project | What It Does | Business Outcome | Tools | Demo |
|---|---------|--------------|------------------|-------|------|
| 1 | **[Sheets → Gmail Alerts](https://github.com/aiagentbuilderhq/sheets-gmail-automation)** | New spreadsheet rows trigger instant email alerts | Never miss a lead/order — response time minutes not hours | Make.com, n8n, Google Sheets API, Gmail API, Webhooks | [Video - Add Link] |
| 2 | **[Weather → Telegram Bot](https://github.com/aiagentbuilderhq/weather-telegram-bot)** | Daily weather + any API data delivered to Telegram automatically | First API integration — foundation for Shopify, Stripe, HubSpot, any API | OpenWeatherMap API, Telegram Bot API, Make.com, n8n, HTTP / Webhooks, JSON | [Video - Add Link] |
| 3 | **[Form → Slack Lead Alerts](https://github.com/aiagentbuilderhq/form-slack-leads)** | Form submissions ping Slack instantly + optional AI qualification | Lead follow-up: hours → seconds, zero missed leads, 21x higher close rate | Google Forms API, Slack API, Make.com, n8n, Webhooks, Gmail API | [Video - Add Link] |
| 4 | **[AI Inbox Assistant](https://github.com/aiagentbuilderhq/ai-inbox-assistant)** | Emails summarized + AI-drafted replies with confidence gate — high confidence drafts, low escalates | Inbox triage: 2 hrs/day → 15 min review, 80% auto-handled | Gmail API, Gemini 1.5 Flash, Groq, Make.com, n8n, MCP, Telegram API, LangChain pattern, RAG-lite | [Video - Add Link] |
| 5 | **[AI Lead Scoring System](https://github.com/aiagentbuilderhq/ai-lead-scoring)** | Leads sourced via Apollo/Hunter, scored 1-10 by Gemini against ICP, daily digest of 8+ only | Lead review: 5 hrs/week → 15 min/day, focus on high-fit only | Apollo.io API, Hunter.io API, Google Sheets API, Gemini, Groq, Make.com, n8n, MCP, Webhooks | [Video - Add Link] |

> **Note on cost:** All automations run on free tiers. The tools are free — the build, documentation, and upkeep are what clients pay for. Saves 10-20 hrs/week per workflow.

---

## 🧱 Tech Stack — What Founders Search For (I Build With These)

**Automation Platforms:**
`Make.com` · `n8n` (self-host + cloud) · `Zapier` (when client already has it) · `Webhooks` · `HTTP APIs` · `Cron / Scheduling`

**AI & LLM:**
`Google AI Studio (Gemini 1.5 Flash / Pro)` · `Groq (Llama 3, Mixtral)` · `OpenAI API (when client provides key)` · `MCP (Model Context Protocol)` · `LangChain patterns` · `RAG-lite (Sheets + Gemini)` · `Prompt Engineering` · `Confidence Gates`

**APIs & Integrations I Connect Daily:**
`Gmail API` · `Google Sheets API` · `Google Forms API` · `Google Drive API` · `Slack API` · `Telegram Bot API` · `OpenWeatherMap API` · `Apollo.io API` · `Hunter.io API` · `Shopify API` · `Stripe API` · `HubSpot API` · `Airtable API` · `Notion API` · `Calendly API` · `Any REST API with JSON`

**Data & Workflow:**
`JSON` · `Data Cleaning & Validation` · `Deduplication` · `Lead Enrichment` · `Email Verification` · `Error Handling & Retries` · `Router / Filters / Data Stores`

**Why This Matters to Founders:** Most freelancers know one tool. I build with Make.com AND n8n, so if your team already uses one, I work in your stack — no new software to learn. MCP + API-first means I can connect any tool with an API, not just the popular ones.

---

## 🏗️ Architecture Pattern (Every Build Follows This)

```
TRIGGER → TRANSFORM → DELIVER
   ↓         ↓          ↓
 (Form,   (Clean,   (Email, Slack,
  Sheet,   Score,    Sheet, Telegram,
  Email,   AI Draft,  Digest)
  Schedule, Webhook)  etc)
```

**Design principles I follow:**
1. Human-in-the-loop for final decisions (AI drafts, human approves)
2. Confidence gates — AI escalates when unsure, never guesses (MCP pattern)
3. Fake/test data only in demos — no client data ever in public repos
4. Documented + Loom walkthrough so any team member can run it without me
5. Works on both Make.com and n8n — client chooses, I build in their preferred stack

---

## 📁 Repository Structure

```
automation-portfolio/ (hub — you are here)
├── README.md (this file — links to 5 live repos below)

5 Live Project Repos (each is independent, pinned on profile):
├── https://github.com/aiagentbuilderhq/sheets-gmail-automation
├── https://github.com/aiagentbuilderhq/weather-telegram-bot
├── https://github.com/aiagentbuilderhq/form-slack-leads
├── https://github.com/aiagentbuilderhq/ai-inbox-assistant
└── https://github.com/aiagentbuilderhq/ai-lead-scoring

Each project repo contains:
├── README.md (overview + architecture + demo)
├── case-study.md (Problem → Solution → Results → Tools)
├── screenshots/ (Make.com / n8n scenario + output)
└── blueprint.json (sanitized Make.com / n8n workflow)
```

---

## 🎥 Demo Videos

All demos are 30-60 sec, unlisted on YouTube (only people with link can watch).

| Project | Live Repo | Loom / YouTube Link |
|---------|-----------|---------------------|
| Sheets → Gmail | [sheets-gmail-automation](https://github.com/aiagentbuilderhq/sheets-gmail-automation) | [Add Link] |
| Weather → Telegram | [weather-telegram-bot](https://github.com/aiagentbuilderhq/weather-telegram-bot) | [Add Link] |
| Form → Slack | [form-slack-leads](https://github.com/aiagentbuilderhq/form-slack-leads) | [Add Link] |
| AI Inbox Assistant | [ai-inbox-assistant](https://github.com/aiagentbuilderhq/ai-inbox-assistant) | [Add Link] |
| AI Lead Scoring | [ai-lead-scoring](https://github.com/aiagentbuilderhq/ai-lead-scoring) | [Add Link] |

**Upload location:** YouTube → Unlisted (not Public, not Private) — see playbook Part 2.6

---

## 📄 What Founders Get

For every automation:
- Working scenario (Make.com blueprint + n8n workflow JSON — sanitized, no keys)
- 15-min Loom walkthrough video
- 1-page documentation (how to edit, add recipients, change triggers)
- 7 days support — if it breaks, fixed free within 24h
- Built on YOUR accounts (Gmail, Sheets, Slack) — you keep everything, no vendor lock-in

---

## 🛡️ Safety Rules

- Never upload real client data — all demos use fake data
- Never store API keys, tokens, or passwords in any file
- Keep repos Public — that's the point (portfolio proof)

---

## 📩 Work With Me

If a repetitive task is eating your week, I offer a free 20-minute audit: I map your process and deliver a 1-page automation plan.

**[Book Your Free Audit Here - Replace With Your Calendar Link]**

Built with Make.com + n8n + Gemini + MCP + APIs — saves 10-20 hrs/week per automation.
Founder-friendly: Works with tools you already have — Gmail, Sheets, Slack, Shopify, HubSpot, Notion, Airtable — no new subscriptions needed.
