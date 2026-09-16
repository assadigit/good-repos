---
source: https://github.com/santinic/audiblez
aliases:
  - audiblez
  - santinic/audiblez
tags: [python, python, epub, tts, kokoro, audiobooks, url]
category: Media
stars: 7882
org: santinic
primary_language: Python
languages: [Python, url]
credibility_score: 48.0/100
date_processed: 2026-07-06

cover: attachments/banners/audiblez_banner.png

---

![banner](attachments/banners/audiblez_banner.png)

# audiblez

> **TL;DR:** Converts .epub e-books to .m4b audiobooks using Kokoro's high-quality TTS model.

**`santinic/audiblez`** · ⭐ 7,882 · 🔧 Python

## What is it?
Audiblez is a Python tool that transforms EPUB e-books into audiobook format (.m4b), using Kokoro—a lightweight yet natural-sounding text-to-speech model with just 82 million parameters. The project focuses on delivering accessible audio versions of text-based books, making content consumable by people who prefer listening over reading.

## How does it work?
The tool parses EPUB files to extract the raw text content, then feeds it to Kokoro's TTS model for speech synthesis. Kokoro was trained on less than 100 hours of audio and supports nine languages (US English, British English, Spanish, French, Hindi, Italian, Japanese, Portuguese, Chinese). Processing is accelerated via CUDA when available—on a Colab T4 GPU it converts Orwell's Animal Farm in about five minutes. A graphical interface is included for easier use without command-line interaction.

## Why is it important? (Core Value)
This project matters because it offers a self-hosted, open-source alternative to paid audiobook services like Audible or Amazon. For the user specifically: it fits into their interest in self-hostable tools and media processing; it demonstrates how to leverage recent high-quality TTS models without relying on commercial APIs; and it can be integrated into larger automation workflows (e.g., converting library collections, personal notes, or documentation). The multi-language support also makes it useful for international content.

## Key Features & Technologies
- Converts EPUB files to .m4b audiobooks
- Uses Kokoro TTS model (82M parameters)
- Supports 9 languages (US, GB, ES, FR, IN, IT, JP, BR, CN)
- CUDA/GPU acceleration for faster synthesis
- Includes graphical user interface
- Self-hosted and open-source

## Difference from Others
Unlike commercial audiobook platforms that license specific books, Audiblez works with any EPUB you provide, making it a flexible converter rather than a content provider. Compared to other open-source TTS projects (Coqui, Piper, etc.), this focuses specifically on the EPUB-to-audiobook workflow and integrates Kokoro's recent model improvements for natural prosody.

## 🏢 Organization & Credibility
- **Developer:** santinic
- **Reputation:** Unknown
- **Stars:** 7,882
- **Forks:** 683
- **Recent Activity:** 0 commits in 3 months
- **Credibility Score:** 48.0/100 (Low)
- **Languages:** Python, url
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
*Source: [GitHub](https://github.com/santinic/audiblez)*
