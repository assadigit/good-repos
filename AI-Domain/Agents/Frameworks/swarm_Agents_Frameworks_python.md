---
source: https://github.com/openai/swarm
aliases:
  - swarm
  - openai/swarm
tags: [python, python, openai, agents, orchestration, sdk, url]
category: Agents/Frameworks
stars: 21768
org: openai
primary_language: Python
languages: [Python, url]
credibility_score: 90.0/100
date_processed: 2026-07-06

cover: attachments/banners/swarm_banner.png

---

![banner](attachments/banners/swarm_banner.png)

# swarm

> **TL;DR:** Educational Python framework for lightweight multi-agent orchestration; now superseded by OpenAI Agents SDK.

**`openai/swarm`** · ⭐ 21,768 · 🔧 Python

## What is it?
Swarm is an experimental, educational framework designed to explore ergonomic and lightweight patterns for coordinating and executing multiple AI agents. It provides a minimalistic interface for defining agents with custom instructions and capabilities, enabling developers to prototype multi-agent workflows without the complexity of production-grade SDKs. The project emphasizes simplicity in agent coordination—allowing agents to hand off tasks to one another via function returns—and includes utilities for running agents, streaming responses, and evaluating their behavior.

## How does it work?
Swarm operates by defining Agent objects with properties like name, instructions, and a list of functions they can call. These functions are ordinary Python functions that can return agent names to signal handoffs. The central client.run method orchestrates conversation between agents: it sends user messages to the specified agent, processes responses (potentially streaming via SSE), and returns a structured message history. Under the hood, the framework likely wraps calls to the OpenAI API for LLM interactions, with utilities that parse incoming/outgoing messages and handle function call routing.

## Why is it important? (Core Value)
For your objectives as a researcher and software engineer focused on AI agents and automation, Swarm serves as an accessible reference implementation showing how OpenAI structures multi-agent orchestration. It demonstrates patterns for handoff functions, streaming responses, and agent evaluation that you can study before migrating to the production-ready Agents SDK or adapting the concepts for self-hosted alternatives. While Swarm itself depends on OpenAI's API (not fully self-hostable), understanding its design will help you build or select frameworks that align with your interest in ergonomic agent coordination, MCP servers, and developer productivity tools.

## Key Features & Technologies
- Python (3.10+) SDK
- Agent definitions (name, instructions, functions)
- Streaming responses via SSE
- Handoff functions returning agent names
- Evaluations module for testing agent behavior
- Simple client.run interface
- OpenAI API integration

## Difference from Others
Swarm differs from the production OpenAI Agents SDK in that it is experimental and educational, prioritizing minimal ergonomics over features like persistent memory or advanced tool integration. Compared to general-purpose agent frameworks like LangChain or AutoGen, Swarm focuses on a lightweight orchestration model without heavy chain-of-thought abstractions. Against self-hosted alternatives (e.g., CrewAI), Swarm is tied to OpenAI's API; however, its simple structure makes it easier to adapt for local LLMs if desired.

## 🏢 Organization & Credibility
- **Developer:** openai
- **Reputation:** High (Major tech company)
- **Stars:** 21,768
- **Forks:** 2319
- **Recent Activity:** 1 commits in 3 months
- **Credibility Score:** 90.0/100 (Excellent)
- **Languages:** Python, url
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
*Source: [GitHub](https://github.com/openai/swarm)*
