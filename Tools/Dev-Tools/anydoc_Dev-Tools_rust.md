---
source: https://github.com/firecrawl/anydoc
aliases:
  - anydoc
  - firecrawl/anydoc
tags: [rust, rust, document-conversion, markdown, firecrawl, llm, python, javascript, html, shell]
category: Dev-Tools
stars: 17007
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

> **TL;DR:** Rust document converter that turns Word, PDF, Excel, PowerPoint, and more into clean Markdown, with Node.js, Python, and WASM bindings.

**`firecrawl/anydoc`** · ⭐ 17,007 · 🔧 Rust

## What is it?
anydoc is a fast Rust library built by Firecrawl that converts office and web document formats—Word, PowerPoint, Excel, OpenDocument, RTF, EPUB, CSV, and PDF—into clean GitHub-Flavored Markdown. It is designed to produce a single, consistent Markdown output regardless of the input format, making it easy to feed documents into LLM pipelines or any text-based workflow. The library is available as a Rust crate, an npm package, a Python package, and a WebAssembly build for browser-based conversion.

The project is open-source under the MIT license and ships as an Agent Skill, allowing AI agents to read any document they encounter. It powers Firecrawl Parse, a hosted API that adds OCR models for scanned pages that anydoc cannot process on its own. A public demo runs the entire conversion locally in the browser via WebAssembly, so files never leave the user's machine.

## How does it work?
anydoc is written in Rust for performance, targeting single-digit millisecond conversion times. It exposes bindings for Node.js (npm), Python (PyPI), and WebAssembly (browser), letting developers integrate document conversion into virtually any stack. The Rust core handles parsing of each format and normalizing the output to GitHub-Flavored Markdown. For the hosted Firecrawl Parse API, OCR models are layered on top to handle scanned pages that the core parser cannot extract text from.

The WebAssembly build compiles the Rust library to run entirely client-side in a browser, enabling zero-infrastructure document conversion. The project also ships as an Agent Skill, so AI agents can invoke it to read documents they encounter during autonomous workflows.

## Why is it important? (Core Value)
anydoc solves the problem of inconsistent, lossy document-to-text conversion that plagues LLM pipelines and content workflows. By normalizing eight different document formats into a single clean Markdown output, it removes the need for per-format parsers and the brittle text extraction that comes with them. For the user, this is a self-hostable, open-source alternative to the hosted Firecrawl Parse API, fitting their interest in self-hostable SaaS alternatives. It also directly supports their AI agent and LLM tooling interests: the Agent Skill packaging means their agents can natively read any office document, and the LLM-ready Markdown output makes it a drop-in component for RAG pipelines and document-grounded agent systems. The Rust core with WASM bindings also offers a low-latency, locally-runnable option that aligns with their homelab and developer productivity goals.

## Key Features & Technologies
- Rust core with single-digit millisecond conversion speed
- Supports Word, PowerPoint, Excel, OpenDocument, RTF, EPUB, CSV, and PDF inputs
- Node.js, Python, and WebAssembly (browser) bindings
- Ships as an Agent Skill for AI agent document reading
- Powers Firecrawl Parse hosted API with OCR for scanned pages
- MIT-licensed and fully self-hostable

## Difference from Others
Compared to general-purpose document converters like pandoc or docx2txt, anydoc targets a single consistent Markdown output across all supported formats, rather than producing format-specific or inconsistent results. Unlike pandoc, which is multi-language and slower, anydoc is written in Rust and optimized for sub-millisecond performance. Compared to other LLM document-parsing tools, anydoc is format-agnostic and lightweight enough to run in the browser via WASM, while still shipping as an Agent Skill for autonomous agent workflows—a combination not commonly found in competing tools. Its origin from Firecrawl, a major web-scraping company, adds credibility and production-grade reliability.

## 🏢 Organization & Credibility
- **Developer:** firecrawl
- **Reputation:** Unknown
- **Stars:** 17,007
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
