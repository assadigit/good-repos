---
source: https://github.com/openai/whisper
aliases:
  - whisper
  - openai/whisper
tags: [python, python, pytorch, speech-recognition, transformers, openai, url]
category: Research
stars: 104340
org: openai
primary_language: Python
languages: [Python, url]
credibility_score: 90.0/100
date_processed: 2026-07-07
last_release: 2025-06-26
cover: attachments/banners/whisper_banner.png

---

![banner](attachments/banners/whisper_banner.png)

# whisper

**`openai/whisper`** · ⭐ 104,340 · 🔧 Python

## What is it?
Whisper is a general-purpose speech recognition model trained on a large dataset of diverse audio, capable of multilingual speech recognition, speech translation, and language identification in a single unified model. It's built as a Transformer sequence-to-sequence architecture that jointly handles multiple speech processing tasks through multitask training with special tokens serving as task specifiers.

The model is designed to replace many stages of traditional speech-processing pipelines, supporting voice activity detection alongside recognition and translation. It was trained by OpenAI on extensive public datasets including LibriSpeech, Common Voice, VoxConverse, VCTK, and LJSpeech, providing robustness across languages and acoustic conditions.

## How does it work?
Whisper uses a Transformer encoder-decoder architecture with an autoregressive approach to handle the inherent sequential nature of speech. The model is trained via multitask learning where all supported tasks (speech recognition in multiple languages, speech translation, language identification, and voice activity detection) are jointly represented as a sequence of tokens predicted by the decoder. Special tokens serve as task specifiers or classification targets, enabling a single model to handle multiple purposes.

The codebase is written in Python using PyTorch for training and inference, with dependencies including OpenAI's tiktoken tokenizer for efficient tokenization. The architecture diagram shows the pipeline integrating these components. Whisper can be self-hosted for local processing or deployed via its API.

## Why is it important? (Core Value)
For your objectives of discovering tools that improve development workflow and finding AI agent frameworks or MCP servers, Whisper could serve as a foundational speech-processing capability integrated into agents—particularly useful if you're building agents that need transcription, language identification, or cross-lingual translation capabilities. Its self-hostable nature aligns with your interest in self-hosted alternatives to SaaS products, allowing you to avoid API costs and maintain data privacy for audio processing workflows.

Additionally, Whisper's open-source codebase from OpenAI (a major tech company) fits your interest in credible projects. You could leverage it as a tool within an agent ecosystem rather than an agent itself, perhaps integrating it with MCP servers for speech-processing capabilities or using it in automation workflows that require audio transcription.

## Key Features & Technologies
- Uses PyTorch for training and inference
- Open-source model from OpenAI
- Supports 98 languages natively
- Multitask architecture with special tokens
- Includes voice activity detection
- Self-hostable for local deployment
- Uses tiktoken tokenizer

## Difference from Others
Compared to other speech recognition models, Whisper stands out for being a unified multitask model that handles recognition, translation, language identification, and voice activity detection in a single architecture—whereas alternatives like Mozilla's DeepSpeech are typically single-language (English-only) and require separate models or post-processing for translation. Google's Speech-to-Text is a cloud-based SaaS solution rather than an open-source model you can self-host. Other open-source projects often lack the extensive training data that gives Whisper its robustness across diverse acoustic conditions and languages, making it particularly suited for applications requiring reliability with minimal tuning.

## 🏢 Organization & Credibility
- **Developer:** openai
- **Reputation:** High (Major tech company)
- **Stars:** 104,340
- **Forks:** 12715
- **Recent Activity:** 1 commits in 3 months
- **Credibility Score:** 90.0/100 (Excellent)
- **Languages:** Python, url
- **Last Release:** 2025-06-26
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
*Source: [GitHub](https://github.com/openai/whisper)*
