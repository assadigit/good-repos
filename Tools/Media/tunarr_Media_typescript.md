---
source: https://github.com/chrisbenincasa/tunarr
aliases:
  - tunarr
  - chrisbenincasa/tunarr
tags: [typescript, ffmpeg, iptv, plex, jellyfin, emby, local-streaming, media-streaming, self-hosted, streaming, tv, swift]
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

> **TL;DR:** Create custom live TV channels from your Plex/Jellyfin/Emby media library, streamed as IPTV.

**`chrisbenincasa/tunarr`** · ⭐ 2,437 · 🔧 TypeScript

## What is it?
Tunarr is a self-hosted utility that lets you turn any media in Plex, Jellyfin, or Emby into live TV channels. It works by adding a spoofed HDHomeRun tuner device to your media server, so Plex, Jellyfin, and Emby treat your local files as if they were broadcast stations.

You can also export an M3U playlist that feeds any IPTV player (e.g., Tivimate) with your custom channels. The project ships as a Docker image under the Zlib license, making it easy to deploy in a homelab environment.

## How does it work?
Tunarr runs as a Docker container and uses ffmpeg to transcode media into streaming formats. It creates a virtual HDHomeRun tuner device that Plex, Jellyfin, and Emby recognize, allowing them to schedule recordings or stream content directly from your local library. Additionally, it generates M3U playlist files that can be imported into any IPTV client.

The spoofed tuner communicates over the network using standard HDHomeRun protocols, while ffmpeg handles the actual media processing. This architecture lets Tunarr bridge the gap between on-demand media servers and live TV broadcasting without requiring external hardware.

## Why is it important? (Core Value)
For someone interested in self-hostable alternatives to SaaS products, Tunarr offers a homelab-friendly way to build personal IPTV services. It solves the problem of having to rely on expensive hardware tuners or third-party streaming platforms, by letting you stream your own movies, TV episodes, and music videos as live channels. The open-source Zlib license means you can audit and modify it if needed, and the Docker image simplifies deployment.

It also provides a community Discord for support, making it a credible project to adopt in a personal knowledge base. For developers focused on automation and infrastructure, Tunarr is a useful example of how simple tools can combine media processing, network streaming, and media-server integration.

## Key Features & Technologies
- Uses ffmpeg for transcoding
- Provides M3U URL output
- Integrates with Plex/Jellyfin/Emby via spoofed HDHomeRun tuner
- Self-hosted Docker image
- Open-source under Zlib license
- Community support via Discord

## Difference from Others
Unlike generic IPTV generators that only output M3U playlists, Tunarr adds the ability to present itself as a tuner device to Plex, Jellyfin, and Emby. This dual capability—both tuner emulation and M3U export—distinguishes it from other self-hosted media servers that lack live TV channel creation features.

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
