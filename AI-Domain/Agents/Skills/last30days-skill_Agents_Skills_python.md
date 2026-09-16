---
source: https://github.com/mvanhorn/last30days-skill
aliases:
  - last30days-skill
  - mvanhorn/last30days-skill
tags: [python, claude, skill, recency, scraping, openclaw, ai-prompts, claude-code, reddit, twitter, hackernews, polymarket]
category: Agents/Skills
stars: 51483
org: mvanhorn
primary_language: Python
languages: [Python, Go, Shell, HTML, url]
credibility_score: 70.5/100
date_processed: 2026-07-11
last_release: 2026-07-07
cover: attachments/banners/last30days-skill_banner.png

---

![banner](attachments/banners/last30days-skill_banner.png)

# last30days-skill

> **TL;DR:** AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web - then synthesizes a grounded summary.

**`mvanhorn/last30days-skill`** · ⭐ 51,483 · 🔧 Python

## What is it?
last30days-skill is an AI agent skill designed for Claude Code and compatible with the broader Agent Skills ecosystem. Its primary purpose is to perform comprehensive research on any topic by scraping and analyzing content from Reddit, X (Twitter), YouTube, Hacker News, Polymarket, and general web search. It then synthesizes these sources into a grounded summary that reflects the most upvoted or liked perspectives rather than editorial curation.

The skill runs an asynchronous pipeline that fetches recent posts, videos, comments, and market data from each platform using their respective APIs or scraping methods. It aggregates the information, extracts key points, and uses Claude to generate a concise, well-cited summary that balances multiple viewpoints. The implementation is modular and can be installed globally via npx skills add with the -g flag, or per-project without it.

It also integrates with OpenClaw for broader agent skill compatibility, supports recency filters (last 30 days), and provides a clean output that can be consumed by downstream tools. The skill respects platform-specific formatting and includes metadata about sources used, making the summary verifiable and transparent.

## How does it work?
The skill is implemented as a modular Python-based agent component that runs within Claude Code's plugin system. On initialization, it loads configuration from SKILL.md and sets up async HTTP clients for each target platform (Reddit, X, YouTube, HN, Polymarket, and generic web search). For each platform, it fetches the most recent posts, comments, video descriptions, and market odds using the appropriate API or scraping strategy. The raw data streams into an aggregation step where a lightweight NLP pipeline extracts topic keywords, sentiment scores, and upvote/like counts. Claude is then invoked with a prompt that instructs it to synthesize these signals into a concise summary, citing sources and noting any conflicting viewpoints.

The output is structured as a markdown document that includes sections for each platform, a consolidated summary, and metadata about the run (timestamp, query, source URLs). The skill also supports global installation via npx skills add with the -g flag, which registers it in the Agent Skills registry so that any compatible runtime can discover and load it. Under the hood, it uses standard Python libraries such as requests, aiohttp, beautifulsoup4, and pandas, plus the Claude Code SDK for invoking the model.

## Why is it important? (Core Value)
last30days-skill directly addresses the user's goal of discovering AI agent tools that improve workflow. It provides a ready-to-use research skill that can be installed into Claude Code or any Agent Skills-compatible environment, giving the user an immediate way to query multiple social platforms and synthesize information without building custom scrapers. For someone interested in self-hostable alternatives to SaaS, the skill runs entirely on their own machine, respecting privacy and avoiding third‑party data pipelines. It also demonstrates a modern approach to scraping: by leveraging platform APIs and lightweight NLP rather than brittle page parsers, it offers a more maintainable solution for automation tasks.

The skill's ability to rank results by upvotes, likes, and real money (Polymarket) means the user gets community‑validated information rather than just editorial picks. This is valuable for research projects that require ground truth from multiple sources. Moreover, the skill integrates with OpenClaw, which expands its reach beyond Claude Code to other agent platforms, making it a versatile building block for larger automation pipelines.

## Key Features & Technologies
- Uses Claude Code marketplace
- Installs globally via npx skills add -g
- Supports recency filters (last 30 days)
- Integrates with OpenClaw
- Fetches from Reddit, X, YouTube, HN, Polymarket, web search
- Generates markdown output with source citations
- Runs entirely locally (self-hosted)

## Difference from Others
Unlike generic web search tools that return raw snippets, last30days-skill aggregates community sentiment by weighting Reddit upvotes, X likes, YouTube views, HN points, and Polymarket odds. It also differs from other Claude Code skills because it is built as a dedicated research pipeline rather than a simple prompt wrapper. Compared to frameworks like LangChain or AutoGen, this skill is not a framework for building agents but a pre‑implemented agent skill that can be dropped into any compatible runtime. Its self‑hosted nature and global install flag make it distinct from SaaS search APIs.

## 🏢 Organization & Credibility
- **Developer:** mvanhorn
- **Reputation:** Unknown
- **Stars:** 51,483
- **Forks:** 4443
- **Recent Activity:** 640 commits in 3 months
- **Credibility Score:** 70.5/100 (Average)
- **Languages:** Python, Go, Shell, HTML, url
- **Last Release:** 2026-07-07
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
*Source: [GitHub](https://github.com/mvanhorn/last30days-skill)*
