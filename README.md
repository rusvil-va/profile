# 🤖 AI & Automation Portfolio – Russel Villota

Hi, I’m **Russel Villota**, an **AI and automations builder** with a **Bachelor’s degree in Computer Science** and a self-taught journey into connecting systems using APIs, code, and logic.

I started with **GoHighLevel automations**, then learned to integrate **third-party tools** and **AI platforms** — first using Zapier, then directly through **Google Apps Script**, **custom code**, and now **n8n**.  
My approach blends **API documentation literacy**, **code-based logic**, and **LLM integration** — not just using AI for answers, but using it as a **coding reference and test generator** when building real-world solutions.

---

## 🧠 Core Skills
- **Automation Platforms:** GoHighLevel, n8n, Google Apps Script, Zapier  
- **AI Integrations:** OpenAI API (ChatGPT, Custom GPTs, Actions), Claude / Claude Code / Anthropic API  
- **APIs:** Proficient in reading and implementing API docs (OAuth2, pagination, HMAC, rate limits)  
- **Programming:** JavaScript / TypeScript, Apps Script (custom UIs + backend logic)  
- **Integrations:** Salesforce, LeadPerfection, ActiProspect, Twilio, Google Workspace  
- **Development Practices:** Code-first integrations, reference-based AI usage, GitHub versioning  

---

## 🚀 Highlighted Projects

### 📞 1. Inbound AI Call Agent (n8n + Vapi + Retell + GoHighLevel)
**Goal:** Create an automated inbound call system using AI voice (Vapi + Retell) that logs calls and updates leads in GoHighLevel.  
**Stack:** n8n, Vapi API, Retell API, GoHighLevel v2  
**Highlights:**  
- Used FunctionItem nodes to parse JSON transcripts  
- Error branches + retries for call logging  
- API-first design: built integration directly from Vapi & Retell documentation  
- Verified data flow via n8n webhook inspection

📁 [workflow export](./workflows/inbound_ai_agent.json)

---

### 🧾 2. SEO Content Generator (n8n + OpenAI + Google)
**Goal:** Generate SEO-optimized content drafts automatically from keyword lists in Google Sheets.  
**Stack:** n8n, OpenAI API, Google Sheets, Google Drive  
**Highlights:**  
- Enforced JSON schema for GPT-4 output  
- Stored markdown drafts directly to Drive  
- Used Apps Script for file automation before integrating into n8n  
- Cost-aware workflow with simple prompt validation  

📁 [workflow export](./workflows/seo_content_generator.json)

---

### ⚙️ Code Snippet
[`deduplicate_contacts.js`](./snippets/deduplicate_contacts.js)  
> Cleans and merges GoHighLevel contacts during syncs.  
> Ensures idempotent updates and reduces redundant tags.

---

## 🪴 About This Repo
This portfolio shows how I **taught myself end-to-end automation engineering**, combining:
- a **Computer Science background**,  
- **API-first mindset**,  
- and **hands-on implementation of AI integrations** across multiple systems.

I prefer reading official docs, experimenting in code, and using AI tools as coding partners — not shortcuts.

**Contact:** data@roaimastermind.com
