---
source: https://github.com/davidondrej/skills
aliases:
  - skills
  - davidondrej/skills
tags: [python, agent, skills, markdown, automation, url]
category: LLM-Tools
stars: 178
org: davidondrej

languages: [url]
credibility_score: 46.5/100
date_processed: 2026-07-05

cover: attachments/banners/skills_banner.png

---

![banner](attachments/banners/skills_banner.png)

# skills

> **TL;DR:** Personal agent skill library with reusable workflows for coding, research, and ops tasks.

**`davidondrej/skills`** · ⭐ 178 · 🔧 N/A

## What is it?
This repository contains a curated collection of reusable skills designed for AI agents working on coding, research, and workflow tasks. Each skill is packaged as a focused workflow that an agent can load when the task calls for it, providing ready-made building blocks for agentic work such as improving codebases, preparing content, researching ideas, reviewing presentations, and handling transcripts. Skills are organized into category folders under `skills/`, each containing a `SKILL.md` file that explains when and how to use it, making discovery and integration straightforward.

## How does it work?
The architecture is intentionally simple: every skill lives in its own folder with a markdown-based `SKILL.md` that defines the workflow, prerequisites, steps, and expected outputs. Agents can reference these skills by name or path—typically through MCP servers or custom loaders—and load them into their context as needed. Because the skills are just text files, they require no heavy dependencies or runtime installation beyond what the agent platform already supports.

## Why is it important? (Core Value)
For you, this repository directly addresses your interest in AI/LLM tooling and developer productivity by offering a set of self-hosted, ready-made skills that can be integrated into your own agent stacks. You mentioned wanting to discover tools that improve development workflow and identify self-hostable alternatives—these skills give you exactly that: modular workflows you can adopt without reinventing the wheel. The skill definitions are written in markdown, so they're easy to parse and extend, aligning with your goal of curating a personal knowledge base of useful tools.

## Key Features & Technologies
- Uses markdown-based skill definitions (`SKILL.md`)
- Organized into category folders (agent orchestration, research and web, ops and setup)
- Designed for integration with AI agents (MCP servers, custom loaders)
- Self-hosted (no external dependencies)
- Includes skill authoring guidance

## Difference from Others
Unlike generic agent tool collections or framework-native toolsets, this repo is a personal library that focuses on discrete, domain-specific skills rather than broad-purpose utilities. Each skill is meant to be loaded on-demand by an agent, providing fine-grained control over workflow composition. The markdown-based definitions also make them easier to audit and adapt compared to code-heavy tool implementations.

## 🏢 Organization & Credibility
- **Developer:** davidondrej
- **Reputation:** Unknown
- **Stars:** 178
- **Forks:** 26
- **Recent Activity:** 27 commits in 3 months
- **Credibility Score:** 46.5/100 (Low)
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
*Source: [GitHub](https://github.com/davidondrej/skills)*
