---
source: https://github.com/Mahanaicoach/google-maps-scraper-kit
aliases:
  - google-maps-scraper-kit
  - Mahanaicoach/google-maps-scraper-kit
tags: [python, scraper, google-maps, docker, llm, automation, shell, url]
category: LLM-Tools
stars: 196
org: Mahanaicoach
primary_language: Python
languages: [Python, Shell, url]
credibility_score: 41.0/100
date_processed: 2026-08-02

cover: attachments/banners/google-maps-scraper-kit_banner.png

---

![banner](attachments/banners/google-maps-scraper-kit_banner.png)

# google-maps-scraper-kit

**`Mahanaicoach/google-maps-scraper-kit`** · ⭐ 196 · 🔧 Python

## What is it?
Google Maps Scraper Kit is a plug-and-play tool that runs a free, open-source Google Maps scraper locally on your own computer. It wraps Georgios Komninos' gosom/google-maps-scraper (MIT) and adds a one-command Docker setup, ready-to-run scripts, and a Claude skill so an LLM can drive the scraping process on autopilot. The kit extracts business details—name, address, phone, website, rating, reviews, lat/lng, emails—and warns about Google's rate limits and ToS compliance. It is designed for responsible, self-hosted data extraction without relying on cloud services.

## How does it work?
The project is built as a thin wrapper around the gosom/google-maps-scraper repository, which handles the actual HTTP requests to Google Maps and parses the responses. The kit provides Docker Compose files for a one-command setup, eliminating the need for manual environment configuration. It includes shell scripts that invoke the scraper with appropriate arguments (depth, keywords, proxies) and exposes a skill interface that Claude can call via tool use. When an LLM triggers the skill, the wrapper runs the scraper locally, respects rate-limit warnings, and returns structured data in JSON.

## Why is it important? (Core Value)
For a software engineer interested in self-hosted tools and AI agents, this kit offers a reliable way to scrape map data without depending on SaaS APIs or cloud services. It can be integrated into personal automation pipelines or research workflows that need business contact information from Google Maps. The built-in Claude skill demonstrates how LLMs can orchestrate scraping tasks, aligning with the user's interest in AI/LLM tooling and MCP servers. Because it runs locally, it also satisfies the desire to curate open-source alternatives and avoid vendor lock‑in.

## Key Features & Technologies
- Dockerized one-command setup
- Thin wrapper around gosom/google-maps-scraper (MIT)
- Claude skill for LLM integration
- Ready-to-run scripts with depth and proxy options
- Rate-limit warnings and responsible-use guidance
- Self-hosted (no cloud dependency)
- Open-source MIT license

## Difference from Others
Compared to the original gosom/google-maps-scraper, this kit adds Docker convenience and LLM integration, making it drop‑in ready for Claude or other agents. Other map scrapers often require manual handling of proxies, rate limits, and output parsing; this project addresses those pain points with clear warnings and ready scripts. It also differs from generic web scrapers by focusing specifically on Google Maps data structures, providing fields like latitude/longitude that many tools omit.

## 🏢 Organization & Credibility
- **Developer:** Mahanaicoach
- **Reputation:** Unknown
- **Stars:** 196
- **Forks:** 41
- **Recent Activity:** 4 commits in 3 months
- **Credibility Score:** 41.0/100 (Low)
- **Languages:** Python, Shell, url
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
*Source: [GitHub](https://github.com/Mahanaicoach/google-maps-scraper-kit)*
