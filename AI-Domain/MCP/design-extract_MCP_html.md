---
source: "https://github.com/Manavarya09/design-extract"
aliases:
  - design-extract
  - Manavarya09/design-extract

tags: [html, javascript, node, mcp, design-tokens, playwright, ai, claude-code-plugin, cli, css, design-system, npx]
category: "MCP"
stars: 4101
org: "Manavarya09"
primary_language: HTML
languages: [HTML, JavaScript, CSS, Swift, Dart]
credibility_score: 62.0/100
date_processed: 2026-09-16
last_release: 2026-08-31
cover: attachments/banners/design-extract_banner.png

---

![banner](attachments/banners/design-extract_banner.png)

# design-extract

> **TL;DR:** One-command extractor for website design systems; outputs DTCG tokens and emits iOS, Android, Flutter, Tailwind, Figma, shadcn/ui.

**`Manavarya09/design-extract`** · ⭐ 4,101 · 🔧 HTML

## What is it?
design-extract is an open-source Node.js CLI and MCP tool that extracts a live website’s complete design system with one command. It targets developers who need to turn an existing site into portable design tokens and code-ready assets rather than relying on screenshots, manual inspection, or raw CSS dumps.

The project produces DTCG-compliant tokens organized into primitive, semantic, and composite layers, then emits them into multiple destinations: iOS SwiftUI, Android Compose, Flutter, WordPress, Tailwind v4, Figma variables, and shadcn/ui. It also includes a CSS health audit and WCAG remediation guidance, making the extracted system useful for both design handoff and accessibility work.

A key part of the project is its MCP server for Claude Code, Cursor, and Windsurf, allowing AI coding agents to consume the extracted token model directly while generating or refactoring UI code. It is MIT licensed, runs on Node 20+, and uses Playwright to inspect rendered web pages.

## How does it work?
The tool is built as a Node.js CLI around browser automation with Playwright. When run against a website, it renders the page, reads computed styles and CSS declarations, and infers reusable design values such as colors, typography, spacing, radii, shadows, and component-level visual properties. Those raw observations are normalized into DTCG token groups instead of being emitted as one-off CSS rules.

Once tokens exist, a set of emitters converts the same source model into target formats for mobile, web, and design tools. The MCP server wraps this extraction and token pipeline so agents can request or use the design system inside coding workflows, while optional audits surface CSS quality and WCAG accessibility issues. A Chrome extension is also listed as part of the project’s interface surface.

## Why is it important? (Core Value)
For a developer focused on AI agents, MCP servers, and self-hostable tooling, this project is useful because it turns web scraping into an agent-friendly design asset pipeline. Instead of manually copying colors or prompting a model with screenshots, the CLI can be run locally and then exposed to Claude Code, Cursor, or Windsurf through MCP, giving agents a structured token context for design-to-code tasks.

It also fits the user’s interest in developer productivity, automation, and accessibility by adding CSS health and WCAG remediation to the same workflow. Because it is MIT licensed and Node-based, it can be adopted as a local utility or integrated into agent workflows without relying on a SaaS design extraction service.

## Key Features & Technologies
- One-command CLI extraction of a website’s complete design system
- DTCG token output with primitive, semantic, and composite layers
- Multi-platform emitters for iOS SwiftUI, Android Compose, Flutter, WordPress, Tailwind v4, Figma variables, and shadcn/ui
- MCP server for Claude Code, Cursor, and Windsurf
- Uses Playwright and Node 20+ to inspect rendered web pages
- Includes CSS health audit and WCAG accessibility remediation

## Difference from Others
Compared with generic CSS scrapers or design-token exporters, design-extract combines live-site extraction, DTCG normalization, multi-framework code emission, and AI-agent integration in one workflow. It is not only a token file generator; the same extracted model can be consumed by MCP-enabled coding agents, which makes it more directly useful for design-to-code automation.

Its accessibility angle also differentiates it from many design-system extractors: after capturing the visual language, it audits CSS health and suggests WCAG remediation, so the output is not just portable but closer to production standards. The project’s breadth—CLI, MCP server, emitters, and Chrome extension—makes it a more complete local pipeline than single-purpose token tools.

## 🏢 Organization & Credibility
- **Developer:** Manavarya09
- **Reputation:** Unknown
- **Stars:** 4,101
- **Forks:** 349
- **Recent Activity:** 166 commits in 3 months
- **Credibility Score:** 62.0/100 (Average)
- **Languages:** HTML, JavaScript, CSS, Swift, Dart
- **Last Release:** 2026-08-31
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
*Source: [GitHub](https://github.com/Manavarya09/design-extract)*
