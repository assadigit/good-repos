---
source: https://github.com/Genymobile/scrcpy
aliases:
  - scrcpy
  - Genymobile/scrcpy
tags: [c, c, android, dev-tools, screen-mirroring, open-source, sdl2, libav, ffmpeg, screen, mirroring, recording]
category: Dev-Tools
stars: 145203
org: Genymobile
primary_language: C
languages: [C, Java, Roff, Shell, Meson]
credibility_score: 70.5/100
date_processed: 2026-07-07
last_release: 2026-05-12
cover: attachments/banners/scrcpy_banner.png

---

![banner](attachments/banners/scrcpy_banner.png)

# scrcpy

**`Genymobile/scrcpy`** · ⭐ 145,203 · 🔧 C

## What is it?
Mirrors Android devices to your PC, enabling low-latency screen control without root or installed apps.

## How does it work?
scrcpy is a lightweight C application that connects to an Android device via USB or TCP/IP. It captures the device's framebuffer through SDL2 and encodes/decodes video using libav/ffmpeg, streaming frames at 30-120 fps with latency as low as 35 ms. The host side renders the stream in a simple window (X11/Wayland on Linux, Win32/GDI on Windows, Cocoa on macOS) and forwards keyboard/mouse events back to the device using Android's built-in mirroring protocol—no root access or installed app is required.

## Why is it important? (Core Value)
For a software engineer building AI agents and automation tools, scrcpy offers a self-hosted mobile testing platform that eliminates SaaS dependencies. It enables reliable mobile UI interaction—critical for agents that must perform on-device steps like app launches, gesture swipes, or OCR. Because it runs locally and installs nothing on the device, it's ideal for CI/CD pipelines, homelab setups, or research where control over the environment matters.

## Key Features & Technologies
- C implementation
- SDL2 display
- libav/ffmpeg video encoding
- USB or TCP/IP connection
- No root required
- Cross-platform (Linux/Windows/macOS)
- Open source

## Difference from Others
Unlike ADB, which is primarily for command execution and logcat, scrcpy provides real-time screen mirroring at high FPS with low latency. It also avoids the bloat of Android Studio's device monitor or proprietary tools like AirDroid by being a single binary that works out of the box on any platform without additional drivers.

## 🏢 Organization & Credibility
- **Developer:** Genymobile
- **Reputation:** Unknown
- **Stars:** 145,203
- **Forks:** 13397
- **Recent Activity:** 104 commits in 3 months
- **Credibility Score:** 70.5/100 (Average)
- **Languages:** C, Java, Roff, Shell, Meson
- **Last Release:** 2026-05-12
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
*Source: [GitHub](https://github.com/Genymobile/scrcpy)*
