---
source: https://github.com/Sophomoresty/gemini-web2api
aliases:
  - gemini-web2api
  - Sophomoresty/gemini-web2api
tags: [javascript, python, llm, gemini, openai-compatible, self-hosted, html, dockerfile, url]
category: LLM-Tools
stars: 2471
org: Sophomoresty
primary_language: JavaScript
languages: [JavaScript, Python, HTML, Dockerfile, url]
credibility_score: 62.0/100
date_processed: 2026-08-02

cover: attachments/banners/gemini-web2api_banner.png

---

![banner](attachments/banners/gemini-web2api_banner.png)

# gemini-web2api

> **TL;DR:** Self-hosted proxy that converts Google Gemini's web UI into an OpenAI-compatible API endpoint via a single Python file.

**`Sophomoresty/gemini-web2api`** · ⭐ 2,471 · 🔧 JavaScript

## What is it?
gemini-web2api is a self-hosted tool that converts Google Gemini's web interface into an OpenAI-compatible API. It runs as a single-file Python script with zero authentication by default, making it accessible without needing to set up credentials. The project supports multiple Gemini models including Flash (3.6), Extended Thinking (20k+ char output), Pro, Auto, and Lite. It provides tool calling support for function calls in OpenAI format, adjustable thinking depth via a @think=N suffix, built-in web search capabilities, and SSE streaming.

The proxy enables using Cherry Studio/ChatBox with a local Gemini instance, effectively letting you run Google's advanced models on your own infrastructure without paying per-token costs. It also includes Codex CLI support for OpenAI's Responses API integration and a native Gemini CLI endpoint for direct Google API compatibility.

## How does it work?
The project is implemented as pure Python in a single file, making it lightweight and easy to deploy. It runs an HTTP server at localhost:8081/v1 that accepts OpenAI-compatible requests. For streaming responses it optionally depends on httpx. The core mechanism involves interacting with Gemini's web UI to extract model responses and stream them back in the expected OpenAI format. Tool calling is supported through function schemas, and thinking depth can be controlled via request suffixes.

## Why is it important? (Core Value)
This project directly supports your objectives as a self-hostable alternative to Google's paid Gemini API, perfect for homelab users wanting to avoid per-token costs while still accessing advanced model capabilities. It works with OpenAI-compatible clients like Cherry Studio and ChatBox, enabling integration into existing workflow tools without requiring changes to your client configuration. The single-file Python design makes it easy to deploy and maintain, aligning with your interest in lightweight self-hostable tools.

From a learning perspective, it demonstrates practical scraping/automation techniques using Gemini's web UI as a backend, which is relevant to your interest in automation workflows. As an open-source reference implementation, it could serve as a foundation for building agent systems that need access to Gemini models without relying on SaaS APIs. The project gives you full control over the inference environment while leveraging Google's model capabilities.

## Key Features & Technologies
- Optional API keys with zero auth by default
- OpenAI-compatible endpoints (/v1/chat/completions, /v1/models)
- Tool calling support for function calls
- Multiple Gemini models (Flash, Extended Thinking, Pro, Auto, Lite)
- Adjustable thinking depth via @think=N suffix
- Built-in web search capability
- Cross-platform pure Python implementation
- Streaming support via httpx
- Codex CLI (/v1/responses) support

## Difference from Others
Other OpenAI-compatible API proxies typically route through SaaS APIs like OpenRouter or Together.ai, or serve local LLMs via llama.cpp. gemini-web2api is unique in specifically using Gemini's web UI as its backend, enabling zero-cost access to Gemini models without API keys. Many other Gemini proxies lack tool calling and streaming out-of-the-box; this project includes both. Its single-file design contrasts with more complex deployments requiring Docker or Kubernetes setups, making it ideal for quick local testing or homelab integration.

## 🏢 Organization & Credibility
- **Developer:** Sophomoresty
- **Reputation:** Unknown
- **Stars:** 2,471
- **Forks:** 542
- **Recent Activity:** 53 commits in 3 months
- **Credibility Score:** 62.0/100 (Average)
- **Languages:** JavaScript, Python, HTML, Dockerfile, url
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
*Source: [GitHub](https://github.com/Sophomoresty/gemini-web2api)*
