---
source: https://github.com/vibheksoni/stealth-browser-mcp
aliases:
  - stealth-browser-mcp
  - vibheksoni/stealth-browser-mcp
tags: [python, python, mcp-server, nodriver, chrome-devtools, stealth-browser, ai-agent-tools, ai-tools, anthropic, anti-bot-bypass, automation-tools, browser-automation]
category: Agents
stars: 1460
org: vibheksoni
primary_language: Python
languages: [Python, JavaScript, Dockerfile, Shell, Batchfile]
credibility_score: 50.0/100
date_processed: 2026-07-05
last_release: 2026-02-10
cover: attachments/banners/stealth-browser-mcp_banner.png

---

![banner](attachments/banners/stealth-browser-mcp_banner.png)

# stealth-browser-mcp

> **TL;DR:** MCP-compatible AI agent for undetectable browser automation that bypasses Cloudflare and anti-bot systems.

**`vibheksoni/stealth-browser-mcp`** · ⭐ 1,460 · 🔧 Python

## What is it?
Stealth Browser MCP is an MCP-compatible AI agent designed for stealthy web automation. It leverages nodriver and Chrome DevTools Protocol to execute real browser instances that bypass Cloudflare, anti-bot systems, and social media blocks—ideal for research agents needing pixel-perfect UI cloning.

Built with FastMCP for modular architecture, it allows AI models to dynamically write network interception hooks and clone interfaces via simple chat prompts. The project emphasizes developer tools and self-hosted alternatives to SaaS scraping services.

A demo section shows live automation of blocked sites, while the toolbox provides ready-to-use MCP functions for integration with Claude or other LLM agents.

## How does it work?
The project implements an MCP server that exposes stealth browser automation as callable tools. AI agents invoke these tools through the Model Context Protocol, which streams responses back to the user interface. Under the hood, nodriver handles Chrome DevTools Protocol interactions with anti-detection techniques (e.g., headless mode disabled, randomized network fingerprints). FastMCP provides a modular framework for composing multiple automation steps into a single MCP call.

## Why is it important? (Core Value)
For a researcher focused on AI agents and MCP servers, this project directly addresses the need for self-hostable, undetectable browser automation that can be integrated into existing agent workflows. It offers a practical alternative to paid scraping services (e.g., ScrapingBee) by using nodriver's stealth capabilities—aligning with interests in developer productivity tools and homelab infrastructure. The MCP-compatible design means it can be chained with other agents or skills, enabling complex multi-step research tasks without relying on external APIs.

## Key Features & Technologies
- Uses nodriver
- Chrome DevTools Protocol
- FastMCP integration
- MCP-compatible server
- Bypasses Cloudflare and anti-bot systems
- Real browser automation instances
- Network interception hooks

## Difference from Others
Unlike generic stealth browsers or Selenium-based solutions, Stealth Browser MCP is purpose-built as an MCP server for AI agents. It explicitly compares to Playwright's MCP implementation in its documentation, highlighting that nodriver provides deeper stealth features (e.g., randomized user-agent strings, fingerprint spoofing) while maintaining compatibility with Claude and other LLMs via FastMCP's modular tool definitions.

## 🏢 Organization & Credibility
- **Developer:** vibheksoni
- **Reputation:** Unknown
- **Stars:** 1,460
- **Forks:** 223
- **Recent Activity:** 12 commits in 3 months
- **Credibility Score:** 50.0/100 (Low)
- **Languages:** Python, JavaScript, Dockerfile, Shell, Batchfile
- **Last Release:** 2026-02-10
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
*Source: [GitHub](https://github.com/vibheksoni/stealth-browser-mcp)*
