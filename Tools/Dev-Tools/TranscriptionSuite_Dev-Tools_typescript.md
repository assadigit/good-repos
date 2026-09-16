---
source: https://github.com/homelab-00/TranscriptionSuite
aliases:
  - TranscriptionSuite
  - homelab-00/TranscriptionSuite
tags: [typescript, python, whisper, cuda, docker, local-first, nemo, mlx, vulkan, dictation-tool, linux-app, macos-app]
category: Dev-Tools
stars: 608
org: homelab-00
primary_language: TypeScript
languages: [TypeScript, Python, JavaScript, Shell, PowerShell]
credibility_score: 57.0/100
date_processed: 2026-07-22
last_release: 2026-07-19
cover: attachments/banners/TranscriptionSuite_banner.png

---

![banner](attachments/banners/TranscriptionSuite_banner.png)

# TranscriptionSuite

**`homelab-00/TranscriptionSuite`** · ⭐ 608 · 🔧 TypeScript

## What is it?
TranscriptionSuite is a free, open-source speech-to-text application that runs entirely on your own computer. Record lectures, dictate documents, or import audio files and receive accurate transcripts with speaker labels in minutes—all without sending data to any cloud service. Your privacy is preserved because everything stays local.

The app combines an Electron-based dashboard UI with a Python backend that supports multiple speech-to-text models, including Whisper, NVIDIA NeMo, VibeVoice-ASR, SenseVoice, whisper.cpp, and MLX for Apple Silicon. It leverages hardware acceleration via NVIDIA CUDA, Apple Metal, or AMD/Intel Vulkan, falling back gracefully to CPU when needed.

Built with Docker for rapid deployment, it ships pre-configured binaries for Windows 11, macOS, and Linux. Additional features include diarization (speaker separation) and a calendar mode that can auto-create events from transcribed meetings, making it suitable for both personal dictation and professional workflows.

## How does it work?
The core architecture consists of an Electron frontend that provides a cross-platform UI (dashboard) communicating with a Python backend that orchestrates speech-to-text inference. The backend loads models via ONNX Runtime or native libraries (whisper.cpp, NeMo's torch-based engine), selects the appropriate hardware accelerator based on available GPUs/Apple Silicon, and pipes audio streams through the chosen model. Results are streamed back to the UI for display and export.

Docker Compose provides a one-command setup that spins up the Python service and any required GPU containers, making it trivial to run the app in homelab environments or on bare metal. The app also includes utilities for diarization using open-source speaker-separation models and calendar mode integration with local calendar APIs.

## Why is it important? (Core Value)
TranscriptionSuite addresses the growing demand for privacy-preserving transcription tools in an era where most SaaS offerings require uploading audio to cloud APIs. By offering multiple model backends, hardware acceleration, and a local-first workflow, it gives users control over both performance and data residency. This is especially valuable for researchers, journalists, or anyone who records sensitive meetings and cannot afford leaks.

For a software engineer and researcher interested in self-hosted alternatives to SaaS products, this project fits perfectly into a homelab stack alongside other privacy-focused tools. It can be cataloged as a developer productivity tool, providing a reliable offline transcription capability that complements LLM-based note-taking pipelines or personal knowledge bases. Its modular design (Electron + Python) also makes it a good learning resource for building cross-platform apps with hardware-accelerated AI models.

## Key Features & Technologies
- Whisper
- NVIDIA NeMo
- MLX
- Vulkan
- diarization
- Dockerized
- Electron

## Difference from Others
Compared to standalone Whisper.cpp or OpenAI's Whisper API, TranscriptionSuite offers a unified GUI that bundles multiple backends and includes diarization and calendar mode out of the box. Unlike cloud-only services such as Otter.ai or Google Speech-to-Text, it runs entirely offline, preserving privacy and avoiding subscription costs. For users who already use Python-based transcription tools, this app provides a ready-made interface and hardware acceleration support that would otherwise require manual model integration and GPU tuning.

## 🏢 Organization & Credibility
- **Developer:** homelab-00
- **Reputation:** Unknown
- **Stars:** 608
- **Forks:** 54
- **Recent Activity:** 484 commits in 3 months
- **Credibility Score:** 57.0/100 (Low)
- **Languages:** TypeScript, Python, JavaScript, Shell, PowerShell
- **Last Release:** 2026-07-19
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
*Source: [GitHub](https://github.com/homelab-00/TranscriptionSuite)*
