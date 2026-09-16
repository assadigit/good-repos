---
source: https://github.com/janskuba/go-to-market-orchestrator
aliases:
  - go-to-market-orchestrator
  - janskuba/go-to-market-orchestrator
tags: [python, claude-code, agents, go-to-market, automation, rest-api, shell, url]
category: Agents/Implementations
stars: 152
org: janskuba
primary_language: Python
languages: [Python, Shell, url]
credibility_score: 36.5/100
date_processed: 2026-07-05

cover: attachments/banners/go-to-market-orchestrator_banner.png

---

![banner](attachments/banners/go-to-market-orchestrator_banner.png)

# go-to-market-orchestrator

> **TL;DR:** Claude Code GTM hooks: triggers Slack, Apollo, Lemlist, Notion, Linear, Figma, Google Sheets actions via REST APIs when Claude finishes work.

**`janskuba/go-to-market-orchestrator`** · ⭐ 152 · 🔧 Python

## What is it?
go-to-market-orchestrator is a Claude Code integration that brings go-to-market automation directly into LLM sessions. It provides pre-built skills covering campaign building, lead enrichment, personalization, and signal monitoring, plus subagents like lead-prioritizer and prospect-profiler orchestrated through a /outbound-pipeline slash command.

The system operates in three layers: SKILLS are instruction modules stored as markdown files that Claude reads; AGENTS + COMMANDS define subagents and workflow commands; HOOKS + ORCHESTRATOR contains settings.json fragments that fire on Claude Code lifecycle events (Stop, PostToolUse, SessionStart) and Python handlers that make real REST API calls to external tools.

## How does it work?
The orchestrator uses Claude Code's built-in hook system. Settings.json fragments are placed in the hooks/ directory, each defining which lifecycle event triggers a handler—typically PostToolUse or SessionEnd. Each hook contains a Python function that receives the session context and executes REST API calls against tools like Apollo for lead data, Lemlist for email sequences, Linear for task management, Figma for asset creation, and Google Sheets for data storage.

Skills live under skills/<name>/SKILL.md in the repo and are copied to ~/.claude/skills/ during session setup. Agents and commands reside in agents/*.md and agents/commands/*.md as markdown files that Claude can invoke via slash commands. The architecture is designed to be entirely self-hosted, with no cloud dependencies beyond the target APIs.

## Why is it important? (Core Value)
This project directly addresses your interest in AI agents, developer tools, and automation by providing a concrete implementation of how to extend Claude Code's capabilities for go-to-market workflows. It demonstrates the pattern of using hooks to trigger real tool actions—an approach you can apply to your own agent integrations.

For self-hosting interests: everything is open-source and runs locally; no SaaS platform is required, making it suitable for homelab or private deployments. The curated library of GTM skills and outbound agents gives you immediate productivity without building from scratch, aligning with your goal of discovering tools that improve development workflows.

## Key Features & Technologies
- Claude Code hooks integration
- Pre-built GTM skills library
- Subagent system (lead-prioritizer, prospect-profiler)
- Slash command orchestration (/outbound-pipeline)
- Python REST API handlers
- Settings.json lifecycle hooks
- Self-hosted architecture

## Difference from Others
Most go-to-market automation tools are SaaS-only platforms that require subscriptions and cloud infrastructure. This project is a self-hosted Claude Code integration, giving you full control over where data lives and what triggers actions. It also provides a reusable skills library rather than requiring you to write custom prompts from scratch, which differs from generic LLM tool wrappers that lack domain-specific workflows.

## 🏢 Organization & Credibility
- **Developer:** janskuba
- **Reputation:** Unknown
- **Stars:** 152
- **Forks:** 41
- **Recent Activity:** 5 commits in 3 months
- **Credibility Score:** 36.5/100 (Low)
- **Languages:** Python, Shell, url
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
*Source: [GitHub](https://github.com/janskuba/go-to-market-orchestrator)*
