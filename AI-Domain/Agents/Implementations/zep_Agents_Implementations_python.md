---
source: https://github.com/getzep/zep
aliases:
  - zep
  - getzep/zep
tags: [python, python, typescript, go, agent, memory, language-model, llm, ai, knowledge-graphs, makefile, jupyter notebook]
category: Agents/Implementations
stars: 4732
org: getzep
primary_language: Python
languages: [Python, Go, TypeScript, Makefile, Jupyter Notebook]
credibility_score: 51.5/100
date_processed: 2026-07-07
last_release: 2025-09-11
cover: attachments/banners/zep_banner.png

---

![banner](attachments/banners/zep_banner.png)

# zep

> **TL;DR:** Examples & integrations for Zep Cloud, a managed agent memory platform with Python, TypeScript, and Go SDKs.

**`getzep/zep`** · ⭐ 4,732 · 🔧 Python

## What is it?
This repository provides example code, framework integrations, and tools for building agent memory with Zep Cloud, a managed AI agent memory platform. It includes SDKs in Python (pip install zep-cloud), TypeScript/JavaScript (npm install @getzep/zep-cloud), and Go (go get github.com/getzep/zep-go/v3). The repo is organized into examples/ and integrations/ directories, each containing language-specific implementations.

The project emphasizes that it is not Zep's product itself but a companion collection of reusable snippets and integration patterns. It also references Graphiti, the open-source temporal knowledge graph framework that powers Zep Cloud, for those interested in the underlying architecture.

## How does it work?
Zep Cloud operates as a managed service exposing APIs (likely REST or gRPC) that the SDKs call to store and retrieve memory across agent sessions. The repository's examples show initialization, message storage, and retrieval patterns using these APIs. Under the hood, Zep leverages Graphiti—a temporal knowledge graph—for persistent memory storage and retrieval, enabling agents to maintain context over time.

The Go SDK uses the github.com/getzep/zep-go/v3 module; the TypeScript SDK is installed via npm as @getzep/zep-cloud; the Python SDK is installed via pip as zep-cloud. Each example demonstrates how to call these APIs to interact with Zep Cloud's memory layer, effectively turning an external SaaS into a usable component for building AI agents.

## Why is it important? (Core Value)
This repository directly aligns with your objectives: it offers ready-made examples and SDKs for integrating agent memory with Zep Cloud, accelerating development of AI agents. It provides open-source components (like Graphiti) that could be self-hosted, matching your interest in self-hostable alternatives. By using these examples, you can quickly prototype agent memory functionality without building from scratch, saving time and effort. Additionally, the repository's focus on knowledge-graphs and LLM tooling fits your AI/LLM interests, and its SDKs make it easy to adopt into existing workflows or build custom MCP-like interfaces.

## Key Features & Technologies
- Python SDK (pip install zep-cloud)
- TypeScript/JavaScript SDK (npm install @getzep/zep-cloud)
- Go SDK (go get github.com/getzep/zep-go/v3)
- Example code in multiple languages
- Integration snippets for various frameworks
- Managed agent memory platform (Zep Cloud)
- Knowledge graph backend (Graphiti)

## Difference from Others
Unlike LangChain or other agent frameworks, this repo is not a general-purpose tool but focuses specifically on Zep Cloud's agent memory platform. It provides example code in multiple languages and integrates with various frameworks, whereas competitors often require building custom memory layers. This makes it more specialized but easier to adopt if you're already using Zep Cloud.

## 🏢 Organization & Credibility
- **Developer:** getzep
- **Reputation:** Unknown
- **Stars:** 4,732
- **Forks:** 637
- **Recent Activity:** 27 commits in 3 months
- **Credibility Score:** 51.5/100 (Low)
- **Languages:** Python, Go, TypeScript, Makefile, Jupyter Notebook
- **Last Release:** 2025-09-11
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
*Source: [GitHub](https://github.com/getzep/zep)*
