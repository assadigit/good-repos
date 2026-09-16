---
source: https://github.com/mobinhasanghasemi/devobin
aliases:
  - devobin
  - mobinhasanghasemi/devobin
tags: [python, python, llm, prompt-engineering, cli, developer-tools, url]
category: LLM-Tools
stars: 9
org: mobinhasanghasemi
primary_language: Python
languages: [Python, url]
credibility_score: 32.0/100
date_processed: 2026-07-17

cover: attachments/banners/devobin_banner.png

---

![banner](attachments/banners/devobin_banner.png)

# devobin

> **TL;DR:** CLI tool that scans your repo and generates custom prompts for AI coding agents to implement features.

**`mobinhasanghasemi/devobin`** · ⭐ 9 · 🔧 Python

## What is it?
DevObin is a CLI-based prompt engineering system that autonomously reads your project code and produces customized engineering prompts for AI coding agents. It does NOT write code — it crafts the perfect prompt so Codex, Claude, Cursor, or any AI agent builds exactly what you need. The key difference is that DevObin reads YOUR code and produces a prompt based on YOUR actual architecture — not a generic template.

You run it in your project directory, connect an LLM provider (OpenAI, Anthropic, Google, or Ollama), describe the feature you want, and DevObin scans the codebase, understands context, and writes a prompt file (e.g., caching_feature_prompt.md) that you give to your AI coding agent. It automates the tedious step of writing precise prompts tailored to your repo.

## How does it work?
DevObin runs as a command-line interface. On startup you invoke `devobin` in your project root. It first reads the repository structure, parses source files to understand context (imports, functions, architecture). Then you issue a prompt via CLI or API call (e.g., `/connect` to set up an LLM provider). DevObin uses the LLM to generate a customized prompt based on your description and the codebase analysis. Finally it writes the prompt file (`caching_feature_prompt.md`) in your project directory, which you then feed to your AI coding agent (Codex, Claude, Cursor) to implement the feature.

## Why is it important? (Core Value)
DevObin helps the user by offering a self-hosted prompt engineering tool that bridges the gap between human requirements and AI coding agents. It reduces the need for manual prompt crafting, saves time, and works with any LLM provider, which aligns with the user's interest in self-hostable tools and developer productivity. Since the user curates GitHub projects for their Obsidian vault, DevObin is a useful addition to their collection of AI agent tooling.

The core value is that it automates the creation of precise prompts tailored to the codebase, making it easier to use AI coding agents effectively, which directly supports the user's goal of improving development workflow with AI agents and developer tools.

## Key Features & Technologies
- CLI tool
- Supports OpenAI/Anthropic/Google/Ollama LLM providers
- Generates prompt files for AI coding agents
- Reads project codebase context
- No code generation — pure prompt crafting
- Self-hostable via pip or git clone
- Uses /connect command to configure provider keys

## Difference from Others
Similar projects include generic prompt templates, other prompt engineering tools like PromptLayer or custom LLM wrappers, and AI coding agents like Codeium, Copilot, Cursor itself. DevObin is different because it reads YOUR code and tailors prompts to your actual architecture, rather than using generic templates. It also specifically avoids writing code, focusing solely on crafting the perfect instruction. Many prompt engineering tools are either generic or require you to manually write prompts; DevObin automates that with context awareness. Additionally, it integrates with multiple LLM providers and works as a CLI tool, making it easy to use in any project.

## 🏢 Organization & Credibility
- **Developer:** mobinhasanghasemi
- **Reputation:** Unknown
- **Stars:** 9
- **Forks:** 3
- **Recent Activity:** 2 commits in 3 months
- **Credibility Score:** 32.0/100 (Low)
- **Languages:** Python, url
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
*Source: [GitHub](https://github.com/mobinhasanghasemi/devobin)*
