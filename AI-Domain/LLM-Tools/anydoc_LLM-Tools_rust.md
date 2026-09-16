---
source: https://github.com/firecrawl/anydoc
aliases:
  - anydoc
  - firecrawl/anydoc
tags: [rust, rust, llm, document-conversion, markdown, firecrawl, python, javascript, html, shell]
category: LLM-Tools
stars: 17003
org: firecrawl
primary_language: Rust
languages: [Rust, Python, JavaScript, HTML, Shell]
credibility_score: 72.0/100
date_processed: 2026-08-19
last_release: 2026-08-13
cover: attachments/banners/anydoc_banner.png

---

![banner](attachments/banners/anydoc_banner.png)

# anydoc

> **TL;DR:** Rust-powered library converting Word, PDF, Excel, and more to clean Markdown for LLMs, with Node.js, Python, and WASM bindings.

**`firecrawl/anydoc`** · ⭐ 17,003 · 🔧 Rust

## What is it?
anydoc is a fast Rust library built by Firecrawl that converts office documents (Word, PowerPoint, Excel, OpenDocument, RTF, EPUB, CSV, and PDF) into clean GitHub-Flavored Markdown. Its core purpose is to produce LLM-ready text output consistently regardless of the input format, solving the problem of feeding diverse document types into language models without format-specific preprocessing. The library achieves single-digit millisecond conversion times, making it suitable for real-time document processing pipelines.

The project provides bindings for Node.js, Python, and WebAssembly (browser), and is distributed via crates.io, npm (@firecrawl/anydoc), and PyPI (firecrawl-anydoc). It powers Firecrawl Parse, a hosted API that adds OCR models for scanned pages that the core library cannot handle. The WASM build runs entirely client-side, so files are converted locally and never leave the user's machine.

Uniquely, anydoc also ships as an Agent Skill (via agentskills.io), allowing AI agents to read any document they encounter. This positions it not just as a developer library but as a capability layer for agent systems.

## How does it work?
The core conversion engine is written in Rust for performance, parsing each supported document format and emitting consistent GitHub-Flavored Markdown. FFI bindings expose the Rust core to Node.js (via NAPI or similar), Python, and WebAssembly, with the WASM build enabling fully client-side conversion in the browser. The library is MIT licensed and can be self-hosted or used through Firecrawl's hosted Parse API, which layers OCR models on top for scanned or image-based pages.

The Agent Skill distribution allows agents to invoke anydoc as a document-reading capability, making it a plug-in component for agent pipelines rather than a standalone application. The demo page at firecrawl.github.io/anydoc runs the WASM build in-browser, converting files locally without server dependencies.

## Why is it important? (Core Value)
For a software engineer and researcher focused on AI agents, developer tools, and self-hosted alternatives, anydoc is a high-value building block for LLM document processing pipelines. The Agent Skill distribution is directly relevant to integrating document-reading capabilities into AI agent systems, aligning with the user's interest in AI agent skills and MCP-adjacent tooling. The self-hosted Rust core with MIT license offers a credible, performant alternative to SaaS document conversion services. The single-digit millisecond performance and consistent Markdown output make it ideal for building agent workflows that need to ingest diverse office documents in real time. The WASM component adds a zero-infrastructure deployment option for browser-based tools. As a project from Firecrawl, a well-known company in LLM data extraction, it carries credibility and production-grade quality signals.

## Key Features & Technologies
- Rust core engine achieving single-digit millisecond document conversion
- Supports Word, PowerPoint, Excel, OpenDocument, RTF, EPUB, CSV, and PDF inputs
- Node.js, Python, and WebAssembly (browser) bindings with consistent Markdown output
- Ships as an Agent Skill enabling AI agents to read documents they encounter
- Powers Firecrawl Parse hosted API with OCR for scanned pages
- MIT licensed and self-hostable via crates.io, npm, and PyPI

## Difference from Others
Compared to general-purpose document converters like Pandoc, anydoc is purpose-built for LLM consumption rather than format-to-format conversion. Pandoc (Haskell) excels at interconvertibility between markup formats but does not optimize for the clean, consistent Markdown that LLMs need, and lacks the performance characteristics of a Rust implementation. anydoc's consistent output across input formats and sub-millisecond conversion times are specifically tuned for feeding documents into language models at scale.

Compared to other LLM document tools (tokenizers, embedding libraries), anydoc addresses the upstream problem of getting structured text out of binary office formats. The Agent Skill distribution model is unique among document conversion tools, positioning it as a capability for agent systems rather than just a developer library. The WASM build provides a zero-server-deployment option that most document conversion tools lack.

## 🏢 Organization & Credibility
- **Developer:** firecrawl
- **Reputation:** Unknown
- **Stars:** 17,003
- **Forks:** 973
- **Recent Activity:** 109 commits in 3 months
- **Credibility Score:** 72.0/100 (Average)
- **Languages:** Rust, Python, JavaScript, HTML, Shell
- **Last Release:** 2026-08-13
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
*Source: [GitHub](https://github.com/firecrawl/anydoc)*
