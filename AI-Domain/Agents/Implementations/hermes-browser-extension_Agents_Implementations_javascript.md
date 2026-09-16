---
source: https://github.com/abundantbeing/hermes-browser-extension
aliases:
  - hermes-browser-extension
  - abundantbeing/hermes-browser-extension
tags: [javascript, typescript, chromium, ai-agent, hermes, local-first, browser-extension, chrome-extension, edge-extension, hermes-agent, nous-research, sidepanel]
category: Agents/Implementations
stars: 1090
org: abundantbeing
primary_language: JavaScript
languages: [JavaScript, CSS, HTML, Python, Batchfile]
credibility_score: 62.0/100
date_processed: 2026-07-23
last_release: 2026-07-21
cover: attachments/banners/hermes-browser-extension_banner.png

---

![banner](attachments/banners/hermes-browser-extension_banner.png)

# hermes-browser-extension

> **TL;DR:** Chrome/Edge side panel that connects web browsing context to Hermes Agent runtime via local gateway or remote API.

**`abundantbeing/hermes-browser-extension`** · ⭐ 1,090 · 🔧 JavaScript

## What is it?
Hermes Browser Extension is a Chrome/Edge/Chromium side panel specifically built for the Hermes Agent runtime, not a browser chatbot. It enables users to connect their active web context through a local gateway, attach to a signed-in Hermes Cloud agent tab, or link to a self-hosted remote API/dashboard. The extension is currently in public alpha v0.2.0 and isn't yet published on the Chrome Web Store.

A notable feature introduced in v0.2.0 is Hermes Assist, which adds a compact, site-aware drafting panel beside supported text composers. It recognizes 31 writing environments and adapts its primary action to each context, making it useful for tasks like drafting responses or summarizing content from web pages.

## How does it work?
The extension uses the Chrome side panel API to provide a persistent UI that sits alongside tabs running Hermes Agent. Local and remote API connections can leverage models, tools, skills, sessions, memory, and MCP servers already configured in the Hermes runtime. Cloud and dashboard-ticket connections are intentionally limited to chat-only interactions.

Architecturally, the extension injects into the active tab's context—capturing DOM elements, URL, page content—and communicates with the Hermes runtime via an injected script or API endpoint. Self-hosted remote connections use a gateway endpoint; Hermes Cloud uses the provider's API; dashboard tickets connect to an internal Hermes UI service.

## Why is it important? (Core Value)
This project directly aligns with your interests in AI agents, LLM tooling, MCP servers, and self-hostable alternatives to SaaS products. As a researcher and software engineer building a personal knowledge base of developer tools, you can use this extension to integrate web browsing context into your local Hermes runtime—enabling local-first workflows, automating research or data extraction tasks, and connecting to MCP servers for tool use. It provides a concrete implementation of an AI agent in the browser that you can adopt alongside other tools in your Obsidian vault under AI-Domain → Agents.

## Key Features & Technologies
- Chrome/Edge side panel API
- Local gateway support
- Hermes Cloud integration
- Remote API/dashboard ticket connections
- MCP server connectivity
- Hermes Assist drafting panel (31 writing environments)
- v0.2.0 public alpha

## Difference from Others
Unlike generic browser extensions or chatbots, this is a purpose-built integration for Hermes Agent specifically. It offers full access to the Hermes runtime's models, tools, skills, sessions, memory, and MCP servers when connected locally or remotely—features that other agent browser extensions typically lack. The site-aware drafting capability of Hermes Assist also distinguishes it from simpler context-readers.

## 🏢 Organization & Credibility
- **Developer:** abundantbeing
- **Reputation:** Unknown
- **Stars:** 1,090
- **Forks:** 105
- **Recent Activity:** 124 commits in 3 months
- **Credibility Score:** 62.0/100 (Average)
- **Languages:** JavaScript, CSS, HTML, Python, Batchfile
- **Last Release:** 2026-07-21
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
*Source: [GitHub](https://github.com/abundantbeing/hermes-browser-extension)*
