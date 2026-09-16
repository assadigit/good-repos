---
source: https://github.com/DeusData/codebase-memory-mcp
aliases:
  - codebase-memory-mcp
  - DeusData/codebase-memory-mcp
tags: [c, c, mcp, code-intelligence, knowledge-graph, developer-tools, claude-code, code-analysis, mcp-server, model-context-protocol, sqlite, tree-sitter]
category: MCP
stars: 27304
org: DeusData
primary_language: C
languages: [C, C++, Shell, TypeScript, Python]
credibility_score: 72.0/100
date_processed: 2026-07-07
last_release: 2026-06-12
cover: attachments/banners/codebase-memory-mcp_banner.png

---

![banner](attachments/banners/codebase-memory-mcp_banner.png)

# codebase-memory-mcp

> **TL;DR:** Pure C MCP server indexing codebases into a knowledge graph — 158 languages, sub-ms queries, 99% fewer tokens.

**`DeusData/codebase-memory-mcp`** · ⭐ 27,304 · 🔧 C

## What is it?
codebase-memory-mcp is a high-performance Model Context Protocol (MCP) server built in pure C that indexes entire codebases into a persistent knowledge graph stored in SQLite. It supports 158 programming languages through tree-sitter parsing and provides sub-millisecond query performance, requiring dramatically fewer tokens than alternative approaches. The project is distributed as a single static binary with zero runtime dependencies, making it lightweight and self-contained.

## How does it work?
The server uses tree-sitter for parsing code across multiple languages into an AST-based knowledge graph stored in SQLite. Its pure C implementation enables sub-millisecond query times while maintaining compatibility with the MCP protocol for seamless integration with LLM-based tools. The hybrid LSP (Language Server Protocol) support allows it to work with 9 different language servers, and it includes built-in agents functionality for orchestrating AI workflows.

## Why is it important? (Core Value)
This project is critical infrastructure for developers building AI-powered development tools. For your specific objectives as a software engineer curating GitHub projects: this MCP server directly supports your interest in AI/LLM tooling (agents, MCP) and provides a self-hostable alternative to SaaS code intelligence products. The pure C implementation means zero runtime dependencies—perfect for homelab deployment with minimal resource overhead. At 27K+ stars with OpenSSF Scorecard certified and SLSA Level 3 supply chain security, it's production-ready. It would fit naturally into your Obsidian vault under 'MCP' or 'Tools' categories, and could power agents that need to understand codebases without relying on external services.

## Key Features & Technologies
- Pure C implementation (zero dependencies)
- Supports 158 programming languages
- Hybrid LSP support (9 languages)
- SQLite knowledge graph storage
- Sub-millisecond query performance
- Single static binary distribution
- OpenSSF Scorecard certified
- SLSA Level 3 supply chain security

## Difference from Others
Unlike Python-based MCP servers (e.g., mcp-server-git) or Node implementations, this is written in pure C for maximum performance and minimal footprint. Compared to other code indexing tools, it specifically implements the MCP protocol standard, making it directly compatible with Claude Code, Cursor, Windsurf, Aider, Gemini CLI, and Opencode—all listed in its topics. The knowledge graph approach (SQLite-backed) differs from simple file-system indexing or embedding-only solutions, offering both semantic understanding and deterministic query performance.

## 🏢 Organization & Credibility
- **Developer:** DeusData
- **Reputation:** Unknown
- **Stars:** 27,304
- **Forks:** 2027
- **Recent Activity:** 918 commits in 3 months
- **Credibility Score:** 72.0/100 (Average)
- **Languages:** C, C++, Shell, TypeScript, Python
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
*Source: [GitHub](https://github.com/DeusData/codebase-memory-mcp)*
