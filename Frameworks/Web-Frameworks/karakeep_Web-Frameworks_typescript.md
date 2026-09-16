---
source: https://github.com/karakeep-app/karakeep
aliases:
  - karakeep
  - karakeep-app/karakeep
tags: [typescript, nextjs, react-native, ollama, self-hosted, bookmarks, bookmarks-manager, read-it-later, bookmark-manager, shell, javascript, astro]
category: Web-Frameworks
stars: 27500
org: karakeep-app
primary_language: TypeScript
languages: [TypeScript, Shell, JavaScript, Astro, Dockerfile]
credibility_score: 70.5/100
date_processed: 2026-07-17
last_release: 2026-05-08
cover: attachments/banners/karakeep_banner.png

---

![banner](attachments/banners/karakeep_banner.png)

# karakeep

> **TL;DR:** Self-hostable bookmark manager with AI tagging and summarization.

**`karakeep-app/karakeep`** · ⭐ 27,500 · 🔧 TypeScript

## What is it?
Karakeep (formerly Hoarder) is a self-hostable bookmark-everything application designed for data hoarders who want privacy and control over their stored information. It allows users to bookmark links, take simple notes, and store images and PDFs, with automatic fetching of metadata like titles, descriptions, and images. The app also supports sorting bookmarks into lists, collaboration on shared lists, and full-text search across all stored content.

What sets Karakeep apart is its integration of AI capabilities directly into the bookmarking workflow. It uses LLM-based automatic tagging and summarization to enrich bookmark entries with relevant metadata without manual effort. The project also aims to be agent-friendly, supporting LLM agents (e.g., OpenClaw, Hermes) through prompt orchestration, making it suitable for building automated workflows on top of stored bookmarks and notes.

## How does it work?
The application is built using NextJS for the web interface and React Native for mobile support, with a backend that likely provides an API for storing and retrieving bookmark data. AI tagging and summarization appear to leverage local LLM models through Ollama integration, giving users offline capability and privacy by running inference on their own hardware. Full-text search is probably implemented via a vector database or an indexable text store (e.g., SQLite, PostgreSQL with full-text extensions). Collaboration features likely use WebSockets or real-time data sync mechanisms to enable multiple users to edit shared lists.

The project emphasizes self-hostability, meaning all components can be deployed on personal infrastructure, supporting the homelab and privacy-focused user base. Translation support via Weblate indicates community-driven localization efforts.

## Why is it important? (Core Value)
For a software engineer and researcher interested in AI agents, developer tools, and automation, Karakeep offers significant value as a self-hostable alternative to SaaS bookmark managers like Raindrop.io or Pocket. It directly addresses the objective of finding self-hosted alternatives to proprietary services, giving full control over data storage and enabling integration into personal knowledge bases (e.g., Obsidian vaults). The AI tagging and summarization capabilities align with interests in LLM tooling and prompt engineering, allowing the user to experiment with local models via Ollama without relying on external APIs.

Moreover, its agent-friendly design means it could serve as a data store for automation workflows or MCP servers that need persistent context (bookmarks, notes) to orchestrate tasks. This positions Karakeep not just as a bookmark manager but as a foundational layer for building more complex agent systems, making it highly relevant to the user's curatorial goals and research interests.

## Key Features & Technologies
- Self-hostable NextJS app
- AI tagging via ollama
- Full text search
- Collaborative lists
- Automatic metadata fetching
- React Native mobile support
- Agent-friendly environment

## Difference from Others
Unlike SaaS bookmark managers (Raindrop, Pocket), Karakeep is open-source and self-hostable, giving full control over data privacy and deployment. It also includes built-in AI summarization and tagging, which most bookmark tools lack entirely. Many alternatives rely on external LLM APIs; here, Ollama support enables local models, preserving offline capability. Compared to generic note-taking apps, Karakeep is purpose-built for bookmarks with structured lists and search, making it a more specialized yet privacy-first solution.

## 🏢 Organization & Credibility
- **Developer:** karakeep-app
- **Reputation:** Unknown
- **Stars:** 27,500
- **Forks:** 1352
- **Recent Activity:** 152 commits in 3 months
- **Credibility Score:** 70.5/100 (Average)
- **Languages:** TypeScript, Shell, JavaScript, Astro, Dockerfile
- **Last Release:** 2026-05-08
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
*Source: [GitHub](https://github.com/karakeep-app/karakeep)*
