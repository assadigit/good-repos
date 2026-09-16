---
source: https://github.com/Saganaki22/ComfyUI-OmniVoice-TTS
aliases:
  - ComfyUI-OmniVoice-TTS
  - Saganaki22/ComfyUI-OmniVoice-TTS
tags: [python, python, tts, voice-cloning, comfyui, ai, custom-nodes, text-to-speech, voice-clone, url]
category: Agents/Implementations
stars: 495
org: Saganaki22
primary_language: Python
languages: [Python, url]
credibility_score: 43.5/100
date_processed: 2026-07-05
last_release: 2026-06-11
cover: attachments/banners/ComfyUI-OmniVoice-TTS_banner.png

---

![banner](attachments/banners/ComfyUI-OmniVoice-TTS_banner.png)

# ComfyUI-OmniVoice-TTS

> **TL;DR:** ComfyUI nodes enabling OmniVoice zero-shot TTS with voice cloning and multi-speaker dialogue.

**`Saganaki22/ComfyUI-OmniVoice-TTS`** · ⭐ 495 · 🔧 Python

## What is it?
ComfyUI-OmniVoice-TTS provides custom nodes that integrate OmniVoice, a zero-shot multilingual text-to-speech model supporting 600+ languages with state-of-the-art quality. The project enables voice cloning from 3-15 second audio samples, voice design via text descriptions (gender, age, pitch, accent), and multi-speaker dialogue generation. It includes links to Hugging Face models, a demo space, arXiv documentation, and Chinese README translations.

## How does it work?
This project extends ComfyUI's node-based workflow system with custom Python nodes that interface with the OmniVoice TTS model. Users load OmniVoice variants (BF16, standard) from Hugging Face repositories and connect them to ComfyUI's graph. The nodes handle text input, audio output, voice cloning parameters, and voice design prompts, all within ComfyUI's visual interface. Model inference runs locally on the user's hardware.

## Why is it important? (Core Value)
For your objectives, this project directly supports self-hostable alternatives to SaaS products—OmniVoice offers zero-shot multilingual TTS without relying on cloud APIs like ElevenLabs or Azure TTS. It aligns with your interest in AI/LLM tooling and developer productivity: integrating TTS into ComfyUI workflows lets you build custom media-generation pipelines locally. The voice cloning and design features enable content creation automation, which fits your automation interests. Additionally, since it's open-source and self-hostable, it supports homelab infrastructure use cases you'd want to explore.

## Key Features & Technologies
- 600+ language support
- Zero-shot TTS model (OmniVoice)
- Voice cloning from 3-15 sec audio
- Voice design via text descriptions
- Multi-speaker dialogue generation
- ComfyUI custom nodes
- Hugging Face model integration

## Difference from Others
Unlike Tortoise-TTS or Coqui TTS, which are standalone models requiring separate deployment, OmniVoice is specifically built as ComfyUI nodes, making it seamless for existing ComfyUI workflows. Compared to ElevenLabs API or Azure TTS, this offers zero-shot cloning and voice design without per-call costs. The 600+ language coverage also exceeds many open-source alternatives like XTTS-v2, though OmniVoice requires BF16 quantization for memory efficiency.

## 🏢 Organization & Credibility
- **Developer:** Saganaki22
- **Reputation:** Unknown
- **Stars:** 495
- **Forks:** 63
- **Recent Activity:** 17 commits in 3 months
- **Credibility Score:** 43.5/100 (Low)
- **Languages:** Python, url
- **Last Release:** 2026-06-11
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
*Source: [GitHub](https://github.com/Saganaki22/ComfyUI-OmniVoice-TTS)*
