---
source: https://github.com/santinic/audiblez
aliases:
  - audiblez
  - santinic/audiblez
tags: [python, python, tts, audiobooks, epub, kokoro, url]
category: Media
stars: 7882
org: santinic
primary_language: Python
languages: [Python, url]
credibility_score: 48.0/100
date_processed: 2026-07-06

cover: attachments/banners/audiblez_banner.png

---

![banner](attachments/banners/audiblez_banner.png)

# audiblez

> **TL;DR:** Converts e-books to audiobooks using Kokoro's text-to-speech model.

**`santinic/audiblez`** · ⭐ 7,882 · 🔧 Python

## What is it?
Audiblez converts .epub e-books into .m4b audiobook files using Kokoro's high-quality text-to-speech model. The project provides both command-line and graphical interfaces, with support for CUDA GPU acceleration on compatible hardware and CPU fallback options.

The tool extracts content from e-book files (including images, metadata, and chapters) and synthesizes speech using Kokoro, which is a relatively small 82M parameter model trained on under 100 hours of audio. This makes it accessible for self-hosted deployment while still delivering natural-sounding output. The project supports multiple languages including English, Spanish, French, Italian, Japanese, Brazilian Portuguese, Chinese, and Hindi.

Performance benchmarks show conversion takes about 5 minutes on a Google Colab T4 GPU (roughly 600 characters per second) versus approximately 1 hour on an M2 MacBook Pro CPU (around 60 characters per second). The Apache-licensed Kokoro model is free to use, making this a cost-effective solution for generating audiobooks without reliance on paid cloud APIs.

## How does it work?
Audiblez processes e-books by first parsing the .epub container format to extract text content, chapter breaks, and metadata. It then feeds this text into Kokoro's TTS model, which generates audio waveforms. The resulting audio is packaged into the .m4b format (a container used for audiobooks). For GPU acceleration, the project leverages CUDA support, allowing faster synthesis on NVIDIA GPUs. On CPU-only machines, it falls back to standard inference without parallelization overhead.

The software can be installed via pip or by cloning and running directly from GitHub. A graphical interface is available for macOS (shown in the README), though the core functionality works as a CLI tool on any platform with Python 3.

## Why is it important? (Core Value)
This project offers significant value to accessibility workflows by enabling self-hosted audiobook generation, which reduces dependency on commercial services like Amazon Audible or Google's TTS APIs. For developers interested in self-hostable software and homelab infrastructure, audiblez represents a practical example of running an open-source LLM-based tool locally without cloud costs.

Specifically for your objectives, this aligns well with your interest in discovering tools that improve development workflow and finding self-hostable alternatives to SaaS products. It also touches on your AI/LLM tooling interests since Kokoro is a model you could potentially integrate into larger agent systems or use as part of a media processing pipeline. The project demonstrates how relatively small LLMs can be repurposed for practical applications beyond the standard chatbot paradigm.

## Key Features & Technologies
- Converts .epub e-books to .m4b audiobooks
- Uses Kokoro TTS model (82M params, Apache licensed)
- Supports multiple languages (US, UK, ES, FR, IN, IT, JP, BR, CN)
- Includes graphical interface for macOS
- CUDA GPU acceleration support
- Free and open-source (Apache license)

## Difference from Others
Compared to other TTS projects that rely on larger models like XTTS or ElevenLabs, audiblez is specifically optimized around Kokoro, which trades some raw quality for much smaller size and lower compute requirements. This makes it far more suitable for self-hosted deployment on modest hardware. Additionally, the project provides a graphical interface option (unlike many CLI-only TTS tools) and includes performance optimizations that allow GPU-accelerated conversion at roughly 600 characters per second on a T4 GPU versus about 60 per second on CPU. The multi-language support also extends beyond typical free TTS solutions, including languages like Hindi and Brazilian Portuguese.

## 🏢 Organization & Credibility
- **Developer:** santinic
- **Reputation:** Unknown
- **Stars:** 7,882
- **Forks:** 683
- **Recent Activity:** 0 commits in 3 months
- **Credibility Score:** 48.0/100 (Low)
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
*Source: [GitHub](https://github.com/santinic/audiblez)*
