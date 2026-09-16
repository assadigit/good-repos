---
source: https://github.com/kyutai-labs/pocket-tts
aliases:
  - pocket-tts
  - kyutai-labs/pocket-tts
tags: [python, python, tts, voice-cloning, self-hosted, pytorch, html, hcl, dockerfile, shell]
category: LLM-Tools
stars: 5296
org: kyutai-labs
primary_language: Python
languages: [Python, HTML, HCL, Dockerfile, Shell]
credibility_score: 52.0/100
date_processed: 2026-07-06
last_release: 2026-05-04
cover: attachments/banners/pocket-tts_banner.png

---

![banner](attachments/banners/pocket-tts_banner.png)

# pocket-tts

**`kyutai-labs/pocket-tts`** · ⭐ 5,296 · 🔧 Python

## What is it?
Pocket TTS is a lightweight text-to-speech model that runs entirely on CPUs without GPU requirements, featuring streaming audio generation, voice cloning, multi-language support (English, French, German, Portuguese, Italian, Spanish), infinite text input handling, and client-side browser implementation. Built with PyTorch 2.5+ and optimized for low latency (~200ms to first chunk).

## How does it work?
Pocket TTS uses PyTorch 2.5+ with optimized CPU kernels and quantization techniques to achieve low-latency streaming audio generation while maintaining high quality. The model is lightweight (~100M parameters) and employs an architecture that supports audio streaming, allowing it to produce sound in real-time without GPU acceleration—likely using chunk-based or autoregressive generation approaches that can handle arbitrarily long text inputs.

## Why is it important? (Core Value)
As a self-hosted TTS solution, Pocket TTS directly serves your objectives by providing a CPU-efficient alternative to SaaS APIs like ElevenLabs or Google Cloud TTS. Its Python API and CLI enable seamless integration into AI agents or automation workflows for voice notifications and responses. The voice cloning feature lets you personalize agent interactions, while multi-language support broadens accessibility. Running entirely on CPU makes it ideal for homelab deployments with limited resources, aligning with your interest in self-hosted software and infrastructure. It also offers an in-browser implementation, expanding its applicability across platforms.

## Key Features & Technologies
- Runs on CPU
- Small model size (~100M parameters)
- Audio streaming
- Python API and CLI
- Voice cloning
- Multi-language support

## Difference from Others
Unlike GPU-dependent models or large SaaS APIs, Pocket TTS stands out for its CPU-only operation, tiny model footprint, streaming audio capability, voice cloning, and open-source Python interface. While other TTS solutions like Coqui TTS or XTTS are either large, require GPUs, or lack streaming features, Pocket TTS delivers low-latency audio (~200ms to first chunk) and supports infinite text inputs. Its client-side browser implementation further differentiates it from server-only alternatives.

## 🏢 Organization & Credibility
- **Developer:** kyutai-labs
- **Reputation:** Unknown
- **Stars:** 5,296
- **Forks:** 576
- **Recent Activity:** 17 commits in 3 months
- **Credibility Score:** 52.0/100 (Low)
- **Languages:** Python, HTML, HCL, Dockerfile, Shell
- **Last Release:** 2026-05-04
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
*Source: [GitHub](https://github.com/kyutai-labs/pocket-tts)*
