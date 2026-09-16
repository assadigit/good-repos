---
source: https://github.com/BerriAI/litellm
aliases:
  - litellm
  - BerriAI/litellm
tags: [python, python, llm, gateway, ai-gateway, self-hosted, anthropic, langchain, llmops, openai, azure-openai, bedrock]
category: LLM-Tools
stars: 52776
org: BerriAI
primary_language: Python
languages: [Python, TypeScript, HTML, Rust, HCL]
credibility_score: 72.0/100
date_processed: 2026-07-07
last_release: 2026-07-05
cover: attachments/banners/litellm_banner.png

---

![banner](attachments/banners/litellm_banner.png)

# litellm

**`BerriAI/litellm`** · ⭐ 52,776 · 🔧 Python

## What is it?
A Python SDK and proxy server that unifies over 100 LLM APIs into a single OpenAI-compatible interface. It provides cost tracking, guardrails, load balancing, and comprehensive logging across providers like Bedrock, Azure, VertexAI, Anthropic, Cohere, Sagemaker, HuggingFace, VLLM, and NVIDIA NIM. Designed for self-hosting with enterprise-ready scalability.

This open-source gateway simplifies integration by handling differences between provider SDKs, enabling self-hosted alternatives to SaaS products, and offering enterprise-ready scalability for your homelab infrastructure.

## How does it work?
The project operates as an AI gateway proxy that intercepts requests to various LLM provider APIs and normalizes them to the OpenAI format. It manages routing between providers, enforces rate limits, tracks usage costs per API key, applies content guardrails (e.g., filters), and logs all interactions for observability. Deployment options include Render, Railway, AWS CloudShell, and GCP CloudShell, enabling flexible self-hosting across cloud providers.

## Why is it important? (Core Value)
This tool solves the fragmented LLM integration landscape by offering a single, open-source gateway that replaces reliance on individual provider SDKs. For your interests in AI/LLM tooling, self-hosted alternatives to SaaS products, and homelab infrastructure, it provides a cost-effective, privacy-preserving way to centralize LLM access with built-in observability and guardrails. Its Rust components (noted in topics) ensure performance for high-throughput scenarios, while the Python SDK integrates smoothly with LangChain and other agent frameworks you may use. As an open-source project from BerriAI, it aligns with your interest in discovering credible tools and avoiding vendor lock-in.

## Key Features & Technologies
- Python SDK
- Proxy Server
- Cost Tracking
- Guardrails
- Load Balancing
- Logging
- Self-hosted

## Difference from Others
Unlike proprietary LLM gateways (e.g., OpenRouter) that are SaaS-only, this project is open source and can be self-hosted, giving you full control over costs and data privacy. Compared to LangChain's built-in LLM integrations, it provides a dedicated proxy layer with advanced features like cost tracking per API key and guardrails, making it more suitable for enterprise deployments where observability and billing transparency are critical.

## 🏢 Organization & Credibility
- **Developer:** BerriAI
- **Reputation:** Unknown
- **Stars:** 52,776
- **Forks:** 9517
- **Recent Activity:** 3462 commits in 3 months
- **Credibility Score:** 72.0/100 (Average)
- **Languages:** Python, TypeScript, HTML, Rust, HCL
- **Last Release:** 2026-07-05
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
*Source: [GitHub](https://github.com/BerriAI/litellm)*
