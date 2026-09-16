---
source: https://github.com/emilycodes-cmd/claude-code-ollama-local
aliases:
  - claude-code-ollama-local
  - emilycodes-cmd/claude-code-ollama-local
tags: [batchfile, windows, ollama, claude-code, self-hosted, cli, url]
category: Agents/Implementations
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

> **TL;DR:** Windows CLI launcher that runs Claude Code locally via Ollama without API key.

**`emilycodes-cmd/claude-code-ollama-local`** · ⭐ 121 · 🔧 Batchfile

## What is it?
This repository provides a ready‑to‑run Windows environment for using Claude Code locally through Ollama. By default it loads the lightweight `qwen3:1.7b` model, which runs on modest hardware, but users can swap in larger models via the launcher script. The package includes a simple batch launcher (`claude-ollama.cmd`) that invokes Ollama's built‑in Claude integration, forwards any extra CLI arguments, and requires only Node.js/npm for installing the Claude Code CLI globally. No Anthropic API key is needed because all inference happens on the local machine.

## How does it work?
The launcher script sets an environment variable `CLAUDE_OLLAMA_MODEL` to the chosen Ollama model; when the user runs the batch file it calls `ollama launch claude --model <model>`. This uses Ollama's native integration with Claude Code, which runs a lightweight LLM server and streams code completions back to the CLI. The repository also ships the source files for Claude Code under `src/`, allowing developers to inspect or modify the code if needed. Installation steps in the README require pulling the model with `ollama pull`, installing the Claude Code CLI via npm, and then executing the launcher from the project directory.

## Why is it important? (Core Value)
For self‑hosting enthusiasts this project solves the cost and privacy concerns of using a paid Claude Code service. By running Ollama locally, developers can experiment with Claude Code without paying API fees or exposing their code to external services. It aligns directly with your interest in discovering self‑hostable alternatives to SaaS products and building a personal knowledge base of useful tools. The lightweight default model makes it viable on lower‑end hardware, while the ability to swap models lets you scale up as needed. Overall it offers a low‑friction way to integrate an AI coding assistant into your local workflow.

## Key Features & Technologies
- Windows CLI launcher script
- No Anthropic API key required (self-hosted)
- Uses Ollama for model inference
- Default lightweight model `qwen3:1.7b`
- Supports swapping models via environment variable or editing the script
- Simple install instructions (npm, ollama pull)
- Passes extra CLI arguments through to Claude Code

## Difference from Others
Similar local LLM runners include Ollama's generic `ollama run` commands for various models, but this project is tailored specifically to Claude Code and provides a ready‑made Windows entry point. Other wrappers for Claude Code typically require an Anthropic API key or run on Linux; this repository fills the gap for Windows users who want a self‑contained, no‑key solution. The default model choice (`qwen3:1.7b`) also differs from the larger `qwen3.5:4b` often used in other setups.

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
