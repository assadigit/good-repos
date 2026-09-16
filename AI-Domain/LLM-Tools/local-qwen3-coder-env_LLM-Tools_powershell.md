---
source: https://github.com/Danmoreng/local-qwen3-coder-env
aliases:
  - local-qwen3-coder-env
  - Danmoreng/local-qwen3-coder-env
tags: [powershell, powershell, bash, llama.cpp, qwen, gguf, shell, url]
category: LLM-Tools
stars: 91
org: Danmoreng
primary_language: PowerShell
languages: [PowerShell, Shell, url]
credibility_score: 42.5/100
date_processed: 2026-07-07

cover: attachments/banners/local-qwen3-coder-env_banner.png

---

![banner](attachments/banners/local-qwen3-coder-env_banner.png)

# local-qwen3-coder-env

> **TL;DR:** Scripts to run Qwen3-Coder/3.5/3.6 locally on Windows & Linux with tuned llama.cpp defaults for coding workflows.

**`Danmoreng/local-qwen3-coder-env`** · ⭐ 91 · 🔧 PowerShell

## What is it?
local-qwen3-coder-env provides streamlined PowerShell and Bash scripts that set up self-hosted environments for running Qwen3-Coder, Qwen3.5, and Qwen3.6 models using llama.cpp on both Windows and Linux systems. The project includes tuned launcher defaults optimized specifically for coding workflows, addressing CUDA version compatibility issues by excluding problematic nvcc 13.2 releases and automatically selecting newer compatible versions on Windows.

Key features include modular model selection allowing users to choose between various Qwen variants including the new Qwen3.6 35B preset models, vision model support with automatic management of mmproj projectors for multimodal tasks, auto-detection of .gguf files placed in the models/ directory, and optimized performance flags such as Flash Attention, KV-cache quantization, --no-mmap, -ub 512, and MoE-aware fitting defaults. A dedicated Windows launcher (run_qwen3_6_27b_optimized.ps1) supports 16GB-class text-first setups.

For users wanting only a focused llama.cpp source build/install flow without Qwen-specific model or agent setup, the project points to a simpler companion repository at Danmoreng/llama.cpp-installer, making it easy to separate core model infrastructure from Qwen-specific configurations.

## How does it work?
The environment operates through cross-platform scripts that handle model loading and execution via llama.cpp, with Windows PowerShell launchers tailored for the CUDA policy workaround and Linux Bash scripts for equivalent functionality. Vision capabilities are enabled automatically by detecting and managing mmproj projectors required for Qwen 3.5/3.6 multimodal models without manual intervention.

Performance tuning is baked into the default configurations: Flash Attention reduces memory bandwidth usage, KV-cache quantization lowers VRAM consumption, and flags like --no-mmap improve streaming performance on limited hardware. The auto-detection mechanism scans the models/ directory for any .gguf files, allowing users to drop Qwen model variants directly without additional setup steps.

## Why is it important? (Core Value)
This project delivers tangible value by enabling self-hosted access to Qwen models, eliminating reliance on SaaS APIs for coding assistance tasks and giving developers full control over model versions, quantization levels, and hardware utilization. The modular architecture means users can tailor the environment to their specific workflows while maintaining compatibility across Windows and Linux ecosystems.

For your knowledge base, local-qwen3-coder-env directly supports multiple objectives: it provides a self-hostable alternative to Qwen SaaS (aligning with your interest in homelab infrastructure), offers AI/LLM tooling for coding workflows (relevant to your LLM-tooling interest), and includes developer productivity features like auto-detection and tuned defaults. You could place this note in the Obsidian vault under AI-Domain or Tools categories, using it as a reference for building local development environments or integrating Qwen models into your own agent-based projects.

## Key Features & Technologies
- Modular Model Selection
- 27B Presets & Launcher
- Vision Model Support
- Auto-Detection
- Optimized Performance
- CUDA Policy Workaround
- Companion Repo

## Difference from Others
Unlike generic llama.cpp installers that require manual model configuration and environment setup, local-qwen3-coder-env includes Qwen-specific presets and tuned defaults for coding workflows out of the box. Compared to other local LLM runners like Ollama or LM Studio, this project focuses exclusively on Qwen model variants and provides PowerShell launchers optimized for Windows CUDA compatibility rather than a unified UI.

The vision model support with automatic mmproj management distinguishes it from basic llama.cpp setups that lack multimodal capabilities, while the modular model selection allows users to mix and match Qwen variants without needing separate repositories. This makes it particularly suitable for developers who want self-contained coding assistants running locally without cloud dependencies.

## 🏢 Organization & Credibility
- **Developer:** Danmoreng
- **Reputation:** Unknown
- **Stars:** 91
- **Forks:** 15
- **Recent Activity:** 15 commits in 3 months
- **Credibility Score:** 42.5/100 (Low)
- **Languages:** PowerShell, Shell, url
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
*Source: [GitHub](https://github.com/Danmoreng/local-qwen3-coder-env)*
