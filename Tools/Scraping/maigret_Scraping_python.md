---
source: https://github.com/soxoj/maigret
aliases:
  - maigret
  - soxoj/maigret
tags: [python, python, scraping, osint, cli, open-source, social-network, identification, socmint, sherlock, investigation, python3]
category: Scraping
stars: 35068
org: soxoj
primary_language: Python
languages: [Python, HTML, Go Template, Batchfile, Makefile]
credibility_score: 70.5/100
date_processed: 2026-07-08
last_release: 2026-07-01
cover: attachments/banners/maigret_banner.png

---

![banner](attachments/banners/maigret_banner.png)

# maigret

> **TL;DR:** Collects OSINT data from 3000+ social media sites into a unified dossier given a username.

**`soxoj/maigret`** · ⭐ 35,068 · 🔧 Python

## What is it?
Maigret is an open-source OSINT framework written in Python that aggregates data from over 3000 social media and website accounts to create a comprehensive profile of a person given a username. It provides a command-line interface for easy local installation and runs on Python 3.10+. The project has received 35,068 stars on GitHub, indicating strong community interest and adoption.

The tool is designed to help investigators, security professionals, and researchers gather information about individuals across multiple platforms in a single location. It outputs structured information such as usernames, profile URLs, follower counts, and other metadata from various social networks including Twitter/X, Instagram, TikTok, Reddit, and many others.

## How does it work?
Maigret is built as a Python package that runs locally via the CLI. It uses asynchronous HTTP requests to fetch data from multiple social platforms, parses responses with standard web scraping libraries, and stores results in structured formats like JSON or SQLite for easy consumption. The codebase is organized into modular scrapers for each platform, allowing users to add custom scrapers for additional sites.

The tool likely employs caching mechanisms to avoid excessive API rate limiting and includes support for various authentication methods (OAuth, cookies) depending on the target site's requirements.

## Why is it important? (Core Value)
Maigret solves the problem of fragmented OSINT data by unifying it into a single dossier; this is valuable for security researchers, journalists, or anyone needing to investigate individuals online. For you, it offers a self-hosted, open-source scraping framework that can be integrated into your own workflows, providing a reliable alternative to cloud-based OSINT services and aligning with your interest in self-hostable software and new approaches to scraping.

The tool is particularly useful for reconnaissance tasks that might feed into AI agents for data gathering, making it a solid foundation for building more sophisticated automated investigation pipelines. Its Python ecosystem ensures compatibility with many other tools you're already using.

## Key Features & Technologies
- Python 3.10+
- CLI interface
- Self-hosted
- Supports 3000+ social media sites
- Modular scraper architecture
- PyPI package
- Open-source (MIT license)

## Difference from Others
Sherlock is a popular OSINT tool that checks if a username exists across many platforms, but it focuses on detection rather than aggregating full profiles. Maigret goes beyond simple detection by collecting and consolidating data into a comprehensive dossier, offering more detailed information such as follower counts and profile URLs. Additionally, Maigret provides a CLI for easy local installation and is written in Python, making it straightforward to extend with custom scrapers.

## 🏢 Organization & Credibility
- **Developer:** soxoj
- **Reputation:** Unknown
- **Stars:** 35,068
- **Forks:** 2657
- **Recent Activity:** 201 commits in 3 months
- **Credibility Score:** 70.5/100 (Average)
- **Languages:** Python, HTML, Go Template, Batchfile, Makefile
- **Last Release:** 2026-07-01
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
*Source: [GitHub](https://github.com/soxoj/maigret)*
