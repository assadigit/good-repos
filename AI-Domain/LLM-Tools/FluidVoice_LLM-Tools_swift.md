---
source: https://github.com/altic-dev/FluidVoice
aliases:
  - FluidVoice
  - altic-dev/FluidVoice
tags: [swift, swift, macos, ai, stt, llama-cpp, dictation, ios, c, shell, url]
category: LLM-Tools
stars: 6182
org: altic-dev
primary_language: Swift
languages: [Swift, C, Shell, url]
credibility_score: 65.5/100
date_processed: 2026-07-05
last_release: 2026-06-28
cover: attachments/banners/FluidVoice_banner.png

---

![banner](attachments/banners/FluidVoice_banner.png)

# FluidVoice

> **TL;DR:** macOS dictation app with on-device AI STT; self-hosted Wispr Flow alternative.

**`altic-dev/FluidVoice`** · ⭐ 6,182 · 🔧 Swift

## What is it?
FluidVoice is an open-source voice-to-text dictation application for macOS that runs entirely on-device using custom trained AI enhancement models. It integrates multiple speech-to-text backends including Whisper, Parakeet, and Cohere models to provide accurate transcription locally without sending audio to the cloud. The app is built with Swift and leverages llama-cpp for efficient local inference of large language models used to enhance speech quality and context.

The project positions itself as a privacy-first alternative to cloud-based dictation services like Wispr Flow, offering users full control over their data while maintaining high accuracy on macOS. It currently supports Homebrew installation via `brew install --cask fluidvoice` and provides manual download links for the latest release, with iOS and Windows versions planned for future releases.

## How does it work?
FluidVoice operates by capturing system audio input from the macOS dictation engine and processing it through a pipeline of on-device AI models. The app uses Swift's native audio frameworks to receive real-time speech input, then routes it to local Whisper or Parakeet models for initial speech-to-text conversion. Custom trained enhancement models (likely fine-tuned variants of these) are applied to improve transcription accuracy and handle edge cases like background noise or dialect variations.

For the AI inference step, FluidVoice integrates llama-cpp, a high-performance C++ library that enables running large language models locally with minimal memory footprint. This allows the app to perform both the initial speech recognition and any downstream enhancement tasks entirely on the user's hardware, ensuring privacy and offline capability. The architecture is designed to be modular, allowing users to swap out model backends if needed.

## Why is it important? (Core Value)
FluidVoice directly aligns with your interest in self-hosted alternatives to SaaS products and open-source developer tools. As a software engineer focused on AI agents and automation, this project offers a practical example of how local LLM inference can be applied to a real-world utility—dictation—without relying on cloud APIs. It demonstrates the viability of running privacy-preserving transcription workflows entirely on-device, which is valuable for anyone building homelab infrastructure or seeking alternatives to services like Wispr Flow.

The app also supports multiple model families, including those from NVIDIA (Nemotron Speech), Cohere, and Apple's own speech models, giving you flexibility to choose the best balance of accuracy and resource usage. Its Swift implementation on macOS makes it particularly relevant for Apple ecosystem users, while the open-source nature allows for inspection, modification, and integration into other workflows. This project could serve as a reference point for how to design and deploy local AI tools that respect user privacy.

## Key Features & Technologies
- macOS support
- Swift framework
- llama-cpp integration
- Whisper model support
- Parakeet model support
- Cohere model support
- Apple Speech model support

## Difference from Others
Unlike cloud-based dictation services, FluidVoice runs entirely on-device with no audio sent to external servers, preserving user privacy. It is specifically optimized for macOS using Swift, whereas many alternatives are cross-platform or require Java/.NET backends. Compared to Wispr Flow, FluidVoice offers self-hosted model support (including custom-trained variants) and integrates with llama-cpp for efficient local inference rather than relying solely on proprietary APIs. Its modular design also allows swapping models without recompiling the app.

## 🏢 Organization & Credibility
- **Developer:** altic-dev
- **Reputation:** Unknown
- **Stars:** 6,182
- **Forks:** 382
- **Recent Activity:** 295 commits in 3 months
- **Credibility Score:** 65.5/100 (Average)
- **Languages:** Swift, C, Shell, url
- **Last Release:** 2026-06-28
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
*Source: [GitHub](https://github.com/altic-dev/FluidVoice)*
