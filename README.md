
---

## 🧩 Project List

### 🧠 01 — AI Agents & RAG

| 📄 File | 📝 Description |
|---|---|
| `01-ai-agents/rag-teaching-assistant.json` | RAG-based teaching assistant agent with retrieval over custom knowledge base |
| `01-ai-agents/rag-google-docs.json` | RAG agent answering questions from Google Docs documents |
| `01-ai-agents/web-chatbot-nf-academy.json` | Web chatbot for NF Academy product Q&A backed by Google Sheets |
| `01-ai-agents/web-chatbot-google-sheets.json` | Self-hosted web chatbot with Google Sheets as knowledge source |

### 🛡️ 02 — Cybersecurity

| 📄 File | 📝 Description |
|---|---|
| `02-cybersecurity/ai-phishing-triage.json` | AI phishing triage: allowlist check → LLM risk scoring (1–10) → Gmail labeling + Telegram alert |

### 📈 03 — Data Intelligence

| 📄 File | 📝 Description |
|---|---|
| `03-data-intelligence/btc-eth-daily-sentiment.json` | Daily BTC/ETH sentiment analysis pipeline with Google Sheets storage |
| `03-data-intelligence/financial-news-summarizer.json` | Daily financial news summarizer via RSS + Gemini, delivered to Telegram |
| `03-data-intelligence/competitor-monitoring.json` | Automated competitor monitoring with share-of-voice analysis and PDF report |

### 💰 04 — Finance & Operations

| 📄 File | 📝 Description |
|---|---|
| `04-finance-operations/invoice-generator.json` | Automated invoice generation with HTML-to-PDF export and email delivery |
| `04-finance-operations/email-expense-tracker.json` | Expense logging from email via IMAP + Google Sheets |
| `04-finance-operations/monthly-report-automation.json` | Monthly report automation merging multiple Google Sheets |
| `04-finance-operations/auto-reconciliation.json` | Automated bank vs internal transaction reconciliation |
| `04-finance-operations/weekly-expense-report.json` | Weekly expense report with AI-generated insights |

### 📣 05 — Content & Marketing

| 📄 File | 📝 Description |
|---|---|
| `05-content-marketing/auto-posting-scheduler.json` | Scheduled auto-posting workflow driven by Google Sheets |
| `05-content-marketing/auto-email-responder.json` | Automated email responder for form submissions |
| `05-content-marketing/routine-content-generator.json` | Routine content generation with Telegram bot and AI image/video |
| `05-content-marketing/best-time-to-post-analyzer.json` | Best-time-to-post analyzer from engagement data |
| `05-content-marketing/ai-image-generator.json` | AI image generation workflow via KIE.ai |
| `05-content-marketing/ai-video-generator.json` | AI video generation workflow via KIE.ai |

### 🚀 06 — Getting Started

| 📄 File | 📝 Description |
|---|---|
| `06-getting-started/no-code-ai-agent.json` | No-code AI agent demo with built-in product knowledge base |

---

## ⚡ How to Use

1. 📥 **Install n8n** (self-hosted or cloud).
2. 📂 **Import a workflow**: open n8n → **Workflow → Import from File** → pilih file `.json`.
3. 🔑 **Configure credentials** inside n8n (Gmail, Telegram, Google Gemini, Google Sheets, Supabase, Google Drive, atau API key lain sesuai workflow).
4. ✏️ **Replace placeholders** seperti `YOUR_TELEGRAM_CHAT_ID`, `YOUR_SPREADSHEET_ID`, `YOUR_KIE_API_KEY`, `YOUR_PDFSHIFT_API_KEY` dengan nilai milikmu sendiri.
5. ▶️ **Activate** workflow.

> ⚠️ **Note:** Credentials dan ID pribadi sudah dihapus atau diganti placeholder. Kamu wajib mengatur credential sendiri sebelum menjalankan workflow.

---

## 🔑 Placeholder Reference

| 🔤 Placeholder | 💡 Arti |
|---|---|
| `YOUR_TELEGRAM_CHAT_ID` | Chat ID Telegram penerima notifikasi |
| `YOUR_SPREADSHEET_ID` | ID Google Spreadsheet |
| `YOUR_DRIVE_FILE_ID` | ID file Google Drive |
| `YOUR_DRIVE_FOLDER_ID` | ID folder Google Drive |
| `YOUR_KIE_API_KEY` | API key KIE.ai |
| `YOUR_PDFSHIFT_API_KEY` | API key PDFShift |
| `YOUR_PHONE_NUMBER` | Nomor telepon (di template invoice) |

---

## 👩‍💻 Author

**Zainab Aznur**
*AI Automation & Data Enthusiast* ✨

<p>
  <a href="https://www.linkedin.com/in/zainab-aznur-baa299232">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://github.com/zainabaznur">
    <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

## 📜 License

MIT License — free to use, modify, and share with attribution.

---

## ⚠️ Disclaimer

Workflow dalam repo ini disediakan untuk keperluan pembelajaran dan portofolio. Beberapa workflow menggunakan API berbayar (KIE.ai, PDFShift, Serper, Groq) — pastikan kamu memahami biaya dan kebijakan masing-masing layanan sebelum digunakan di lingkungan produksi.

---

<p align="center">
  ⭐ <strong>If you find this repo useful, give it a star!</strong> ⭐
</p>
