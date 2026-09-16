---
source: https://github.com/gooseworks-ai/goose-skills
aliases:
  - goose-skills
  - gooseworks-ai/goose-skills
tags: [python, npm, claude, cursor, skills, automation, claude-skills, claudecode, claudecode-skills, codex, gtm, javascript]
category: Agents/Skills
stars: 965
org: gooseworks-ai
primary_language: Python
languages: [Python, JavaScript, HTML, CSS, Shell]
credibility_score: 55.5/100
date_processed: 2026-07-05

cover: attachments/banners/goose-skills_banner.png

---

![banner](attachments/banners/goose-skills_banner.png)

# goose-skills

> **TL;DR:** npm library of 200+ growth/marketing skills for Claude Code, Cursor, and Codex AI agents.

**`gooseworks-ai/goose-skills`** · ⭐ 965 · 🔧 Python

## What is it?
Goose Skills is an open-source npm package that provides ready-to-use growth and go-to-market (GTM) capabilities for AI coding agents such as Claude Code, Cursor, and Codex. It packages over 200 skills covering ads, social media management, content creation, SEO, lead generation, and data scraping, each defined by a standardized metadata contract that allows agents to discover and invoke them via function calling.

Installation is straightforward: run npx gooseworks install --claude (or --cursor, --codex) to register the skill modules for your agent. After logging in with npx gooseworks login, you can query the catalog via npx gooseworks catalog or browse at https://skills.gooseworks.ai. The project is MIT licensed and includes a web UI for skill discovery.

## How does it work?
Goose Skills is distributed as an npm package that registers a set of skill modules when installed with npx gooseworks install. Each module defines a metadata contract—a JSON schema describing the function name, description, input parameters, and output type—allowing AI coding agents to discover skills via a REST catalog endpoint or locally. The agent calls these skills using standard function-calling interfaces; authentication is handled through environment variables set after npx gooseworks login. For scraping tasks, underlying tools may use Puppeteer or Playwright, while ads and social media skills likely delegate to APIs (e.g., Google Ads, Twitter) with stored credentials.

The skill metadata contract is part of the package's public API; agents can query gooseworks-catalog endpoint or read local JSON files. The npm package also provides a CLI for installing and managing skills across different agent types (Claude Code, Cursor, Codex), ensuring compatibility with each agent's tool invocation protocol.

## Why is it important? (Core Value)
Goose Skills offers a self-contained, MIT-licensed library that packages over 200 growth and GTM capabilities, including data scraping functions, directly callable by AI coding agents. This gives developers a ready-made toolkit to automate marketing tasks (ads, social, content) without building each function from scratch, and the standardized metadata contract can serve as a reference for constructing custom skill modules or extending other frameworks. Because it's distributed via npm, you can self-host the library in your homelab or integrate it into any agent runtime, aligning with your interest in open-source alternatives to SaaS products and new scraping approaches.

## Key Features & Technologies
- npm package
- MIT license
- 200+ pre-built skills
- works with Claude Code/Cursor/Codex
- skill metadata contract
- authentication via login
- web catalog UI

## Difference from Others
Unlike generic LLM tool libraries that focus on coding tasks (e.g., LangChain's built-in tools), Goose Skills is specialized for growth and marketing activities, covering ads, social media, content creation, SEO, lead generation, and data scraping. While MCP servers define a protocol for context sharing, Goose Skills defines a metadata contract specifically for skill discovery and invocation, making it more aligned with function-calling agents. It also provides an npm package that works across multiple AI coding agents (Claude Code, Cursor, Codex) whereas other tool libraries often target a single platform. This cross-agent compatibility and marketing focus set it apart from typical developer utilities or automation scripts.

## 🏢 Organization & Credibility
- **Developer:** gooseworks-ai
- **Reputation:** Unknown
- **Stars:** 965
- **Forks:** 179
- **Recent Activity:** 151 commits in 3 months
- **Credibility Score:** 55.5/100 (Low)
- **Languages:** Python, JavaScript, HTML, CSS, Shell
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
*Source: [GitHub](https://github.com/gooseworks-ai/goose-skills)*
