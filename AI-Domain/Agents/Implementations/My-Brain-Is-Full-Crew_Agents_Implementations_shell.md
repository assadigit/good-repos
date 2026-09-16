---
source: "https://github.com/gnekt/My-Brain-Is-Full-Crew"
aliases:
  - My-Brain-Is-Full-Crew
  - gnekt/My-Brain-Is-Full-Crew

tags: [shell, ai-agents, obsidian, multi-agent, second-brain, self-hosted, python, go template, javascript, url]
category: "Agents/Implementations"
stars: 3645
org: "gnekt"
primary_language: Shell
languages: [Shell, Python, Go Template, JavaScript, url]
credibility_score: 46.0/100
date_processed: 2026-09-16



---

# My-Brain-Is-Full-Crew

> **TL;DR:** A crew of 8+ AI agents with 14 skills that manages your Obsidian vault, nutrition, and mental wellness across multiple CLI platforms.

**`gnekt/My-Brain-Is-Full-Crew`** · ⭐ 3,645 · 🔧 Shell

## What is it?
My-Brain-Is-Full-Crew is a multi-agent system designed as a "second brain" that goes beyond note-taking. It deploys a crew of 8+ specialized AI agents working together with 14 distinct skills to manage three intertwined domains: personal knowledge (organized in an Obsidian vault), nutrition/diet tracking, and mental wellness/anxiety management. The project was built by a PhD who experienced memory decline, poor dietary habits, and anxiety, and frames the brain as part of a larger body-mind system rather than an isolated information processor.

The crew handles organizing, filing, connecting, searching, transcribing, and triaging email across any language. It runs on four AI coding platforms—Claude Code, Gemini CLI, OpenCode, and Codex CLI—from a single codebase, meaning the same agent definitions and skill set are portable across backends. The project is MIT-licensed and operates entirely on a local Obsidian vault, with an active Discord community for support and sharing.

## How does it work?
The architecture centers on a "crew" pattern: multiple specialized agents (8+) each own a slice of the personal-ops problem space (knowledge curation, email triage, nutrition logging, wellness check-ins, etc.) and coordinate through a shared Obsidian vault as their persistent memory/state store. The 14 skills are modular capabilities attached to these agents—functions like search, file, connect, transcribe, and triage—that can be composed across agents.

The codebase is platform-agnostic: the same agent/skill definitions are consumed by Claude Code, Gemini CLI, OpenCode, and Codex CLI, meaning the user picks their preferred LLM backend without forking or rewriting. All data lives in a local Obsidian vault (markdown files), keeping everything self-hosted and inspectable. Language handling is built in, so users can interact with the crew in any natural language.

## Why is it important? (Core Value)
For this user—already organizing a personal knowledge base in an Obsidian vault and actively researching AI agent architectures—this project is a direct reference implementation. It demonstrates how to decompose a complex personal-ops domain into a crew of specialized agents with discrete, reusable skills (the 14-skill taxonomy), which maps closely to the agent/skill patterns the user is evaluating for their own tooling. The cross-platform CLI support (Claude Code, Gemini CLI, OpenCode, Codex CLI) shows how to keep agent definitions portable across LLM backends, a practical pattern for anyone building MCP servers or agent integrations.

Because it is MIT-licensed and runs entirely on a local Obsidian vault, it satisfies the user's preference for self-hosted alternatives over SaaS. The three-domain scope (knowledge + nutrition + mental wellness) also makes it a concrete example of multi-domain agent orchestration beyond a single narrow use case, giving the user a working template to study before designing their own agent crews.

## Key Features & Technologies
- Multi-agent crew architecture with 8+ specialized AI agents
- 14 modular skills covering knowledge management, nutrition tracking, and mental wellness
- Cross-platform: same codebase runs on Claude Code, Gemini CLI, OpenCode, and Codex CLI
- Local Obsidian vault as persistent state store (self-hosted, MIT licensed)
- Email triage, transcription, search, and filing with language-agnostic interaction
- Active Discord community for support and skill sharing

## Difference from Others
Most second-brain tools are single-agent or plugin-based: one bot that files notes, one plugin that tags headings. My-Brain-Is-Full-Crew takes a crew approach—multiple agents with distinct responsibilities (knowledge curation, email triage, nutrition logging, wellness check-ins) coordinated through a shared vault, which mirrors how a small ops team would divide labor. The 14-skill layer is also more granular than typical agent frameworks that expose only generic tool-calling; each skill is a named, reusable capability.

The cross-platform CLI support (four LLM backends from one codebase) sets it apart from solutions locked to a single provider's SDK. Compared to Obsidian community plugins or single-agent note bots, this project treats the vault as the system of record for an entire personal-ops stack, not just a document store, and the MIT license plus local-only data model make it immediately adoptable without vendor lock-in.

## 🏢 Organization & Credibility
- **Developer:** gnekt
- **Reputation:** Unknown
- **Stars:** 3,645
- **Forks:** 359
- **Recent Activity:** 1 commits in 3 months
- **Credibility Score:** 46.0/100 (Low)
- **Languages:** Shell, Python, Go Template, JavaScript, url
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
*Source: [GitHub](https://github.com/gnekt/My-Brain-Is-Full-Crew)*
