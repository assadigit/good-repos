---
source: https://github.com/thewh1teagle/vibe
aliases:
  - vibe
  - thewh1teagle/vibe
tags: [typescript, rust, whisper, transcription, desktop, privacy, ai, cross-platform, openai, transcribe, python, css]
category: Media
stars: 7132
org: thewh1teagle
primary_language: TypeScript
languages: [TypeScript, Rust, Python, CSS, HTML]
credibility_score: 59.5/100
date_processed: 2026-08-19
last_release: 2026-07-15
cover: attachments/banners/vibe_banner.png

---

![banner](attachments/banners/vibe_banner.png)

# vibe

> **TL;DR:** Local, privacy-first desktop app for transcribing audio/video with Whisper models, batch processing, and multi-format export.

**`thewh1teagle/vibe`** · ⭐ 7,132 · 🔧 TypeScript

## What is it?
Vibe is a cross-platform desktop application that performs speech-to-text transcription entirely on the user's local device. It supports transcription of audio and video files in nearly every language, with no data ever leaving the user's machine. The app provides a user-friendly GUI for loading files, running transcription, and previewing results in real time.

Key features include batch transcription of multiple files, support for multiple export formats (SRT, VTT, TXT, HTML, PDF, JSON, DOCX), and the ability to transcribe audio from popular websites like YouTube, Vimeo, Facebook, and Twitter. It supports Whisper, Nemotron 3.5, and Parakeet TDT v3 models, giving users flexibility in model choice. Optional integrations with the Claude API and Ollama enable multilingual summarization and local AI analysis of transcripts.

The project is written in Rust and distributed as a downloadable desktop app, positioning itself as a privacy-focused alternative to cloud-based transcription services.

## How does it work?
Vibe is a Rust-based desktop application that runs AI speech recognition models (Whisper, Nemotron 3.5, Parakeet TDT v3) locally on the user's hardware. Users load audio or video files through a graphical interface, select a model, and the app processes the media locally to produce text output. Realtime preview allows users to see transcription progress as it happens.

For summarization, Vibe can optionally call the Claude API for multilingual transcript summaries or use Ollama for fully local AI analysis. The app also supports fetching audio from popular video platforms (YouTube, Vimeo, etc.) for transcription. Output can be exported in multiple formats including subtitles (SRT, VTT), documents (PDF, DOCX), and structured data (JSON, HTML).

## Why is it important? (Core Value)
Vibe solves the privacy and cost problems inherent in cloud-based transcription services like OpenAI's Whisper API, Descript, or Rev. By running entirely offline, it eliminates data privacy concerns and recurring API costs, making it a self-hosted alternative to SaaS transcription products. For the user, this is directly relevant as a self-hostable alternative to SaaS products and an AI/LLM tooling project that integrates with Ollama for local AI workflows. It fits into their knowledge base as a practical, privacy-first media tool that demonstrates how AI models (Whisper, Nemotron) can be deployed locally in a polished desktop application. The Ollama integration also makes it a useful reference for building local AI pipelines in Rust-based desktop apps.

## Key Features & Technologies
- Fully offline transcription with Whisper, Nemotron 3.5, and Parakeet TDT v3 models
- Batch transcription of multiple audio/video files
- Supports SRT, VTT, TXT, HTML, PDF, JSON, DOCX export formats
- Ollama integration for local AI analysis and batch summaries
- Claude API integration for multilingual transcript summarization
- Transcribes audio from YouTube, Vimeo, Facebook, Twitter and other platforms
- Cross-platform desktop app built in Rust with realtime preview

## Difference from Others
Compared to cloud transcription services (OpenAI Whisper API, Google Speech-to-Text, Descript), Vibe offers complete privacy and zero marginal cost since all processing happens locally. Compared to other local Whisper GUIs (like Whisper.cpp GUIs or whisper-tui), Vibe distinguishes itself with a polished cross-platform desktop experience, multi-model support (not just Whisper), and built-in website audio extraction. Unlike command-line tools, it provides a user-friendly graphical interface with realtime preview and batch processing. The Ollama integration for local summarization sets it apart from basic transcription tools by adding an AI analysis layer without requiring external API calls.

## 🏢 Organization & Credibility
- **Developer:** thewh1teagle
- **Reputation:** Unknown
- **Stars:** 7,132
- **Forks:** 486
- **Recent Activity:** 40 commits in 3 months
- **Credibility Score:** 59.5/100 (Low)
- **Languages:** TypeScript, Rust, Python, CSS, HTML
- **Last Release:** 2026-07-15
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
*Source: [GitHub](https://github.com/thewh1teagle/vibe)*
