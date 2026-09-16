---
source: https://github.com/tashfeenahmed/freellmapi
aliases:
  - freellmapi
  - tashfeenahmed/freellmapi
tags: [typescript, python, llm, api, proxy, routing, html, javascript, css, dockerfile]
category: LLM-Tools
stars: 15293
org: tashfeenahmed
primary_language: TypeScript
languages: [TypeScript, HTML, JavaScript, CSS, Dockerfile]
credibility_score: 72.0/100
date_processed: 2026-07-06
last_release: 2026-06-20
cover: attachments/banners/freellmapi_banner.png

---

![banner](attachments/banners/freellmapi_banner.png)

# freellmapi

> **TL;DR:** Unifies 18 free LLM providers behind one OpenAI-compatible endpoint with smart routing.

**`tashfeenahmed/freellmapi`** · ⭐ 15,293 · 🔧 TypeScript

## What is it?
FreeLLMAPI is an open-source proxy service that aggregates free tiers from Google, Groq, Cerebras, NVIDIA, Mistral, OpenRouter, GitHub Models, Cohere, Cloudflare, HuggingFace, Z.ai (Zhipu), Ollama, Kilo, Pollinations, LLM7, OVH AI Endpoints, OpenCode Zen, and AI Horde, plus custom OpenAI-compatible chat, embedding, image, and audio endpoints, behind a single /v1 API. Keys are stored encrypted. A router picks the best available model for each request, falls over to the next provider when one is rate-limited, and tracks per-key usage so you stay under every free-tier cap.

## How does it work?
The project functions as an API aggregator proxy. Incoming requests to the unified /v1 endpoint are intercepted by a routing layer that evaluates available models across all connected providers based on rate limits, latency, and cost. Requests are forwarded to the optimal backend API, responses are normalized to the OpenAI-compatible format, and errors trigger automatic failover to the next best provider. API keys are stored locally with encryption to protect credentials.

## Why is it important? (Core Value)
This project directly aligns with your interests in self-hosted alternatives to SaaS products and AI/LLM tooling. By aggregating free tiers from multiple providers, it reduces reliance on paid APIs and offers a way to stay within free-tier caps while experimenting with different models—all without managing each provider individually. The smart routing and failover features provide automation benefits for workflow orchestration. For a developer focused on homelab infrastructure, this is a practical, MIT-licensed tool that simplifies LLM access and cost management.

## Key Features & Technologies
- Aggregates 18 free LLM providers
- Unified /v1 endpoint
- Smart routing & automatic failover
- Encrypted key storage
- Usage tracking per API key
- Docker support
- MIT License

## Difference from Others
Unlike commercial aggregators like OpenRouter or other single-provider wrappers, FreeLLMAPI specifically focuses on free tiers and includes usage tracking to prevent hitting rate limits across multiple providers. Its self-hosted nature contrasts with SaaS solutions, offering full control over routing logic and data privacy. The open-source codebase also allows customization beyond what closed platforms provide.

## 🏢 Organization & Credibility
- **Developer:** tashfeenahmed
- **Reputation:** Unknown
- **Stars:** 15,293
- **Forks:** 2224
- **Recent Activity:** 345 commits in 3 months
- **Credibility Score:** 72.0/100 (Average)
- **Languages:** TypeScript, HTML, JavaScript, CSS, Dockerfile
- **Last Release:** 2026-06-20
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
*Source: [GitHub](https://github.com/tashfeenahmed/freellmapi)*
