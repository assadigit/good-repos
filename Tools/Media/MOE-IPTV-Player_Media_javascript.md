---
source: https://github.com/Mohammad-Aali/MOE-IPTV-Player
aliases:
  - MOE-IPTV-Player
  - Mohammad-Aali/MOE-IPTV-Player
tags: [javascript, iptv, cloudflare-workers, self-hosted, media, automation, url]
category: Media
stars: 59
org: Mohammad-Aali
primary_language: JavaScript
languages: [JavaScript, url]
credibility_score: 42.5/100
date_processed: 2026-07-07

cover: attachments/banners/MOE-IPTV-Player_banner.png

---

![banner](attachments/banners/MOE-IPTV-Player_banner.png)

# MOE-IPTV-Player

> **TL;DR:** Serverless IPTV web player with M3U management and dead-link cleaning via Cloudflare Workers.

**`Mohammad-Aali/MOE-IPTV-Player`** · ⭐ 59 · 🔧 JavaScript

## What is it?
MOE-IPTV-Player is a fully serverless IPTV web player built entirely on Cloudflare Workers edge infrastructure. It serves as a CORS proxy to enable smooth playback of video streams directly in the browser, while managing M3U playlist URLs through Cloudflare KV storage. The player includes password protection via cookie-based authentication and provides a user-friendly interface for adding, editing, and deleting IPTV source URLs.

## How does it work?
The project leverages Cloudflare Workers to run serverless JavaScript code at the edge, eliminating the need for traditional backend servers or databases. When you deploy it, you create a Worker application, paste in the worker.js code, and bind a KV namespace for persistent storage of your M3U playlists. The player fetches video streams through the Worker's proxy domain to bypass CORS restrictions that typically block direct playback of m3u8 files in browsers. All metadata—your custom sources, cleaned playlists, and favorites—is stored in Cloudflare KV, which provides automatic global replication without managing any database servers.

## Why is it important? (Core Value)
This project aligns perfectly with your interests in self-hostable alternatives to SaaS products and infrastructure. MOE-IPTV-Player gives you a privacy-friendly IPTV experience entirely under your control—hosted on Cloudflare for free, requiring no paid subscriptions or third-party services. The dead-link cleaner automates playlist maintenance, reducing manual effort when channels go offline. For your workflow, this provides a clean, serverless media player you can deploy yourself without managing any backend infrastructure, fitting neatly into your Obsidian vault under self-hosted software and homelab tools.

## Key Features & Technologies
- Serverless (Cloudflare Workers)
- CORS Proxy for m3u8 streams
- Password protection via cookies
- M3U source management UI
- Dead-link cleaner
- Favorites system
- KV storage

## Difference from Others
Unlike traditional IPTV players like VLC or Kodi, which require local hardware and OS installation, this runs serverless in the browser. Compared to subscription-based SaaS IPTV services, it's completely free with no monthly fees. It also differs from self-hosted media servers (like Jellyfin or Plex) by being purpose-built for IPTV specifically—it handles M3U playlists directly rather than managing local media files.

## 🏢 Organization & Credibility
- **Developer:** Mohammad-Aali
- **Reputation:** Unknown
- **Stars:** 59
- **Forks:** 17
- **Recent Activity:** 12 commits in 3 months
- **Credibility Score:** 42.5/100 (Low)
- **Languages:** JavaScript, url
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
*Source: [GitHub](https://github.com/Mohammad-Aali/MOE-IPTV-Player)*
