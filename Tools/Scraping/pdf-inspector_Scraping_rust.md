---
source: https://github.com/firecrawl/pdf-inspector
aliases:
  - pdf-inspector
  - firecrawl/pdf-inspector
tags: [rust, rust, pdf, pdf-extraction, ocr-routing, firecrawl, markdown, nodejs, pdf-parser, python, text-extraction, pdf-classification]
category: Scraping
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

> **TL;DR:** Fast Rust PDF library that classifies text-based vs scanned PDFs and extracts text to Markdown, with Python/Node/WASM bindings.

**`firecrawl/pdf-inspector`** · ⭐ 16,150 · 🔧 Rust

## What is it?
pdf-inspector is a high-performance Rust library built by Firecrawl for PDF inspection, classification, and text extraction. Its primary purpose is to quickly determine whether a PDF is text-based or scanned (in ~10-50ms), enabling smart routing decisions that skip expensive OCR services for the ~54% of PDFs that don't need them. It extracts position-aware text and converts it to clean Markdown with headings, lists, code blocks, and tables.

The library provides bindings for Python (PyPI), Node.js (npm), and browser WebAssembly, making it accessible across the major language ecosystems. Native Rust and CLI consumers can optionally enable selective OCR. It is designed to handle text-based PDFs locally in under 200ms, eliminating the need for cloud-based OCR services in production pipelines.

## How does it work?
The core engine is written in Rust for performance. It samples PDF content streams to classify documents into four categories — TextBased, Scanned, ImageBased, or Mixed — returning a confidence score (0.0-1.0) and per-page OCR routing decisions. For text-based PDFs, it performs position-aware extraction that captures font information, X/Y coordinates, and automatic multi-column reading order. The extracted text is then converted to Markdown, with headings inferred from font size ratios (H1-H4), bullet/numbered/letter lists, code blocks via monospace font detection, and tables via rectangle-based and heuristic detection.

The Rust core is wrapped with FFI bindings for Python (via PyO3), Node.js (via N-API), and WebAssembly for browser use. This multi-language binding approach means a single Rust implementation serves all three ecosystems, ensuring consistent behavior and performance across platforms.

## Why is it important? (Core Value)
For a developer focused on AI/LLM tooling, scraping, and developer productivity, this project solves a concrete and costly problem in LLM data pipelines: deciding whether to run expensive OCR on every PDF. By classifying PDFs in under 50ms and skipping OCR for text-based documents, it directly reduces infrastructure costs and latency in scraping-to-LLM pipelines. As a Rust library with Python, Node, and WASM bindings, it fits naturally into the user's multi-language workflow and can be self-hosted (MIT license), aligning with their interest in self-hostable alternatives to SaaS products. Being built by Firecrawl — a well-known scraping company — adds credibility, and the ~54% text-based PDF stat demonstrates real-world impact on cost optimization.

## Key Features & Technologies
- Smart PDF classification (TextBased, Scanned, ImageBased, Mixed) in ~10-50ms with confidence scores
- Position-aware text extraction with font info, X/Y coordinates, and multi-column reading order
- Markdown conversion with headings, lists, code blocks, and table detection
- Python, Node.js, and WebAssembly bindings from a single Rust core
- Per-page OCR routing decisions to minimize expensive OCR calls
- Selective OCR opt-in for native Rust and CLI consumers
- Sub-200ms local processing for text-based PDFs

## Difference from Others
Most PDF libraries (pdfplumber, PyPDF2, pdf.js) focus solely on text extraction or rendering. pdf-inspector takes a classification-first approach: its primary output is a routing decision (do we need OCR?), not just extracted text. This makes it a decision-layer component rather than a pure extraction tool. It is also the only PDF library in this space that ships with first-class Rust core plus Python, Node.js, and WASM bindings, giving it a performance and language-coverage advantage. The fact that it is built by Firecrawl for their own production scraping pipeline signals battle-tested reliability at scale, and the explicit ~54% text-based PDF statistic grounds its value in real production data.

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
