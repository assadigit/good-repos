---
source: https://github.com/ashendilantha/stalkie
aliases:
  - stalkie
  - ashendilantha/stalkie
tags: [go, go, osint, scraping, proxy, headless-browser, url]
category: Scraping
stars: 88
org: ashendilantha
primary_language: Go
languages: [Go, url]
credibility_score: 41.0/100
date_processed: 2026-07-05

cover: attachments/banners/stalkie_banner.png

---

![banner](attachments/banners/stalkie_banner.png)

# stalkie

> **TL;DR:** Self-hosted OSINT tool that checks usernames across 13+ platforms with confidence scoring and proxy support.

**`ashendilantha/stalkie`** · ⭐ 88 · 🔧 Go

## What is it?
Stalkie is a social media OSINT (Open Source Intelligence) tool designed to find usernames across more than 13 platforms. Unlike simpler tools that only report binary found/not-found results, it provides confidence scoring (0–100) based on multiple signals including HTTP status codes, title matches, and body mentions. This nuanced approach helps users understand the reliability of each result rather than treating all hits as equal.

The tool is built with several smart features to handle real-world scraping challenges. It strips script tags before analysis to avoid false negatives from JS bundles on platforms like YouTube and TikTok. For sites that implement login walls (Instagram, LinkedIn), it detects when a profile page actually serves a login redirect instead of the real content and flags it appropriately rather than reporting it as found.

## How does it work?
Stalkie is written in Go and uses go-rod for headless browser rendering with Chromium. This allows it to handle JavaScript-heavy pages that don't work with plain HTTP requests. The architecture supports proxy routing (HTTP, SOCKS5, Tor by default on 127.0.0.1:9050) enabling stealth operations and bypassing IP-based blocks. It includes configurable concurrent workers with rate limiting, letting users balance between speed and stealth tradeoffs. Results can be exported in multiple formats including TXT, CSV, and JSON with full metadata preserved.

## Why is it important? (Core Value)
This project is particularly valuable for your interests in developer productivity tools, self-hosted software, and learning new approaches to scraping. Stalkie provides a self-contained, self-hostable alternative to commercial OSINT services, giving you full control over data handling and no reliance on SaaS products. The confidence scoring approach could be integrated into research workflows or automated pipelines for tracking brand mentions, user databases, or social media analysis. Since you're focused on automation and scraping, this tool directly aligns with your goal of learning new approaches to web data extraction and provides a practical foundation that could feed into larger agent systems or data orchestration projects.

## Key Features & Technologies
- Confidence scoring (0–100 based on multiple signals)
- Script-tag stripping before analysis
- Login wall detection for Instagram/LinkedIn
- Headless browser mode with go-rod
- Proxy & Tor support (HTTP, SOCKS5, Tor)
- Bulk input via file processing
- Multi-format export (TXT, CSV, JSON)
- Configurable concurrent workers with rate limiting

## Difference from Others
Compared to similar OSINT tools, Stalkie stands out for its confidence scoring rather than binary results, which provides more actionable intelligence. Many scraping tools don't handle login walls or strip script tags—features that prevent false positives and false negatives on modern platforms. The headless browser integration is particularly notable as it handles JS-heavy sites that many HTTP-only scrapers fail on. Additionally, the Tor/proxy support out of the box gives it stealth capabilities that most tools lack.

## 🏢 Organization & Credibility
- **Developer:** ashendilantha
- **Reputation:** Unknown
- **Stars:** 88
- **Forks:** 9
- **Recent Activity:** 12 commits in 3 months
- **Credibility Score:** 41.0/100 (Low)
- **Languages:** Go, url
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
*Source: [GitHub](https://github.com/ashendilantha/stalkie)*
