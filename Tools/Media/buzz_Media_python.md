---
source: "https://github.com/chidiwilliams/buzz"
aliases:
  - buzz
  - chidiwilliams/buzz

tags: [python, whisper, audio, transcription, self-hosted, makefile, shell, inno setup, url]
category: "Media"
stars: 21525
org: "chidiwilliams"
primary_language: Python
languages: [Python, Makefile, Shell, Inno Setup, url]
credibility_score: 70.5/100
date_processed: 2026-09-16
last_release: 2026-08-23
cover: attachments/banners/buzz_banner.png

---

![banner](attachments/banners/buzz_banner.png)

# buzz

> **TL;DR:** Offline desktop app that transcribes and translates audio/video using OpenAI Whisper with real-time mic input.

**`chidiwilliams/buzz`** · ⭐ 21,525 · 🔧 Python

## What is it?
Buzz is a cross-platform desktop application that performs speech-to-text transcription and translation entirely on your local machine, powered by OpenAI's Whisper models. It handles audio files, video files, YouTube links, and live microphone input in real time. The app includes a dedicated presentation window designed for accessibility during talks and events, making it useful for live captioning scenarios.

Beyond basic transcription, Buzz adds speech separation before transcription to improve accuracy on noisy multi-speaker audio, and includes speaker identification within transcribed media. It supports multiple Whisper model sizes and backends, giving users flexibility in balancing speed versus accuracy depending on their hardware.

## How does it work?
Buzz wraps OpenAI's Whisper models behind a desktop GUI with pluggable inference backends: PyTorch with CUDA acceleration for Nvidia GPUs, CoreML for Apple Silicon Macs, and C++ via Whisper.cpp with Vulkan support for most integrated and discrete GPUs. Audio input is processed locally through these backends, meaning no audio ever leaves the machine.

For live transcription, Buzz captures microphone input in real time and renders captions in a dedicated presentation window. Pre-processing includes speech separation to isolate speakers from noisy backgrounds before running Whisper, followed by speaker identification to tag who said what. The application supports multiple Transformer model sizes so users can pick the right trade-off between latency and accuracy for their use case.

## Why is it important? (Core Value)
For a developer focused on self-hosted alternatives and AI tooling, Buzz eliminates any dependency on cloud transcription services (Otter.ai, Rev.com, Google Speech-to-Text API) while still delivering production-quality speech-to-text. It slots directly into a homelab or personal workflow: you can pipe meeting recordings, podcast files, or YouTube lectures through it without paying per-minute API fees or worrying about data leaving your network. The multi-backend support (CUDA, Apple Silicon, Vulkan/Whisper.cpp) means it is practical across the hardware a developer typically owns—laptop, desktop, or a dedicated inference box—making it a credible self-hosted replacement for SaaS transcription products and a useful building block if you want to feed transcripts into downstream AI agent pipelines.

## Key Features & Technologies
- Offline/local speech-to-text powered by OpenAI Whisper models
- Multiple inference backends: CUDA, Apple Silicon (CoreML), Vulkan via Whisper.cpp
- Real-time microphone transcription with dedicated presentation/captioning window
- Speech separation and speaker identification for multi-speaker audio
- Supports audio files, video files, and YouTube links as input
- Translation of transcribed content alongside transcription
- Cross-platform desktop GUI application

## Difference from Others
Compared to cloud transcription SaaS products like Otter.ai or Rev.com, Buzz runs entirely offline—no per-minute fees, no data leaving your machine, and no API keys to manage. Compared to other open-source Whisper wrappers (e.g., faster-whisper CLI tools or simple Python scripts), Buzz ships as a polished desktop application with real-time microphone capture, a presentation-mode captioning window, built-in speech separation for noisy audio, and speaker identification—features that go well beyond a bare model inference loop. The multi-backend abstraction (CUDA / CoreML / Vulkan) also sets it apart from single-backend tools, making it the most hardware-flexible local transcription option available.

## 🏢 Organization & Credibility
- **Developer:** chidiwilliams
- **Reputation:** Unknown
- **Stars:** 21,525
- **Forks:** 1597
- **Recent Activity:** 54 commits in 3 months
- **Credibility Score:** 70.5/100 (Average)
- **Languages:** Python, Makefile, Shell, Inno Setup, url
- **Last Release:** 2026-08-23
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
*Source: [GitHub](https://github.com/chidiwilliams/buzz)*
