---
source: https://github.com/jkawamoto/mcp-youtube-transcript
aliases:
  - mcp-youtube-transcript
  - jkawamoto/mcp-youtube-transcript
tags: [python, mcp, python, youtube, transcript, self-hosted, mcp-server, dockerfile, url]
category: MCP
stars: 429
org: jkawamoto
primary_language: Python
languages: [Python, Dockerfile, url]
credibility_score: 49.5/100
date_processed: 2026-07-10
last_release: 2026-07-09
cover: attachments/banners/mcp-youtube-transcript_banner.png

---

![banner](attachments/banners/mcp-youtube-transcript_banner.png)

# mcp-youtube-transcript

**`jkawamoto/mcp-youtube-transcript`** · ⭐ 429 · 🔧 Python

## What is it?
MCP server that retrieves transcripts from YouTube videos, providing timed transcript extraction.

## How does it work?
This project implements a Model Context Protocol (MCP) server, exposing tools to external MCP clients for transcript retrieval. The `get_transcript` tool fetches plain transcripts with optional language selection and pagination support via cursor-based fetching. The `get_timed_transcript` variant includes timestamps alongside the transcript text. Built in Python and packaged with uv, it can be deployed via Docker as indicated by the Dockerhub badge.

## Why is it important? (Core Value)
This MCP server directly serves your interest in AI/LLM tooling and MCP servers. As an MCP protocol implementation, it can be integrated into any MCP-compatible workflow or agent system to retrieve YouTube video content on demand, enabling your agents to search, summarize, or reference YouTube videos within LLM conversations. It also aligns with your self-hosted software preference—the Docker image and uv-based packaging make it easy to run locally in your homelab infrastructure rather than relying on SaaS solutions.

## Key Features & Technologies
- MCP server implementation
- Python runtime
- uv package manager
- Docker support
- pre-commit hooks
- YouTube transcript extraction
- timed transcript tool

## Difference from Others
Unlike general-purpose YouTube scrapers or static archive tools, this project is specifically built as an MCP server, making it interoperable with the growing ecosystem of LLM agents and tools that consume the Model Context Protocol. Other YouTube transcript projects typically expose simple APIs or CLI interfaces; this one follows the MCP specification, enabling seamless integration as a capability module in agent-based workflows.

## 🏢 Organization & Credibility
- **Developer:** jkawamoto
- **Reputation:** Unknown
- **Stars:** 429
- **Forks:** 68
- **Recent Activity:** 38 commits in 3 months
- **Credibility Score:** 49.5/100 (Low)
- **Languages:** Python, Dockerfile, url
- **Last Release:** 2026-07-09
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
*Source: [GitHub](https://github.com/jkawamoto/mcp-youtube-transcript)*
