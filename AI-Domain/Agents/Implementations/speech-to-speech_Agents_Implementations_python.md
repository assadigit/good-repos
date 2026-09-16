---
source: https://github.com/huggingface/speech-to-speech
aliases:
  - speech-to-speech
  - huggingface/speech-to-speech
tags: [python, python, speech, llm, voice-agent, open-source, ai, assistant, language-model, machine-learning, speech-synthesis, speech-to-text]
category: Agents/Implementations
stars: 10401
org: huggingface
primary_language: Python
languages: [Python, Dockerfile, url]
credibility_score: 85.0/100
date_processed: 2026-08-02
last_release: 2026-06-11
cover: attachments/banners/speech-to-speech_banner.png

---

![banner](attachments/banners/speech-to-speech_banner.png)

# speech-to-speech

> **TL;DR:** Build local voice agents with open-source models via a modular VAD→STT→LLM→TTS pipeline exposed as an OpenAI Realtime-compatible WebSocket API.

**`huggingface/speech-to-speech`** · ⭐ 10,401 · 🔧 Python

## What is it?
Speech To Speech is a low-latency, fully modular voice-agent pipeline built from open-source components (VAD → STT → LLM → TTS). It exposes an OpenAI Realtime-compatible WebSocket API, allowing each component to be swapped with different models or services—whether hosted providers, Hugging Face inference endpoints, or local vLLM/llama.cpp servers. This flexibility enables fully local, open stacks for voice agents. The pipeline powers production deployments for thousands of Reachy Mini robots, demonstrating its reliability and scalability.

## How does it work?
The system is organized as a pipeline with four stages: Voice Activity Detection (VAD) to identify speech segments, Speech-to-Text (STT) using open-source ASR models, a Large Language Model (LLM) for reasoning or response generation, and Text-to-Speech (TTS) for audio output. Each stage is modular, allowing you to plug in different implementations—e.g., swap the LLM with vLLM or llama.cpp on your own hardware, use HF Inference Providers for STT, etc. The pipeline communicates via an OpenAI Realtime-compatible WebSocket API, enabling real-time streaming of audio and text, which is crucial for low-latency voice interactions.

## Why is it important? (Core Value)
This project is valuable because it offers a self-hostable, modular voice-agent pipeline using open-source models (VAD → STT → LLM → TTS) exposed via an OpenAI Realtime-compatible WebSocket API. For your interests in AI agents and self-hosted software, it provides a flexible foundation you can integrate into your workflow—potentially as an MCP server or automation interface. Its production use in Reachy Mini robots demonstrates reliability, and its Apache 2.0 license ensures freedom to modify and deploy locally, aligning with your desire for open-source alternatives to SaaS products.

## Key Features & Technologies
- Modular voice-agent pipeline (VAD → STT → LLM → TTS)
- OpenAI Realtime-compatible WebSocket API
- Swappable components with open-source models
- Production-ready backend for Reachy Mini robots
- Apache 2.0 license
- PyPI package
- Supports vLLM and llama.cpp servers

## Difference from Others
Unlike generic voice-agent frameworks (e.g., LangChain) or monolithic pipelines (e.g., Coqui), this project offers a modular pipeline where each component (VAD, STT, LLM, TTS) is swappable and exposed via an OpenAI Realtime-compatible WebSocket API. It also supports local deployment with vLLM or llama.cpp, making it more flexible for self-hosted setups compared to other projects that rely on proprietary APIs or fixed model stacks.

## 🏢 Organization & Credibility
- **Developer:** huggingface
- **Reputation:** Medium (Well-known organization)
- **Stars:** 10,401
- **Forks:** 1269
- **Recent Activity:** 192 commits in 3 months
- **Credibility Score:** 85.0/100 (Good)
- **Languages:** Python, Dockerfile, url
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
*Source: [GitHub](https://github.com/huggingface/speech-to-speech)*
