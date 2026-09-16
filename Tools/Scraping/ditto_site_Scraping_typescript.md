---
source: https://github.com/ion-design/ditto.site
aliases:
  - ditto.site
  - ion-design/ditto.site
tags: [typescript, typescript, scraping, nextjs, vite, mcp, html, javascript, python, dockerfile]
category: Scraping
stars: 212
org: ion-design
primary_language: TypeScript
languages: [TypeScript, HTML, JavaScript, Python, Dockerfile]
credibility_score: 54.0/100
date_processed: 2026-07-07

cover: attachments/banners/ditto_site_banner.png

---

![banner](attachments/banners/ditto_site_banner.png)

# ditto.site

> **TL;DR:** Clones any public URL into a deterministic Next.js or Vite React app using a capture-to-code pipeline.

**`ion-design/ditto.site`** · ⭐ 212 · 🔧 TypeScript

## What is it?
ditto.site is a self-hostable TypeScript service that takes any public web URL and captures exactly what the browser rendered, then emits a deterministic Next.js App Router or Vite React project. It is not an LLM-powered page author; it is a capture-to-code pipeline that guarantees byte-stable output from the same frozen capture input.

The service offers both a REST API (https://api.ditto.site) and an MCP server endpoint for integration with AI agents or workflow orchestrators. It includes a verified-email signup flow and key generation at https://www.ditto.site/api-key, making it easy to set up self-hosted instances without needing an existing repository or the site's source code.

Because it works with modern Node.js (>=20) and is MIT-licensed, ditto.site fits well into homelab and developer tool stacks, providing a reliable way to archive or clone any live website into a fully functional TypeScript app without relying on proprietary SaaS tools.

## How does it work?
The core pipeline runs inside a Node.js environment and uses headless browsers to fetch the target URL, wait for full render, capture the DOM, CSS, JavaScript, and assets exactly as seen in the browser. This frozen capture is stored deterministically so that any subsequent run yields identical output.

The captured data is then transformed into a Next.js App Router or Vite React project, depending on the requested target. The transformation is purely syntactic: it generates component files, routes, and assets that replicate the visual layout, ensuring that the generated code can be built and deployed without further modifications.

## Why is it important? (Core Value)
ditto.site directly addresses the user's interest in self-hostable alternatives to SaaS tools by providing a deterministic way to clone any public site into a TypeScript app without needing the original source code. This is valuable for building offline archives, custom UIs, or integrating live web content into internal dashboards—tasks that often require scraping but benefit from a reproducible pipeline rather than ad-hoc scripts.

The inclusion of an MCP server endpoint means ditto.site can be invoked by AI agents (e.g., a research agent that needs to fetch a page and then generate code) or workflow orchestrators, aligning with the user's objective to discover AI agent frameworks and MCP servers. Because the service is MIT-licensed and runs on Node.js, it fits naturally into homelab stacks and can be self-hosted alongside other developer tools, making it a credible addition to the user's Obsidian vault under a "Tools" or "Infrastructure" domain.

## Key Features & Technologies
- Deterministic capture-to-code pipeline
- Generates Next.js App Router projects
- Vite React build option
- REST API endpoint
- MCP server integration
- MIT license
- Node.js >=20

## Difference from Others
Compared to generic web scrapers like Puppeteer or Playwright, ditto.site goes beyond data extraction—it reconstructs the entire visual layout into a fully functional Next.js/Vite React codebase, offering a deterministic clone rather than a raw HTML dump. This distinguishes it from tools like web-to-html converters that output static HTML, which lack the TypeScript scaffolding and routing needed for modern web apps.

Unlike LLM-powered page generators that produce hallucinated content, ditto.site is a capture-to-code pipeline where the same frozen capture yields byte-stable output, making it more reliable for archival or offline use cases. Its MCP server also enables direct integration with AI agents, whereas many scrapers lack any programmable interface.

## 🏢 Organization & Credibility
- **Developer:** ion-design
- **Reputation:** Unknown
- **Stars:** 212
- **Forks:** 21
- **Recent Activity:** 68 commits in 3 months
- **Credibility Score:** 54.0/100 (Low)
- **Languages:** TypeScript, HTML, JavaScript, Python, Dockerfile
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
*Source: [GitHub](https://github.com/ion-design/ditto.site)*
