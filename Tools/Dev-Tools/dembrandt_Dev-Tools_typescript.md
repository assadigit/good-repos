---
source: https://github.com/dembrandt/dembrandt
aliases:
  - dembrandt
  - dembrandt/dembrandt
tags: [typescript, nodejs, cli, design-systems, mcp, playwright, design-tokens, frontend, reverse-engineering, productivity, css, design-engineering]
category: Dev-Tools
stars: 2082
org: dembrandt
primary_language: TypeScript
languages: [TypeScript, JavaScript, HTML, url]
credibility_score: 62.0/100
date_processed: 2026-07-05
last_release: 2026-07-03
cover: attachments/banners/dembrandt_banner.png

---

![banner](attachments/banners/dembrandt_banner.png)

# dembrandt

> **TL;DR:** CLI tool that reverse-engineers any website's design system into CSS tokens in seconds.

**`dembrandt/dembrandt`** · ⭐ 2,082 · 🔧 TypeScript

## What is it?
Dembrandt is a CLI application that extracts a website's visual design system into structured design tokens—including logo, colors, typography, borders, and more—in just a few seconds. It operates as a single-command tool designed for rapid reverse-engineering of any web site's design language.

The core functionality centers on scraping and analyzing a target website to identify its design elements: color palettes, font families and weights, border styles, logo assets, and other visual tokens. These are then output in an organized format that can be consumed by developers or designers for consistent implementation across projects.

## How does it work?
The tool is built as a Node.js CLI application using Playwright for browser automation to scrape the target website. It visits the provided URL, inspects the DOM and CSS to identify design elements, and extracts them into structured JSON format representing design tokens.

Dembrandt also includes an MCP (Model Context Protocol) server component (dembrandt-mcp) that exposes tools like get_design_tokens, get_color_palette, and get_typography. This allows AI agents and LLM-based workflows to call Dembrandt programmatically—for example, asking Claude Code or Cursor to "extract the color palette from dembrandt.com" will invoke the tool automatically.

## Why is it important? (Core Value)
For a software engineer and researcher focused on AI agents, developer tools, and automation, Dembrandt addresses multiple objectives. It provides a reliable MCP server that can be integrated directly into agent workflows, supporting reverse-engineering of existing websites without manual inspection.

The tool also aligns with interests in productivity and self-hostable alternatives: it's open-source, runs locally via npm, and can be added to any MCP-compatible client (Claude Code, Cursor, Windsurf). For developers building design systems or auditing existing sites, it accelerates the design-to-code workflow by extracting tokens programmatically rather than manually inspecting stylesheets.

## Key Features & Technologies
- Node.js CLI tool
- Uses Playwright for web scraping
- Extracts design tokens (logo, colors, typography, borders)
- MCP server integration (Claude Code, Cursor, Windsurf)
- Outputs structured JSON design tokens
- Reverse-engineering focused
- Supports design audits

## Difference from Others
Dembrandt differs from other design token tools in several key ways. Most existing solutions are framework-specific (Tailwind, Styled Components) or require manual inspection of a site's CSS. Dembrandt is framework-agnostic—it works with any website—and uses Playwright for deep extraction rather than simple style parsing.

Unlike UI auditing libraries that focus on accessibility or contrast analysis, Dembrandt concentrates on reverse-engineering design systems into usable tokens. It also stands out as one of the few tools offering MCP server integration, making it immediately actionable within AI agent workflows.

## 🏢 Organization & Credibility
- **Developer:** dembrandt
- **Reputation:** Unknown
- **Stars:** 2,082
- **Forks:** 204
- **Recent Activity:** 156 commits in 3 months
- **Credibility Score:** 62.0/100 (Average)
- **Languages:** TypeScript, JavaScript, HTML, url
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
*Source: [GitHub](https://github.com/dembrandt/dembrandt)*
