---
source: "https://github.com/AgriciDaniel/on-page-seo"
aliases:
  - on-page-seo
  - AgriciDaniel/on-page-seo

tags: [typescript, react, node.js, seo, automation, ai, ai-seo, claude-code, claude-code-skill, marketing-automation, open-source]
category: "Automation"
stars: 253
org: "AgriciDaniel"
primary_language: TypeScript
languages: [TypeScript, CSS, HTML, JavaScript, url]
credibility_score: 41.0/100
date_processed: 2026-09-16

cover: attachments/banners/on-page-seo_banner.png

---

![banner](attachments/banners/on-page-seo_banner.png)

# on-page-seo

> **TL;DR:** Self-hosted on-page SEO analyzer auditing up to 500 pages across 74 metrics with Firecrawl and DataForSEO APIs.

**`AgriciDaniel/on-page-seo`** · ⭐ 253 · 🔧 TypeScript

## What is it?
On-Page SEO Analyzer is a full-stack web application that automates on-page SEO audits for websites. It discovers pages via the Firecrawl API, then analyzes each page against 74 SEO metrics powered by the DataForSEO API, including Core Web Vitals (LCP, FID, CLS). Users can run audits of up to 500 pages at once, watch real-time progress, and export results as CSV or JSON reports. The project originated from an n8n workflow and was evolved into a standalone app, with the full build journey documented on YouTube.

The frontend is built with React 19, TypeScript, Vite, TanStack Router, React Query, Tailwind CSS with Shadcn/ui components, and Recharts for data visualization. The backend runs on Node.js with Express and persists data in SQLite via better-sqlite3. External dependencies include a Firecrawl API key for page discovery and a DataForSEO account for SEO metric collection.

The project is tagged with 'ai', 'claude-code', and 'claude-code-skill' topics, indicating it was built or is intended to be used alongside Claude Code as a developer workflow tool, though the core analysis pipeline relies on traditional REST APIs rather than an LLM.

## How does it work?
The application uses a two-stage pipeline: (1) Firecrawl crawls the target website to discover all pages up to a 500-page cap, and (2) DataForSEO's API is queried per page to pull 74 SEO metrics including title/meta analysis, heading structure, image alt text, internal linking, and Core Web Vitals scores. Results are stored in a local SQLite database and surfaced through a React dashboard with live progress updates, sortable tables, and exportable CSV/JSON reports.

The Node.js Express backend orchestrates the crawl-then-analyze workflow, while the React 19 frontend (Vite + TanStack Router + React Query) provides a responsive UI with dark mode and Recharts-based visualizations. The architecture is deliberately lightweight—no external database server, no message queue—making it straightforward to self-host with just Node.js 18+ and two API keys.

## Why is it important? (Core Value)
For the user's stated interests in automation, developer productivity, and self-hostable alternatives to SaaS, this project offers a concrete example of turning a niche marketing/SEO workflow into a self-contained open-source tool. It demonstrates how Firecrawl (crawling) and DataForSEO (metric APIs) can be wired together in a Node.js + React stack without relying on a proprietary SaaS dashboard—directly relevant to the user's goal of identifying self-hostable alternatives.

The 'claude-code' and 'claude-code-skill' topics also make it a useful reference for AI-assisted development workflows: the project was built (and is maintained) with Claude Code, showing how an LLM-powered coding agent can scaffold a full-stack app from a prior n8n automation. For the user's Obsidian knowledge base, it slots into the Automation/Tools domain as a working example of API-orchestrated data pipelines and a potential template for building similar audit or monitoring tools around other SaaS APIs.

## Key Features & Technologies
- Discovers up to 500 pages per site via Firecrawl crawling API
- Analyzes 74 SEO metrics per page through the DataForSEO API
- Tracks Core Web Vitals (LCP, FID, CLS) scores
- Real-time audit progress with live dashboard updates
- Export results as CSV or JSON reports
- React 19 + TypeScript frontend with TanStack Router, Shadcn/ui, and Recharts
- Node.js Express backend with SQLite (better-sqlite3) persistence

## Difference from Others
Most SEO tools are either monolithic SaaS platforms (Ahrefs, SEMrush) or lightweight crawlers that stop at basic link/heading checks. On-Page SEO Analyzer differentiates by being fully self-hostable and API-composable: it lets you swap in your own Firecrawl and DataForSEO credentials, keeps all data in a local SQLite file, and exposes the raw 74-metric dataset via CSV/JSON export—something most SaaS competitors gate behind paid tiers. Compared to generic scraping libraries (e.g., Scrapy, Crawlee), it ships with a purpose-built dashboard and progress UX rather than leaving you to wire up your own UI. Its origin as an n8n workflow that was productized into a standalone app also makes it a useful architectural reference for the user's interest in workflow-to-app evolution patterns.

## 🏢 Organization & Credibility
- **Developer:** AgriciDaniel
- **Reputation:** Unknown
- **Stars:** 253
- **Forks:** 58
- **Recent Activity:** 0 commits in 3 months
- **Credibility Score:** 41.0/100 (Low)
- **Languages:** TypeScript, CSS, HTML, JavaScript, url
- **Last Release:** No releases
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
*Source: [GitHub](https://github.com/AgriciDaniel/on-page-seo)*
