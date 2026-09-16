---
source: https://github.com/moonshine-ai/moonshine
aliases:
  - moonshine
  - moonshine-ai/moonshine
tags: [c++, python, stt, tts, intent-recognition, self-hosted, voice, voice-recognition, c, shell, swift]
category: Agents/Frameworks
stars: 10237
org: moonshine-ai
primary_language: C++
languages: [C++, C, Python, Shell, Swift]
credibility_score: 72.0/100
date_processed: 2026-07-22
last_release: 2026-07-16
cover: attachments/banners/moonshine_banner.png

---

![banner](attachments/banners/moonshine_banner.png)

# moonshine

> **TL;DR:** Self-hosted voice agent toolkit providing on-device STT, TTS, and intent recognition for low-latency conversational interfaces.

**`moonshine-ai/moonshine`** · ⭐ 10,237 · 🔧 C++

## What is it?
Moonshine Voice is an open-source AI toolkit for developers building real-time voice agents and applications. It provides on-device speech-to-text (STT), text-to-speech (TTS), and intent recognition, enabling low-latency conversational interfaces without relying on external APIs or accounts. The framework is optimized for live streaming, performing much of the processing while the user is still speaking.

All models are trained from scratch and support a range of sizes, from high-accuracy variants that outperform Whisper Large V3 at the top end down to tiny 1MB models for constrained deployments. It runs on Python, iOS, Android, and macOS, making it platform-agnostic for cross-device deployments. The toolkit includes a library for easy integration across platforms, with the same codebase working everywhere.

Unlike Whisper or other standalone STT/TTS models, Moonshine bundles intent recognition and conversational agent capabilities directly into the toolkit, allowing developers to build voice interfaces that can understand user intent in real time. Its on-device architecture eliminates latency from network calls and avoids the need for API keys or cloud accounts.

## How does it work?
Moonshine provides a library that includes speech-to-text models (likely transformer-based ASR), text-to-speech models (possibly vocoder-based), and intent recognition (a language model or classifier). The system processes audio in streaming fashion, performing much of the work while the user is still speaking, which reduces latency. It runs on-device, so there are no network calls to external services. The toolkit also supports cross-platform compilation for Python, mobile, and macOS.

## Why is it important? (Core Value)
Moonshine gives you a self-hostable toolkit for building voice agents without relying on cloud APIs or accounts, directly supporting your interest in self-hosted alternatives to SaaS. Its intent-recognition and conversational-agent capabilities provide an AI agent framework you can integrate into your Obsidian vault under 'AI-Domain' or 'Frameworks', and its cross-platform support (Python, iOS, Android, macOS) aligns with your developer productivity focus. Additionally, the low-latency streaming and tiny models make it ideal for homelab deployments where privacy and speed matter.

## Key Features & Technologies
- Speech-to-text (STT)
- Text-to-speech (TTS)
- Intent recognition for conversational agents
- On-device processing (no API keys needed)
- Cross-platform support (Python, iOS, Android, macOS)
- Low-latency streaming (processes while user still talking)
- Tiny models (~1MB) for constrained deployments

## Difference from Others
Similar projects include Whisper (OpenAI), Vosk, Coqui TTS, Google Cloud Speech-to-Text, Amazon Polly, Azure Speech Service, and also frameworks like LangChain, AutoGen, CrewAI. Moonshine is different because it bundles STT, TTS, and intent recognition in a single on-device toolkit optimized for low latency, whereas Whisper is just STT, Coqui TTS just TTS, and the others are cloud services requiring API keys. Also, Moonshine offers higher accuracy than Whisper Large V3 at the top end and tiny models for constrained deployments.

## 🏢 Organization & Credibility
- **Developer:** moonshine-ai
- **Reputation:** Unknown
- **Stars:** 10,237
- **Forks:** 539
- **Recent Activity:** 140 commits in 3 months
- **Credibility Score:** 72.0/100 (Average)
- **Languages:** C++, C, Python, Shell, Swift
- **Last Release:** 2026-07-16
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
*Source: [GitHub](https://github.com/moonshine-ai/moonshine)*
