---
source: https://github.com/LoredCast/filewizard
aliases:
  - filewizard
  - LoredCast/filewizard
tags: [python, python, ffmpeg, tesseract, whisper, docker, javascript, css, html, dockerfile]
category: Media
stars: 859
org: LoredCast
primary_language: Python
languages: [Python, JavaScript, CSS, HTML, Dockerfile]
credibility_score: 39.5/100
date_processed: 2026-07-06
last_release: 2025-10-25
cover: attachments/banners/filewizard_banner.png

---

![banner](attachments/banners/filewizard_banner.png)

# filewizard

> **TL;DR:** Self-hosted web UI for file conversion, OCR, audio transcription, and TTS.

**`LoredCast/filewizard`** · ⭐ 859 · 🔧 Python

## What is it?
File Wizard is a self-hosted, browser-based utility that combines file format conversion, optical character recognition, and audio processing into one cohesive application. It wraps commonly used command-line tools—FFmpeg for video/audio manipulation, LibreOffice and Pandoc for document conversion, ImageMagick for image processing, and Tesseract OCR/ocrmypdf for extracting text from images and PDFs—plus faster-whisper for high-quality audio transcription. The project is packaged as Docker images with a default CPU-only build and a separate CUDA-enabled image for GPU acceleration.

The user interface is intentionally minimal: a responsive dark theme featuring drag-and-drop file uploads, a standard file picker, real-time progress updates, persistent history of processed files, and a dedicated /settings page for configuring conversion tools and OAuth authentication (which can be disabled entirely in local mode). Despite its simplicity, it addresses the practical need for privacy-focused alternatives to SaaS services like Convertio or FreeConvert.

## How does it work?
The architecture is built around FastAPI, which serves as the backend API handling incoming file uploads and orchestrating subprocess invocations of the underlying CLI tools. The frontend is vanilla HTML/JS/CSS—no heavy framework—delivering a lean, fast experience. Docker images are pre-built with all dependencies baked in; the default image runs everything on CPU, while the -cuda variant includes CUDA-capable libraries for GPU offloading where supported by the tools. Background job processing appears to be implemented server-side with real-time status updates (likely via WebSockets or polling), and the /settings endpoint allows users to dynamically register additional CLI tools by editing a settings.yml file.

## Why is it important? (Core Value)
This project directly aligns with your interest in self-hosted alternatives to SaaS services and homelab infrastructure. As a researcher working on AI agents, you frequently process documents and audio; File Wizard gives you a local, privacy-preserving way to convert files, extract text via OCR, and transcribe audio without relying on cloud APIs or paying per-use fees. It also fits into your Obsidian vault under Tools—easy to discover, lightweight, and extensible through the settings file. The security warning about public exposure is appropriate for a tool that can run arbitrary CLI commands; it's intended for local use or behind proper OAuth/OIDC providers, which is a sensible design choice for self-hosted software.

## Key Features & Technologies
- Converts between many file formats via extensible settings.yml
- OCR for PDFs and images using Tesseract and ocrmypdf
- Audio transcription with faster-whisper models
- Simple responsive dark UI with drag-and-drop and file picker
- Background job processing with real-time status updates and history
- /settings page for configuring tools and OAuth (local mode without auth)
- CPU-only default image with optional -cuda Docker build for GPU

## Difference from Others
Compared to other self-hosted file converters, File Wizard is specifically oriented toward OCR and audio transcription alongside general conversion. Most alternatives like Calibre focus on e-book formats, or generic FFmpeg wrappers handle only video/audio without text extraction. The combination of Tesseract/ocrmypdf for optical recognition and faster-whisper for speech-to-text in a single web UI is distinctive. Additionally, the settings.yml approach lets you dynamically add any CLI tool you have installed, which provides more flexibility than hard-coded tool lists in similar projects.

## 🏢 Organization & Credibility
- **Developer:** LoredCast
- **Reputation:** Unknown
- **Stars:** 859
- **Forks:** 52
- **Recent Activity:** 0 commits in 3 months
- **Credibility Score:** 39.5/100 (Low)
- **Languages:** Python, JavaScript, CSS, HTML, Dockerfile
- **Last Release:** 2025-10-25
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
*Source: [GitHub](https://github.com/LoredCast/filewizard)*
