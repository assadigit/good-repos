---
source: https://github.com/disler/fixing-smartass-opus-5
aliases:
  - fixing-smartass-opus-5
  - disler/fixing-smartass-opus-5
tags: [just, claude, system-prompt, prompt-engineering, llm-tools, engineering, url]
category: LLM-Tools
stars: 151
org: disler
primary_language: Just
languages: [Just, url]
credibility_score: 41.0/100
date_processed: 2026-08-19

cover: attachments/banners/fixing-smartass-opus-5_banner.png

---

![banner](attachments/banners/fixing-smartass-opus-5_banner.png)

# fixing-smartass-opus-5

> **TL;DR:** A single system prompt file that transforms Claude Opus 5 from verbose into precise engineering output.

**`disler/fixing-smartass-opus-5`** · ⭐ 151 · 🔧 Just

## What is it?
Fixing-smartass-opus-5 is a curated system prompt designed to transform Claude Opus 5 (and similar frontier coding models) from a verbose, theatrical 'smartass' into a precise senior engineering partner. The project addresses common issues with Opus 5 including excessive verbosity, six-header responses, em-dash chaining, and unnecessary co-author credit stamps on commits.

The core deliverable is the file `sr_opus_5_system_prompt.md`, which users append to their session system prompt when working with Claude Code, Pi, or any LLM harness that supports an appendable system prompt. The project also includes a `/install` command (located at `.claude/commands/install.md`) for agentic tools like Claude Code and Pi, which handles dependency verification and setup.

## How does it work?
The project operates through simple system prompt injection. Users either manually append the `sr_opus_5_system_prompt.md` content to their LLM session's system prompt, or run a `/install` slash command in agentic tools like Claude Code. The installed command verifies prerequisites (`just`, `claude`, `herdr`, `jq`, and optionally `pi`) and auto-installs missing dependencies before confirming the compare loop is ready for use.

## Why is it important? (Core Value)
This project directly addresses a common pain point for software engineers using frontier LLMs: excessive verbosity that wastes tokens, obscures answers, and adds cognitive load. By providing a battle-tested system prompt, it eliminates hours of trial-and-error prompt engineering. For the user described — an engineer focused on AI agents and developer tools — this is highly relevant as it represents practical prompt engineering for production-grade agent interactions. It also aligns with their interest in improving development workflows through better LLM tooling.

The project's value extends beyond mere brevity: it ensures commits are clean (no co-author credits), responses are structured appropriately, and the model focuses on actual engineering output rather than performative prose.

## Key Features & Technologies
- Single file system prompt (`sr_opus_5_system_prompt.md`) for immediate deployment
- Agentic `/install` command with dependency verification and auto-installation
- Targets Claude Opus 5, Claude Code, Pi, and compatible LLM harnesses
- Eliminates verbose formatting (headers, em dashes, bold theater)
- Removes unnecessary co-author credit stamps on commits
- Designed for mid to senior engineers running frontier coding agents

## Difference from Others
Unlike generic prompt templates or broad agent frameworks, this project is narrowly focused on a specific pain point: Opus 5's verbose output style. It doesn't attempt to be a full agent framework like LangChain or CrewAI; instead, it provides a drop-in system prompt that works across multiple agentic tools (Claude Code, Pi). Its value proposition is specificity and immediate utility — one file fixes the most common complaint about Opus 5's production use.

## 🏢 Organization & Credibility
- **Developer:** disler
- **Reputation:** Unknown
- **Stars:** 151
- **Forks:** 19
- **Recent Activity:** 1 commits in 3 months
- **Credibility Score:** 41.0/100 (Low)
- **Languages:** Just, url
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
*Source: [GitHub](https://github.com/disler/fixing-smartass-opus-5)*
