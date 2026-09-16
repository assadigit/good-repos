---
source: https://github.com/amaancoderx/npxskillui
aliases:
  - npxskillui
  - amaancoderx/npxskillui
tags: [typescript, node, cli, scraping, design-systems, claude, url]
category: LLM-Tools
stars: 975
org: amaancoderx
primary_language: TypeScript
languages: [TypeScript, url]
credibility_score: 42.0/100
date_processed: 2026-07-05

cover: attachments/banners/npxskillui_banner.png

---

![banner](attachments/banners/npxskillui_banner.png)

# npxskillui

> **TL;DR:** CLI that extracts design systems from websites or codebases for Claude Code.

**`amaancoderx/npxskillui`** · ⭐ 975 · 🔧 TypeScript

## What is it?
SkillUI is a command-line utility that performs static analysis on any website, Git repository, or local codebase to extract its complete design system—including colors, typography, spacing, animations, components, and screenshots—into a folder ready for Claude Code. By crawling the target source and packaging the results, it enables developers to open the output folder, invoke Claude, and ask it to build a UI that already knows the exact design language.

The tool requires Node.js ≥18 and is MIT-licensed. It's positioned as a pure static analysis solution with no AI involvement and no API keys needed, making it lightweight and privacy-friendly compared to alternatives.

## How does it work?
SkillUI runs as a Node.js CLI that parses HTML/CSS/JS assets and uses static analysis (no AI) to infer design tokens. It likely employs standard web scraping libraries, CSS parsers, and possibly regex to pull colors, fonts, spacing units, and other UI specifications from the source files, then organizes them into a structured folder. The output is written in a format that Claude Code can read automatically when invoked from that directory.

## Why is it important? (Core Value)
SkillUI offers a self-hosted, zero-API-key approach to reverse-engineering design systems, fitting the user's goal of curating self-hostable alternatives to SaaS products. By providing a pure static analysis tool for extracting UI specifications, it directly supports the user's interests in developer productivity tools and scraping/automation techniques. As a CLI that works seamlessly with Claude Code, it also aligns with the user's focus on AI agents and developer tools.

## Key Features & Technologies
- Node.js CLI
- pure static analysis (no AI)
- extracts design tokens (colors, typography, spacing, animations, components, screenshots)
- outputs a folder Claude Code reads automatically
- MIT license

## Difference from Others
Unlike design system extraction tools that rely on AI or require API keys, SkillUI performs only static analysis, making it faster, cheaper, and more privacy-friendly. Compared to generic web scrapers, it focuses specifically on UI design tokens rather than raw data. It also bridges the gap between design systems and LLM agents by packaging results in a format Claude Code can consume directly.

## 🏢 Organization & Credibility
- **Developer:** amaancoderx
- **Reputation:** Unknown
- **Stars:** 975
- **Forks:** 103
- **Recent Activity:** 7 commits in 3 months
- **Credibility Score:** 42.0/100 (Low)
- **Languages:** TypeScript, url
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
*Source: [GitHub](https://github.com/amaancoderx/npxskillui)*
