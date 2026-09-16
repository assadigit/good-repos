---
source: https://github.com/tobi/qmd
aliases:
  - qmd
  - tobi/qmd
tags: [typescript, cli, search, llm, nodejs, local, python, shell, javascript, nix]
category: Automation
stars: 27501
org: tobi
primary_language: TypeScript
languages: [TypeScript, Python, Shell, JavaScript, Nix]
credibility_score: 72.0/100
date_processed: 2026-07-06
last_release: 2026-05-29
cover: attachments/banners/qmd_banner.png

---

![banner](attachments/banners/qmd_banner.png)

# qmd

> **TL;DR:** Local CLI search engine combining BM25, vector, and LLM re-ranking for markdown docs.

**`tobi/qmd`** · ⭐ 27,501 · 🔧 TypeScript

## What is it?
QMD is a command-line tool that indexes your personal knowledge base—markdown notes, meeting transcripts, documentation, and more. It supports multiple search modes: fast keyword search via BM25, semantic search using vector embeddings, and LLM-powered re-ranking to surface the most relevant documents. You organize documents into collections (e.g., notes, meetings) and attach contextual metadata that guides the LLM when selecting results. All processing runs locally on your machine using node-llama-cpp and GGUF models, keeping your data private.

The workflow is straightforward: install via npm or bun, create collections with `qmd collection add`, add context with `qmd context add`, generate embeddings with `qmd embed`, then search with `qmd search` or `qmd vsearch`. The CLI also lets you query by natural language, making it ideal for agentic flows that need to retrieve information from your own docs without sending data to a cloud service.

## How does it work?
QMD's architecture combines three search layers. First, BM25 indexes all text in your documents for fast keyword queries. Second, it generates vector embeddings (likely using a small language model via node-llama-cpp) to enable semantic similarity searches. Third, an LLM re-ranks the top results from both layers, incorporating any context metadata you've added to each collection. The tool stores collections with associated context fields that act as hints for the LLM when deciding which documents are most relevant to a query. All of this runs locally without any external services.

## Why is it important? (Core Value)
For a software engineer focused on self-hosted tools, AI/LLM infrastructure, and automation, QMD directly addresses several objectives. It provides an on-device search engine that works seamlessly with Obsidian vaults or any markdown-based knowledge base, eliminating the need to ship documents to SaaS services like Notion or Google Docs. The local LLM re-ranking capability aligns with your interest in AI/LLM tooling and gives you control over which models run where. Because it's a CLI tool, you can script it into larger automation workflows—e.g., automatically indexing new notes after meetings or enriching search results for an agentic assistant. Its high star count (27,501) indicates credibility and active maintenance, making it a reliable addition to your homelab stack.

## Key Features & Technologies
- BM25 full-text indexing
- Vector semantic search
- LLM re-ranking with node-llama-cpp
- GGUF model support
- CLI interface (npm/bun)
- Collection-based organization
- Context metadata for LLM guidance

## Difference from Others
Compared to Obsidian's built-in search or generic tools like Exa, QMD offers a hybrid approach: it doesn't rely solely on vectors or keywords but combines them with an LLM re-ranking step that leverages local GGUF models. This gives it better relevance for natural language queries while keeping everything offline. Other local search solutions often require heavy dependencies (e.g., Python + transformers) or cloud APIs; QMD runs entirely within Node.js, making it lightweight and easy to bundle into containers or servers.

## 🏢 Organization & Credibility
- **Developer:** tobi
- **Reputation:** Unknown
- **Stars:** 27,501
- **Forks:** 1722
- **Recent Activity:** 143 commits in 3 months
- **Credibility Score:** 72.0/100 (Average)
- **Languages:** TypeScript, Python, Shell, JavaScript, Nix
- **Last Release:** 2026-05-29
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
*Source: [GitHub](https://github.com/tobi/qmd)*
