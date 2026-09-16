---
source: https://github.com/cjpais/handy
aliases:
  - handy
  - cjpais/handy
tags: [rust, rust, typescript, tauri, speech-to-text, whisper, tauri-v2, accessibility, cross-platform, nix, nsis, css]
category: LLM-Tools
stars: 25885
org: cjpais
primary_language: Rust
languages: [Rust, TypeScript, Nix, NSIS, CSS]
credibility_score: 66.0/100
date_processed: 2026-07-07
last_release: 2026-07-01
cover: attachments/banners/handy_banner.png

---

![banner](attachments/banners/handy_banner.png)

# handy

> **TL;DR:** Offline speech-to-text desktop app using Whisper.

**`cjpais/handy`** · ⭐ 25,885 · 🔧 Rust

## What is it?
Handy is a cross-platform desktop application that provides privacy-focused speech transcription. It works completely offline, allowing users to press a shortcut, speak, and have their words transcribed locally without sending any audio data to the cloud. The project emphasizes being free, open source, extensible, and simple—aiming to be the most forkable tool rather than the best speech-to-text app.

Key features include support for multiple operating systems (Windows, macOS, Linux), configurable keyboard shortcuts or push-to-talk modes, and integration with Whisper for high-quality transcription. The codebase is built using Tauri v2, which provides a robust framework for creating native-like desktop applications while maintaining open-source licensing.

## How does it work?
The application operates through a straightforward four-step process: users press a configurable keyboard shortcut (or enable push-to-talk mode) to start recording, speak their desired text, release the shortcut, and Handy immediately processes the audio using Whisper running locally on their machine. Whisper handles the speech recognition entirely offline, meaning no audio data leaves the user's device. The resulting transcription is then pasted directly into whatever text field or application the user had focused on when they initiated recording.

Technically, Handy uses Tauri v2 as its core framework, which combines a lightweight backend (Rust) with a frontend (typically web technologies like TypeScript/JavaScript). This architecture ensures native performance and cross-platform compatibility while keeping the entire pipeline—audio capture, Whisper inference, text output—local to the user's system. The privacy-first design means Whisper models are downloaded once and cached locally, avoiding any dependency on external APIs or network calls during transcription.

## Why is it important? (Core Value)
Handy fills a critical gap in the open-source ecosystem by providing a truly private, free, and extensible speech-to-text solution. Unlike commercial alternatives that monetize user voice data or require internet connectivity, Handy keeps all processing local and gives users full control over their workflow. Its simplicity—focused solely on transcription without unnecessary features—makes it an ideal foundation for further development.

For someone like you, who curates tools for a personal knowledge base, Handy offers immediate value as a self-hostable utility that can be integrated into your Obsidian vault or other productivity systems. You can fork it to adapt Whisper models, add custom keyboard shortcuts, or embed its transcription capabilities into AI agent workflows (e.g., voice commands for agents). Its open-source nature aligns with your interest in discovering tools that improve development workflows and finding self-hostable alternatives to SaaS products. Additionally, Handy's cross-platform support ensures compatibility across your various devices, while its privacy focus resonates with your commitment to open-source and data-minimalist approaches.

## Key Features & Technologies
- Uses Whisper for transcription
- Cross-platform desktop app (Windows/macOS/Linux)
- Privacy-first (no cloud processing)
- Configurable keyboard shortcut or push-to-talk mode
- Built on Tauri v2 framework
- Open source and extensible codebase
- Simple UI focused on one job

## Difference from Others
Handy stands out among speech-to-text tools primarily for its commitment to privacy and openness. While services like Google Docs Voice Typing, Speechify, or Otter.ai require internet access and send audio data to cloud servers (potentially monetizing it), Handy processes everything locally with Whisper. Commercial apps often bundle transcription features with broader productivity suites, whereas Handy is minimalist—just one tool for one job. Its open-source license invites community contributions and forks, making it more adaptable than proprietary alternatives. Additionally, Handy's Tauri-based architecture provides native desktop performance without the overhead of web wrappers, giving it a competitive edge in both privacy and usability.

## 🏢 Organization & Credibility
- **Developer:** cjpais
- **Reputation:** Unknown
- **Stars:** 25,885
- **Forks:** 2218
- **Recent Activity:** 40 commits in 3 months
- **Credibility Score:** 66.0/100 (Average)
- **Languages:** Rust, TypeScript, Nix, NSIS, CSS
- **Last Release:** 2026-07-01
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
*Source: [GitHub](https://github.com/cjpais/handy)*
