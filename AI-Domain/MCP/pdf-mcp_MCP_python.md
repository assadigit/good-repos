---
source: https://github.com/I-CAN-hack/pdf-mcp
aliases:
  - pdf-mcp
  - I-CAN-hack/pdf-mcp
tags: [python, python, mcp, pdf, pymupdf, llm, mcp-server, url]
category: MCP
stars: 52
org: I-CAN-hack
primary_language: Python
languages: [Python, url]
credibility_score: 37.0/100
date_processed: 2026-08-02

cover: attachments/banners/pdf-mcp_banner.png

---

![banner](attachments/banners/pdf-mcp_banner.png)

# pdf-mcp

> **TL;DR:** MCP server for reading, rendering, and searching PDF files with image extraction capabilities.

**`I-CAN-hack/pdf-mcp`** · ⭐ 52 · 🔧 Python

## What is it?
pdf-mcp is an MCP (Model Context Protocol) server that enables LLMs to interact with PDF documents programmatically. It provides a suite of tools for extracting metadata, table of contents, text content, rendered images, and performing full-text searches across PDFs. The implementation relies on the PyMuPDF library (also known as fitz) and its LLM integration module PyMuPDF4LLM, which handle parsing, OCR, and rendering at the C level for high performance.

The server is designed to be stateless and requires only the filename of a PDF file in the current working directory; each request returns JSON responses that can be directly consumed by an LLM or any MCP client. Setup is straightforward: add an entry to your .mcp.json configuration file with the uvx command pointing to the GitHub repository, or use the codex CLI to add the server. For development, the project uses uv for dependency management and includes a test PDF generation script to verify functionality.

## How does it work?
The core of pdf-mcp is built on PyMuPDF (fitz), a high-performance PDF library written in C that handles parsing, rendering, and OCR. PyMuPDF4LLM provides an LLM-friendly interface that returns structured JSON responses suitable for MCP clients. The server runs as an MCP endpoint that listens for JSON-RPC requests over stdin/stdout; each request is stateless and only needs the PDF filename as a parameter. Requests return JSON objects containing either text, markdown, HTML, or base64-encoded PNG images. Installation is handled via uvx, which uses uv to resolve and run the server from the repository, making it easy to drop into existing MCP configurations.

## Why is it important? (Core Value)
This project directly aligns with your interests in AI/LLM tooling, MCP servers, and self-hosted software. As a self-hostable alternative to SaaS PDF tools, it gives you full control over where PDFs are processed and what data is returned—important for privacy-sensitive research or development workflows. The ability to render images at configurable DPI means you can preserve diagrams, tables, and charts that pure text extraction would lose, which is especially valuable when analyzing datasheets, manuals, or technical papers. Integrating pdf-mcp into your Obsidian vault under AI-Domain or Tools provides a reliable, open-source PDF handling capability that complements other MCP servers you may already use (e.g., for code execution, web browsing). The fact that it uses uv (a modern Python package manager) and PyMuPDF (a mature library) also matches your interest in self-hosted software and homelab infrastructure.

## Key Features & Technologies
- PyMuPDF
- PyMuPDF4LLM
- get_pdf_info
- get_table_of_contents
- get_page_text
- get_page_image
- search_text

## Difference from Others
Other PDF tools for LLMs often rely on generic parsers like pdfplumber or PyPDF2 that provide only text extraction and lack image rendering or structured metadata. Some MCP servers exist but may not offer the full suite of tools (metadata, TOC, search) in a single stateless service. This project stands out because it combines all these capabilities: metadata retrieval, table of contents extraction, text extraction in multiple formats, page image rendering, and full-text search—all via a simple JSON-RPC interface. The use of PyMuPDF gives high-performance parsing and rendering at the C level, while the MCP integration makes it easy to drop into existing agent stacks. Additionally, the project includes CLI entrypoints for uvx and codex, simplifying installation and testing, and provides a test PDF generation script for verifying LLM capabilities on PDFs.

## 🏢 Organization & Credibility
- **Developer:** I-CAN-hack
- **Reputation:** Unknown
- **Stars:** 52
- **Forks:** 6
- **Recent Activity:** 1 commits in 3 months
- **Credibility Score:** 37.0/100 (Low)
- **Languages:** Python, url
- **Last Release:** No releases
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
*Source: [GitHub](https://github.com/I-CAN-hack/pdf-mcp)*
