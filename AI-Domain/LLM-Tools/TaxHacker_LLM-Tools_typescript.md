---
source: https://github.com/vas3k/TaxHacker
aliases:
  - TaxHacker
  - vas3k/TaxHacker
tags: [typescript, llm, ocr, accounting, self-hosted, currency, currency-exchange, taxes, ai-analysis, expenses, invoices, gemini]
category: LLM-Tools
stars: 6496
org: vas3k
primary_language: TypeScript
languages: [TypeScript, CSS, Dockerfile, JavaScript, Shell]
credibility_score: 59.5/100
date_processed: 2026-07-06
last_release: 2026-04-03
cover: attachments/banners/TaxHacker_banner.png

---

![banner](attachments/banners/TaxHacker_banner.png)

# TaxHacker

> **TL;DR:** Self-hosted AI accounting app that uses LLMs and OCR to extract data from receipts, invoices, and PDFs for offline expense tracking.

**`vas3k/TaxHacker`** · ⭐ 6,496 · 🔧 TypeScript

## What is it?
TaxHacker is a self-hosted accounting application that leverages large language models to automatically extract financial data from receipts, invoices, and PDF documents. Users can upload photos of expense items and the app uses OCR combined with AI analysis to identify product names, amounts, dates, merchants, and tax information. The extracted data is saved into a structured database that resembles an Excel spreadsheet, making it easy to manage finances offline without relying on cloud SaaS solutions.

It supports custom prompt engineering, allowing users to define their own fields or analysis patterns. Automatic currency conversion is built in for international transactions. The app integrates with multiple LLM backends including Google Gemini, Ollama, and OpenAI, giving flexibility in model selection.

## How does it work?
TaxHacker operates by first using OCR technology to convert image-based documents into readable text. The extracted text is then processed through a large language model (LLM) that applies pattern matching and semantic analysis to identify accounting-relevant entities like amounts, dates, merchants, and tax codes. Users can provide custom prompts to the LLM to extract additional or modified fields. The system outputs structured JSON data which is stored in an SQLite or similar local database, presented through a web UI for review and export.

## Why is it important? (Core Value)
TaxHacker is valuable because it brings accounting automation into a self-hosted environment, eliminating reliance on proprietary cloud services that charge per-transaction fees or store sensitive financial data externally. For the user, this directly aligns with the objective of identifying self-hostable alternatives to SaaS products and building homelab infrastructure. The project demonstrates practical applications of LLM-based document analysis, supporting interests in AI/LLM tooling and prompt engineering. Additionally, its OCR capabilities complement skills in scraping and automation, making it a useful addition to a curated knowledge base of developer productivity tools.

## Key Features & Technologies
- Self-hosted
- OCR recognition via Gemini/Ollama/OpenAI
- Custom LLM prompts for field extraction
- Currency conversion
- Structured data export (Excel-like)
- Receipt/invoice parsing

## Difference from Others
Unlike commercial accounting software like QuickBooks or Xero which operate as cloud SaaS with subscription fees, TaxHacker is fully self-hosted and open-source, giving users complete control over their data and eliminating ongoing per-transaction costs. Traditional expense tracking apps rely on rule-based parsing or simple OCR without AI, limiting flexibility in field extraction. TaxHacker's key differentiator is its integration of large language models to understand document content semantically, plus support for custom prompts that let users define exactly what information to extract from receipts or invoices.

## 🏢 Organization & Credibility
- **Developer:** vas3k
- **Reputation:** Unknown
- **Stars:** 6,496
- **Forks:** 1069
- **Recent Activity:** 22 commits in 3 months
- **Credibility Score:** 59.5/100 (Low)
- **Languages:** TypeScript, CSS, Dockerfile, JavaScript, Shell
- **Last Release:** 2026-04-03
- **Quality:** ✅ good

## 💡 My Ideas & Notes
[Add your personal thoughts here]

## 📱 Social Signal (Manual)
- **Source:** [Dropdown: Reddit/X/Instagram/GitHub Search/Other]
- **Link:** [URL]
- **Notes:** [Context]

## 📔 Journal
[Date] - [Your experiences]

---
*Source: [GitHub](https://github.com/vas3k/TaxHacker)*
