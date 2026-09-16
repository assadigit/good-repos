---
source: https://github.com/abus-aikorea/voice-pro
aliases:
  - voice-pro
  - abus-aikorea/voice-pro
tags: [python, gradio, tts, whisper, voice-cloning, self-hosted, faster-whisper, subtitles, transcription, translator, webui, speech-recognition]
category: Automation
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

> **TL;DR:** Gradio WebUI combining TTS, voice cloning, Whisper transcription, YouTube download, vocal isolation, and multilingual translation in one self-hosted tool.

**`abus-aikorea/voice-pro`** · ⭐ 12,506 · 🔧 Python

## What is it?
Voice-Pro is a comprehensive Gradio-based web application that serves as an all-in-one AI audio processing platform. It integrates multiple powerful open-source models including Edge-TTS and Kokoro for text-to-speech generation, E2-TTS and F5-TTS with CosyVoice for zero-shot voice cloning, Whisper/Faster-Whisper/WhisperX for speech recognition with timestamps, Demucs and MDX-Net for vocal isolation, and multilingual translation capabilities. The tool also includes YouTube video downloading functionality via yt-dlp.

## How does it work?
The application uses a Gradio WebUI as its frontend interface, which orchestrates various backend processing pipelines. For transcription tasks, it leverages Whisper or Faster-Whisper (with CUDA acceleration support) to convert audio to text with timestamp alignment. Voice cloning workflows use E2-TTS or F5-TTS models that perform zero-shot voice conversion by analyzing a reference audio sample and synthesizing new speech in that voice. The YouTube downloader extracts audio from videos, which can then be processed through the vocal isolation pipeline (Demucs/MDX-Net) to separate vocals from instrumental tracks before being fed into TTS or translation modules.

## Why is it important? (Core Value)
For the user's objectives of finding self-hostable alternatives to SaaS products and discovering AI tooling that improves development workflows, Voice-Pro is highly relevant. It replaces multiple paid services (ElevenLabs for voice cloning, Otter.ai/Whisper API for transcription, translation APIs) with a single self-hosted solution running locally on the user's infrastructure. The project directly addresses interests in 'self-hosted software and homelab infrastructure' by providing a complete pipeline that can be deployed privately without relying on third-party APIs or cloud services. It also supports the 'automation and workflow orchestration' interest by combining disparate audio processing tools into one cohesive interface.

## Key Features & Technologies
- Zero-shot voice cloning with E2-TTS, F5-TTS, and CosyVoice
- Whisper/Faster-Whisper transcription with timestamp alignment
- Multilingual translation support
- YouTube video download via yt-dlp
- Vocal isolation using Demucs and MDX-Net
- Edge-TTS and Kokoro TTS engines
- Gradio WebUI with CUDA acceleration

## Difference from Others
Unlike specialized tools that focus on a single function (e.g., separate voice cloning services, standalone transcribers), Voice-Pro consolidates the entire audio processing pipeline into one interface. This eliminates the need to juggle multiple SaaS subscriptions or self-host disparate tools. While ElevenLabs offers similar voice capabilities, it's a cloud-based paid service; Voice-Pro provides a free, self-hosted alternative with full control over data privacy and deployment.

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
