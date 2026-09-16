---
source: https://github.com/Archive228/loopkit
aliases:
  - loopkit
  - Archive228/loopkit
tags: [shell, agent, skills, claude, llm, automation, javascript, url]
category: Agents/Skills
stars: 426
org: Archive228
primary_language: Shell
languages: [Shell, JavaScript, url]
credibility_score: 43.5/100
date_processed: 2026-07-08

cover: attachments/banners/loopkit_banner.png

---

![banner](attachments/banners/loopkit_banner.png)

# loopkit

> **TL;DR:** Drop-in .claude/ harness with 33–41 battle-tested skills for Claude Code, Cursor, Codex, Gemini CLI coding agents.

**`Archive228/loopkit`** · ⭐ 426 · 🔧 Shell

## What is it?
loopkit provides a minimal .claude/ directory harness designed to integrate with Claude Code, Cursor, Codex, and Gemini CLI coding agents. It includes 41 battle-tested skills that help agents plan actions, execute them, and verify results through file-based enforcement. The project emphasizes simplicity—dropping the harness into a project folder is all that's needed, as it skips existing files and avoids interfering with the user's environment.

The core purpose of loopkit is to give coding agents reliable, pre-built capabilities without requiring custom development. By offering 33–41 skills (as documented), it solves the problem of agents lacking consistent tooling across different environments. Its unique value lies in being drop-in ready—users simply install it into their project folder, and it respects existing files while enforcing a Plan → Act → Verify workflow. This makes it particularly useful for teams or individuals working with Claude Code, Cursor, Codex, or Gemini CLI, offering a lightweight alternative to larger agent frameworks that may be overkill or harder to self-host.

## How does it work?
loopkit consists of a .claude/ directory structure containing skill definitions and enforcement scripts. When installed via the provided curl command, it drops these files into the target project without overwriting existing content. The skills are designed to be invoked by coding agents (Claude Code, Cursor, etc.) through standard tool calling or file-based APIs. Each skill implements a Plan → Act → Verify cycle, likely using file system operations or agent-specific interfaces to ensure that actions are recorded and verified.

The project leverages simple Bash scripts for installation and possibly Python or other languages for the actual skill implementations, though the exact language isn't specified in the README. Its minimal design means it doesn't require additional dependencies beyond what the coding agents already support.

## Why is it important? (Core Value)
loopkit addresses the need for reliable, pre-built skills that coding agents can use without requiring custom development. By providing 41 battle-tested skills and a minimal .claude/ harness, it solves the problem of agents lacking consistent tooling across different environments. Its unique value lies in being drop-in ready—users simply install it into their project folder, and it respects existing files while enforcing a Plan → Act → Verify workflow.

Given your objectives to discover tools that improve development workflow, find AI agent frameworks and MCP servers you can integrate into projects, and identify self-hostable alternatives to SaaS products, loopkit is particularly relevant. It offers a lightweight, open-source solution for coding agents, aligning with your interest in AI/LLM tooling, developer productivity tools, and self-hosted software. The skills it provides could be integrated into your Obsidian vault under the 'AI-Domain' or 'Frameworks' categories, aiding your knowledge base of useful tools.

## Key Features & Technologies
- drop-in .claude/ harness
- Plan → Act → Verify enforcement
- MIT license
- self-hostable alternative to SaaS
- Bash install script

## Difference from Others
Unlike generic agent frameworks that provide broad orchestration, loopkit offers a minimal, drop-in harness focused exclusively on coding-agent skills with explicit Plan → Act → Verify enforcement. It's designed as a self-hostable alternative to SaaS-based agent tools, providing 41 battle-tested skills rather than just a framework for building agents.

Other projects like LangChain or AutoGen are more general-purpose and require additional setup, whereas loopkit is specifically tailored to Claude Code and similar agents, making it ideal for users who want immediate integration without complex dependencies.

## 🏢 Organization & Credibility
- **Developer:** Archive228
- **Reputation:** Unknown
- **Stars:** 426
- **Forks:** 82
- **Recent Activity:** 14 commits in 3 months
- **Credibility Score:** 43.5/100 (Low)
- **Languages:** Shell, JavaScript, url
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
*Source: [GitHub](https://github.com/Archive228/loopkit)*
