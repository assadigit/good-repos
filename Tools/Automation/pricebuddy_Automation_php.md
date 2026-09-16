---
source: https://github.com/jez500/pricebuddy
aliases:
  - pricebuddy
  - jez500/pricebuddy
tags: [php, self-hosted, automation, scraping, ai, docker, open-source, price-comparison, price-monitoring, price-tracker, shopping, blade]
category: Automation
stars: 987
org: jez500
primary_language: PHP
languages: [PHP, Blade, JavaScript, SCSS, Dockerfile]
credibility_score: 57.0/100
date_processed: 2026-07-05
last_release: 2026-07-02
cover: attachments/banners/pricebuddy_banner.png

---

![banner](attachments/banners/pricebuddy_banner.png)

# pricebuddy

**`jez500/pricebuddy`** · ⭐ 987 · 🔧 PHP

## What is it?
PriceBuddy is an open-source self-hostable price tracker built for the messy web—any store, any product URL. It runs locally so you keep all data private, avoids subscription fees, and monitors exactly the sites you care about without relying on someone else's integrations.

Key features include automatic price monitoring with full history stored in your own database, availability/stock tracking, cross-store comparisons, and an AI fallback that can parse pages with awkward markup. The web app serves as a central dashboard while API endpoints and a CLI make the tool scriptable for automation workflows.

## How does it work?
The project uses a web frontend served via a Node/Python backend with API endpoints. Data persists in a local database (probably PostgreSQL or SQLite). Deployment is handled by Docker Compose, and the CLI allows scripting of monitoring tasks. It scrapes product pages, stores normalized data in a local database, and periodically rechecks URLs on a schedule. When a page is difficult to scrape, it can invoke an external AI provider to extract price and stock information.

## Why is it important? (Core Value)
PriceBuddy fills the gap left by SaaS trackers that only support a handful of stores. By running locally you keep all data private, avoid subscription fees, and control exactly which sites to monitor—perfect for hobbyist shopping or household wishlists. The AI fallback makes it robust against frequent markup changes. For your workflow, this gives you a self-hosted alternative to price-tracking services and demonstrates a new approach that blends traditional scraping with LLM enhancement.

## Key Features & Technologies
- Self-hostable via Docker Compose
- API and CLI for scripting
- AI provider fallback for difficult pages
- Persistent local database
- Cross-store tracking (any product URL)
- Availability/stock monitoring
- Web dashboard for configuration

## Difference from Others
Unlike CamelCamelCamel, Keepa, or Honey which are closed SaaS services limited to specific retailers, PriceBuddy works on any store you paste a URL into. It also offers full data ownership and local storage, while the others keep your history in their cloud. The AI fallback is another differentiator—most scrapers break when markup changes, but PriceBuddy can adapt by calling an LLM.

## 🏢 Organization & Credibility
- **Developer:** jez500
- **Reputation:** Unknown
- **Stars:** 987
- **Forks:** 55
- **Recent Activity:** 102 commits in 3 months
- **Credibility Score:** 57.0/100 (Low)
- **Languages:** PHP, Blade, JavaScript, SCSS, Dockerfile
- **Last Release:** 2026-07-02
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
*Source: [GitHub](https://github.com/jez500/pricebuddy)*
