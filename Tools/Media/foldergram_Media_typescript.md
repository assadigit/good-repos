---
source: https://github.com/foldergram/foldergram
aliases:
  - foldergram
  - foldergram/foldergram
tags: [typescript, typescript, vue, nodejs, docker, sqlite, express, ffmpeg, folder-based, instagram, local-first, media-gallery]
category: Media
stars: 496
org: foldergram
primary_language: TypeScript
languages: [TypeScript, Vue, CSS, HTML, JavaScript]
credibility_score: 51.0/100
date_processed: 2026-07-07
last_release: 2026-06-01
cover: attachments/banners/foldergram_banner.png

---

![banner](attachments/banners/foldergram_banner.png)

# foldergram

> **TL;DR:** Self-hosted folder-based Instagram-style photo and video gallery app.

**`foldergram/foldergram`** · ⭐ 496 · 🔧 TypeScript

## What is it?
Foldergram is a self-hosted web application that transforms local folders into an Instagram-inspired photo and video gallery. It provides a clean, responsive UI built with Vue 3 and Vite, allowing users to browse their media files as if they were on Instagram, while keeping everything offline and under their control.

The app organizes media by folder structure, supports both photos and videos, and includes PWA capabilities so it can be installed on desktop or mobile devices. Metadata is stored in a lightweight SQLite database, making the installation minimal and fast to deploy via Docker containers.

## How does it work?
The backend runs on Node.js 22 LTS using Express for HTTP routing and serves static assets from Vite's dev server. FFmpeg is invoked when processing video thumbnails or transcoding uploads. All state persists in SQLite, which reads the local file system to build the gallery index.

Deployment is Dockerized with an official GitHub Container Registry image, simplifying setup for homelab environments. The frontend communicates via REST APIs exposed by Express, and the PWA manifest enables offline-first caching of UI resources.

## Why is it important? (Core Value)
For a software engineer focused on self-hostable alternatives to SaaS products, Foldergram directly addresses your interest in privacy‑preserving media management tools. It replaces Instagram's cloud dependency with a locally run instance that keeps all photos and videos on your own storage, fitting neatly into a homelab setup.

In your Obsidian vault you can categorize it under Infrastructure or Tools, using it as a reference for building custom media galleries. Its open‑source AGPL v3 license ensures you can audit the code, and its lightweight Docker image aligns with your workflow of discovering developer productivity tools that integrate cleanly into existing stacks.

## Key Features & Technologies
- Local-first folder-based gallery UI
- Dockerized deployment (official GHCR image)
- Vue 3 + Vite frontend
- Express.js backend API
- SQLite metadata storage
- FFmpeg video transcoding
- PWA installable on mobile/desktop

## Difference from Others
Compared to other self-hosted photo galleries like PhotoPrism (Java, tag‑based) or Immich (Go, cloud‑optimized), Foldergram is intentionally lightweight and focused on folder structure rather than AI‑driven tagging. It runs entirely on Node.js/Express, uses SQLite instead of PostgreSQL, and offers PWA support with a minimal footprint—ideal for homelab users who want a simple Instagram‑style experience without heavy dependencies.

## 🏢 Organization & Credibility
- **Developer:** foldergram
- **Reputation:** Unknown
- **Stars:** 496
- **Forks:** 26
- **Recent Activity:** 44 commits in 3 months
- **Credibility Score:** 51.0/100 (Low)
- **Languages:** TypeScript, Vue, CSS, HTML, JavaScript
- **Last Release:** 2026-06-01
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
*Source: [GitHub](https://github.com/foldergram/foldergram)*
