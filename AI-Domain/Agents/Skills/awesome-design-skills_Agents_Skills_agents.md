---
source: https://github.com/bergside/awesome-design-skills
aliases:
  - awesome-design-skills
  - bergside/awesome-design-skills
tags: [agents, design-systems, markdown, ai-tools, typeui, agent-skills, agentic-ai, agentic-workflow, ai, ai-agents, awesome, awesome-list]
category: Agents/Skills
stars: 1569
org: bergside

languages: [url]
credibility_score: 56.0/100
date_processed: 2026-07-05

cover: attachments/banners/awesome-design-skills_banner.png

---

![banner](attachments/banners/awesome-design-skills_banner.png)

# awesome-design-skills

> **TL;DR:** Curated registry of 67 design system SKILL/DESIGN files for AI agents like Claude Code, Cursor, Codex.

**`bergside/awesome-design-skills`** · ⭐ 1,569 · 🔧 N/A

## What is it?
This repository is a curated registry of 67 design system skill files tailored for AI-powered agentic tools such as Claude Code, Cursor, Codex, and others. Each skill is packaged as a folder containing two markdown files: SKILL.md provides instructions directly usable by AI agents (including tokens, component rules, accessibility constraints, and quality gates), while DESIGN.md offers human-readable documentation of the design intent, rationale, and implementation notes.

The project is complemented by a preview platform at TypeUI where users can explore all available skills visually before pulling them into their own projects. This dual-file approach ensures that both machine-interpretable agent instructions and human-understandable design documentation are distributed together as part of the same skill package.

## How does it work?
The architecture revolves around a centralized markdown-based registry that serves as a single source of truth for design system skills across multiple AI agent ecosystems. Each skill lives in its own folder within the repository, allowing straightforward cloning or programmatic fetching. The project exposes an npm-based CLI (typeui.sh) that lets users pull any skill into their project with a single command—likely using `npx typeui.sh pull <skill-name>`. This CLI probably reads the registry metadata, downloads the corresponding SKILL.md and DESIGN.md files, and places them in the desired location. The TypeUI preview page functions as a lightweight UI that indexes the repository contents, enabling users to browse skills by category or agent type before deciding which ones to incorporate.

## Why is it important? (Core Value)
For a software engineer and researcher focused on AI agents, developer tools, and automation, this registry directly addresses several core objectives. It provides ready-made design system skills that can be integrated into agentic workflows, reducing the need to reinvent common patterns for each project. The dual markdown files align perfectly with the user's interest in AI/LLM tooling (agents, skills, MCP) and developer productivity tools. Moreover, because the registry is open-source and maintained on GitHub, it can be self-hosted or used as a reference within an Obsidian vault under the AI-Domain or Tools category. By offering a curated list of 67 skills, it also serves as a credible resource for building personal knowledge bases of useful tools and frameworks.

## Key Features & Technologies
- Curated registry of 67 design system skills
- Each skill ships with SKILL.md (agent instructions) and DESIGN.md (human documentation)
- TypeUI preview platform for visual exploration
- npm-based CLI tool (typeui.sh) for pulling skills into projects
- Supports multiple AI agents: Claude Code, Cursor, Codex, and others
- Design system rules include tokens, accessibility constraints, and quality gates
- Centralized markdown repository for easy sharing and adoption

## Difference from Others
Unlike generic awesome lists or static design system repositories, this project is purpose-built for AI agents. It provides both SKILL.md (machine-readable) and DESIGN.md (human-readable) files, whereas most other repositories only contain documentation. Other design system registries typically focus on CSS variables, component libraries, or UI kits without any agent-specific instructions. Furthermore, the inclusion of a CLI tool (typeui.sh) and a preview UI (TypeUI) makes it uniquely convenient for integration into development workflows, setting it apart from purely markdown-based lists.

## 🏢 Organization & Credibility
- **Developer:** bergside
- **Reputation:** Unknown
- **Stars:** 1,569
- **Forks:** 150
- **Recent Activity:** 31 commits in 3 months
- **Credibility Score:** 56.0/100 (Low)
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
*Source: [GitHub](https://github.com/bergside/awesome-design-skills)*
