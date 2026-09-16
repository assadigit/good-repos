---
source: https://github.com/withoutbg/withoutbg-python
aliases:
  - withoutbg-python
  - withoutbg/withoutbg-python
tags: [python, python, onnx, openai, background-removal, computer-vision, image-matting, image-processing, ai-background-removal, image-background-removal, background-removal-open-source, background-removal-toolkit]
category: Media
stars: 1216
org: withoutbg
primary_language: Python
languages: [Python, Makefile, url]
credibility_score: 56.0/100
date_processed: 2026-08-02
last_release: 2026-07-19


---

# withoutbg-python

**`withoutbg/withoutbg-python`** · ⭐ 1,216 · 🔧 Python

## What is it?
Python SDK for background removal that runs locally with open weights or calls the Cloud API via a unified interface. Same code works offline or online, suitable for scripts, notebooks, backends, and batch jobs.

## How does it work?
The SDK loads pre-trained ONNX models (open weights) and performs inference on your machine using PyTorch/ONNX Runtime when you have CPU/GPU. For higher quality results it can forward the image to the Cloud API endpoint, which returns a processed PNG. Both paths expose identical function signatures, so you can swap between local and cloud without changing your code. CI pipelines test both modes.

## Why is it important? (Core Value)
This project gives you a self-hostable alternative to SaaS background-removal services, preserving privacy and eliminating per-image costs. Since it's Apache 2.0 licensed you can integrate it into any stack. For AI agents, it enables document scanning, invoice processing, or image-based workflows that require background removal without relying on external APIs. It fits your interest in self-hosted tools and developer productivity.

## Key Features & Technologies
- Python SDK
- ONNX model support
- Cloud API integration
- Apache 2.0 license
- Batch processing

## Difference from Others
Unlike remove.bg (cloud-only) or background-remover (local only), this SDK unifies both paths under the same API, letting you choose local for privacy or cloud for sharper edges. It also emphasizes offline use and includes example images and documentation for easy integration.

## 🏢 Organization & Credibility
- **Developer:** withoutbg
- **Reputation:** Unknown
- **Stars:** 1,216
- **Forks:** 62
- **Recent Activity:** 26 commits in 3 months
- **Credibility Score:** 56.0/100 (Low)
- **Languages:** Python, Makefile, url
- **Last Release:** 2026-07-19
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
*Source: [GitHub](https://github.com/withoutbg/withoutbg-python)*
