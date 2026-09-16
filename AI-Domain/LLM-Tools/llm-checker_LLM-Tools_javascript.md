---
source: https://github.com/Pavelevich/llm-checker
aliases:
  - llm-checker
  - signerless/llm-checker
tags: [javascript, cli, llm, ollama, model-selector, nodejs, python, shell, url]
category: LLM-Tools
stars: 2790
org: signerless
primary_language: JavaScript
languages: [JavaScript, Python, Shell, url]
credibility_score: 62.0/100
date_processed: 2026-07-07
last_release: 2026-06-20
cover: attachments/banners/llm-checker_banner.png

---

![banner](attachments/banners/llm-checker_banner.png)

# llm-checker

> **TL;DR:** CLI tool that scans hardware and recommends which LLM models you can run locally, with Ollama integration.

**`signerless/llm-checker`** · ⭐ 2,790 · 🔧 JavaScript

## What is it?
LLM Checker is an intelligent CLI that analyzes your system hardware (RAM, GPU) and recommends optimal LLM models you can run locally. It maintains a multi-source registry of over 33k exact model artifacts from Hugging Face, GPT4All, and Ollama's catalog, scoring each model deterministically based on your hardware constraints. The tool provides live synchronization with Ollama's model definitions and runtime targeting capabilities, making it easy to discover which models will actually fit on your machine.

## How does it work?
The project is a Node.js CLI application (npm package) that scans your system for available memory, GPU compute capabilities, and other hardware metrics. It queries Ollama's API to retrieve supported model definitions and capabilities, then cross-references these with its bundled multi-source registry containing detailed specifications for 33k+ models. A deterministic scoring algorithm ranks models based on how well they match your hardware constraints (e.g., quantization levels, VRAM requirements). The tool also supports runtime targeting, allowing it to suggest models that can be executed directly via Ollama once you've installed them.

## Why is it important? (Core Value)
Self-hosting LLMs is essential for privacy-conscious developers and researchers who want to avoid relying on external APIs. This tool eliminates the tedious trial-and-error of manually checking model compatibility with your hardware. For a software engineer interested in AI agents, developer tools, and automation, LLM Checker provides a reliable way to discover which models can be integrated into local agent systems or pipelines. Its tight Ollama integration makes it particularly valuable for homelab setups where you want to run open-source models locally without SaaS dependencies.

## Key Features & Technologies
- AI-powered hardware scanning
- Multi-source model registry (Hugging Face, Ollama, GPT4All)
- Live sync with Ollama catalog
- Runtime targeting
- Hardware-calibrated memory estimation
- CLI interface

## Difference from Others
Many other model selector tools require manual configuration or only support a single source like Hugging Face. LLM Checker stands out by integrating directly with Ollama, which is the de facto standard for local LLM inference. It also provides deterministic scoring rather than heuristic-based recommendations, making it more reliable for hardware-limited environments. Additionally, its bundled registry covers 33k+ exact artifacts including various quantizations and model variants, far exceeding what most other tools offer.

## 🏢 Organization & Credibility
- **Developer:** signerless
- **Reputation:** Unknown
- **Stars:** 2,790
- **Forks:** 184
- **Recent Activity:** 51 commits in 3 months
- **Credibility Score:** 62.0/100 (Average)
- **Languages:** JavaScript, Python, Shell, url
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
*Source: [GitHub](https://github.com/Pavelevich/llm-checker)*
