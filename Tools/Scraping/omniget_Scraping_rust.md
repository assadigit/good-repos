---
source: https://github.com/tonhowtf/omniget
aliases:
  - omniget
  - tonhowtf/omniget
tags: [rust, rust, tauri, svelte, media-downloader, yt-dlp, download-manager, instagram-downloader, reddit-downloader, tiktok-downloader, twitter-downloader, video-downloader]
category: Scraping
stars: 7248
org: tonhowtf
primary_language: Rust
languages: [Rust, TypeScript, JavaScript, CSS, HTML]
credibility_score: 67.0/100
date_processed: 2026-07-23
last_release: 2026-07-10
cover: attachments/banners/omniget_banner.png

---

![banner](attachments/banners/omniget_banner.png)

# omniget

> **TL;DR:** Cross-platform media downloader with PDF/EPUB reader, focus mode, timestamped notes, and spaced repetition.

**`tonhowtf/omniget`** · ⭐ 7,248 · 🔧 Rust

## What is it?
OmniGet is a native cross-platform desktop application built with Tauri (Rust) and Svelte that lets you download media from over 1,800 sites without using a terminal. It includes a built-in PDF/EPUB reader with focus mode, timestamped notes, and spaced repetition for studying downloaded content.

## How does it work?
The app uses Tauri's Rust backend to handle OS-level processes (invoking yt-dlp, managing file storage), while Svelte provides a responsive frontend UI. Media downloads are performed via yt-dlp, which parses URLs and streams content; the plugin system allows adding new site integrations or modifying behavior. PDF/EPUB reading likely leverages a lightweight rendering engine to present documents in focus mode. The app stores notes and timestamps in a local database for spaced repetition algorithms.

## Why is it important? (Core Value)
For your objectives, OmniGet provides a self-hostable alternative to SaaS media consumption tools—no cloud dependency or subscription required. The Rust/Tauri stack gives you a modern, performant foundation you could adapt as a template for other developer tools. Its plugin system demonstrates extensibility that's valuable when integrating with automation pipelines (e.g., triggering spaced repetition via LLM agents). The focus mode and timestamped notes directly support learning workflows, aligning with your interest in AI agents and automation. In short, it's both an immediate utility and a case study in cross-platform Rust app architecture.

## Key Features & Technologies
- Native cross-platform (Rust + Svelte)
- PDF/EPUB reader with focus mode
- Timestamped notes & spaced repetition
- 1,800+ site media downloader via yt-dlp
- Extensible plugin system
- GPL-3.0 license
- Open-source desktop app

## Difference from Others
Compared to JDownloader2 (Java-based, lacks native UI), Video DownloadHelper (Chrome extension only), or other Tauri apps that are simpler, OmniGet integrates a dedicated reading environment with spaced repetition—seamless from download to study. It uses Rust for better performance and smaller binary size vs Java/Python solutions. The plugin system enables community-driven extensions, unlike many static CLI tools.

## 🏢 Organization & Credibility
- **Developer:** tonhowtf
- **Reputation:** Unknown
- **Stars:** 7,248
- **Forks:** 618
- **Recent Activity:** 114 commits in 3 months
- **Credibility Score:** 67.0/100 (Average)
- **Languages:** Rust, TypeScript, JavaScript, CSS, HTML
- **Last Release:** 2026-07-10
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
*Source: [GitHub](https://github.com/tonhowtf/omniget)*
