---
source: https://github.com/zcaceres/markdownify-mcp
aliases:
  - markdownify-mcp
  - zcaceres/markdownify-mcp
tags: [typescript, mcp, markdown, typescript, python, scraping, ai, anthropic, anthropic-ai, anthropic-claude, model-context-protocol, ocr]
category: MCP
stars: 2802
org: zcaceres
primary_language: TypeScript
languages: [TypeScript, Shell, Dockerfile, JavaScript, Batchfile]
credibility_score: 50.0/100
date_processed: 2026-07-13
last_release: 2026-05-01
cover: attachments/banners/markdownify-mcp_banner.png

---

![banner](attachments/banners/markdownify-mcp_banner.png)

# markdownify-mcp

> **TL;DR:** MCP server that converts PDFs, images, audio, web pages to Markdown for self-hosted document processing.

**`zcaceres/markdownify-mcp`** · ⭐ 2,802 · 🔧 TypeScript

## What is it?
markdownify-mcp is a Model Context Protocol (MCP) server designed to convert a wide variety of file formats and web content into clean Markdown text. It serves as a self-hosted alternative to cloud-based document conversion services, enabling local processing of PDFs, images, audio files, Office documents, and more. The core utility lies in providing AI agents and developers with a reliable, privacy-preserving way to extract readable content from unstructured sources without relying on external APIs.

The project leverages the Python library markitdown under the hood, which handles the heavy lifting of parsing binary and media files. On the MCP side, it exposes a set of tools that conform to the Model Context Protocol specification, allowing LLMs and agent frameworks to invoke conversions via standard JSON-RPC messaging. This architecture means the server can be integrated directly into AI workflows, desktop applications, or any system that supports the MCP protocol.

Key features include conversion of PDFs, DOCX, XLSX, PPTX files; extraction of text and OCR from images; audio transcription using built-in speech-to-text; web scraping for YouTube transcripts and Bing search results; and retrieval of existing Markdown files. All of these are exposed as MCP tools, making the server highly versatile for developers building AI-powered document handling pipelines.

## How does it work?
The server is built with TypeScript and Bun, which handles the Node.js runtime and package management. Upon installation, a preinstall script creates a Python virtual environment at .venv and installs markitdown[all], pulling in all required parsers for various file types. The main server logic lives in src/server.ts, where MCP tool definitions are declared. When an MCP client requests a conversion (e.g., 'convert_pdf'), the server reads the provided file path, invokes the appropriate markitdown parser, and returns the resulting Markdown string. For web content, it uses headless browsers or HTTP requests to fetch pages, extract text via OCR or transcript APIs, and format as Markdown. The MCP protocol ensures all interactions are stateless and follow the standard JSON-RPC over SSE pattern.

## Why is it important? (Core Value)
For a software engineer and researcher focused on AI agents, developer tools, automation, and self-hosted software, markdownify-mcp directly supports several objectives. It offers a self-hosted alternative to SaaS document conversion services (like Google Docs or OneDrive), aligning with the goal of reducing cloud dependencies. As an MCP server, it integrates seamlessly into AI agent stacks, allowing agents to request conversions without custom API glue code. The ability to convert audio files to Markdown (via transcription) and web pages (YouTube transcripts, Bing results) expands research workflows, enabling local extraction of information from multimedia sources. Moreover, because the output is Markdown, it can be fed directly into Obsidian vaults or other knowledge management tools, reinforcing the user's practice of curating a personal knowledge base. The project also reflects interest in open-source tools from major tech companies (Bun, Python) and demonstrates a practical application of MCP for real-world document processing tasks.

## Key Features & Technologies
- Uses Model Context Protocol
- Converts PDF, DOCX, XLSX, PPTX, images, audio
- Web scraping (YouTube, Bing)
- Built with TypeScript/Bun
- Python virtual environment under the hood
- Self-hosted alternative to SaaS
- Returns Markdown output

## Difference from Others
Unlike generic document converters such as Pandoc or standalone CLI tools, markdownify-mcp is specifically built as an MCP server, providing a standardized interface for AI agents and LLMs to request conversions via JSON-RPC. This makes it more suitable for integration into AI-driven workflows where the conversion step is invoked programmatically rather than through command-line arguments. Additionally, while other tools may require custom glue code to expose their capabilities to language models, markdownify-mcp adheres to the MCP spec, ensuring compatibility with any MCP client without additional adaptation.

## 🏢 Organization & Credibility
- **Developer:** zcaceres
- **Reputation:** Unknown
- **Stars:** 2,802
- **Forks:** 238
- **Recent Activity:** 7 commits in 3 months
- **Credibility Score:** 50.0/100 (Low)
- **Languages:** TypeScript, Shell, Dockerfile, JavaScript, Batchfile
- **Last Release:** 2026-05-01
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
*Source: [GitHub](https://github.com/zcaceres/markdownify-mcp)*
