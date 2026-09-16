---
source: https://github.com/thedotmack/claude-mem
aliases:
  - claude-mem
  - thedotmack/claude-mem
tags: [javascript, python, ai-agents, memory, vector-db, rag, embeddings, ai, ai-memory, anthropic, artificial-intelligence, claude]
category: Agents/Implementations
stars: 88247
org: thedotmack
primary_language: JavaScript
languages: [JavaScript, TypeScript, Shell, HTML, Dockerfile]
credibility_score: 72.0/100
date_processed: 2026-07-23
last_release: 2026-07-13
cover: attachments/banners/claude-mem_banner.png

---

![banner](attachments/banners/claude-mem_banner.png)

# claude-mem

> **TL;DR:** Persistent memory layer for AI agents – captures session actions, AI-compresses context, injects relevant info into future sessions. Works with Claude Code, OpenClaw, Codex, Gemini, Hermes, Copilot, OpenCode.

**`thedotmack/claude-mem`** · ⭐ 88,247 · 🔧 JavaScript

## What is it?
Claude-Mem is a persistent memory layer designed specifically for AI agents. It captures everything your agent does during sessions, compresses it with AI summarization, and injects relevant context back into future sessions, enabling agents to maintain knowledge across long-running interactions. The project supports Claude Code, OpenClaw, Codex, Gemini, Hermes, Copilot, OpenCode and many other agent frameworks.

Technically, the system records all agent actions during a session and stores them as embeddings in ChromaDB for efficient retrieval. When needed, it performs similarity searches to retrieve relevant past context, compresses the retrieved data with AI summarization, and injects the compressed context back into the agent's session memory. SQLite is used as a lightweight fallback for local storage when vector DB isn't available.

## How does it work?
The architecture follows a capture-compress-inject pattern: during any agent session, all actions are logged and converted to embeddings stored in ChromaDB. At retrieval time, semantic similarity search finds relevant historical context, which is then compressed using AI summarization before being injected back into the agent's memory space. This pipeline enables persistent context across sessions without overwhelming the agent with raw history. SQLite provides a minimal fallback storage layer for environments where vector databases aren't desired.

## Why is it important? (Core Value)
Claude-Mem addresses the critical problem of losing context across long-running AI agent sessions, which is one of the most common failure modes in multi-turn agent interactions. By persisting and compressing memories intelligently, it enables agents to recall past interactions without needing to re-execute them, dramatically improving user experience and agent reliability.

For a self-hosted developer like yourself, this project offers significant value: it provides a privacy-friendly memory layer that can replace SaaS services like mem0 or OpenMemory, aligns with your interests in AI/LLM tooling and developer productivity, and gives you a reusable component to integrate into your Obsidian vault knowledge base. It also demonstrates self-hostable alternatives to commercial memory services, which is a core part of your stated objectives.

## Key Features & Technologies
- Captures all agent actions during sessions
- AI-compressed context memory layer
- Multi-agent support (Claude Code, OpenClaw, Codex, Gemini, Hermes, Copilot, OpenCode)
- ChromaDB vector store for embeddings
- SQLite fallback storage
- RAG integration capabilities
- Memory engine abstraction

## Difference from Others
Unlike mem0, which focuses on personal assistant memory and is more of a SaaS-oriented product, Claude-Mem is explicitly agent-centric and supports multiple LLM frameworks out of the box. OpenMemory provides general-purpose memory storage but lacks the AI compression step that makes Claude-Mem efficient with context. SuperMemory is primarily for data storage without intelligent summarization. Claude-Mem stands out by offering persistent memory across sessions combined with AI-based summarization and broad multi-agent compatibility, making it a specialized tool for the agent ecosystem rather than a general memory service.

## 🏢 Organization & Credibility
- **Developer:** thedotmack
- **Reputation:** Unknown
- **Stars:** 88,247
- **Forks:** 7660
- **Recent Activity:** 391 commits in 3 months
- **Credibility Score:** 72.0/100 (Average)
- **Languages:** JavaScript, TypeScript, Shell, HTML, Dockerfile
- **Last Release:** 2026-07-13
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
*Source: [GitHub](https://github.com/thedotmack/claude-mem)*
