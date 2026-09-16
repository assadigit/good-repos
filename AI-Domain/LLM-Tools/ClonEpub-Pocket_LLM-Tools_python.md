---
source: https://github.com/jarodise/ClonEpub-Pocket
aliases:
  - ClonEpub-Pocket
  - jarodise/ClonEpub-Pocket
tags: [python, python, electron, pocket-tts, epub, audiobook, javascript, css, typescript, html]
category: LLM-Tools
stars: 21
org: jarodise
primary_language: Python
languages: [Python, JavaScript, CSS, TypeScript, HTML]
credibility_score: 35.5/100
date_processed: 2026-07-05
last_release: 2026-03-11
cover: attachments/banners/ClonEpub-Pocket_banner.png

---

![banner](attachments/banners/ClonEpub-Pocket_banner.png)

# ClonEpub-Pocket

> **TL;DR:** Convert EPUB e-books to audiobooks with voice cloning. Standalone Electron app powered by Pocket TTS — CPU-only, no GPU.

**`jarodise/ClonEpub-Pocket`** · ⭐ 21 · 🔧 Python

## What is it?
ClonEpub-Pocket is a self-contained open-source tool that converts EPUB e-books into high-quality audiobooks using AI-powered voice cloning. It runs as an Electron desktop application with a bundled Python backend, allowing it to operate on any modern computer without requiring a GPU. The app includes preset voices and lets users clone their own voice from short audio samples, then save those clones as reusable presets for future use.

Under the hood, the tool loads a compact Pocket TTS model (~240 MB) automatically on first run, extracts text from the EPUB file, and synthesizes speech with realistic prosody. It's designed for CPU-only operation, using just two cores, and achieves roughly six times real-time speed on Apple Silicon. The interface features a modern dark theme with chapter selection, making it easy to navigate long books.

This project stands out among similar e-book conversion utilities because it combines voice cloning capabilities directly into the workflow, offers a fully offline experience, and maintains low latency (~200 ms) for the first audio chunk.

## How does it work?
ClonEpub is built as an Electron desktop app with a bundled Python backend. When you open the app, it automatically downloads the Pocket TTS model (a 100M-parameter TTS engine from Kyutai Labs) on first run. The EPUB file is parsed to extract its text content, which is then fed into Pocket TTS for synthesis. Voice cloning works by uploading a short audio sample (10–30 seconds) and training a lightweight model to mimic that voice; the cloned voice can be saved as a preset for reuse.

All processing runs on CPU only, using just two cores, which keeps memory usage around 1.1 GB and makes it suitable for any modern machine, including those without a GPU. The app manages model caching so repeated conversions don't re-download the model.

## Why is it important? (Core Value)
From a user perspective, ClonEpub-Pocket aligns well with your interests in self-hostable alternatives to SaaS tools and open-source projects from major tech companies. It provides a fully offline audiobook generation workflow, which is valuable if you want to avoid subscription services for e-book accessibility. The voice cloning capability could also be integrated into personal AI agent pipelines—for example, as a skill that allows an agent to generate narrated content in the user's own voice.

Since it runs on any computer without GPU requirements, it fits neatly into homelab or minimal hardware setups. Its bundled Python backend means you can inspect or modify the code if needed, and its open license makes it suitable for inclusion in your curated knowledge base. Overall, it's a practical tool that bridges e-book consumption with AI-driven voice synthesis in a self-hosted manner.

## Key Features & Technologies
- Electron desktop app
- Bundled Python backend
- Voice cloning from short audio samples
- Preset voices (8 built-in)
- Auto model download on first run
- CPU-only operation (~2 cores)
- Dark-themed UI with chapter selection

## Difference from Others
Compared to other EPUB-to-audiobook tools, ClonEpub-Pocket differentiates itself by including voice cloning directly in the app rather than requiring external services. Many alternatives rely on cloud APIs or GPU-accelerated models, whereas this runs entirely locally with minimal resources. Its bundled Python backend ensures offline operation, and the dark-themed UI offers a modern experience absent from older tools. While some projects focus solely on text extraction, ClonEpub adds the personalization aspect of cloned voices and preset management.

## 🏢 Organization & Credibility
- **Developer:** jarodise
- **Reputation:** Unknown
- **Stars:** 21
- **Forks:** 1
- **Recent Activity:** 0 commits in 3 months
- **Credibility Score:** 35.5/100 (Low)
- **Languages:** Python, JavaScript, CSS, TypeScript, HTML
- **Last Release:** 2026-03-11
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
*Source: [GitHub](https://github.com/jarodise/ClonEpub-Pocket)*
