---
source: https://github.com/aouicher/graphmind
aliases:
  - graphmind
  - aouicher/graphmind
tags: [rust, rust, mcp, ai, code-intelligence, tree-sitter, ai-agent, chatgpt, claude, claude-code, cursor, graph]
category: MCP
stars: 182
org: aouicher
primary_language: Rust
languages: [Rust, TypeScript, Shell, CSS, Python]
credibility_score: 57.0/100
date_processed: 2026-07-05
last_release: 2026-06-12
cover: attachments/banners/graphmind_banner.png

---

![banner](attachments/banners/graphmind_banner.png)

# graphmind

> **TL;DR:** Local-first code intelligence for AI assistants: turns your codebase into a queryable knowledge graph with 25 MCP tools.

**`aouicher/graphmind`** · ⭐ 182 · 🔧 Rust

## What is it?
GraphMind is a local-first code intelligence tool that converts your entire codebase into a persistent knowledge graph AI assistants can query, navigate, and remember. It provides 25 Model Context Protocol (MCP) tools enabling reasoning about structure, dependencies, dead code, and blast radius without re-reading the whole repository each session.

The project builds an AST-based structural graph using tree-sitter to parse over 30 programming languages, complemented by semantic embeddings for memory retention across sessions. This reduces token usage by up to 5,700× compared to raw search—saving roughly 10M tokens per session—and works seamlessly with Claude Code, Cursor, Windsurf, Cline, Zed, Continue, and any MCP-compatible AI assistant.

GraphMind is distributed as both a command-line tool and a desktop application (Mac & Windows), making it easy to integrate into your development workflow. Its MIT license and Rust implementation ensure it's self-hostable and privacy-focused, aligning with the goal of building a personal knowledge base of useful tools without relying on cloud services.

## How does it work?
GraphMind is written in Rust and uses tree-sitter to parse source code across 30+ languages, building an AST-based structural graph that persists locally. Semantic embeddings are computed to retain context across AI sessions, dramatically reducing token consumption (up to 5,700× fewer tokens than raw search). The project exposes 25 MCP tools via a Model Context Protocol server, allowing any MCP-compatible AI assistant to query the graph directly from your machine without sending code to the cloud.

## Why is it important? (Core Value)
GraphMind solves the problem of AI assistants starting each session from zero, forcing them to re-read entire codebases and forget prior decisions. By turning your repository into a persistent knowledge graph, it retains structural and semantic context across sessions, enabling efficient reasoning about architecture, dependencies, and blast radius. For a software engineer curating tools for an Obsidian vault, GraphMind fits the AI-Domain or Tools category—offering self-hosted, privacy-focused code intelligence that directly improves developer workflow while aligning with interests in MCP servers, developer productivity tools, and self-hostable alternatives to SaaS products.

## Key Features & Technologies
- 25 MCP tools for code intelligence
- AST-based structural graph via tree-sitter (30+ languages)
- Semantic embeddings for memory retention
- CLI tool and desktop app (Mac & Windows)
- MIT license

## Difference from Others
Unlike cloud-based code search tools (e.g., GitHub Code Search) or generic LLM wrappers that re-index the entire repository each query, GraphMind builds a local, persistent graph that retains context across sessions. It also provides 25 specialized MCP tools rather than just general-purpose search, and supports a wide range of languages via tree-sitter. The desktop app and CLI make it more accessible than purely API-first solutions.

## 🏢 Organization & Credibility
- **Developer:** aouicher
- **Reputation:** Unknown
- **Stars:** 182
- **Forks:** 13
- **Recent Activity:** 575 commits in 3 months
- **Credibility Score:** 57.0/100 (Low)
- **Languages:** Rust, TypeScript, Shell, CSS, Python
- **Last Release:** 2026-06-12
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
*Source: [GitHub](https://github.com/aouicher/graphmind)*
