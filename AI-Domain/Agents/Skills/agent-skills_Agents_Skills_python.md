---
source: https://github.com/sleekdotdesign/agent-skills
aliases:
  - agent-skills
  - sleekdotdesign/agent-skills
tags: [python, ai-agent, skill, api-integration, mobile-app-design, url]
category: Agents/Skills
stars: 559
org: sleekdotdesign

languages: [url]
credibility_score: 43.5/100
date_processed: 2026-08-19

cover: attachments/banners/agent-skills_banner.png

---

![banner](attachments/banners/agent-skills_banner.png)

# agent-skills

> **TL;DR:** A self-hosted AI agent skill library for Sleek, an AI-powered mobile app design tool.

**`sleekdotdesign/agent-skills`** · ⭐ 559 · 🔧 N/A

## What is it?
Agent Skills is a curated collection of AI agent skills built on top of Sleek, an AI-powered mobile app design platform. It allows agents to interact with Sleek's API to perform tasks such as designing mobile apps, creating screens, and managing projects automatically. The project provides a standardized way for agents to discover and install skills via `npx skills add`, making it easy to equip autonomous agents with domain-specific capabilities.

## How does it work?
The skill system works by installing skill modules into `.agents/skills/` in the working directory, where each skill is a self-contained module that can be discovered and invoked by an agent. Skills are triggered via the `npx skills add` CLI command (either interactively or with direct package paths). Each skill requires a Sleek API key stored in the `SLEEK_API_KEY` environment variable to authenticate requests to Sleek's API, which then executes the AI-powered design operations on behalf of the agent.

## Why is it important? (Core Value)
This project is particularly valuable for users interested in AI agent tooling and self-hostable alternatives to SaaS products. It provides a clean abstraction layer that decouples an agent from the underlying SaaS platform (Sleek), making it easier to swap out or compose different design tools as needed. For someone building custom agents, this represents a practical example of how skills can be modularized and installed dynamically — a pattern applicable beyond just Sleek. It also aligns with the user's interest in automation and workflow orchestration by demonstrating how an agent can autonomously perform complex creative tasks (app design) through API integration.

## Key Features & Technologies
- Interactive skill installation via `npx skills add`
- Sleek API integration for AI-powered mobile app generation
- Modular skill architecture with SKILL.md discovery files
- Environment-based authentication (`SLEEK_API_KEY`)
- MIT licensed open-source

## Difference from Others
Unlike general-purpose agent frameworks (LangChain, AutoGen) that provide a runtime for agents, this project focuses specifically on providing ready-to-use skills that integrate with an external SaaS platform. It's more specialized than generic LLM tools — it's not just a prompt template or API wrapper; it's a full skill module designed to be composed into larger agent workflows. The key differentiator is the `skills` CLI tooling and the standardized installable package format, which abstracts away the complexity of connecting agents to third-party APIs.

## 🏢 Organization & Credibility
- **Developer:** sleekdotdesign
- **Reputation:** Unknown
- **Stars:** 559
- **Forks:** 53
- **Recent Activity:** 10 commits in 3 months
- **Credibility Score:** 43.5/100 (Low)
- **Languages:** url
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
*Source: [GitHub](https://github.com/sleekdotdesign/agent-skills)*
