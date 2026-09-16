---
source: https://github.com/kangarooking/cangjie-skill
aliases:
  - cangjie-skill
  - kangarooking/cangjie-skill
tags: [python, python, ai-skills, prompt-engineering, openclaw, claude, agent-workflows, automation, book-to-skill, knowledge-distillation, skill-generator, templates]
category: Agents/Skills
stars: 4243
org: kangarooking
primary_language: Python
languages: [Python, url]
credibility_score: 54.5/100
date_processed: 2026-07-22

cover: attachments/banners/cangjie-skill_banner.png

---

![banner](attachments/banners/cangjie-skill_banner.png)

# cangjie-skill

> **TL;DR:** Distills high-value content into callable AI skills for agents.

**`kangarooking/cangjie-skill`** · ⭐ 4,243 · 🔧 Python

## What is it?
Cangjie-skill extracts methodologies from books, long videos, podcasts, interviews, courses and any other content with transcribable text, turning them into independent, reusable skill packages that can be invoked by AI agents. It applies knowledge-distillation techniques to identify actionable methods, then uses an LLM (via OpenClaw platform for OpenAI function-calling or Claude Code for Anthropic tool-use) to generate a JSON-schema function definition that captures the method's description, parameters, and return type. These definitions are assembled into self-contained skill modules that can be combined, pressure-tested, and deployed alongside other agent tools. The project also suggests pairing with its video-downloader skill to first download videos, extract subtitles/transcripts, and feed the resulting text into cangjie-skill for skill generation.

## How does it work?
Cangjie-skill reads source material (text files, transcripts from videos/podcasts) and applies knowledge-distillation techniques to extract actionable methodologies. It uses an LLM (likely via OpenClaw/Claude Code) to parse content, identify key concepts, and generate a skill definition—a JSON-schema function that describes the method, parameters, and return type. These definitions are then assembled into reusable skill packages that can be invoked by AI agents.

## Why is it important? (Core Value)
Cangjie-skill directly supports your objective to discover AI agent tools that improve development workflow. By converting books, videos, podcasts into callable skills, it gives you a new class of AI agents that can retrieve and execute methods from high-value content, effectively extending your own knowledge base with self-hosted skill packages. Its OpenClaw and Claude Code integrations align with your interest in MCP servers and LLM tooling, while its open-source nature fits your desire for self-hostable alternatives to SaaS.

## Key Features & Technologies
- Knowledge distillation from books, videos, podcasts
- Generates callable AI skills (function definitions)
- Integrates with OpenClaw platform (OpenAI function-calling)
- Integrates with Claude Code platform (Anthropic tool-use)
- Uses prompt engineering to extract methodologies
- Provides skill templates and reusable packages
- Works on any transcribed content (subtitles, transcripts)

## Difference from Others
Similar projects include nuwa-skill (distilling human colleagues) and darwin-skill (skill evolution). Cangjie-skill differs because it focuses on content rather than people, providing a systematic extraction pipeline that yields reusable skill packages. It also supports multiple content types (books, podcasts, long videos) and integrates with OpenClaw/Claude Code, whereas nuwa-skill is more about human knowledge. Additionally, cangjie-skill's approach to knowledge distillation via prompt engineering may be more generalizable.

## 🏢 Organization & Credibility
- **Developer:** kangarooking
- **Reputation:** Unknown
- **Stars:** 4,243
- **Forks:** 560
- **Recent Activity:** 25 commits in 3 months
- **Credibility Score:** 54.5/100 (Low)
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
*Source: [GitHub](https://github.com/kangarooking/cangjie-skill)*
