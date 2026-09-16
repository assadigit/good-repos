---
source: https://github.com/marc-shade/world-intel-mcp
aliases:
  - world-intel-mcp
  - marc-shade/world-intel-mcp
tags: [python, python, mcp, ai-tools, security, dashboard, anthropic, claude, model-context-protocol, cybersecurity, threat-intelligence, geopolitical]
category: MCP
stars: 191
org: marc-shade
primary_language: Python
languages: [Python, HTML, Shell, url]
credibility_score: 41.0/100
date_processed: 2026-08-02

cover: attachments/banners/world-intel-mcp_banner.png

---

![banner](attachments/banners/world-intel-mcp_banner.png)

# world-intel-mcp

> **TL;DR:** MCP server providing 113 real-time intelligence tools across 30+ domains with a live dashboard and Qdrant vector store for semantic search.

**`marc-shade/world-intel-mcp`** · ⭐ 191 · 🔧 Python

## What is it?
World Intelligence MCP Server is a self-hosted, open-source intelligence platform that exposes over 113 Model Context Protocol (MCP) tools covering financial markets, geopolitics, military activity, cyber threats, climate data, and many other domains. All data is aggregated from free public APIs such as Yahoo Finance, CoinGecko, FRED, SEC EDGAR, and others—no paid subscriptions required. The project includes a live Leaflet dashboard with 20 map layers for visualizing real-time feeds, Server-Sent Events (SSE) streaming for low-latency updates, and AI-generated situation briefs. Additionally, it ships with a CLI and integrates Qdrant as a vector store enabling natural language semantic search across the entire accumulated intelligence database.

## How does it work?
The architecture centers on the Model Context Protocol, which allows any LLM or agent to query the server using standard MCP tool calls. Data ingestion pipelines pull from dozens of free APIs (Yahoo Finance, CoinGecko, FRED, SEC EDGAR, and many more) and write results into a Qdrant vector database for semantic indexing. Real-time feeds are pushed via SSE streams, while the dashboard is built with LeafletJS and rendered in a web UI. All logic runs in Python 3.11+ under a permissive MIT license, making it straightforward to deploy on any self-hosted infrastructure.

## Why is it important? (Core Value)
This MCP server directly aligns with your interest in AI/LLM tooling, developer productivity, and self-hosted alternatives to SaaS products. As a software engineer and researcher focused on AI agents, you can integrate this server into your Obsidian vault under an AI-Domain or Tools category, giving you immediate access to 113 real-time intelligence tools without relying on paid services. The Qdrant vector store enables natural language queries like "military activity near Taiwan" across historical data—perfect for research and security analysis. Since the project works with Claude (Anthropic) and other LLMs, it fits your workflow of building agents that need world awareness. Moreover, the self-hosted nature means you retain full control over data privacy and can extend it with custom tools tailored to your security or geopolitical monitoring needs.

## Key Features & Technologies
- MCP server exposing 113 real-time intelligence tools
- Live Leaflet dashboard with 20 map layers
- Qdrant vector store for semantic search across all data
- SSE streaming for real-time updates
- CLI interface for programmatic access
- All data from free public APIs (no paid subscriptions)
- MIT licensed

## Difference from Others
Compared to other MCP tool servers, this project stands out by covering 30+ distinct domains—from financial markets and geopolitics to cyber threats and climate—while providing a live dashboard and vector store for semantic search. Many existing MCP implementations focus on a single domain (e.g., code generation, file system access) or lack real-time visualizations. Unlike SaaS intelligence platforms that require subscriptions, this server is fully open-source and self-hostable, giving you complete control over data privacy and the ability to customize tools for your specific research or security workflows.

## 🏢 Organization & Credibility
- **Developer:** marc-shade
- **Reputation:** Unknown
- **Stars:** 191
- **Forks:** 36
- **Recent Activity:** 1 commits in 3 months
- **Credibility Score:** 41.0/100 (Low)
- **Languages:** Python, HTML, Shell, url
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
*Source: [GitHub](https://github.com/marc-shade/world-intel-mcp)*
