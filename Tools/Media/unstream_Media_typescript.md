---
source: https://github.com/amiralibg/unstream
aliases:
  - unstream
  - amiralibg/unstream
tags: [typescript, music, docker, self-hosted, audio-conversion, media, python, css, html, javascript]
category: Media
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

> **TL;DR:** Self-hosted music downloader that converts Spotify/YouTube/Deezer URLs to tagged MP3 files via Docker.

**`amiralibg/unstream`** · ⭐ 213 · 🔧 TypeScript

## What is it?
Unstream is a self-hosted music downloading and conversion tool that lets users paste URLs from Spotify, Deezer, Apple Music, YouTube, or SoundCloud (tracks, albums, or playlists) and receive tagged MP3 audio files. It supports multiple quality levels (128, 192, 320 kbps) or the original stream untouched. The tool requires no accounts, API keys, or paid services — everything runs locally via Docker Compose.

The interface ships in both Farsi and English (Farsi is the default locale, reflecting its target audience), switchable from the header. Finished downloads land in a local folder (./downloads/<job-id>/) as real, tagged audio files. The project is designed so that users own their music files directly, with no third-party intermediary.

## How does it work?
Unstream operates as a Docker-based service deployed via `docker compose up -d`. It requires no local dependencies beyond Docker — no Python, Node, or ffmpeg on the user's machine. The service exposes a web interface on localhost:8080 where users can search across all supported catalogs simultaneously or paste a specific URL. The backend handles the extraction and conversion pipeline, producing tagged MP3 files at the user-selected bitrate.

The architecture is containerized and self-contained, making it a single-command deployment. The bilingual interface (Farsi/English) is configurable via the environment variable `UNSTREAM_DEFAULT_LOCALE`. The project includes documentation in English and Farsi, with a design document explaining the Farsi-first approach.

## Why is it important? (Core Value)
For a software engineer focused on self-hosted alternatives to SaaS products, Unstream represents a concrete example of a self-hosted media tool that eliminates dependency on paid streaming services and API ecosystems. It aligns with the interest in self-hostable software and homelab infrastructure — a single Docker Compose deployment replaces multiple SaaS music services. The project also demonstrates an approach to cross-platform data extraction (pulling audio from five different services without official APIs) that could inform scraping or automation workflows. Additionally, the Farsi/English bilingual design and the 'no API keys, no accounts' philosophy make it a useful reference for building accessible, zero-configuration self-hosted tools.

## Key Features & Technologies
- Supports Spotify, Deezer, Apple Music, YouTube, and SoundCloud URL extraction
- Docker Compose single-command deployment with no local dependencies
- Tagged MP3 output at selectable quality (128/192/320 kbps) or original stream
- Bilingual Farsi/English interface with configurable default locale
- Searches all supported catalogs simultaneously
- No accounts, API keys, or paid services required

## Difference from Others
Unlike typical music downloaders that rely on official APIs (which require developer accounts and have rate limits) or browser extensions (which are fragile and platform-locked), Unstream operates entirely locally with no external API dependencies. It supports five major music platforms in a single tool rather than requiring separate tools per service. Compared to general-purpose media converters (like yt-dlp), Unstream is purpose-built for music catalogs with built-in tagging, multi-platform search, and a polished bilingual web UI. The Farsi-first design also sets it apart from most English-only open-source media tools, targeting an underserved audience.

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
