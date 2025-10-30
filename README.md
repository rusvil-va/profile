# 🤖 AI & Automation Portfolio – Russel Villota

Hi, I’m **Russel Villota**, a self-taught **AI and automation builder** with a **Bachelor’s degree in Computer Science** and hands-on experience integrating CRMs, APIs, and AI platforms.  

I started with **GoHighLevel automations**, then moved into **API-level integrations**, connecting third-party apps directly or via tools like **Zapier**, **Google Apps Script**, and more recently **n8n**, where I now design multi-step orchestration flows that bridge systems and AI models.

---

## 🧠 Core Skills
- **Automation:** GoHighLevel, n8n, Zapier, Apps Script  
- **Integrations:** Salesforce, LeadPerfection, ActiProspect, Twilio, Google Workspace  
- **AI:** OpenAI, Vapi, Retell – AI voice & chat agents  
- **Programming:** JavaScript, TypeScript, Python basics, Apps Script  
- **Infrastructure:** Docker (compose, healthchecks), Postgres basics  
- **Other Tools:** GitHub, Google Cloud, Markdown pipelines

---

## 🚀 Highlighted Projects

### 📞 1. Inbound Call AI Agent (n8n + Vapi + GoHighLevel)
**Goal:** Handle inbound customer calls using an AI voice agent (Vapi/Retell), automatically log call details into GoHighLevel, and update lead status.  
**Stack:** n8n, Vapi, Retell, GoHighLevel v2  
**Highlights:**
- Webhook + Function nodes to parse JSON transcripts
- Retry + DLQ setup for missed API calls
- Idempotency keys to prevent duplicate contact creation  
- Logs stored in Google Sheets for transparency  

📁 [workflow export](./workflows/inbound_ai_agent.json)

---

### 🧾 2. SEO Content Generator (n8n + OpenAI + Google)
**Goal:** Automate SEO content creation using keyword inputs from Google Sheets, generate draft articles with GPT-4, and output markdown files to Google Drive.  
**Stack:** n8n, OpenAI API, Google Sheets, Google Drive  
**Highlights:**
- JSON schema validation for GPT output  
- Markdown conversion and Drive file creation  
- Cost tracking for API usage in structured logs  
- Used error branches and repair loops for resilience  

📁 [workflow export](./workflows/seo_content_generator.json)

---

### ⚙️ Code Snippet
[`deduplicate_contacts.js`](./snippets/deduplicate_contacts.js)
> Cleans and merges GoHighLevel contacts during syncs.  
> Ensures idempotent updates and reduces redundant tags.

---

## 🪴 About This Repo
This portfolio demonstrates how I’ve **grown from platform-based automations (GoHighLevel)** to building **custom, API-driven and AI-powered automations using n8n** — integrating **voice, LLM, and CRM systems** end-to-end.

If you’d like to know more, reach me at **data@roaimastermind.com**.
