---
source: https://github.com/breferrari/obsidian-mind
aliases:
  - obsidian-mind
  - breferrari/obsidian-mind
tags: [typescript, node, obsidian, claude-code, codex-cli, semantic-search, ai-agents, gemini-cli, knowledge-management, obsidian-vault, persistent-memory, second-brain]
category: LLM-Tools
stars: 3468
org: breferrari
primary_language: TypeScript
languages: [TypeScript, JavaScript, url]
credibility_score: 56.0/100
date_processed: 2026-07-22
last_release: 2026-07-19
cover: attachments/banners/obsidian-mind_banner.png

---

![banner](attachments/banners/obsidian-mind_banner.png)

# obsidian-mind

> **TL;DR:** Obsidian vault giving AI coding agents persistent memory; built for Claude Code with hooks for Codex CLI and Gemini CLI.

**`breferrari/obsidian-mind`** · ⭐ 3,468 · 🔧 TypeScript

## What is it?
Obsidian Mind is a self-organizing Obsidian vault designed to give AI coding agents persistent memory. It provides full support for Claude Code and working hooks for Codex CLI and Gemini CLI, allowing agents to access notes, links, indexes, and performance tracking across sessions. Every conversation builds on the last, creating a growing knowledge base that agents can reference.

The vault integrates deeply with Obsidian's ecosystem, using Node.js for runtime compatibility and Obsidian CLI for automation. It leverages semantic search via QMD to quickly surface relevant notes, and supports Obsidian Skills API for additional capabilities. Templates and indexes help organize content as the agent works.

Built as open-source under MIT license, it offers a self-hosted alternative to SaaS AI memory tools while providing developer productivity features tailored for Obsidian users.

## How does it work?
Obsidian Mind uses Node.js (v22+) as its runtime, interacting with Obsidian via the Obsidian API and Obsidian CLI for automation. The vault maintains a persistent session state where each conversation is indexed and linked to previous notes, enabling agents to recall past discussions. Semantic search powered by QMD allows fast retrieval of relevant content, while hooks from Claude Code, Codex CLI, and Gemini CLI provide command access to the vault's functions.

The architecture includes integration points for Obsidian Skills API, allowing additional capabilities beyond basic note management. Templates are used to structure new notes, and indexes track performance metrics across sessions, ensuring a self-organizing knowledge base that grows with agent usage.

## Why is it important? (Core Value)
This project directly addresses the persistent memory gap for AI coding agents, which is a critical limitation in current tooling. By providing a self-hosted, open-source solution that works with Claude Code (Anthropic), Codex CLI (OpenAI), and Gemini CLI (Google), it gives developers a reliable alternative to SaaS-based AI memory services. For your workflow, Obsidian Mind enables you to curate a personal knowledge base of useful tools and frameworks, organized within your Obsidian vault under categories like AI-Domain or Tools. Its integration with Obsidian CLI and Skills supports your interest in developer productivity tools and self-hosted software, making it a credible adoption candidate.

The semantic search and indexing features align with your objectives to discover tools that improve development workflow and learn about new approaches to automation. As an MIT-licensed project from a reputable open-source contributor, it meets your criteria for credibility and self-hostability, offering both immediate utility and potential for integration into larger agent frameworks or MCP servers.

## Key Features & Technologies
- Uses Node.js runtime
- Integrates with Obsidian CLI
- Supports Obsidian Skills API
- Provides semantic search via QMD
- Full Claude Code support
- Hooks for Codex CLI and Gemini CLI
- MIT-licensed open source

## Difference from Others
Similar Obsidian plugins often focus on static note-taking or generic AI integration without persistent memory across agent sessions. Obsidian Mind stands out by being specifically built for coding agents (Claude Code, Codex CLI, Gemini CLI) and providing hooks that let agents query notes, links, indexes, and performance metrics. Unlike MCP servers or reference implementations, it offers a self-hosted alternative to SaaS AI memory tools while maintaining deep Obsidian ecosystem integration through Obsidian CLI and Skills.

Its semantic search via QMD and template-based organization provide features that many competing tools lack, making it a more robust choice for developers who need both memory persistence and easy content management within Obsidian.

## 🏢 Organization & Credibility
- **Developer:** breferrari
- **Reputation:** Unknown
- **Stars:** 3,468
- **Forks:** 433
- **Recent Activity:** 40 commits in 3 months
- **Credibility Score:** 56.0/100 (Low)
- **Languages:** TypeScript, JavaScript, url
- **Last Release:** 2026-07-19
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
*Source: [GitHub](https://github.com/breferrari/obsidian-mind)*
