---
source: https://github.com/shannhk/llm-wikid
aliases:
  - llm-wikid
  - shannhk/llm-wikid
tags: [shell, python, obsidian, agent, wiki, markdown, url]
category: Agents/Implementations
stars: 296
org: shannhk
primary_language: Shell
languages: [Shell, url]
credibility_score: 43.5/100
date_processed: 2026-07-07



---

# llm-wikid

**`shannhk/llm-wikid`** · ⭐ 296 · 🔧 Shell

## What is it?
LLM Wikid is an AI-maintained knowledge base designed to live within Obsidian, following Karpathy's LLM Wiki pattern. You simply dump raw sources (PDFs, web pages, articles) into a folder, and an AI agent reads them, compiles structured wiki pages with cross-references, runs bias checks, and maintains a master index. Every question you ask gets filed back in, causing the wiki to compound over time as you use it.

This system is explicitly **not RAG**. While RAG re-derives answers every time by chunking documents and running vector search, LLM Wikid compiles knowledge once into structured wiki pages, keeps them current, and pre-builds cross-references. Karpathy found that at ~100 articles / ~400K words, this compiled approach outperforms RAG for Q&A.

The tool works with any agent that can read markdown and run shell commands: Claude Code, OpenClaw, Hermes, Codex, or your own setup. You start by cloning the repo, opening it as an Obsidian vault, then running your chosen agent (e.g., `claude --dangerously-skip-permissions`). The agent reads CLAUDE.md—the schema file that controls the entire system—and knows everything from there.

## How does it work?
The architecture centers on a single schema file (CLAUDE.md) that defines how the agent should behave. When you initialize the repo, the agent loads this file and immediately understands its purpose: ingest raw documents, generate structured wiki pages, add cross-references between articles, run bias detection, and maintain an index. The agent then processes whatever files you drop into the input directory, writes output to Obsidian-compatible markdown files, and updates the index accordingly.

The system is intentionally agnostic about which agent powers it—any tool capable of reading markdown and executing shell commands will work. This means you can swap in Claude Code, OpenClaw, Hermes, Codex, or build your own custom agent without changing the core repository.

## Why is it important? (Core Value)
This project directly aligns with your objectives as a software engineer and researcher focused on AI agents and developer productivity tools. It offers a self-hosted alternative to SaaS knowledge bases—no external API dependencies, just a local Obsidian vault that compounds over time. The structured wiki approach contrasts with typical RAG-based tools you likely evaluate, giving you a persistent, maintainable knowledge base that respects Obsidian's local-first workflow.

For your interest in self-hosted software and homelab infrastructure, LLM Wikid fits naturally: it's a small repository you can deploy alongside other Obsidian plugins, with no cloud services required. The master index and bias-checking features could enhance your research notes and documentation workflows, while the agent-agnostic design lets you integrate it with whatever automation stack you build.

## Key Features & Technologies
- Works directly with Obsidian vaults as local markdown
- Agent-agnostic: Claude Code, OpenClaw, Hermes, Codex, or custom agents
- Structured wiki page generation from raw sources (PDFs, web pages, articles)
- Pre-built cross-references between generated articles
- Bias detection and checks via LLM analysis
- Maintains a master index of all processed content
- CLAUDE.md schema file that controls the entire system

## Difference from Others
Unlike RAG-based knowledge bases that chunk documents and perform vector search on-the-fly, LLM Wikid takes a compiled approach: it generates structured wiki pages once, maintains them, and pre-builds all cross-references. This matches Karpathy's LLM Wiki pattern where the compiled wiki outperforms RAG for Q&A at scale. The system also differs from Obsidian's native AI tools and other wikis because it requires an external agent to drive the compilation—giving you full control over the process while keeping everything local.

## 🏢 Organization & Credibility
- **Developer:** shannhk
- **Reputation:** Unknown
- **Stars:** 296
- **Forks:** 30
- **Recent Activity:** 14 commits in 3 months
- **Credibility Score:** 43.5/100 (Low)
- **Languages:** Shell, url
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
*Source: [GitHub](https://github.com/shannhk/llm-wikid)*
