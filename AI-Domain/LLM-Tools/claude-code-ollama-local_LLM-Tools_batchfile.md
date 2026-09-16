---
source: https://github.com/emilycodes-cmd/claude-code-ollama-local
aliases:
  - claude-code-ollama-local
  - emilycodes-cmd/claude-code-ollama-local
tags: [batchfile, claude, ollama, windows, local, cli, url]
category: LLM-Tools
stars: 121
org: emilycodes-cmd
primary_language: Batchfile
languages: [Batchfile, url]
credibility_score: 39.5/100
date_processed: 2026-07-06

cover: attachments/banners/claude-code-ollama-local_banner.png

---

![banner](attachments/banners/claude-code-ollama-local_banner.png)

# claude-code-ollama-local

> **TL;DR:** Windows launcher to run Claude Code locally via Ollama without Anthropic API key.

**`emilycodes-cmd/claude-code-ollama-local`** · ⭐ 121 · 🔧 Batchfile

## What is it?
This project provides a simple Windows launcher that enables running Claude Code locally through Ollama, eliminating the need for an Anthropic API key. The repository contains a batch script (claude-ollama.cmd) that invokes Ollama's CLI with Claude model integration, along with setup instructions and troubleshooting notes for CPU/GPU configurations.

## How does it work?
The launcher is essentially a wrapper around Ollama's command-line interface. When executed, it calls `ollama launch claude --model qwen3:1.7b` to start Claude Code with the specified model. The script supports passing additional arguments that are forwarded to the underlying Claude Code process. Users can modify the default model in the batch file by changing the CLAUDE_OLLAMA_MODEL environment variable.

## Why is it important? (Core Value)
This self-hosted solution is valuable for privacy-conscious developers who want Claude's coding capabilities without relying on Anthropic's cloud API or paying per-token fees. It runs entirely locally, making it suitable for air-gapped environments or users concerned about data leakage. The project specifically addresses hardware constraints by defaulting to the smaller 1.7b model variant, with clear guidance on upgrading to larger models as hardware permits. For users interested in homelab infrastructure and self-hosted alternatives to SaaS products, this aligns directly with their stated interests.

## Key Features & Technologies
- Windows batch launcher
- Ollama integration
- Configurable default model
- CPU/GPU troubleshooting guide
- No API key required
- Simple CLI interface
- Setup instructions

## Difference from Others
Unlike the official Anthropic CLI which requires an API key and runs in the cloud, this project enables fully local execution through Ollama. It's more lightweight than full Claude Code implementations - essentially a thin wrapper script rather than a comprehensive framework. The 1.7b default model choice distinguishes it from other Ollama Claude setups that may default to larger models.

## 🏢 Organization & Credibility
- **Developer:** emilycodes-cmd
- **Reputation:** Unknown
- **Stars:** 121
- **Forks:** 34
- **Recent Activity:** 0 commits in 3 months
- **Credibility Score:** 39.5/100 (Low)
- **Languages:** Batchfile, url
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
*Source: [GitHub](https://github.com/emilycodes-cmd/claude-code-ollama-local)*
