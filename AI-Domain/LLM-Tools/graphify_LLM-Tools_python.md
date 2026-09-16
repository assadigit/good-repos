---
source: https://github.com/Graphify-Labs/graphify
aliases:
  - graphify
  - Graphify-Labs/graphify
tags: [python, python, llm-tools, tree-sitter, graphrag, skills, claude-code, knowledge-graph, codex, openclaw, antigravity, gemini]
category: LLM-Tools
stars: 79072
org: Graphify-Labs
primary_language: Python
languages: [Python, Dockerfile, url]
credibility_score: 72.0/100
date_processed: 2026-07-07
last_release: 2026-07-06
cover: attachments/banners/graphify_banner.png

---

![banner](attachments/banners/graphify_banner.png)

# graphify

> **TL;DR:** Turns any project folder into a queryable knowledge graph for AI coding assistants.

**`Graphify-Labs/graphify`** · ⭐ 79,072 · 🔧 Python

## What is it?
Graphify is an AI coding assistant skill that transforms any folder of code, SQL schemas, R scripts, shell scripts, docs, papers, images, or videos into a queryable knowledge graph. It integrates with multiple AI models including Claude Code, Codex, OpenCode, Cursor, Gemini CLI, and more, enabling developers to build robust knowledge bases from their project artifacts.

The tool parses code using tree-sitter for syntax-aware extraction, builds a unified graph combining application code, database schemas, and infrastructure, and applies graphrag techniques to generate embeddings or link prompts. It also incorporates Leiden community detection for clustering nodes within the graph, providing a structured representation that can be queried and used by AI agents.

## How does it work?
Graphify operates as a self-contained skill that ingests files from arbitrary project folders. It uses tree-sitter to parse source code into abstract syntax trees, extracts documentation and media assets, and constructs a knowledge graph that unifies application code, database schemas, and infrastructure components. The graph is enriched with embeddings via retrieval augmented generation (RAG) techniques and further structured using Leiden community detection algorithms to identify clusters of related entities.

The resulting knowledge graph can be queried through an API or CLI, providing a single source of truth for AI coding assistants. This architecture allows multiple models to interact with the same underlying graph structure, making Graphify a versatile tool for building custom agent workflows and knowledge bases.

## Why is it important? (Core Value)
For developers focused on AI agents and developer tools, Graphify provides a self-hostable alternative to cloud-based knowledge graph services. It directly addresses the need for integrating multiple AI models into a unified workflow, enabling researchers to curate their own knowledge base of useful tools. The ability to turn any project folder into a queryable graph aligns with interests in automation and scraping, offering a foundation for building custom agent capabilities.

Its support for Claude Code, Codex, OpenCode, Cursor, Gemini CLI, and more makes it particularly valuable for those seeking flexible AI coding assistants without vendor lock-in. Graphify can be integrated into Obsidian vaults or other personal knowledge management systems, providing a credible, open-source solution that improves development productivity by consolidating disparate project artifacts into a single queryable structure.

## Key Features & Technologies
- Supports multiple AI coding assistants (Claude Code, Codex, OpenCode, Cursor, Gemini CLI)
- Uses tree-sitter for syntax-aware parsing
- Implements graphrag techniques
- Applies Leiden community detection
- Retrieval Augmented Generation (RAG) integration
- Handles diverse file types (code, docs, images, videos)
- Self-hosted knowledge graph

## Difference from Others
Compared to other knowledge graph tools for codebases like CodeMap or generic RAG indexing solutions, Graphify stands out by being a skill that can be used across multiple AI models rather than being model-specific. Its integration of tree-sitter provides precise syntax awareness, while the combination of graphrag and Leiden community detection offers advanced clustering capabilities not commonly found in similar projects.

Additionally, Graphify's unified approach to combining application code, database schemas, and infrastructure into a single graph differentiates it from tools that only index documentation or treat code as separate entities. This holistic representation enables more coherent querying and reasoning across heterogeneous project artifacts, making it uniquely suited for developers building custom AI agent workflows.

## 🏢 Organization & Credibility
- **Developer:** Graphify-Labs
- **Reputation:** Unknown
- **Stars:** 79,072
- **Forks:** 7798
- **Recent Activity:** 951 commits in 3 months
- **Credibility Score:** 72.0/100 (Average)
- **Languages:** Python, Dockerfile, url
- **Last Release:** 2026-07-06
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
*Source: [GitHub](https://github.com/Graphify-Labs/graphify)*
