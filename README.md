# Hi, I'm Muhammad Tayyab 👋

**Automation specialist — I build n8n + AI workflows that capture leads, cut manual work, and never fail silently.**

I help small businesses and agencies turn repetitive processes into reliable automations: connecting their tools, adding AI where it genuinely helps, and keeping a human in the loop where it matters.

---

### 🛠️ What I build

- **Lead capture & qualification** — forms, inboxes and marketplaces → one clean CRM, with AI scoring and reply drafts
- **AI-assisted workflows** — structured LLM output (Gemini / OpenAI) with validation and safe fallbacks
- **Integrations** — Google Workspace, Gmail, Sheets, webhooks and REST APIs
- **Notifications & follow-ups** — alerts, daily digests, reminders, so nothing slips through
- **Production basics, every time** — retries, error workflows, deduplication, logging and tests

---

### ⭐ Featured project

#### [LeadFlow — AI lead intake & follow-up automation](https://github.com/motayyabautomation/leadflow-case-study)

> Every enquiry captured, cleaned, qualified by AI and followed up — without a single lead slipping through.

[![LeadFlow lead alerts in Gmail, each with an AI score and urgency](https://raw.githubusercontent.com/motayyabautomation/leadflow-case-study/main/screenshots/02-lead-alerts-inbox.jpg)](https://github.com/motayyabautomation/leadflow-case-study)

```
Website form ─┐                               ┌─ new ───────► Gemini (strict JSON) → validate → Sheets CRM → alert
Lead emails  ─┼─► clean & validate ─► dedupe ─┼─ returning ─► update original row → alert
Test mode    ─┘                               └─ invalid ───► Needs Review tab → alert

Daily 08:00 ─► follow-ups due digest + Gmail drafts for unanswered quotes
Any failure ─► Error Log + email alert
```

- Multi-source intake (website form + Angi / Thumbtack / Yelp notification emails)
- Email & phone normalisation, duplicate detection across sheet and batch, round-robin assignment
- Gemini qualification with schema-validated output, guardrails, and a privacy-aware prompt
- **21 automated tests** that run the workflows' real Code-node logic
- Human-in-the-loop: customer replies are always drafts, never auto-sent

**Stack:** n8n · Gemini API · Google Sheets · Gmail · JavaScript · Docker

📄 [Read the case study →](https://github.com/motayyabautomation/leadflow-case-study) · Full source available to clients on request.

---

### 🧰 Tools

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat&logo=googlegemini&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google_Sheets-34A853?style=flat&logo=googlesheets&logoColor=white)
![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=flat&logo=gmail&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-555555?style=flat&logo=postman&logoColor=white)

---

### 🤝 How I work

**Simple, reliable, easy to maintain.** Every workflow I deliver comes with error handling, a test mode with sample data, a one-place config, and setup documentation, so you can run it without me.

### 📫 Work with me

Have a repetitive process that eats your team's time? I'd like to hear about it.

[![Hire me on Freelancer](https://img.shields.io/badge/Hire_me_on-Freelancer-29B2FE?style=for-the-badge&logo=freelancer&logoColor=white)](https://www.freelancer.pk/u/tayyabm03)

📍 Pakistan · UTC+5 · available full-time for freelance projects
