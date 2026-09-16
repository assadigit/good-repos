---
source: https://github.com/fishaudio/fish-speech
aliases:
  - fish-speech
  - fishaudio/fish-speech
tags: [python, python, llama, tts, vqgan, vqvae, transformer, valle, vits, typescript, dockerfile, jupyter notebook]
category: Media
stars: 31150
org: fishaudio
primary_language: Python
languages: [Python, TypeScript, Dockerfile, Jupyter Notebook, CSS]
credibility_score: 53.0/100
date_processed: 2026-07-07
last_release: 2026-03-10
cover: attachments/banners/fish-speech_banner.png

---

![banner](attachments/banners/fish-speech_banner.png)

# fish-speech

> **TL;DR:** High-quality open-source TTS with expressive voice cloning using transformer and VQ-GAN models.

**`fishaudio/fish-speech`** · ⭐ 31,150 · 🔧 Python

## What is it?
Fish Speech is a state-of-the-art open-source text-to-speech system that combines cutting-edge AI techniques to deliver natural, emotionally expressive speech synthesis. Built on advanced transformer architectures, it integrates voice cloning capabilities alongside robust text-to-speech generation, making it suitable for applications ranging from accessibility tools to media production and virtual assistants. The project has garnered significant attention with over 31K stars on GitHub, indicating strong community interest in self-hostable TTS solutions.

## How does it work?
The system leverages a multi-stage pipeline combining transformer-based acoustic modeling with VQ-GAN (Vector Quantized Generative Adversarial Networks) for high-fidelity audio synthesis. It incorporates Valle (a model for generating expressive prosody) and VITS (Voice Informers Transformer Synthesizer) architectures, along with VQ-VAE (Vector Quantized Variational Autoencoder) for efficient latent representation of speech sounds. The architecture processes text inputs through embeddings, applies acoustic modeling to generate mel-spectrograms or latent codes, then passes these through a vocoder (likely HiFi-GAN or similar) to reconstruct the final audio waveform.

## Why is it important? (Core Value)
For someone focused on AI tools and self-hosted alternatives to SaaS products, Fish Speech offers a compelling open-source TTS solution that can be deployed locally without relying on commercial APIs. This directly supports homelab infrastructure goals by providing media processing capabilities that can integrate into agent workflows—for instance, enabling voice agents with expressive speech synthesis rather than monotone robotic output. The project's emphasis on voice cloning means it could serve as a building block for personalized assistant voices, while its transformer-based foundation aligns well with current LLM ecosystem integration patterns.

## Key Features & Technologies
- Uses transformer-based acoustic models (Valle, VITS)
- VQ-GAN based vocoder for audio generation
- Voice cloning and expressive prosody capabilities
- VQ-VAE latent representation encoding
- Docker containerization support
- Multi-language documentation and community resources
- Open-source with active GitHub repository

## Difference from Others
Compared to other open-source TTS projects like Coqui TTS or Tortoise, Fish Speech stands out for its strong focus on voice cloning alongside standard text-to-speech. While some alternatives prioritize either naturalness or speed, this project appears to balance both with SOTA performance metrics. The integration of Valle and VQ-GAN architectures suggests more recent and advanced modeling approaches than older VITS-only solutions. Additionally, the active Discord community and extensive documentation indicate a well-supported, evolving project rather than a static reference implementation.

## 🏢 Organization & Credibility
- **Developer:** fishaudio
- **Reputation:** Unknown
- **Stars:** 31,150
- **Forks:** 2666
- **Recent Activity:** 4 commits in 3 months
- **Credibility Score:** 53.0/100 (Low)
- **Languages:** Python, TypeScript, Dockerfile, Jupyter Notebook, CSS
- **Last Release:** 2026-03-10
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
*Source: [GitHub](https://github.com/fishaudio/fish-speech)*
