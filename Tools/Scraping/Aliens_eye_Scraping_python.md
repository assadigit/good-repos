---
source: https://github.com/arxhr007/Aliens_eye
aliases:
  - Aliens_eye
  - arxhr007/Aliens_eye
tags: [python, python, osint, social-media, ai, scraping, linux, python3, debain, information, information-gathering, termux]
category: Scraping
stars: 2025
org: arxhr007
primary_language: Python
languages: [Python, Dockerfile, url]
credibility_score: 54.5/100
date_processed: 2026-07-05
last_release: 2026-07-03
cover: attachments/banners/Aliens_eye_banner.png

---

![banner](attachments/banners/Aliens_eye_banner.png)

# Aliens_eye

> **TL;DR:** AI-powered OSINT scanner that detects usernames across 840+ social media platforms using ML-blended detection.

**`arxhr007/Aliens_eye`** · ⭐ 2,025 · 🔧 Python

## What is it?
Aliens_eye is an AI-powered OSINT tool designed to scan over 840 social media platforms asynchronously, using a blend of machine learning models and heuristic detection that incorporates structural signals like HTTP status codes, DOM shape, keywords, and fingerprinting. The project focuses on identifying usernames across these platforms efficiently through advanced detection methods.

The tool runs on Linux and supports Termux environments, making it suitable for self-hosted deployments or portable use on Android devices. It provides a command-line interface for scanning operations and can be integrated into larger automation pipelines or workflows that require multi-platform username discovery.

## How does it work?
The project uses Python scripts to make HTTP requests to each platform's API or web page, parsing responses for username indicators and detection signals. The ML component appears to be a local model trained on patterns of usernames across platforms, likely using TensorFlow or similar frameworks. Heuristic detection checks structural signals such as HTTP status codes, DOM shape (presence of specific HTML elements), keywords in response bodies, and fingerprinting techniques like user-agent analysis.

The asynchronous architecture suggests use of asyncio or multiprocessing to handle many platforms concurrently, enabling the 840+ platform scanning capability mentioned in highlights. This parallel processing approach allows for rapid coverage across all supported social media services.

## Why is it important? (Core Value)
This tool gives you a self-hosted OSINT capability for username scanning that can be integrated into AI agent workflows needing social media information gathering. It represents a fresh approach to scraping by blending ML detection with structural heuristics, potentially improving accuracy over pure heuristic tools.

For your specific interests in discovering developer productivity tools, this provides a novel scraping technique you might want to evaluate. The self-hosted nature aligns with your interest in alternatives to SaaS products, and the Termux/Linux support makes it suitable for homelab infrastructure or portable deployment scenarios.

## Key Features & Technologies
- 840+ platforms scanned asynchronously
- ML-blended detection with structural signals
- Python implementation
- Linux and Termux compatible
- OSINT-focused username scanner
- Heuristic detection (HTTP status, DOM shape, keywords)
- Self-hosted alternative to SaaS tools

## Difference from Others
Unlike Sherlock or Maigret which rely purely on heuristic matching of known username patterns, this project uses AI/ML detection blended with structural signals for higher accuracy across unknown accounts. It also runs entirely on Linux/ Termux making it self-hostable unlike proprietary services, and handles 840+ platforms simultaneously rather than sequentially.

## 🏢 Organization & Credibility
- **Developer:** arxhr007
- **Reputation:** Unknown
- **Stars:** 2,025
- **Forks:** 223
- **Recent Activity:** 22 commits in 3 months
- **Credibility Score:** 54.5/100 (Low)
- **Languages:** Python, Dockerfile, url
- **Last Release:** 2026-07-03
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
*Source: [GitHub](https://github.com/arxhr007/Aliens_eye)*
