---
source: https://github.com/lobehub/lobe-chat
aliases:
  - lobe-chat
  - lobehub/lobe-chat
tags: [typescript, python, mcp, agent, orchestration, self-hosted, chatgpt, openai, ai, gpt, claude, gemini]
category: Agents
stars: 79543
org: lobehub
primary_language: TypeScript
languages: [TypeScript, HTML, Shell, JavaScript, Gherkin]
credibility_score: 70.5/100
date_processed: 2026-07-06
last_release: 2026-07-06
cover: attachments/banners/lobe-chat_banner.png

---

![banner](attachments/banners/lobe-chat_banner.png)

# lobe-chat

> **TL;DR:** Self-hosted AI agent orchestration platform that hires, schedules, and reports on your entire AI team.

**`lobehub/lobe-chat`** · ⭐ 79,543 · 🔧 TypeScript

## What is it?
LobeHub is an AI agent orchestration platform designed to manage multiple autonomous agents around the clock. It treats your entire AI workforce as a team that can be hired, scheduled, and reported on — all without you needing to stay online. The system integrates with major LLM providers including OpenAI, Claude, Gemini, and DeepSeek, allowing you to mix and match models based on cost, latency, or capability. A central knowledge base stores prompts, context, and tool definitions that agents can access.

## How does it work?
The platform appears to use an event-driven loop engine architecture to coordinate agent lifecycles — hiring new agents, scheduling tasks, and aggregating reports into dashboards. Under the hood, it likely exposes MCP (Model Context Protocol) endpoints for tool integration, allowing agents to call external APIs or interact with local filesystems. The architecture is designed around asynchronous task queues to handle long-running agent sessions, with self-hosting via Docker or bare metal.

## Why is it important? (Core Value)
For a software engineer and researcher focused on AI agents, LobeHub offers significant value as both an orchestrator and framework for multi-agent workflows. It directly addresses your objective to find AI agent frameworks and MCP servers you can integrate — this platform serves that purpose while also providing self-hostability crucial for privacy-focused deployments. Its support for multiple model backends means you can experiment with different LLMs without vendor lock-in, aligning with your interest in self-hosted alternatives to SaaS products. The knowledge base component helps you curate prompts and tool definitions, supporting your goal of building a personal knowledge base. Additionally, the platform's emphasis on reporting and scheduling provides the workflow automation you seek, all while keeping full control over data.

## Key Features & Technologies
- Supports OpenAI, Claude, Gemini, DeepSeek models
- Uses MCP for tool integration
- Central knowledge base for prompts and context
- Event-driven loop engine for orchestration
- Self-hosted via Docker or bare metal
- Multi-agent collaboration
- Scheduled 7×24 operations
- Reporting dashboard

## Difference from Others
Compared to CrewAI, LangGraph, or AutoGen, LobeHub distinguishes itself through its 'Chief Agent Operator' philosophy that emphasizes off-hours automation and comprehensive reporting. While many agent frameworks focus on building single-agent workflows or simple multi-agent teams, LobeHub treats the entire AI workforce as a managed team with hiring, scheduling, and reporting capabilities built in. It also appears to have stronger self-hosting support out of the box, making it more suitable for homelab environments where you want full control over data and deployment.

## 🏢 Organization & Credibility
- **Developer:** lobehub
- **Reputation:** Unknown
- **Stars:** 79,543
- **Forks:** 15559
- **Recent Activity:** 2169 commits in 3 months
- **Credibility Score:** 70.5/100 (Average)
- **Languages:** TypeScript, HTML, Shell, JavaScript, Gherkin
- **Last Release:** 2026-07-06
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
*Source: [GitHub](https://github.com/lobehub/lobe-chat)*
