---
source: https://github.com/sherlock-project/sherlock
aliases:
  - sherlock
  - sherlock-project/sherlock
tags: [python, python, scraping, osint, cli, cybersecurity, reconnaissance, linux, sherlock, python3, redteam, tools]
category: Scraping
stars: 87926
org: sherlock-project
primary_language: Python
languages: [Python, Dockerfile, Shell, url]
credibility_score: 60.0/100
date_processed: 2026-08-02
last_release: 2025-09-16
cover: attachments/banners/sherlock_banner.png

---

![banner](attachments/banners/sherlock_banner.png)

# sherlock

> **TL;DR:** Hunts social media accounts by username across 400+ networks using automated scraping.

**`sherlock-project/sherlock`** · ⭐ 87,926 · 🔧 Python

## What is it?
Sherlock is an open-source Python CLI tool that hunts down social media accounts by username across over 400 social networks. The project provides a lightweight, scriptable way to discover and aggregate user presence across platforms like Twitter, Instagram, GitHub, LinkedIn, and many others. It supports installation via pipx, Docker, or package managers, making it easy to integrate into existing workflows.

The tool is designed for OSINT investigations, account enumeration tasks, and security research. By automating the process of checking each platform for a given username, Sherlock removes the manual effort required to search dozens of sites individually. Its modular architecture allows contributors to add support for new platforms or refine detection logic for existing ones.

## How does it work?
Sherlock operates by programmatically querying the profile lookup endpoints of hundreds of social media websites. Each platform is handled by a dedicated module that sends HTTP requests (often with appropriate headers and user-agents) to retrieve the target's profile page. The returned HTML is parsed—typically using libraries like BeautifulSoup or regex—to extract key identifiers such as usernames, profile URLs, or account status. Results are then aggregated into a single output list.

The project is written in Python 3 and relies on a modular structure where each supported network corresponds to a separate file or function. This design enables the community to contribute new platform handlers or improve existing ones. Installation methods like pipx, Docker, or dnf ensure users can run Sherlock without needing to manage dependencies manually.

## Why is it important? (Core Value)
For a software engineer and researcher focused on AI agents, developer tools, and automation, Sherlock offers a reliable, self-hosted way to perform OSINT data gathering without depending on commercial SaaS platforms. Its open-source nature lets you audit the scraping logic for security and privacy concerns, which aligns with your interest in self-hostable alternatives and homelab infrastructure. The CLI interface and Docker support make it easy to integrate into larger automation pipelines or combine with other tools (e.g., storing results in a database or feeding them into an AI agent that performs deeper analysis).

Additionally, Sherlock's active community and clear contribution guidelines mean it will likely stay updated as new social networks emerge, providing long-term value for ongoing research projects. Its deterministic scraping approach also complements AI-driven workflows by supplying structured data sources that can be further processed or analyzed.

## Key Features & Technologies
- Python 3 CLI
- Automated web scraping across 400+ platforms
- Docker support for containerized deployment
- Modular architecture for easy platform additions
- Open-source with community contributions

## Difference from Others
While tools like Maltego or SpiderFoot provide broader OSINT capabilities, Sherlock is specifically focused on username-based hunting across many social networks. It's lightweight and CLI-first, making it ideal for scripting into automated workflows rather than a full-featured SIEM-style platform. Compared to AI-driven discovery agents, Sherlock uses deterministic HTTP requests and HTML parsing—no LLMs or probabilistic ranking involved—ensuring reproducible results. This makes it a solid complement to AI tools that might need structured input data.

## 🏢 Organization & Credibility
- **Developer:** sherlock-project
- **Reputation:** Unknown
- **Stars:** 87,926
- **Forks:** 10323
- **Recent Activity:** 10 commits in 3 months
- **Credibility Score:** 60.0/100 (Average)
- **Languages:** Python, Dockerfile, Shell, url
- **Last Release:** 2025-09-16
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
*Source: [GitHub](https://github.com/sherlock-project/sherlock)*
