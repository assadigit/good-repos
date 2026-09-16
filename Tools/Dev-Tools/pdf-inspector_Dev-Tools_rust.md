---
source: https://github.com/firecrawl/pdf-inspector
aliases:
  - pdf-inspector
  - firecrawl/pdf-inspector
tags: [rust, rust, pdf, text-extraction, markdown, ocr-routing, nodejs, pdf-extraction, pdf-parser, python, pdf-classification, html]
category: Dev-Tools
stars: 16150
org: firecrawl
primary_language: Rust
languages: [Rust, Python, HTML, JavaScript, url]
credibility_score: 70.5/100
date_processed: 2026-08-19
last_release: 2026-08-17
cover: attachments/banners/pdf-inspector_banner.png

---

![banner](attachments/banners/pdf-inspector_banner.png)

# pdf-inspector

> **TL;DR:** Fast Rust PDF library that classifies scanned vs text-based PDFs, extracts text, and converts to Markdown with smart OCR routing.

**`firecrawl/pdf-inspector`** · ⭐ 16,150 · 🔧 Rust

## What is it?
pdf-inspector is a fast Rust library built by Firecrawl for PDF inspection, classification, and text extraction. Its primary purpose is to intelligently detect whether a PDF is text-based or scanned, enabling smart routing decisions that skip expensive OCR services for the ~54% of PDFs that don't need them. The library extracts text with position awareness and converts PDFs to clean Markdown without requiring OCR by default.

The library offers bindings for Python, Node.js, and browser WebAssembly, making it accessible across major language ecosystems. It includes a CLI for native Rust consumers who can opt into selective OCR. Built by Firecrawl to handle text-based PDFs locally in under 200ms, it is designed for high-throughput data pipelines where cost and latency matter.

Key capabilities include smart classification (detecting TextBased, Scanned, ImageBased, or Mixed PDFs in ~10-50ms), position-aware text extraction with font info and X/Y coordinates, automatic multi-column reading order, and Markdown conversion with headings, lists, code blocks, tables, and bold/italic formatting.

## How does it work?
The library is written in Rust and operates by sampling PDF content streams to classify documents. It detects whether a PDF is text-based, scanned, image-based, or mixed, returning a confidence score (0.0-1.0) and per-page OCR routing decisions. For text-based PDFs, it performs position-aware text extraction that captures font information, X/Y coordinates, and automatic multi-column reading order. The extracted text is then converted to clean Markdown, with headings inferred from font size ratios, code blocks detected via monospace font detection, and tables identified through rectangle-based and heuristic methods.

The core is a native Rust library with language bindings for Python (via PyO3), Node.js (via NAPI), and browser WebAssembly. Native Rust and CLI consumers can opt into selective OCR for pages that require it, while the default path skips OCR entirely for text-based content. The classification step is designed to be extremely fast (~10-50ms) so it can be used as a pre-filter in larger data pipelines before committing to expensive OCR services.

## Why is it important? (Core Value)
For a software engineer and researcher focused on AI agents, developer tools, and automation, pdf-inspector is directly relevant to building LLM pipelines that ingest PDF documents. The smart OCR routing decision is a critical component in any document-processing pipeline: it lets you avoid paying for OCR on the majority of PDFs (text-based ones) while still handling scanned documents correctly. The multi-language bindings (Python, Node.js, WASM) make it easy to integrate into existing projects, and the Rust core ensures high performance at scale.

This project also represents a self-hostable alternative to commercial OCR APIs (like AWS Textract or Google Vision). For someone building AI agents that need to process PDFs, this library provides the classification and extraction layer that determines whether to send a document to an LLM with pre-extracted text or to an OCR service first. The 16,150 stars and Firecrawl's production use case signal a mature, battle-tested library. The WASM binding is particularly valuable for browser-based document processing tools.

## Key Features & Technologies
- Smart PDF classification (TextBased, Scanned, ImageBased, Mixed) in ~10-50ms with confidence scoring
- Position-aware text extraction with font info, X/Y coordinates, and multi-column reading order
- Markdown conversion with headings, lists, code blocks, tables, and bold/italic formatting
- Native Rust core with Python, Node.js, and WebAssembly bindings
- Selective OCR routing to skip expensive OCR for ~54% of text-based PDFs
- CLI support for native Rust consumers
- Built by Firecrawl for production-grade, high-throughput data pipelines

## Difference from Others
Compared to general-purpose PDF libraries like PyMuPDF, pdfplumber, or pdf.js, pdf-inspector is specifically optimized for the classification-first workflow: it answers the routing question (do I need OCR?) before doing extraction. This is a pipeline-level optimization that other libraries don't address as a first-class concern. The position-aware extraction with multi-column reading order and font-size-based heading inference gives it an edge over simpler text extractors that lose structural information.

The multi-language Rust core with WASM, Python, and Node.js bindings is also a differentiator. Most PDF libraries are single-language. The fact that it's built by Firecrawl, a production web scraping company, means it's designed for the specific problem of processing PDFs at scale in data pipelines, not just one-off document parsing. The ~200ms local processing time for text-based PDFs makes it a cost-effective alternative to cloud OCR APIs.

## 🏢 Organization & Credibility
- **Developer:** firecrawl
- **Reputation:** Unknown
- **Stars:** 16,150
- **Forks:** 1118
- **Recent Activity:** 149 commits in 3 months
- **Credibility Score:** 70.5/100 (Average)
- **Languages:** Rust, Python, HTML, JavaScript, url
- **Last Release:** 2026-08-17
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
*Source: [GitHub](https://github.com/firecrawl/pdf-inspector)*
