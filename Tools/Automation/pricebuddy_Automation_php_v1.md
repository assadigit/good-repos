---
source: https://github.com/jez500/pricebuddy
aliases:
  - pricebuddy
  - jez500/pricebuddy
tags: [php, python, self-hosted, price-tracking, automation, scraping, open-source, price-comparison, price-monitoring, price-tracker, shopping, blade]
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

> **TL;DR:** Self-hostable price tracker that monitors products across stores and notifies when deals match your criteria.

**`jez500/pricebuddy`** · ⭐ 987 · 🔧 PHP

## What is it?
PriceBuddy is an open source, self-hostable price tracking application designed for users who prefer owning their data rather than relying on SaaS services. Instead of keeping dozens of browser tabs open to watch prices fluctuate, you paste a product URL into PriceBuddy, and it automatically checks the page on a schedule, storing price history and comparing listings across different stores.

## How does it work?
The application operates as a web app with an API and CLI interface. When you provide a product URL, PriceBuddy scrapes the page to extract price and availability information, then stores this data in its database for historical tracking. It runs on a configurable schedule to poll products repeatedly. For pages with complex or frequently changing markup that would be difficult to parse with static selectors, it can optionally leverage an AI provider you configure to help handle the scraping more robustly.

## Why is it important? (Core Value)
This project directly addresses several of your objectives: it offers a self-hostable alternative to commercial SaaS price trackers (CamelCamelCamel, Honey, etc.), giving you full control over your data. As someone researching automation and developer tools, the CLI and API provide excellent integrability into your own workflows—perhaps triggering notifications via your preferred channels or feeding price data into dashboards. The optional AI-powered scraping component is particularly relevant to your interests in AI/LLM tooling, demonstrating a practical use case for LLMs beyond agents: they can serve as dynamic parsers when static approaches fail on messy product pages.

## Key Features & Technologies
- Self-hostable with Docker
- Tracks price history automatically
- Cross-store comparison
- Stock status monitoring
- Web app + API + CLI interfaces
- Optional AI provider for difficult pages
- Open source

## Difference from Others
Most dedicated price trackers are SaaS services that only support stores where someone has previously built an integration. PriceBuddy is fundamentally different because it's self-hostable—you deploy it yourself, own all the data, and can track any product on any store you have access to. Its architecture is also explicitly built for the 'messy web': it handles normal product pages, changing markup structures, multiple listings for the same item, stores that go in and out of stock, and the common problem where advertised 'sale' prices aren't genuinely discounted. This flexibility is a key advantage over rigid SaaS solutions.

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
