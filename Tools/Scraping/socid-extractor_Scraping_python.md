---
source: https://github.com/soxoj/socid-extractor
aliases:
  - socid-extractor
  - soxoj/socid-extractor
tags: [python, python, scraping, osint, html-parsing, data-extraction, socmint, osint-framework, osint-python, osint-tool, account-extraction, socid]
category: Scraping
stars: 1034
org: soxoj
primary_language: Python
languages: [Python, Shell, url]
credibility_score: 54.5/100
date_processed: 2026-07-05
last_release: 2026-05-26
cover: attachments/banners/socid-extractor_banner.png

---

![banner](attachments/banners/socid-extractor_banner.png)

# socid-extractor

**`soxoj/socid-extractor`** · ⭐ 1,034 · 🔧 Python

## What is it?
Turns any public profile page into structured OSINT records across 130+ platforms via HTML/API parsing.

## How does it work?
The tool parses HTML pages and API responses from public profiles, extracting fields like usernames, display names, bios, avatars, locations, joined dates, follower counts, external links, and persistent internal identifiers. It uses Python's standard libraries (requests for HTTP calls, BeautifulSoup/lxml for HTML parsing) with a modular design where each site has its own parser function stored in a dictionary, enabling easy addition of new platforms without requiring API keys or a headless browser.

## Why is it important? (Core Value)
This self-hosted scraper directly supports the user's goal of building a personal OSINT data source that can be integrated into AI agent pipelines or workflow automations. Its no-API-key and no-headless-browser design reduces external dependencies, making it suitable for homelab environments and aligning with the interest in self-hostable alternatives to SaaS products. The stable internal identifiers provide a reliable way to track accounts across platform redesigns, which is valuable for OSINT research and can feed into automated decision-making systems.

## Key Features & Technologies
- Parses HTML pages and public APIs
- Extracts usernames, display names, bios, avatars, locations, joined dates, follower counts, external links
- No API keys required
- No headless browser needed
- Returns flat machine-readable dictionary
- 130+ platforms supported
- Stable internal identifiers (persistent IDs)

## Difference from Others
Unlike commercial APIs (e.g., WebHose.io, Fireant) that require paid API keys and often need headless browsers, this tool scrapes directly from public pages without any credentials. It also provides stable internal identifiers that persist across platform redesigns—a feature absent in most generic scraping libraries. The single-function-call design contrasts with frameworks like Scrapy or Playwright that require full project setups.

## 🏢 Organization & Credibility
- **Developer:** soxoj
- **Reputation:** Unknown
- **Stars:** 1,034
- **Forks:** 110
- **Recent Activity:** 24 commits in 3 months
- **Credibility Score:** 54.5/100 (Low)
- **Languages:** Python, Shell, url
- **Last Release:** 2026-05-26
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
*Source: [GitHub](https://github.com/soxoj/socid-extractor)*
