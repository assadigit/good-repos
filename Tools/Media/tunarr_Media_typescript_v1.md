---
source: https://github.com/chrisbenincasa/tunarr
aliases:
  - tunarr
  - chrisbenincasa/tunarr
tags: [typescript, ffmpeg, iptv, plex, self-hosted, streaming, local-streaming, media-streaming, tv, emby, jellyfin, swift]
category: Media
stars: 2437
org: chrisbenincasa
primary_language: TypeScript
languages: [TypeScript, Swift, JavaScript, Dockerfile, Shell]
credibility_score: 62.0/100
date_processed: 2026-07-06
last_release: 2026-06-27
cover: attachments/banners/tunarr_banner.png

---

![banner](attachments/banners/tunarr_banner.png)

# tunarr

> **TL;DR:** Turn your Plex/Jellyfin/Emby library into a live IPTV channel with a spoofed HDHomeRun tuner.

**`chrisbenincasa/tunarr`** · ⭐ 2,437 · 🔧 TypeScript

## What is it?
Tunarr lets you build custom live TV channels from your existing media libraries — movies, TV episodes, music videos, or local files — and stream them as if they were real broadcast channels. Instead of relying on external IPTV services, you create your own channels using content already stored on your home servers.

You can add Tunarr's spoofed HDHomeRun tuner directly to Plex, Jellyfin, or Emby, making your media appear as live TV channels in those clients. Alternatively, you can grab the M3U URL and use it with any IPTV player like Tivimate. The project is self-hosted and provides Docker images for easy deployment.

## How does it work?
Tunarr operates by watching your Plex/Jellyfin/Emby servers or local file paths for media that can be used as live TV content. It then generates an M3U playlist URL that references the content, effectively presenting it as a broadcast stream. The backend likely uses ffmpeg (indicated by the topics) to handle any necessary transcoding or streaming protocol conversion.

The project is distributed both as source code and pre-built Docker images, making it straightforward to deploy in a homelab environment. Integration with Plex/Jellyfin/Emby is achieved through their respective tuner API endpoints, allowing seamless discovery of your custom channels.

## Why is it important? (Core Value)
For a software engineer interested in self-hosted alternatives to SaaS products and homelab infrastructure, Tunarr directly addresses the desire for open-source tools that replace commercial services. It lets you keep all your media on your own servers while still enjoying live TV functionality without subscribing to expensive IPTV providers.

The project also aligns with interests in automation and workflow orchestration — once configured, it runs autonomously, polling content sources and maintaining playlist URLs. Additionally, it represents a practical example of how media server ecosystems (Plex/Jellyfin/Emby) can be extended beyond their intended use cases, demonstrating the flexibility of self-hosted software.

## Key Features & Technologies
- Uses ffmpeg
- Self-hosted
- Docker image available
- Generates M3U playlists
- Spoofed HDHomeRun tuner support
- Integrates with Plex/Jellyfin/Emby
- Local streaming

## Difference from Others
Unlike full IPTV server solutions that manage existing broadcast streams, Tunarr focuses specifically on converting your personal media library into live TV channels. It provides a lightweight, self-contained approach rather than trying to be a general-purpose media server replacement.

Compared to building similar functionality from scratch with raw ffmpeg and custom APIs, Tunarr offers an out-of-the-box solution with Docker support and pre-configured tuner integration for Plex/Jellyfin/Emby — saving significant development time while maintaining the flexibility of local streaming.

## 🏢 Organization & Credibility
- **Developer:** chrisbenincasa
- **Reputation:** Unknown
- **Stars:** 2,437
- **Forks:** 106
- **Recent Activity:** 174 commits in 3 months
- **Credibility Score:** 62.0/100 (Average)
- **Languages:** TypeScript, Swift, JavaScript, Dockerfile, Shell
- **Last Release:** 2026-06-27
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
*Source: [GitHub](https://github.com/chrisbenincasa/tunarr)*
