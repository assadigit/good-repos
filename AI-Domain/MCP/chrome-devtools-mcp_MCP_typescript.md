---
source: "https://github.com/ChromeDevTools/chrome-devtools-mcp"
aliases:
  - chrome-devtools-mcp
  - ChromeDevTools/chrome-devtools-mcp

tags: [typescript, mcp, chrome-devtools, puppeteer, browser-automation, performance-tracing, mcp-server, browser, chrome, debugging, devtools, javascript]
category: "MCP"
stars: 52121
org: "ChromeDevTools"
primary_language: TypeScript
languages: [TypeScript, JavaScript, HTML, url]
credibility_score: 69.0/100
date_processed: 2026-09-16
last_release: 2026-09-08
cover: attachments/banners/chrome-devtools-mcp_banner.png

---

![banner](attachments/banners/chrome-devtools-mcp_banner.png)

# chrome-devtools-mcp

> **TL;DR:** MCP server giving AI coding agents full Chrome DevTools control for debugging, performance tracing, and browser automation via Puppeteer.

**`ChromeDevTools/chrome-devtools-mcp`** · ⭐ 52,121 · 🔧 TypeScript

## What is it?
chrome-devtools-mcp is an official MCP (Model Context Protocol) server from the ChromeDevTools organization that bridges AI coding agents—such as Claude, Cursor, Copilot, or Antigravity—to a live Chrome browser instance. It exposes the full power of Chrome DevTools to these agents, enabling them to record performance traces, extract actionable insights, analyze network requests, capture screenshots, and inspect console messages with source-mapped stack traces. The project also ships a standalone CLI so developers can use its capabilities without an MCP client.

Built on top of Puppeteer for reliable browser automation (with automatic waiting for action results) and the Chrome DevTools Protocol for deep performance and debugging data, the server turns any MCP-compatible coding assistant into a capable browser debugger and performance analyst. It is distributed as an npm package and maintained by the team behind Chrome's DevTools frontend.

## How does it work?
The project runs as an MCP server that registers a set of tools (browser control, network inspection, screenshot capture, console reading, performance tracing) which coding agents call over the Model Context Protocol. Under the hood it drives a real Chrome instance through Puppeteer for automation and action-result waiting, while tapping into the DevTools Protocol to collect traces, CDP network events, and console output with source maps. A lightweight CLI wrapper is provided so the same toolset can be invoked from a terminal without an MCP client.

Because it speaks the standard MCP protocol, any agent runtime that supports MCP tool-calling (Claude Code, Cursor, Copilot, etc.) can discover and invoke these tools dynamically, eliminating custom browser-automation glue code in agent prompts.

## Why is it important? (Core Value)
For a software engineer curating AI-agent tooling and MCP servers, this project is a turnkey integration: install the npm package, point your coding agent at it, and the agent gains first-class Chrome debugging and performance-analysis capabilities without writing any Puppeteer or CDP code yourself. It directly matches your stated interests in MCP servers, AI/LLM tooling, and open-source projects from major tech companies (this is the official ChromeDevTools org). Because it is self-hosted via npm and protocol-standard, you can drop it into any agent pipeline you are building—whether you are prototyping a new agent framework or evaluating how MCP tool-calling works in practice. It also serves as a reference implementation for how to expose complex browser-debugging capabilities through the MCP spec.

## Key Features & Technologies
- Official MCP server exposing Chrome DevTools tools to coding agents
- Puppeteer-driven browser automation with automatic action-result waiting
- Chrome DevTools Protocol performance tracing and actionable insights extraction
- Network request analysis, screenshot capture, and console inspection with source-mapped stack traces
- Standalone CLI for non-MCP usage
- Maintained by the ChromeDevTools team (official Chrome organization)
- Distributed as an npm package for easy self-hosting

## Difference from Others
Most browser-automation libraries (Selenium, Playwright, raw Puppeteer) require developers to write glue code and expose custom APIs; they do not speak a standard agent protocol. chrome-devtools-mcp stands out because it is natively an MCP server—any MCP-capable agent can discover its tools without bespoke integration code—and because it surfaces the full DevTools Protocol (performance traces, CDP network events, source-mapped console) rather than just DOM manipulation. It is also maintained by the official Chrome DevTools team, giving it a level of authority and fidelity to Chrome internals that third-party Puppeteer wrappers cannot match. Compared to generic MCP browser servers, its emphasis on performance-trace extraction and in-depth debugging (not just click-and-type automation) makes it uniquely suited for agent-driven QA and performance-debugging workflows.

## 🏢 Organization & Credibility
- **Developer:** ChromeDevTools
- **Reputation:** Unknown
- **Stars:** 52,121
- **Forks:** 3855
- **Recent Activity:** 287 commits in 3 months
- **Credibility Score:** 69.0/100 (Average)
- **Languages:** TypeScript, JavaScript, HTML, url
- **Last Release:** 2026-09-08
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
*Source: [GitHub](https://github.com/ChromeDevTools/chrome-devtools-mcp)*
