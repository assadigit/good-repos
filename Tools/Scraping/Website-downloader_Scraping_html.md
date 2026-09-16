---
source: https://github.com/AhmadIbrahiim/Website-downloader
aliases:
  - Website-downloader
  - AhmadIbrahiim/Website-downloader
tags: [html, node, scraping, wget, self-hosted, offline, offline-web-pages, downloader, scraper, assets, javascript, handlebars]
category: Scraping
stars: 3539
org: AhmadIbrahiim
primary_language: HTML
languages: [HTML, JavaScript, Handlebars, CSS, url]
credibility_score: 46.0/100
date_processed: 2026-07-07

cover: attachments/banners/Website-downloader_banner.png

---

![banner](attachments/banners/Website-downloader_banner.png)

# Website-downloader

> **TL;DR:** Self-hosted website archiver that downloads complete pages with assets via wget and compresses them for offline browsing.

**`AhmadIbrahiim/Website-downloader`** · ⭐ 3,539 · 🔧 HTML

## What is it?
Website-downloader is a Node.js utility that recursively fetches entire websites, including all linked resources like JavaScript, CSS, images, and fonts. It uses wget with specific flags to mirror the site, convert links to relative paths, adjust file extensions based on content type, and download page prerequisites (like stylesheets). The tool then packages these assets into a compressed archive using archiver, delivering a complete offline copy of the target domain.

## How does it work?
The application leverages wget for the heavy lifting of recursive downloading, utilizing flags like --mirror, --convert-links, and --page-requisites to ensure all necessary assets are captured. It pipes wget's output into archiver (likely tar or zip) to create a single downloadable file. The README indicates it runs via Node.js scripts that invoke the system wget binary, making it a lightweight, dependency-minimal solution.

## Why is it important? (Core Value)
This project aligns directly with your interest in self-hostable alternatives to SaaS products and automation workflow orchestration. By providing a lightweight, Node.js-based scraper that archives websites offline, it offers a practical way to capture web content without relying on external services like Archive.org. You can deploy it in your homelab or container environment to automate scraping specific domains for research, backups, or personal archives. Its use of wget ensures compatibility across systems, and the compressed output makes storage and retrieval efficient.

## Key Features & Technologies
- Uses wget
- Compresses with archiver
- Node.js
- Self-hosted
- Offline browsing
- Recursive download
- Converts links to relative

## Difference from Others
Unlike Archive.org, which is a massive, centralized service, this tool lets you self-host the archiving logic locally or on any server. It's more lightweight and scriptable than browser-based scrapers, offering better control over what gets downloaded (via wget flags). Compared to other Node.js scrapers, its focus on full-site mirroring with asset preservation makes it distinct for offline use cases.

## 🏢 Organization & Credibility
- **Developer:** AhmadIbrahiim
- **Reputation:** Unknown
- **Stars:** 3,539
- **Forks:** 949
- **Recent Activity:** 4 commits in 3 months
- **Credibility Score:** 46.0/100 (Low)
- **Languages:** HTML, JavaScript, Handlebars, CSS, url
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
*Source: [GitHub](https://github.com/AhmadIbrahiim/Website-downloader)*
