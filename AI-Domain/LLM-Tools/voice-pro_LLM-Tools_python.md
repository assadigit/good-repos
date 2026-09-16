---
source: https://github.com/abus-aikorea/voice-pro
aliases:
  - voice-pro
  - abus-aikorea/voice-pro
tags: [python, gradio, whisper, tts, voice-cloning, self-hosted, faster-whisper, subtitles, transcription, translator, webui, speech-recognition]
category: LLM-Tools
stars: 12506
org: abus-aikorea
primary_language: Python
languages: [Python, CSS, JavaScript, Batchfile, Shell]
credibility_score: 58.5/100
date_processed: 2026-08-19
last_release: 2026-07-13
cover: attachments/banners/voice-pro_banner.png

---

![banner](attachments/banners/voice-pro_banner.png)

# voice-pro

> **TL;DR:** Gradio WebUI for AI voice processing: TTS, zero-shot voice cloning, transcription, translation, and YouTube download.

**`abus-aikorea/voice-pro`** · ⭐ 12,506 · 🔧 Python

## What is it?
Voice-Pro is a self-hosted Gradio WebUI application that provides a comprehensive suite of AI-powered speech tools. It supports text-to-speech using Edge-TTS and kokoro models, zero-shot voice cloning with E2-TTS, F5-TTS, and CosyVoice, audio transcription via Whisper/Faster-Whisper, multilingual translation, YouTube video downloading, vocal isolation with Demucs/MDX-Net, and karaoke generation. The tool is built as a unified web interface that brings together multiple large models into one accessible dashboard.

## How does it work?
The application uses Gradio to provide a web-based frontend that connects to backend processes running Whisper (and Faster-Whisper) for speech recognition, Edge-TTS and kokoro for text-to-speech synthesis, E2-TTS/F5-TTS/CosyVoice for zero-shot voice cloning, Demucs/MDX-Net for audio source separation (vocal isolation), and yt-dlp for YouTube downloading. CUDA support is included for GPU-accelerated inference on supported hardware.

## Why is it important? (Core Value)
For a software engineer and researcher focused on AI agents, developer tools, and automation, Voice-Pro directly addresses the need for self-hostable alternatives to SaaS products like ElevenLabs or cloud-based transcription services. It eliminates API costs and data privacy concerns by running Whisper, TTS models, and voice cloning engines locally. The project serves as a reference implementation of how to orchestrate multiple large audio/speech models into a cohesive developer-friendly interface, making it valuable for understanding model integration patterns and building custom AI workflows.

## Key Features & Technologies
- Gradio WebUI with unified dashboard
- Zero-shot voice cloning (E2-TTS, F5-TTS, CosyVoice)
- Text-to-speech with Edge-TTS and kokoro
- Speech recognition with Whisper/Faster-Whisper/WhisperX
- Multilingual translation and subtitle generation
- YouTube video download via yt-dlp
- Vocal isolation using Demucs and MDX-Net

## Difference from Others
Unlike SaaS alternatives (ElevenLabs, Murf.ai) that charge per-use or require API access, Voice-Pro is self-hosted and free to run locally. Compared to other open-source projects like RVC (Retrieval-based Voice Conversion), it provides a more integrated web interface combining TTS, STT, translation, and audio processing in one place rather than requiring users to manage multiple separate tools.

## 🏢 Organization & Credibility
- **Developer:** abus-aikorea
- **Reputation:** Unknown
- **Stars:** 12,506
- **Forks:** 1810
- **Recent Activity:** 6 commits in 3 months
- **Credibility Score:** 58.5/100 (Low)
- **Languages:** Python, CSS, JavaScript, Batchfile, Shell
- **Last Release:** 2026-07-13
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
*Source: [GitHub](https://github.com/abus-aikorea/voice-pro)*
