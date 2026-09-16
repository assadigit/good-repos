---
source: https://github.com/rodrigogs/whats-reader
aliases:
  - whats-reader
  - rodrigogs/whats-reader
tags: [svelte, svelte, electron, whisper, ai, privacy, backup, bookmarks, whatsapp, chat-viewer, desktop-app, offline]
category: Media
stars: 248
org: rodrigogs
primary_language: Svelte
languages: [Svelte, TypeScript, JavaScript, CSS, HTML]
credibility_score: 39.5/100
date_processed: 2026-07-07
last_release: 2026-04-03


---

# whats-reader

> **TL;DR:** Offline WhatsApp chat reader with Whisper AI transcription and privacy-first SvelteKit/Electron desktop app.

**`rodrigogs/whats-reader`** · ⭐ 248 · 🔧 Svelte

## What is it?
whats-reader (also known as WhatsApp Backup Reader) is a privacy-focused desktop and web application that allows users to browse their WhatsApp chat exports entirely offline. The core purpose is to let people read, search, and analyze WhatsApp backups without ever uploading data to cloud services or requiring an active internet connection.

The app provides several key features: it can parse WhatsApp chat export files (typically JSON format) and present them in a readable interface with bookmarks for easy navigation, full-text search across messages, and statistics such as message counts and timeline views. Voice messages are transcribed locally using Whisper AI, keeping all data on the user's device.

## How does it work?
whats-reader uses Electron to create a cross-platform desktop application that runs a Chromium-based browser environment with Node.js access. The UI is built with SvelteKit, which provides a reactive frontend optimized for performance and code organization. For transcription, it integrates Whisper running locally on the user's machine (the 'AI-Whisper_local' badge indicates this), meaning no audio data leaves the device.

The architecture follows a typical Electron pattern: the main process manages native OS features and loads the SvelteKit-rendered frontend in a renderer process. CI/CD workflows are automated via GitHub Actions to test changes against the latest WhatsApp export formats, ensuring compatibility.

## Why is it important? (Core Value)
This project is valuable because it gives users full control over their privacy when handling sensitive chat data. Unlike many other tools that require uploading WhatsApp exports to cloud services or depend on internet connectivity, whats-reader ensures 100% offline operation with no data leaving the device. The integration of Whisper for local transcription means voice messages are processed without sending audio files to external APIs.

For the user's specific objectives and interests, this project aligns well in several ways: it is a self-hostable alternative to SaaS products (no subscription or cloud dependency), which directly supports the goal of identifying privacy-first, locally-run software. It is a developer tool built with open-source technologies (Svelte, Electron) that could be integrated into homelab setups or used as part of an Obsidian vault's 'Tools' category. Additionally, it touches AI/LLM-related interests through Whisper, though it is not an AI agent—it's an infrastructure/utility tool that processes media files from chats.

## Key Features & Technologies
- Whisper AI (local)
- SvelteKit
- Electron 39
- Privacy-first
- Bookmarks & search

## Difference from Others
whats-reader stands out compared to similar projects in two main ways: its privacy-first design and its tech stack. Many other WhatsApp export readers are Python scripts or Node.js CLI tools that may still require internet connectivity or rely on cloud APIs (e.g., Whisper via OpenAI's service). whats-reader, by contrast, runs entirely offline and uses local Whisper, ensuring no data leaves the device.

Additionally, the SvelteKit + Electron combination is relatively uncommon for this use case. Most comparable tools are built with heavier frameworks like React or plain Python, which can be less performant and harder to package as a single portable app. whats-reader's focus on keeping all processing local and its use of SvelteKit's reactive paradigm also makes it more lightweight and easier to maintain as a standalone desktop application.

## 🏢 Organization & Credibility
- **Developer:** rodrigogs
- **Reputation:** Unknown
- **Stars:** 248
- **Forks:** 24
- **Recent Activity:** 0 commits in 3 months
- **Credibility Score:** 39.5/100 (Low)
- **Languages:** Svelte, TypeScript, JavaScript, CSS, HTML
- **Last Release:** 2026-04-03
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
*Source: [GitHub](https://github.com/rodrigogs/whats-reader)*
