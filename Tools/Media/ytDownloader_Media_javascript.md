---
source: https://github.com/aandrew-me/ytDownloader
aliases:
  - ytDownloader
  - aandrew-me/ytDownloader
tags: [javascript, electron, nodejs, yt-dlp, video-downloader, cross-platform, downloader, youtube, javascript, linux, video, windows]
category: Media
stars: 9994
org: aandrew-me
primary_language: JavaScript
languages: [JavaScript, HTML, CSS, Shell, PowerShell]
credibility_score: 67.0/100
date_processed: 2026-07-22
last_release: 2026-07-17
cover: attachments/banners/ytDownloader_banner.png

---

![banner](attachments/banners/ytDownloader_banner.png)

# ytDownloader

> **TL;DR:** Desktop GUI video/audio downloader supporting hundreds of sites via yt-dlp, cross-platform (Linux/Windows/macOS).

**`aandrew-me/ytDownloader`** · ⭐ 9,994 · 🔧 JavaScript

## What is it?
ytDownloader is a modern desktop application that provides a graphical interface for downloading videos and audio from hundreds of websites using the powerful yt-dlp engine under the hood. Built with Electron, it runs natively on Linux, Windows, and macOS, offering a user-friendly experience while leveraging the extensive site support of yt-dlp.

Key features include cross-platform packaging options (AppImage, Snap, Flatpak, Chocolatey, WinGet) for easy installation without requiring development tools. The app integrates ffmpeg for audio extraction (e.g., converting video streams to MP3) and includes compression utilities to reduce file sizes before saving.

## How does it work?
The application wraps the yt-dlp command-line tool within an Electron framework to create a GUI front-end. When a user pastes a URL, ytDownloader invokes yt-dlp with appropriate flags to fetch video streams, then uses ffmpeg (bundled or system-installed) to extract audio tracks if requested. All operations run locally on the user's machine, respecting their privacy and avoiding cloud dependencies.

Distribution is handled via multiple package formats: AppImage for Linux universal binaries, Snap and Flatpak for sandboxed Linux environments, and Chocolatey/WinGet for Windows package managers. This ensures the software can be installed through standard system mechanisms on each platform.

## Why is it important? (Core Value)
ytDownloader offers a self-hostable alternative to SaaS video services, enabling offline media archiving and integration with homelab setups (e.g., Jellyfin, Plex). For developers interested in automation, it provides a GUI that can be scripted or combined with other tools for workflow orchestration. The cross-platform packaging aligns perfectly with your interest in self-hosted software and infrastructure, making it easy to deploy on any machine without relying on proprietary platforms.

Given your objectives to discover tools improving development workflow and identify self-hostable alternatives, this project directly supports media handling needs while offering a convenient entry point for non-technical users. It also demonstrates how Electron apps can be packaged for broad distribution, a pattern useful in building other productivity tools.

## Key Features & Technologies
- Electron-based GUI
- Cross-platform support (Linux, Windows, macOS)
- yt-dlp integration (supports hundreds of sites)
- AppImage/Snap/Flatpak packaging options
- ffmpeg for audio extraction
- Compression utilities

## Difference from Others
Compared to the original yt-dlp CLI tool, ytDownloader adds a graphical interface and convenient packaging options, making it accessible to users who prefer not to use command-line tools. Unlike older youtube-dl, it benefits from yt-dlp's extensive site support and modern features like compression. While other GUI wrappers exist, this project emphasizes multiple distribution formats (AppImage, Snap, Flatpak) and integrates ffmpeg out-of-the-box for audio conversion.

## 🏢 Organization & Credibility
- **Developer:** aandrew-me
- **Reputation:** Unknown
- **Stars:** 9,994
- **Forks:** 891
- **Recent Activity:** 73 commits in 3 months
- **Credibility Score:** 67.0/100 (Average)
- **Languages:** JavaScript, HTML, CSS, Shell, PowerShell
- **Last Release:** 2026-07-17
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
*Source: [GitHub](https://github.com/aandrew-me/ytDownloader)*
