---
source: https://github.com/thewh1teagle/vibe
aliases:
  - vibe
  - thewh1teagle/vibe
tags: [typescript, rust, whisper, ollama, transcription, offline, ai, cross-platform, desktop, openai, transcribe, python]
category: LLM-Tools
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

> **TL;DR:** Self-hosted audio/video transcription tool using Whisper, Ollama, and other local models with full privacy.

**`thewh1teagle/vibe`** · ⭐ 7,132 · 🔧 TypeScript

## What is it?
Vibe is a cross-platform desktop application that transcribes audio and video files entirely offline on your device. It supports multiple model backends including Whisper, Nemotron 3.5, Parakeet TDT v3 for transcription, and Ollama for local AI analysis and batch summarization. The tool features a user-friendly design with real-time preview and outputs transcripts in various formats (SRT, VTT, TXT, HTML, PDF, JSON, DOCX).

## How does it work?
Vibe is built in Rust as a cross-platform desktop application. It loads local AI models (Whisper via GGUF, Nemotron 3.5, Parakeet TDT v3) directly on your device and processes audio/video files through these models without sending any data to external servers. For summarization, it can optionally call the Claude API or use Ollama for local LLM-based analysis. The application provides a GUI with real-time preview of transcripts as files are processed.

## Why is it important? (Core Value)
For a software engineer and researcher focused on self-hostable alternatives to SaaS products, Vibe directly addresses privacy concerns by ensuring no data ever leaves your device during transcription. It eliminates dependency on cloud-based transcription services (like AssemblyAI or Deepgram) while providing professional-grade accuracy through multiple model backends. The Ollama integration is particularly valuable for developers who want to experiment with local LLMs and build AI-powered workflows without incurring API costs or exposing sensitive audio data. The ability to batch transcribe files and support multiple output formats makes it a practical tool for processing large media libraries locally.

## Key Features & Technologies
- Offline transcription — no data leaves your device
- Supports Whisper, Nemotron 3.5, Parakeet TDT v3 models
- Ollama integration for local AI analysis and batch summaries
- Cross-platform desktop application built with Rust
- Realtime transcript preview during processing
- Batch transcription of multiple files at once
- Supports SRT, VTT, TXT, HTML, PDF, JSON, DOCX output formats

## Difference from Others
Unlike cloud-based transcription services (AssemblyAI, Deepgram, Whisper API), Vibe keeps all data local and private. Compared to other open-source tools like Whisper WebUI or Whisper Desktop, it offers a more polished GUI experience with additional features like real-time preview, batch processing, and multi-model support including Nemotron 3.5 and Parakeet TDT v3. The Ollama integration differentiates it further by enabling on-device LLM-based summarization without requiring an API key.

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
