---
source: https://github.com/apify/crawlee
aliases:
  - crawlee
  - apify/crawlee
tags: [typescript, javascript, typescript, scraping, automation, nodejs, web-scraping, web-crawling, npm, headless-chrome, puppeteer, apify]
category: Scraping
stars: 24532
org: apify
primary_language: TypeScript
languages: [TypeScript, MDX, JavaScript, CSS, Dockerfile]
credibility_score: 72.0/100
date_processed: 2026-07-07
last_release: 2026-06-04
cover: attachments/banners/crawlee_banner.png

---

![banner](attachments/banners/crawlee_banner.png)

# crawlee

> **TL;DR:** Web scraping library for Node.js with Puppeteer/Playwright support, proxy rotation, and headful/headless modes.

**`apify/crawlee`** · ⭐ 24,532 · 🔧 TypeScript

## What is it?
Crawlee is a web scraping and browser automation library built for Node.js and TypeScript developers. It provides a high-level API to construct reliable web crawlers that can extract data from websites while handling complex scenarios like JavaScript-rendered content, dynamic pages, and anti-bot protections. The library integrates with multiple browser automation tools (Puppeteer, Playwright) as well as non-browser DOM parsers (Cheerio, JSDOM) and raw HTTP requests, giving users flexibility in how they interact with webpages.

Key features include support for both headful and headless Chrome modes, built-in proxy rotation to distribute load and avoid rate limits, and the ability to download various file types such as HTML, PDFs, images (JPG, PNG) directly during crawling. It also offers utilities for extracting data specifically tailored for AI/LLM pipelines, RAG systems, or GPT integrations, making it suitable for both traditional web scraping tasks and modern AI data pipelines.

The project is maintained by Apify, a well-known platform for web scraping and automation, which ensures active development, comprehensive documentation, and a large community of users (over 24k stars on GitHub). This backing provides confidence in its long-term reliability and compatibility with the Node.js ecosystem.

## How does it work?
Crawlee follows a modular architecture that combines browser automation, DOM parsing, and HTTP client capabilities into a single cohesive library. At its core is the crawler engine, which orchestrates navigation through websites, manages proxy rotation, and handles concurrency controls like request delays, retries, and timeouts. The library provides two primary modes: headful (full browser with JavaScript execution) and headless (browser without UI), allowing users to choose based on their scraping needs.

Under the hood, it offers adapters for Puppeteer and Playwright, enabling seamless control of Chrome/Chromium browsers, while also supporting Cheerio and JSDOM for static HTML parsing and JSDOM for JS-less document simulation. For cases where browser automation isn't required, crawlee can make raw HTTP requests directly, respecting headers, cookies, and other request options. All these mechanisms are wrapped in a TypeScript-friendly API that includes utilities for downloading files, extracting data, and handling anti-bot protections.

## Why is it important? (Core Value)
For a software engineer focused on AI agents, developer tools, and automation—particularly interested in self-hostable alternatives to SaaS products—Crawlee is highly relevant. It provides a robust, well-maintained library that can be easily integrated into personal or organizational data pipelines without relying on managed scraping services. Its support for proxy rotation and headless modes makes it suitable for building reliable scrapers that can operate in restricted network environments or scale across multiple sources.

Moreover, the fact that it is maintained by Apify—a platform known for its scraping infrastructure—and has a large community ensures that you get regular updates, documentation, and potential support if you encounter issues. This aligns with your interest in discovering tools that improve development workflow and in self-hostable software. You can use Crawlee to extract data specifically for AI/LLM pipelines, RAG systems, or GPT integrations, thereby directly supporting your objective of gathering high-quality training data or knowledge bases for your own models or agents.

## Key Features & Technologies
- Puppeteer
- Playwright
- Cheerio
- JSDOM
- proxy rotation
- headful/headless Chrome
- raw HTTP
- Node.js/TypeScript

## Difference from Others
Compared to other scraping libraries, Crawlee stands out by combining browser automation and DOM parsing into a single library with built-in proxy rotation and file download capabilities. While Puppeteer and Playwright focus solely on browser control, and Cheerio/Scrapy are purely for static HTML or Python-based scraping, Crawlee offers a unified API that works seamlessly across both headful and headless modes. It also provides specific utilities for AI/LLM data extraction, which is less common in generic scrapers. Additionally, its TypeScript-first design and integration with the Node.js ecosystem make it more ergonomic for JavaScript/TypeScript developers compared to Python-centric solutions like Scrapy or BeautifulSoup.

## 🏢 Organization & Credibility
- **Developer:** apify
- **Reputation:** Unknown
- **Stars:** 24,532
- **Forks:** 1527
- **Recent Activity:** 121 commits in 3 months
- **Credibility Score:** 72.0/100 (Average)
- **Languages:** TypeScript, MDX, JavaScript, CSS, Dockerfile
- **Last Release:** 2026-06-04
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
*Source: [GitHub](https://github.com/apify/crawlee)*
