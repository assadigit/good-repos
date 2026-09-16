---
source: "https://github.com/blader/humanizer"
aliases:
  - humanizer
  - blader/humanizer

tags: [python, agent-skill, prompt-engineering, claude-code, writing-tools, markdown, agent-skills, ai-writing, codex, cursor, url]
category: "Agents/Skills"
stars: 49038
org: "blader"
primary_language: Python
languages: [Python, url]
credibility_score: 66.0/100
date_processed: 2026-09-16
last_release: 2026-09-06
cover: attachments/banners/humanizer_banner.png

---

![banner](attachments/banners/humanizer_banner.png)

# humanizer

> **TL;DR:** Agent skill that rewrites AI-generated text to sound natural, compatible with Claude Code, Codex, Cursor, and other agents.

**`blader/humanizer`** · ⭐ 49,038 · 🔧 Python

## What is it?
Humanizer is a lightweight agent skill that rewrites AI-sounding prose so it reads as if written by a human, without altering the underlying meaning. It is distributed as a single Markdown file (SKILL.md) and integrates with any agent runtime that supports the skills protocol, including Claude Code, Codex, Cursor, and Claude Desktop. Installation is handled through the Skills CLI (`npx skills add blader/humanizer --global`) or, for Claude Code 2.1.142+, as a native plugin via `/plugin install`.

The skill is invoked with the `/humanizer` slash command or by asking in plain English to humanize text. It accepts pasted text or file paths and supports voice matching: users can supply 2–3 paragraphs of their own writing, and Humanizer mirrors that sample's rhythm, vocabulary, and tone in the rewrite. Because it is pure Markdown with no runtime code, there are no dependencies to manage and no model-specific coupling.

With nearly 50,000 GitHub stars and ~4,000 forks, Humanizer has become a de facto standard for post-editing AI-generated copy across the agent ecosystem.

## How does it work?
Humanizer is implemented as a single SKILL.md file containing prompt-engineering instructions that teach the host LLM to detect and replace hallmarks of machine-generated writing—overly uniform sentence structure, hedging phrases, redundant qualifiers, and other stylistic tells. When the user invokes `/humanizer` (or asks in natural language), the agent loads the skill's Markdown into its context window and applies the rewriting rules to the supplied text.

The skill is agent-agnostic by design: it contains no code, API calls, or model-specific logic. It relies entirely on the host agent's instruction-following ability. Optional voice matching works by having the user paste a writing sample; the skill then instructs the model to adopt that sample's cadence and diction before rewriting the target text. Distribution is handled by the Skills CLI (npx skills add) for cross-agent installs or as a Claude Code plugin, keeping the install surface minimal.

## Why is it important? (Core Value)
Humanizer solves a practical post-generation problem: AI-assisted writing often carries stylistic fingerprints—repetitive sentence lengths, overuse of em-dashes, hedging language, and a generic "AI voice"—that make output feel synthetic even when the content is accurate. By providing a single, installable skill rather than a standalone app or API, it slots directly into the agent workflows engineers already use (Claude Code, Codex, Cursor), eliminating context switching.

For the user described, this project sits squarely at the intersection of AI/LLM tooling and developer productivity. As someone who curates GitHub projects for an Obsidian knowledge base organized by domain, Humanizer is a concrete example of the emerging "agent skills" pattern: a Markdown file that extends an agent's capabilities without requiring a new runtime or MCP server. It demonstrates prompt-engineering techniques (voice matching, style transfer via few-shot examples) that can be replicated in custom skill development, and it validates the skills.sh distribution model the user is tracking. The project also offers a template for building similar single-file skills—e.g., tone adjusters, summarizers, or domain-specific formatters—that could be added to the user's own agent stack.

## Key Features & Technologies
- Single-file Markdown skill (SKILL.md) with no runtime dependencies
- Cross-agent compatibility via the Skills CLI and Claude Code plugin
- Voice matching using user-supplied writing samples for tone and rhythm transfer
- Invocable via /humanizer slash command or natural-language prompts
- File-path input support for rewriting prose in docs or launch posts
- Distributed through npx skills add and Claude Desktop skill upload

## Difference from Others
Compared to standalone AI writing tools (e.g., ProWritingAI, Grammarly's AI detector, or LLM-based paraphrasers), Humanizer does not run as a separate service or require its own model call; it is a prompt layer that piggybacks on the agent the user is already running. Unlike heavier MCP servers or custom GPT wrappers, it has zero infrastructure overhead—no API keys, no server process, no token-billing beyond the host agent's existing usage.

Against other agent skills in the ecosystem, Humanizer stands out for its narrow, well-defined scope (style de-AI-ification rather than generation or editing) and its voice-matching feature, which lets users calibrate output to their personal writing style. The 49k-star count signals broad community trust and adoption across multiple agent platforms, making it a reference implementation for the skills.sh distribution model.

## 🏢 Organization & Credibility
- **Developer:** blader
- **Reputation:** Unknown
- **Stars:** 49,038
- **Forks:** 3982
- **Recent Activity:** 38 commits in 3 months
- **Credibility Score:** 66.0/100 (Average)
- **Languages:** Python, url
- **Last Release:** 2026-09-06
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
*Source: [GitHub](https://github.com/blader/humanizer)*
