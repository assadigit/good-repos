---
source: https://github.com/jarvis2f/telegram-files
aliases:
  - telegram-files
  - jarvis2f/telegram-files
tags: [java, typescript, telegram, docker, self-hosted, automation, downloader, nextjs, shadcn-ui, tdlib, vertx, unraid]
category: Scraping
stars: 2365
org: jarvis2f
primary_language: Java
languages: [Java, TypeScript, JavaScript, Python, Shell]
credibility_score: 50.0/100
date_processed: 2026-07-17
last_release: 2026-06-16
cover: attachments/banners/telegram-files_banner.png

---

![banner](attachments/banners/telegram-files_banner.png)

# telegram-files

> **TL;DR:** Self-hosted Telegram file downloader for continuous, stable, and unattended downloads.

**`jarvis2f/telegram-files`** · ⭐ 2,365 · 🔧 Java

## What is it?
Telegram Files is a self-hosted web application that provides seamless file downloading from Telegram channels and groups. Built with Next.js for the frontend and TDLib (Telegram Database Library) for backend integration, it allows users to manage and download files simultaneously across multiple Telegram accounts. The project emphasizes reliability with pause/resume functionality for long-running downloads, making it suitable for unattended operation.

## How does it work?
The application uses Next.js as its web framework with shadcn-ui components for the frontend interface. On the backend, it leverages TDLib to connect directly to Telegram servers and retrieve files from channels/groups. Docker is used for containerization, allowing straightforward deployment on infrastructure like Unraid or homelab setups. Vert.x appears to be involved in handling async operations or event loops, contributing to stable concurrent downloads across multiple accounts.

## Why is it important? (Core Value)
This project offers a self-hosted alternative to Telegram's native downloaders and various SaaS-based file extractors, which often rely on third-party APIs with rate limits or privacy concerns. For someone interested in homelab infrastructure and automation, it provides a reliable way to continuously monitor Telegram channels and groups for files, saving them locally without paying subscription fees. The multiple-account support means users can organize downloads by source, and the pause/resume capability ensures no files are lost during network interruptions—making it particularly valuable for unattended operation in a personal infrastructure setup.

## Key Features & Technologies
- Uses Next.js for frontend
- Integrates with TDLib Telegram API
- Docker containerization support
- Pause and resume downloads
- Multiple Telegram account management
- Self-hosted web UI with shadcn-ui

## Difference from Others
Unlike simple Telegram download bots or CLI tools that only handle direct messages, this project provides a full-featured web interface for managing ongoing downloads. Compared to other self-hosted scrapers, it specifically targets Telegram's media infrastructure via TDLib rather than generic HTTP scraping, offering more reliable access to Telegram channels and groups. The Docker/Unraid support also distinguishes it as infrastructure-ready rather than just a standalone script.

## 🏢 Organization & Credibility
- **Developer:** jarvis2f
- **Reputation:** Unknown
- **Stars:** 2,365
- **Forks:** 173
- **Recent Activity:** 10 commits in 3 months
- **Credibility Score:** 50.0/100 (Low)
- **Languages:** Java, TypeScript, JavaScript, Python, Shell
- **Last Release:** 2026-06-16
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
*Source: [GitHub](https://github.com/jarvis2f/telegram-files)*
