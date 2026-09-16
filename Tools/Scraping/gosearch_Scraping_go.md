---
source: https://github.com/ibnaleem/gosearch
aliases:
  - gosearch
  - ibnaleem/gosearch
tags: [go, golang, osint, username-search, cli, security, digital-footprint, digital-footprint-lookup, osint-framework, osint-reconnaissance, osint-resources, osint-tool]
category: Scraping
stars: 3625
org: ibnaleem
primary_language: Go
languages: [Go, url]
credibility_score: 56.0/100
date_processed: 2026-08-19
last_release: 2026-06-06
cover: attachments/banners/gosearch_banner.png

---

![banner](attachments/banners/gosearch_banner.png)

# gosearch

> **TL;DR:** Go-based OSINT CLI that concurrently searches a username across 300+ websites to map a digital footprint.

**`ibnaleem/gosearch`** · ⭐ 3,625 · 🔧 Go

## What is it?
GoSearch is an open-source OSINT tool written in Go that searches a username across more than 300 websites to discover a person's digital footprint. It is intended for security researchers, penetration testers, and OSINT practitioners who need to locate social media profiles and online accounts from a username.

The project provides a single CLI binary that automates the repetitive process of checking each site manually. It is maintained with community contributions and emphasizes broad website coverage for username reconnaissance.

## How does it work?
GoSearch operates as a standalone Go binary installed from the repository. It uses Go's concurrency model to issue parallel HTTP requests to a maintained set of website endpoints for a given username. The project relies on contributors to expand and maintain website coverage, and the README emphasizes that the binary performs the searching work for the user.

## Why is it important? (Core Value)
GoSearch solves the time-consuming problem of manually searching many websites for a username. For the user described, it is valuable as a self-hosted, open-source CLI that can be run locally without relying on SaaS OSINT platforms. It also serves as a practical reference for building concurrent web scraping and username enumeration workflows, which can be adapted into automation pipelines or AI agent skills for information gathering.

## Key Features & Technologies
- Go-based CLI binary
- Searches usernames across 300+ websites
- Uses concurrent HTTP requests
- OSINT username reconnaissance
- Installable via go install
- Community-maintained website coverage

## Difference from Others
Compared with Sherlock and similar username lookup tools, GoSearch is a Go-based alternative focused on a single lightweight binary and parallel searching. It targets the same username discovery problem but positions itself as a self-contained tool for OSINT and red teaming workflows. Its broad website coverage and community-driven maintenance make it a practical alternative to other username checkers.

## 🏢 Organization & Credibility
- **Developer:** ibnaleem
- **Reputation:** Unknown
- **Stars:** 3,625
- **Forks:** 324
- **Recent Activity:** 39 commits in 3 months
- **Credibility Score:** 56.0/100 (Low)
- **Languages:** Go, url
- **Last Release:** 2026-06-06
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
*Source: [GitHub](https://github.com/ibnaleem/gosearch)*
