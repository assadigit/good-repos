---
source: https://github.com/tandpfun/wardrobe
aliases:
  - wardrobe
  - tandpfun/wardrobe
tags: [javascript, nodejs, automation, ai, clothes, self-hosted, css, html, url]
category: Automation
stars: 864
org: tandpfun
primary_language: JavaScript
languages: [JavaScript, CSS, HTML, url]
credibility_score: 45.0/100
date_processed: 2026-07-17

cover: attachments/banners/wardrobe_banner.png

---

![banner](attachments/banners/wardrobe_banner.png)

# wardrobe

> **TL;DR:** AI-powered wardrobe manager that imports clothes from images and generates modeled outfit ideas using Codex skills.

**`tandpfun/wardrobe`** · ⭐ 864 · 🔧 JavaScript

## What is it?
Wardrobe is a Node.js application designed to help users manage their personal clothing collection using AI-based image processing. The project extracts and organizes clothes from images, leveraging what appears to be some form of gpt-image technology for visual analysis and item identification. It includes two Codex skills: one imports clothes from local directories and generates modeled photos of individual items, while the other styles complete outfits and creates a modeled lookbook.

## How does it work?
The application runs locally on Node.js (version 22+), requiring an OpenAI API key in `.env` to enable the importer functionality. Users provide a reference PNG image of themselves at `data/model-reference.png`, which is used for modeling clothes. When Codex skill prompts are executed, the system processes images, reviews cutouts and generated photos, then writes structured data to `data/library.json` and `data/imported/`. The workflow appears to involve image analysis, object recognition or extraction, and generation of modeled outfit representations.

## Why is it important? (Core Value)
This project aligns well with your interest in self-hosted alternatives and AI tooling. Wardrobe offers a privacy-conscious way to manage personal wardrobe data without relying on commercial services—everything runs locally, and you control the API keys used for image processing. As someone focused on developer productivity tools and automation, this could serve as a useful example of how LLM-powered agents can be applied to non-trivial domain tasks beyond code or general research. Additionally, it may provide a practical use case for exploring MCP-style integrations where Codex skills act as the agent interface.

## Key Features & Technologies
- Node.js (v22+)
- Codex skills integration
- gpt-image based processing
- MIT license
- Local-first design

## Difference from Others
Unlike commercial wardrobe apps that rely on cloud-based image recognition services, Wardrobe is open-source and self-hosted, giving you full control over data privacy. It also differs from general-purpose AI agents by focusing on a specific domain task—managing clothing collections—with specialized skills rather than being a general framework or agent platform.

## 🏢 Organization & Credibility
- **Developer:** tandpfun
- **Reputation:** Unknown
- **Stars:** 864
- **Forks:** 126
- **Recent Activity:** 9 commits in 3 months
- **Credibility Score:** 45.0/100 (Low)
- **Languages:** JavaScript, CSS, HTML, url
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
*Source: [GitHub](https://github.com/tandpfun/wardrobe)*
