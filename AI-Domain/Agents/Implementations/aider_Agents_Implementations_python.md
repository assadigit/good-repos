---
source: https://github.com/Aider-AI/aider
aliases:
  - aider
  - Aider-AI/aider
tags: [python, python, llm, agent, git, cli, chatgpt, command-line, gpt-4, openai, gpt-3, gpt-35-turbo]
category: Agents/Implementations
stars: 47121
org: Aider-AI
primary_language: Python
languages: [Python, CSS, Shell, Tree-sitter Query, JavaScript]
credibility_score: 58.5/100
date_processed: 2026-07-07
last_release: 2025-08-09
cover: attachments/banners/aider_banner.png

---

![banner](attachments/banners/aider_banner.png)

# aider

> **TL;DR:** AI pair programming assistant that edits code directly in your git repo with LLM guidance.

**`Aider-AI/aider`** · ⭐ 47,121 · 🔧 Python

## What is it?
Aider is an open-source AI pair programming tool that runs entirely from your terminal and integrates directly with your git repository. It allows you to collaboratively build or modify codebases by chatting with an LLM that can read, understand, and edit your source files. The tool treats the git repository as the single source of truth, making it safe to use for both greenfield projects and existing codebases. With over 6.8 million PyPI installs and nearly 50k GitHub stars, it's gained significant adoption among developers.

## How does it work?
Aider operates by using an LLM to generate edits to your codebase files, then applies those edits directly in your git repository. It supports multiple model providers including OpenAI, Anthropic (Claude), and local models via llama.cpp. The tool parses the entire repository context before each edit operation, allowing it to understand project structure and dependencies. You interact with aider through a CLI interface where you can describe changes or ask questions, and it will make the appropriate file modifications while committing to git.

## Why is it important? (Core Value)
Aider directly addresses your interest in discovering tools that improve development workflow and finding AI agent implementations. As someone focused on self-hostable alternatives to SaaS products, aider is valuable because it's open-source with no external dependencies beyond APIs or local models you control—you can run it in a homelab environment. For automation learning, aider automates code editing tasks through LLM guidance rather than traditional scripting. It also aligns with your interest in developer productivity tools by providing an intelligent coding partner that works natively in your terminal environment, making it accessible regardless of IDE preference.

## Key Features & Technologies
- Integrates directly with git repositories as source of truth
- Supports multiple model providers (OpenAI, Anthropic, llama.cpp)
- Opensource Python CLI package with PyPI distribution
- Reads entire repository context before each edit operation
- Safe for both greenfield projects and existing codebases
- Terminal-first interaction model via chat interface

## Difference from Others
Unlike Cursor (an IDE plugin) or Copilot (VS Code extension), aider is designed to work from the command line with git as its primary storage mechanism, making it more suitable for terminal-focused workflows and CI/CD pipelines. Compared to traditional code-editing LLMs that require external IDE integrations, aider's direct git editing approach means changes are versioned immediately without requiring separate commit workflows.

## 🏢 Organization & Credibility
- **Developer:** Aider-AI
- **Reputation:** Unknown
- **Stars:** 47,121
- **Forks:** 4705
- **Recent Activity:** 19 commits in 3 months
- **Credibility Score:** 58.5/100 (Low)
- **Languages:** Python, CSS, Shell, Tree-sitter Query, JavaScript
- **Last Release:** 2025-08-09
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
*Source: [GitHub](https://github.com/Aider-AI/aider)*
