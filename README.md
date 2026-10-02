# 🤖 Automation Portfolio — 90-Day Build-in-Public

**Isaac | AI Workflow Automation Specialist | Nigeria 🇳🇬 | Day 30/90**

Every automation below was built, tested, and documented during my 90-day journey from $0 to first USD client. Each project includes: problem → solution → architecture → results → demo video → tools.

**Contact:** Free 20-Min Automation Audit → [Add Your Google Calendar Appointment Link Here] | Upwork | Fiverr | Contra

---

## 📊 Portfolio At A Glance

| # | Project | What It Does | Business Outcome | Tools | Demo |
|---|---------|--------------|------------------|-------|------|
| 1 | **[Sheets → Gmail Alerts]([./../01-sheets-gmail-automation](https://github.com/aiagentbuilderhq/sheets-gmail-automation))** | New spreadsheet rows trigger instant email alerts | Never miss a lead/order — response time minutes not hours | Make.com, Google Sheets, Gmail | [Video - Add Link] |
| 2 | **[Weather → Telegram Bot]([./../02-weather-telegram-bot)](https://github.com/aiagentbuilderhq/weather-telegram-bot)** | Daily weather delivered to Telegram automatically | First API integration — foundation for any API work | OpenWeatherMap API, Make.com, Telegram Bot API | [Video - Add Link] |
| 3 | **[Form → Slack Lead Alerts](aiagentbuilderhq/form-slack-leads)** | Form submissions ping Slack instantly | Lead follow-up: hours → seconds, zero missed leads | Google Forms, Make.com, Slack API | [Video - Add Link] |
| 4 | **[AI Inbox Assistant]([./../04-ai-inbox-assistant](https://github.com/aiagentbuilderhq/ai-inbox-assistant))** | Emails summarized + AI-drafted replies with confidence gate | Inbox triage: 2 hrs/day → 15 min review | Gmail, Gemini 1.5 Flash, Make.com, Telegram | [Video - Add Link] |
| 5 | **[AI Lead Scoring System]([./../05-ai-lead-scoring)](https://github.com/aiagentbuilderhq/ai-lead-scoring)** | Leads scored 1-10 against ICP + daily digest of 8+ only | Lead review: 5 hrs/week → 15 min/day | Apollo, Hunter, Sheets, Gemini, Make.com | [Video - Add Link] |

> **Note on cost:** All automations run on free tiers. The tools are free — the build, documentation, and upkeep are what clients pay for. Saves 10-20 hrs/week per workflow.

---

## 🧱 Architecture Pattern (Every Build Follows This)

```
TRIGGER → TRANSFORM → DELIVER
   ↓         ↓          ↓
 (Form,   (Clean,   (Email, Slack,
  Sheet,   Score,    Sheet, Telegram,
  Email,   AI Draft,  Digest)
  Schedule)  etc)
```

**Design principles I follow:**
1. Human-in-the-loop for final decisions (AI drafts, human approves)
2. Confidence gates — AI escalates when unsure, never guesses
3. Fake/test data only in demos — no client data ever in public repos
4. Documented so any team member can run it without me

---

## 📁 Repository Structure

```
automation-portfolio/
├── week-1/                          # Screenshots evidence week 1
├── week-2/                          # Screenshots evidence week 2
├── projects/
│   ├── sheets-gmail-alerts/         # Case study + screenshots
│   ├── weather-telegram-bot/
│   ├── form-slack-leads/
│   ├── ai-inbox-assistant/
│   └── ai-lead-scoring/
├── demos/
│   └── links.md                     # All Loom / YouTube unlisted links
└── README.md                        # This file
```

---

## 🎥 Demo Videos

All demos are 30-60 sec, unlisted on YouTube (only people with link can watch).

| Project | Loom / YouTube Link |
|---------|---------------------|
| Sheets → Gmail | [Add Link] |
| Weather → Telegram | [Add Link] |
| Form → Slack | [Add Link] |
| AI Inbox Assistant | [Add Link] |
| AI Lead Scoring | [Add Link] |

**Upload location:** YouTube → Unlisted (not Public, not Private) — see playbook Part 2.6

---

## 📄 Case Studies

Each project folder contains:
- `README.md` — quick overview
- `case-study.md` — Problem → Solution → Results → Tools → Timeline
- `screenshots/` — Make.com scenario + output
- `blueprint.json` — Make.com blueprint (sanitized, no keys)

---

## 🛡️ Safety Rules

- Never upload real client data — all demos use fake data
- Never store API keys, tokens, or passwords in any file
- Keep this repo Public — that's the point (portfolio proof)

---

## 📩 Work With Me

If a repetitive task is eating your week, I offer a free 20-minute audit: I map your process and deliver a 1-page automation plan.

**[Book Your Free Audit Here - Replace With Your Calendar Link]**

Built with Make.com + Gemini 1.5 Flash — saves 10-20 hrs/week per automation.
