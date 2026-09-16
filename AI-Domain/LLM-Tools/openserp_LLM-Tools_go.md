---
source: https://github.com/karust/openserp
aliases:
  - openserp
  - karust/openserp
tags: [go, llm, search, scraper, cli, opensource, baidu, google, search-engine, serp, serpapi, yandex]
category: LLM-Tools
stars: 840
org: karust
primary_language: Go
languages: [Go, JavaScript, Dockerfile, Makefile, url]
credibility_score: 57.0/100
date_processed: 2026-07-05
last_release: 2026-06-29
cover: attachments/banners/openserp_banner.png

---

![banner](attachments/banners/openserp_banner.png)

# openserp

> **TL;DR:** Self-hosted SERP API for Google, Bing, Yandex, Baidu, DuckDuckGo, Ecosia search with page extraction.

**`karust/openserp`** · ⭐ 840 · 🔧 Go

## What is it?
OpenSERP is a free, open-source SERP API and CLI that provides live search results from multiple engines including Google, Yandex, Baidu, Bing, DuckDuckGo, and Ecosia. It can be used as a search tool for LLMs, agents, and RAG pipelines, or as a scraper backend for SEO rank tracking across multiple search engines. The project is especially useful when your workflow needs RU/CN web coverage instead of another Google-only API.

## How does it work?
OpenSERP is implemented in Go and provides dedicated endpoints for each supported search engine. It performs browser-rendered searches to extract page content, then returns structured JSON results. The `/mega/search` endpoint queries all selected engines simultaneously, merges the results, and deduplicates them.

## Why is it important? (Core Value)
OpenSERP solves the need for multi-engine search data in RAG pipelines and SEO workflows. It's free, open-source, and can be self-hosted, making it an excellent alternative to paid SERP APIs like Serper or SerpApi. For a software engineer building AI agents or curating tools, OpenSERP offers a reliable, self-hostable source of diverse search results, especially valuable for RU/CN coverage where Google-only APIs fall short. As someone focused on self-hosted alternatives and homelab infrastructure, this project aligns perfectly with your interests in scraping, automation, and building a personal knowledge base of useful open-source tools.

## Key Features & Technologies
- Multi-engine search endpoints
- Browser-rendered page extraction
- /mega/search megasearch endpoint
- Self-hostable Go CLI
- Docker support

## Difference from Others
Unlike commercial SERP APIs like Serper or SerpApi, OpenSERP is free and open-source, giving you full control over hosting and data privacy. It supports a broader range of engines including Yandex, Baidu, and Ecosia, which many competitors lack. The mega endpoint offers a unique way to query all engines at once, merging results—something not typically available in other tools.

## 🏢 Organization & Credibility
- **Developer:** karust
- **Reputation:** Unknown
- **Stars:** 840
- **Forks:** 112
- **Recent Activity:** 77 commits in 3 months
- **Credibility Score:** 57.0/100 (Low)
- **Languages:** Go, JavaScript, Dockerfile, Makefile, url
- **Last Release:** 2026-06-29
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
*Source: [GitHub](https://github.com/karust/openserp)*
