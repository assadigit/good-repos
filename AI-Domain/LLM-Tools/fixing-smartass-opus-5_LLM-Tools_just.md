---
source: https://github.com/disler/fixing-smartass-opus-5
aliases:
  - fixing-smartass-opus-5
  - disler/fixing-smartass-opus-5
tags: [just, prompt-engineering, claude-opus, system-prompt, llm-tools, developer-productivity, url]
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

> **TL;DR:** A system prompt that transforms Claude Opus 5 from a verbose smartass into a precise senior engineering partner.

**`disler/fixing-smartass-opus-5`** · ⭐ 151 · 🔧 Just

## What is it?
Fixing-smartass-opus-5 is a prompt engineering project that provides a single file (`sr_opus_5_system_prompt.md`) designed to be appended to every session with the Claude Opus 5 model. The author argues that Opus 5 itself isn't broken — rather, its default communication channel produces exhausting output characterized by excessive headers, verbal tics (em dash chaining, "you're absolutely right"), load-bearing filler, and unnecessary bold theater. This system prompt fixes those issues directly.

## How does it work?
The project operates through a simple append-based approach: the `sr_opus_5_system_prompt.md` file is added to every session with Opus 5 (via Claude Code, Pi, or any harness that allows an appendable system prompt). For agentic workflows, it includes an `/install` slash command at `.claude/commands/install.md` that runs a justfile-based installer which verifies dependencies (`just`, `claude`, `herdr`, `jq`, `pi`) and auto-installs what it can. The core mechanism is the system prompt itself — by redefining how Opus 5 frames its responses, it reduces token waste and improves practical utility.

## Why is it important? (Core Value)
This project directly addresses a critical pain point for engineers using frontier LLMs: wasted output tokens and poor communication quality. For an engineer focused on AI agents and developer tools, this is immediately actionable — it's a drop-in improvement that turns one of the smartest models into a more usable partner without requiring model replacement or complex reconfiguration. The single-file approach means zero maintenance overhead; just append once and reap cleaner responses across all sessions.

## Key Features & Technologies
- Single-file system prompt (`sr_opus_5_system_prompt.md`) that transforms response quality
- /install slash command for Claude Code, Pi, and agentic tools
- Targets specific verbose patterns: negative parallelism, em dash chaining, load-bearing filler
- Works with any harness supporting appendable system prompts
- Zero-config after initial setup via justfile-based installer

## Difference from Others
Unlike agent frameworks (LangChain, AutoGen) or MCP servers that orchestrate multi-step workflows, this is a focused prompt engineering artifact — one file that fundamentally changes how an LLM communicates. Unlike generic system prompt collections, it's specifically tuned to eliminate the particular verbose patterns of Opus 5. It doesn't require building infrastructure; it simply redefines the conversation contract between engineer and model.

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
