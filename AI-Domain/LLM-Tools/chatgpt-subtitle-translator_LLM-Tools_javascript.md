---
source: https://github.com/Cerlancism/chatgpt-subtitle-translator
aliases:
  - chatgpt-subtitle-translator
  - Cerlancism/chatgpt-subtitle-translator
tags: [javascript, python, llm, translation, srt-subtitles, openai, chatgpt, cli, gui, srt, subtitle, web]
category: LLM-Tools
stars: 390
org: Cerlancism
primary_language: JavaScript
languages: [JavaScript, CSS, HTML, url]
credibility_score: 51.0/100
date_processed: 2026-09-01
last_release: 2026-04-13
cover: attachments/banners/chatgpt-subtitle-translator_banner.png

---

![banner](attachments/banners/chatgpt-subtitle-translator_banner.png)

# chatgpt-subtitle-translator

> **TL;DR:** CLI and web tool translating SRT subtitles via ChatGPT/OpenAI-compatible APIs with line-accurate output and token optimization.

**`Cerlancism/chatgpt-subtitle-translator`** · ⭐ 390 · 🔧 JavaScript

## What is it?
chatgpt-subtitle-translator is a translation utility that leverages the OpenAI ChatGPT API (or any OpenAI-compatible LLM endpoint) to translate SRT subtitle files while preserving strict line-to-line correspondence. Unlike generic LLM translation prompts, it strips SRT timing/metadata overhead before sending text to the model and batches lines to minimize token consumption, then reassembles the output so each translated line maps one-to-one with its source line—preventing the timing drift that plagues naive subtitle translation.

The project ships both a web UI (hosted at cerlancism.github.io) and a CLI, making it usable from a browser or scripted into pipelines. It supports OpenAI's Structured Output mode for more reliable formatting and works with any OpenAI-compatible API, including local LLMs via Ollama.

The project has seen active development, with a documented v2-to-v3 migration guide indicating breaking changes were made to improve the translation pipeline.

## How does it work?
The tool parses an SRT file into individual subtitle cues, strips timing and index metadata, and groups remaining text lines into batches sized to fit within the model's context window while respecting per-line boundaries. Each batch is sent to the LLM with a prompt enforcing one-to-one line correspondence; the response is then validated and re-wrapped with original timestamps. Token efficiency comes from removing redundant SRT headers/footers per cue and batching, avoiding per-line API calls.

The backend talks to any OpenAI-compatible chat-completions endpoint (OpenAI, Ollama, or other compatible servers). A web UI is provided for browser-based use, and a CLI wrapper allows scripting. Structured Output support ensures the model returns cleanly delimited lines that can be parsed back into valid SRT without fragile regex post-processing.

## Why is it important? (Core Value)
For users who produce or localize video content—YouTubers, open-source maintainers with multilingual audiences, or accessibility teams—this tool eliminates the two biggest pain points of LLM-based subtitle translation: timing misalignment and runaway token costs. By guaranteeing line-to-line parity and batching aggressively, it produces a drop-in replacement SRT file that can be loaded into any player without manual re-timing.

For the described user (a software engineer/researcher focused on AI tooling and self-hosted infrastructure), this project is directly relevant in two ways. First, it supports Ollama, meaning the entire translation workflow can run against a local LLM with no API key or cloud dependency—fitting their interest in self-hostable alternatives to SaaS. Second, the CLI surface makes it easy to wire into an automation pipeline (e.g., a nightly cron that translates new subtitle drops), aligning with their focus on workflow orchestration and developer productivity. The token-optimization approach is also a useful reference pattern for anyone building LLM-powered batch tools.

## Key Features & Technologies
- Translates SRT subtitles with guaranteed one-to-one line correspondence
- Token-efficient batching that strips SRT metadata before API calls
- Web UI and CLI interfaces
- Works with any OpenAI-compatible chat-completions API (OpenAI, Ollama, etc.)
- Supports OpenAI Structured Output for reliable parsing
- Self-hostable via Ollama for local LLM inference

## Difference from Others
Most LLM translation examples on GitHub are single-prompt scripts or notebook cells that translate a blob of text and leave the user to manually re-time subtitles. chatgpt-subtitle-translator's distinguishing contribution is the structural guarantee: it treats SRT as a line-aligned format, strips timing overhead before inference, and validates that output lines match input lines count-wise, so the result is a valid SRT file with no manual post-processing. Compared to general-purpose LLM translation wrappers (e.g., simple OpenAI CLI wrappers), this project's niche focus on subtitle timing integrity and token budgeting makes it purpose-built for localization workflows rather than freeform text translation.

## 🏢 Organization & Credibility
- **Developer:** Cerlancism
- **Reputation:** Unknown
- **Stars:** 390
- **Forks:** 44
- **Recent Activity:** 25 commits in 3 months
- **Credibility Score:** 51.0/100 (Low)
- **Languages:** JavaScript, CSS, HTML, url
- **Last Release:** 2026-04-13
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
*Source: [GitHub](https://github.com/Cerlancism/chatgpt-subtitle-translator)*
