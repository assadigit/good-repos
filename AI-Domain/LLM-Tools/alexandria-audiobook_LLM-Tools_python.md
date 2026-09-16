---
source: https://github.com/Finrandojin/alexandria-audiobook
aliases:
  - alexandria-audiobook
  - Finrandojin/alexandria-audiobook
tags: [python, python, llm, tts, voice-cloning, self-hosted, pinokio, ai, audiobook, audiobook-generator, fastapi, lora]
category: LLM-Tools
stars: 796
org: Finrandojin
primary_language: Python
languages: [Python, HTML, Jupyter Notebook, JavaScript, Dockerfile]
credibility_score: 51.0/100
date_processed: 2026-07-05
last_release: 2026-03-03
cover: attachments/banners/alexandria-audiobook_banner.png

---

![banner](attachments/banners/alexandria-audiobook_banner.png)

# alexandria-audiobook

> **TL;DR:** AI-powered audiobook generator with multi-voice cloning and LLM script annotation.

**`Finrandojin/alexandria-audiobook`** · ⭐ 796 · 🔧 Python

## What is it?
Alexandria Audiobook Generator is a self-hosted platform that transforms any book or novel into a fully-voiced audiobook using AI-powered text-to-speech. It features a built-in Qwen3-TTS engine with batch processing capabilities and provides a browser-based editor for fine-tuning every line before final export. The tool supports multiple output formats including MP3, chaptered M4B files, and Audacity multi-track projects.

## How does it work?
The project is built on the Qwen3-TTS engine, which handles the core text-to-speech synthesis. The architecture leverages FastAPI for the backend API layer and integrates with Pinokio (a platform for running AI models locally). The workflow involves parsing input text, using LLMs for script annotation to identify speakers and dialogue, training voice clones via LoRA techniques, applying per-line style control, and finally exporting the generated audio. All components are designed to run self-hosted rather than relying on external SaaS APIs.

## Why is it important? (Core Value)
This project is valuable because it solves the problem of creating professional-quality audiobooks without depending on expensive voice actor platforms or subscription services. For a self-hosting enthusiast, it represents a credible alternative to commercial audiobook platforms like Audible or Spotify's audio books. The LLM-based script annotation and voice cloning capabilities mean the quality scales with compute rather than manual effort. Specifically for your interests, this project aligns well as an AI/LLM tool that can integrate into developer workflows, offers self-hosted alternatives to SaaS products, and demonstrates advanced techniques like LoRA training that you might want to explore further.

## Key Features & Technologies
- Uses Qwen3-TTS engine
- Voice cloning with LoRA training
- Browser-based editor for line-by-line fine-tuning
- Exports to MP3, M4B, and Audacity multi-track
- Built on FastAPI backend
- Self-hosted (Pinokio platform)
- Multi-voice support

## Difference from Others
Unlike basic text-to-speech tools that offer only a single static voice, Alexandria provides multi-voice cloning with per-line style control. Compared to generic audiobook platforms (Audible, Spotify), it runs self-hosted so you own the data and can customize voices via LoRA training rather than paying for premium accounts. Its LLM-powered script annotation means speaker identification and dialogue generation are handled automatically, which is more advanced than simple batch TTS.

## 🏢 Organization & Credibility
- **Developer:** Finrandojin
- **Reputation:** Unknown
- **Stars:** 796
- **Forks:** 91
- **Recent Activity:** 45 commits in 3 months
- **Credibility Score:** 51.0/100 (Low)
- **Languages:** Python, HTML, Jupyter Notebook, JavaScript, Dockerfile
- **Last Release:** 2026-03-03
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
*Source: [GitHub](https://github.com/Finrandojin/alexandria-audiobook)*
