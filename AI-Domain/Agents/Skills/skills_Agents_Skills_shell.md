---
source: https://github.com/mattpocock/skills
aliases:
  - skills
  - mattpocock/skills
tags: [shell, typescript, node, agent, prompt, npm, url]
category: Agents/Skills
stars: 158537
org: mattpocock
primary_language: Shell
languages: [Shell, url]
credibility_score: 70.5/100
date_processed: 2026-07-06
last_release: 2026-06-17
cover: attachments/banners/skills_banner.png

---

![banner](attachments/banners/skills_banner.png)

# skills

> **TL;DR:** CLI tool for installing curated agent skills for real engineering workflows.

**`mattpocock/skills`** · ⭐ 158,537 · 🔧 Shell

## What is it?
Skills is a collection of practical agent skills curated by engineer Matt Pocock for building robust, production-grade LLM agents. Unlike overly opinionated frameworks that take control away from developers, these skills are designed to be small, composable, and adaptable. They provide the foundational capabilities needed to implement reliable agent behaviors without falling into 'vibe coding'.

The project focuses on real engineering challenges: handling context limits, managing tool invocations, maintaining state across turns, and ensuring agents produce deterministic outputs. Each skill is a modular piece that can be combined and extended as needed, giving developers flexibility while providing proven patterns from decades of engineering experience.

## How does it work?
The skills are distributed as installable packages via npm (using `npx skills@latest add mattpocock/skills`). Each skill is likely a self-contained prompt or capability definition that can be invoked by any LLM agent. The installer fetches the package, extracts the skill definitions (probably stored as JSON/YAML prompts), and makes them available in the user's environment.

Because these skills are model-agnostic, they work with any LLM regardless of token limits or instruction-following capabilities. This means you can use them whether you're running local models, calling APIs, or integrating with frameworks like LangChain, AutoGen, or custom agent implementations.

## Why is it important? (Core Value)
For your objectives, Skills directly addresses your interest in AI/LLM tooling and developer productivity tools. It provides concrete, reusable building blocks for agents that you can integrate into your projects rather than relying on monolithic frameworks. The fact that these are curated skills means they represent distilled best practices from real engineering work, giving you credible patterns to adopt.

Regarding self-hostable alternatives and infrastructure interests: the skills appear to be data-driven (prompts/capability definitions), making them potentially usable in any environment without dependencies on specific SaaS services. This aligns well with your goal of finding self-hostable options.

For your Obsidian vault organization, Skills fits into your 'AI-Domain' or 'Tools' category as a foundational agent capability library. It's also relevant to your interest in scraping and automation since many skills likely involve data extraction workflows that could complement other projects you're curating.

## Key Features & Technologies
- Installable via npx
- Model-agnostic (works with any LLM)
- Composable skill definitions
- CLI-based workflow
- Newsletter updates (~60k subscribers)
- No opinionated framework dependencies

## Difference from Others
Unlike monolithic agent frameworks like LangChain or AutoGen that provide end-to-end orchestration, Skills offers modular capabilities you can pick and choose. Compared to other prompt libraries (like prompt-foo), these are specifically designed for agent interactions, not just evaluation. The key differentiator is the focus on real engineering patterns over trendy approaches like GSD/BMAD/Spec-Kit that the curator explicitly critiques for taking control away from developers.

## 🏢 Organization & Credibility
- **Developer:** mattpocock
- **Reputation:** Unknown
- **Stars:** 158,537
- **Forks:** 13628
- **Recent Activity:** 235 commits in 3 months
- **Credibility Score:** 70.5/100 (Average)
- **Languages:** Shell, url
- **Last Release:** 2026-06-17
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
*Source: [GitHub](https://github.com/mattpocock/skills)*
