---
source: https://github.com/phuc-nt/my-translator
aliases:
  - my-translator
  - phuc-nt/my-translator
tags: [python, rust, tauri, speech-to-text, text-to-speech, privacy, macos, real-time, soniox, speech-translation, stt, tts]
category: Media
stars: 1253
org: phuc-nt
primary_language: Python
languages: [Python, JavaScript, HTML, Rust, CSS]
credibility_score: 56.0/100
date_processed: 2026-08-02
last_release: 2026-07-11
cover: attachments/banners/my-translator_banner.png

---

![banner](attachments/banners/my-translator_banner.png)

# my-translator

**`phuc-nt/my-translator`** · ⭐ 1,253 · 🔧 Python

## What is it?
My Translator is a privacy-focused desktop application that processes audio locally on macOS and Windows without sending data to any server. It captures system audio or microphone input, transcribes it in real-time, and overlays translated text on screen. The app uses Rust and Tauri for cross-platform compatibility, supports both English and Vietnamese, and includes free text-to-speech functionality.

## How does it work?
The application leverages Tauri, a Rust-based framework for building cross-platform desktop apps, to provide native performance on both Intel and Apple Silicon Macs as well as Windows 10/11. Audio input is captured directly from the system or microphone via OS-level APIs, then streamed to Soniox for real-time speech-to-text transcription. Translations are generated locally (presumably using an open-source LLM or translation model), and the resulting text is overlaid on a minimal UI window. Text-to-speech output uses free TTS engines without requiring external services.

## Why is it important? (Core Value)
This project directly addresses the user's need for self-hostable AI tooling by providing a privacy-first speech translation solution that runs entirely locally without depending on cloud APIs. For someone building homelab infrastructure or integrating audio processing into AI agents, my-translator offers an open-source (MIT licensed) alternative to SaaS services like Google Translate. Its cross-platform support (macOS Intel/Apple Silicon and Windows) aligns with the user's interest in developer productivity tools, while the Rust backend ensures efficient local performance suitable for embedding in larger automation pipelines.

## Key Features & Technologies
- Built with Tauri
- Rust backend
- macOS Intel & Apple Silicon support
- Windows 10/11 compatibility
- Privacy-first local processing
- Real-time speech-to-text via Soniox
- Free text-to-speech engine

## Difference from Others
Unlike Google Translate or Microsoft Translator, which rely on cloud APIs and incur costs, my-translator runs entirely locally with no external server required. Its native cross-platform support for both Intel Macs and Apple Silicon PCs distinguishes it from many Whisper-based solutions that often require GPU acceleration or Linux environments. Additionally, the free text-to-speech engine contrasts with paid options like Amazon Polly or Google Cloud TTS.

## 🏢 Organization & Credibility
- **Developer:** phuc-nt
- **Reputation:** Unknown
- **Stars:** 1,253
- **Forks:** 396
- **Recent Activity:** 29 commits in 3 months
- **Credibility Score:** 56.0/100 (Low)
- **Languages:** Python, JavaScript, HTML, Rust, CSS
- **Last Release:** 2026-07-11
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
*Source: [GitHub](https://github.com/phuc-nt/my-translator)*
