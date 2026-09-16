---
source: "https://github.com/docling-project/docling"
aliases:
  - docling
  - docling-project/docling

tags: [python, document-parsing, pdf, rag, llm, ai, convert, documents, tables, document-parser, docx]
category: "LLM-Tools"
stars: 66496
org: "docling-project"
primary_language: Python
languages: [Python, Shell, Dockerfile, Makefile, url]
credibility_score: 69.0/100
date_processed: 2026-09-16
last_release: 2026-09-16
cover: attachments/banners/docling_banner.png

---

![banner](attachments/banners/docling_banner.png)

# docling

> **TL;DR:** Document parser that converts PDFs, DOCX, PPTX, XLSX, and images into structured text, tables, and JSON to feed RAG and gen-AI pipelines.

**`docling-project/docling`** · ⭐ 66,496 · 🔧 Python

## What is it?
Docling is an open-source Python library (66k+ stars) whose stated mission is to "get your documents ready for gen AI." It ingests a wide range of document formats—PDF, DOCX, PPTX, XLSX, HTML, and images—and converts them into clean, structured representations such as Markdown and JSON that preserve reading order, tables, and document structure. Rather than simply dumping raw text, Docling parses documents so the content is suitable for retrieval-augmented generation (RAG), chunking, and feeding directly into large language models.

The project is backed by a research paper (arXiv:2408.09869) and published on PyPI as the `docling` package. It uses modern Python tooling (uv, Ruff, Pydantic v2) and ships with live documentation at docling-project.github.io/docling/. Its topic tags emphasize its core capabilities: document parsing, table extraction, PDF-to-JSON, PDF-to-text, and conversion of office formats.

## How does it work?
Docling operates as a Python library that runs a document processing pipeline over input files. It applies layout-aware parsing (grounded in the associated arXiv research) to recover structure—text blocks, tables, and their spatial relationships—from PDFs and other binary formats, then serializes the result into structured output such as JSON or Markdown using Pydantic v2 models. The result is machine-readable document content with preserved structure that can be chunked, embedded, or retrieved in RAG pipelines.

As a library rather than a service, it runs locally (self-hostable by default), installs via PyPI/uv, and integrates into existing Python data or LLM workflows as an ingestion step. Its tooling stack—uv for dependency management, Ruff for linting/formatting, Pydantic v2 for validated schemas—signals a modern, maintainable codebase.

## Why is it important? (Core Value)
Docling solves the "dirty middle" of document intelligence: raw PDFs, slides, and spreadsheets are notoriously bad inputs for LLMs because text extraction loses tables, reading order, and structure. By producing structured, AI-ready output locally, it removes a major bottleneck in building RAG systems and document-grounded agents—exactly the kind of integration primitive the user is looking for when curating agent frameworks and MCP-style tooling.

For this user specifically: it's self-hostable (no SaaS lock-in), MIT-licensed, Python-native, and has a very large community (66k stars, 4.7k forks), which clears the credibility bar for adoption notes in an Obsidian vault. It slots directly into AI-agent or LLM-tooling projects as a document ingestion skill—pair it with embedding/indexing tools to build a local RAG stack, or expose it as a tool/skill for agents that need to read documents.

## Key Features & Technologies
- Parses PDF, DOCX, PPTX, XLSX, HTML, and images into structured output
- Table extraction and structure-preserving parsing (backed by arXiv research paper)
- Outputs JSON/Markdown optimized for RAG ingestion and LLM consumption
- Python library with Pydantic v2-validated schemas; installable via PyPI/uv
- MIT-licensed, self-hostable, high-trust community (66k+ stars)

## Difference from Others
Compared to generic PDF-to-text converters (e.g., PyMuPDF-style extractors) that just pull raw text, Docling is purpose-built for generative AI: it preserves tables, layout, and document structure so downstream LLM/RAG pipelines get faithful content rather than flattened strings. Compared to commercial document-processing SaaS, it runs fully locally with no vendor dependency.

What stands out is the research-grounded parsing pipeline plus structured serialization (Pydantic models → JSON/Markdown), making it a drop-in ingestion layer for agent and RAG stacks rather than a one-off converter script. Its scale (66k stars) also signals broad, production-adjacent adoption.

## 🏢 Organization & Credibility
- **Developer:** docling-project
- **Reputation:** Unknown
- **Stars:** 66,496
- **Forks:** 4790
- **Recent Activity:** 304 commits in 3 months
- **Credibility Score:** 69.0/100 (Average)
- **Languages:** Python, Shell, Dockerfile, Makefile, url
- **Last Release:** 2026-09-16
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
*Source: [GitHub](https://github.com/docling-project/docling)*
