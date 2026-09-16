---
source: https://github.com/yilewang/llm-for-zotero
aliases:
  - llm-for-zotero
  - yilewang/llm-for-zotero
tags: [typescript, python, zotero, llm-agent, rag, mcp, academic-paper, literature-analysis, zotero-plugin, codex, research-tool, css]
category: Agents/Implementations
stars: 2322
org: yilewang
primary_language: TypeScript
languages: [TypeScript, CSS, HTML, Python, JavaScript]
credibility_score: 62.0/100
date_processed: 2026-07-17
last_release: 2026-07-16
cover: attachments/banners/llm-for-zotero_banner.png

---

![banner](attachments/banners/llm-for-zotero_banner.png)

# llm-for-zotero

> **TL;DR:** Self-hosted research agent that integrates LLMs with Zotero for literature analysis via RAG and MCP.

**`yilewang/llm-for-zotero`** · ⭐ 2,322 · 🔧 TypeScript

## What is it?
llm-for-zotero is an open-source research agent system designed to extend Zotero with AI-powered capabilities. It transforms your personal academic library into an intelligent research assistant, enabling automated literature analysis, paper summarization, and answering research questions based on the contents of your Zotero collection. The project is deeply integrated with Zotero using its official Plugin Template, making it a native extension rather than a separate tool you must manually connect.

## How does it work?
The system operates as a Zotero plugin (written in Python) that intercepts user interactions within the Zotero interface and routes relevant queries to an LLM-powered agent. It leverages Retrieval Augmented Generation (RAG) by indexing paper metadata and contents from your library, then retrieving relevant documents based on query context before synthesizing answers. The project also incorporates Codex model support for code-generation tasks and integrates with MCP (Model Context Protocol) servers for tool orchestration, allowing the agent to interact with external services and perform complex research workflows.

## Why is it important? (Core Value)
This project directly addresses your interests in AI/LLM tooling, self-hosted software, and MCP servers. As a self-hosted alternative to SaaS-based research agents, it gives you full control over your data and models without relying on third-party services. The Zotero plugin architecture means you can keep your entire research workflow contained within your existing library system rather than migrating to a new platform. Its MCP integration aligns with your goal to discover MCP servers for tool orchestration in agent projects. Being open-source under AGPL, it's also suitable for inclusion in your Obsidian vault as a credible, adoptable tool that improves research productivity.

## Key Features & Technologies
- Zotero plugin integration using official Plugin Template
- LLM-powered RAG (Retrieval Augmented Generation) for literature analysis
- Codex model support for code-generation tasks
- MCP server compatibility for tool orchestration
- Open-source under AGPL v3 license
- Self-hosted with no SaaS dependencies
- Academic paper indexing and metadata extraction

## Difference from Others
While Zotero AI and other research agents typically integrate via generic LLM APIs or require separate installations, llm-for-zotero is purpose-built as a Zotero plugin, making it the most seamless integration available. Its combination of RAG with MCP server support distinguishes it from simpler chat-based plugins that lack orchestration capabilities. The project also explicitly targets academic workflows, offering features like literature analysis and paper summarization that generic agents don't prioritize.

## 🏢 Organization & Credibility
- **Developer:** yilewang
- **Reputation:** Unknown
- **Stars:** 2,322
- **Forks:** 117
- **Recent Activity:** 454 commits in 3 months
- **Credibility Score:** 62.0/100 (Average)
- **Languages:** TypeScript, CSS, HTML, Python, JavaScript
- **Last Release:** 2026-07-16
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
*Source: [GitHub](https://github.com/yilewang/llm-for-zotero)*
