---
source: https://github.com/amiralibg/unstream
aliases:
  - unstream
  - amiralibg/unstream
tags: [typescript, docker, music, self-hosted, audio, mp3, python, css, html, javascript]
category: Scraping
stars: 213
org: amiralibg
primary_language: TypeScript
languages: [TypeScript, Python, CSS, HTML, JavaScript]
credibility_score: 55.5/100
date_processed: 2026-08-19

cover: attachments/banners/unstream_banner.png

---

![banner](attachments/banners/unstream_banner.png)

# unstream

> **TL;DR:** Self-hosted Docker app that downloads tagged mp3s from Spotify, Deezer, Apple Music, YouTube, and SoundCloud via URL or search.

**`amiralibg/unstream`** · ⭐ 213 · 🔧 TypeScript

## What is it?
Unstream is a self-hosted music download tool that lets users paste a track, album, or playlist URL from Spotify, Deezer, Apple Music, YouTube, or SoundCloud — or search across all catalogs simultaneously — and receive tagged audio files. It runs entirely via Docker, requiring no Python, Node, or ffmpeg on the host machine. The interface is available in both Farsi and English, with Farsi as the default locale, reflecting its primary audience.
The tool supports multiple output quality options, including 128, 192, and 320 kbps MP3 encoding, or the original stream untouched. Finished tracks are saved as real files in a local directory, giving users full ownership of their music library without relying on any streaming service or third-party API. The project emphasizes file ownership, positioning it as a self-sovereignty tool rather than a convenience wrapper around streaming services.

## How does it work?
Unstream is deployed via `docker compose up -d` and exposes a web UI at `localhost:8080`. The application resolves URLs from supported music platforms, downloads the corresponding audio, and tags the resulting files with metadata. The entire pipeline runs within Docker containers, abstracting away dependencies like Python, Node, and ffmpeg from the host system.
The tool operates without requiring any API keys, accounts, or paid service integrations. Users can either paste a specific URL or use the built-in search to query multiple catalogs at once. The bilingual interface (Farsi/English) is switchable from the header, and the default locale can be configured via the `UNSTREAM_DEFAULT_LOCALE` environment variable. Downloads are organized by job ID in a `./downloads/` directory.

## Why is it important? (Core Value)
For a software engineer focused on self-hostable alternatives to SaaS products, Unstream represents a practical example of a self-hosted media tool that eliminates dependency on commercial streaming services. It provides a Docker-based solution that runs independently, with no API keys or paid tiers, making it a strong candidate for homelab infrastructure. The project demonstrates how to build a complete web application (frontend + backend + audio processing) that's deployable with a single Docker Compose command.
The tool's approach to multi-platform URL resolution without API keys is technically interesting, and the bilingual UI (built for a Farsi-speaking audience) shows thoughtful localization. For someone building a personal knowledge base of self-hosted tools, Unstream fills the "own your media" gap in a homelab setup, complementing other self-hosted services. The Docker-only deployment model is also relevant for infrastructure experimentation.

## Key Features & Technologies
- Multi-platform URL support (Spotify, Deezer, Apple Music, YouTube, SoundCloud)
- Docker Compose deployment with no host dependencies
- Selectable output quality (128/192/320 kbps MP3 or original stream)
- Tagged audio file output with metadata
- Bilingual Farsi/English web UI with configurable default locale
- No API keys, accounts, or paid services required
- Cross-catalog search across all supported platforms

## Difference from Others
Compared to other music download tools, Unstream stands out for its zero-configuration approach — no API keys, no accounts, no paid services. Most alternatives require OAuth tokens or paid API access to resolve URLs. The Docker-based deployment means the entire toolchain (including ffmpeg for audio processing) is containerized, eliminating host dependencies entirely.
The bilingual interface with Farsi as the default locale is distinctive, reflecting a specific audience focus rather than a generic global tool. The cross-catalog search feature, allowing simultaneous querying of multiple music platforms, is also a differentiator. The project's emphasis on file ownership positions it as a self-sovereignty tool rather than just a downloader.

## 🏢 Organization & Credibility
- **Developer:** amiralibg
- **Reputation:** Unknown
- **Stars:** 213
- **Forks:** 43
- **Recent Activity:** 74 commits in 3 months
- **Credibility Score:** 55.5/100 (Low)
- **Languages:** TypeScript, Python, CSS, HTML, JavaScript
- **Last Release:** No releases
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
*Source: [GitHub](https://github.com/amiralibg/unstream)*
