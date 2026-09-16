---
source: https://github.com/MSC72m/media_downloader
aliases:
  - media_downloader
  - MSC72m/media_downloader
tags: [python, python, yt-dlp, desktop, cross-platform, media, customtkinter, desktop-application, instagram-downloader, media-downloader, music-downloader, pinterest-downloader]
category: Scraping
stars: 258
org: MSC72m
primary_language: Python
languages: [Python, Inno Setup, Batchfile, Shell, url]
credibility_score: 57.0/100
date_processed: 2026-07-07
last_release: 2026-06-16
cover: attachments/banners/media_downloader_banner.png

---

![banner](attachments/banners/media_downloader_banner.png)

# media_downloader

> **TL;DR:** Cross-platform desktop app to download videos and audio from YouTube, Spotify, TikTok, Instagram, Twitter, Pinterest, SoundCloud, RadioJavan using yt-dlp.

**`MSC72m/media_downloader`** · ⭐ 258 · 🔧 Python

## What is it?
Media Downloader is a cross-platform desktop application that lets users download videos and audio from a wide range of social media platforms, including YouTube, Instagram, TikTok, Twitter, Pinterest, SoundCloud, Spotify, and RadioJavan. Built on top of the yt-dlp library, it provides a user-friendly GUI using customtkinter, making it accessible to non-technical users while still leveraging the powerful capabilities of yt-dlp under the hood.

Key features include support for both video and audio extraction, automatic handling of platform-specific formats, and a clean, modern interface. The application is fully open-source under the GPLv3 license and offers pre-built installers for Windows, macOS, and Linux. It is actively maintained (version 1.1.1) with a modest but growing community (258 stars, 25 forks).

Media Downloader stands out among similar tools because it combines a graphical interface with the robustness of yt-dlp, making it suitable for both casual users and developers who want to automate media retrieval. While other solutions focus on command-line usage or single-platform scrapers, this project provides broad platform coverage in one convenient application.

## How does it work?
Media Downloader operates by using yt-dlp as its core download engine, which is invoked through customtkinter's GUI interface. When a user enters a URL (YouTube, Instagram, TikTok, etc.), the application parses the input and passes it to yt-dlp via subprocess calls or direct API interaction. The downloaded content is then saved to a designated local directory on the system.

The architecture relies on Python 3.10+ with customtkinter providing a modern, cross-platform UI that adapts to Windows, Linux, and macOS environments. There are no external cloud dependencies—the application runs entirely locally, fetching media directly from the target platform's servers and writing files to disk. This makes it suitable for homelab setups and self-hosted workflows.

## Why is it important? (Core Value)
This project is valuable because it offers a self-hosted alternative to SaaS-based media consumption services (YouTube Premium, Spotify offline, etc.), giving users full control over their downloads without subscription costs. It is open-source under GPLv3, making its code transparent and auditable—which aligns with your interest in learning new approaches to scraping and automation.

Specifically for your objectives: Media Downloader provides a practical example of building a GUI wrapper around yt-dlp, which you can study as a reference implementation for your own scraper projects. It demonstrates cross-platform deployment patterns (Windows installer, macOS/Linux native builds) that are useful when evaluating self-hostable tools. Additionally, consolidating many platforms in a single desktop app improves workflow efficiency—something you've explicitly mentioned wanting to learn about.

As a developer tool, it also serves as a credible reference for how yt-dlp integrates with user-facing applications, which can inform your broader exploration of scraping techniques and automation patterns. The GPLv3 license ensures long-term maintainability and community trust.

## Key Features & Technologies
- cross-platform
- customtkinter GUI
- yt-dlp integration
- GPLv3 license
- desktop application

## Difference from Others
Media Downloader differs from similar tools in several ways: it is a graphical desktop application rather than a command-line only utility (like yt-dlp or youtube-dl), making it accessible to non-technical users. It supports a broader range of platforms than many dedicated YouTube downloaders, including Instagram, TikTok, Twitter, Pinterest, SoundCloud, Spotify, and RadioJavan—often in the same tool. While other GUI wrappers exist, this one is actively maintained with a clean, modern interface built on customtkinter, and it provides pre-built installers for Windows, macOS, and Linux (unlike many tools that only work on specific platforms). Additionally, its GPLv3 license makes it fully open-source, unlike some commercial or proprietary media downloaders.

## 🏢 Organization & Credibility
- **Developer:** MSC72m
- **Reputation:** Unknown
- **Stars:** 258
- **Forks:** 25
- **Recent Activity:** 65 commits in 3 months
- **Credibility Score:** 57.0/100 (Low)
- **Languages:** Python, Inno Setup, Batchfile, Shell, url
- **Last Release:** 2026-06-16
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
*Source: [GitHub](https://github.com/MSC72m/media_downloader)*
