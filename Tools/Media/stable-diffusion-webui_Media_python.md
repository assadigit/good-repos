---
source: https://github.com/AUTOMATIC1111/stable-diffusion-webui
aliases:
  - stable-diffusion-webui
  - AUTOMATIC1111/stable-diffusion-webui
tags: [python, python, gradio, stable-diffusion, image-generation, media, deep-learning, diffusion, image2image, img2img, text2image, txt2img]
category: Media
stars: 164010
org: AUTOMATIC1111
primary_language: Python
languages: [Python, JavaScript, CSS, HTML, Shell]
credibility_score: 54.5/100
date_processed: 2026-07-07
last_release: 2025-02-09
cover: attachments/banners/stable-diffusion-webui_banner.png

---

![banner](attachments/banners/stable-diffusion-webui_banner.png)

# stable-diffusion-webui

> **TL;DR:** Web interface for Stable Diffusion image generation with inpainting, outpainting, and upscaling tools.

**`AUTOMATIC1111/stable-diffusion-webui`** · ⭐ 164,010 · 🔧 Python

## What is it?
Stable Diffusion Web UI is a web-based interface for generating images using Stable Diffusion models, built with Gradio. It supports multiple modes including txt2img and img2img, outpainting, inpainting, color sketch, prompt matrix, upscaling, attention specification, loopback processing, X/Y/Z plots, textual inversion, and extras like face restoration (GFPGAN) and upscaling networks (RealESRGAN, ESRGAN). The interface is designed for self-hosting and provides one-click installation but still requires Python and Git.

## How does it work?
The interface is built with Gradio, which provides a lightweight web server that loads Stable Diffusion models (SD 1.5, SDXL) from disk or cache. Gradio handles the HTTP request/response cycle, forwarding prompts to the underlying PyTorch model. The project includes one-click install scripts that set up Python, Git, and dependencies, but users must still install Python and Git manually. GPU acceleration is supported via PyTorch's CUDA backend when available.

## Why is it important? (Core Value)
Stable Diffusion Web UI offers a self-hosted alternative to proprietary image generation SaaS services, giving developers full control over models, parameters, and data privacy. For someone focused on self-hostable software and homelab infrastructure, this project provides a ready-to-run image generation stack that can be deployed locally or on a server cluster. It also includes advanced features like textual inversion and face restoration, which could be leveraged in agent workflows that require image synthesis. However, it is not primarily an AI agent framework; it's a media tool that might be useful for content creation tasks.

## Key Features & Technologies
- txt2img and img2img modes
- outpainting and inpainting
- prompt matrix
- attention specification
- loopback processing
- X/Y/Z plots
- textual inversion

## Difference from Others
Unlike ComfyUI's node-based workflow or Forge's performance-focused UI, Stable Diffusion Web UI offers a simpler Gradio-based interface with extensive community extensions (e.g., textual inversion, face restoration). While Forge focuses on speed and modern Python features, Web UI has been around longer and includes many legacy features like X/Y/Z plots and attention syntax. It also provides one-click install scripts, making it easier for beginners to get started compared to ComfyUI's more manual setup.

## 🏢 Organization & Credibility
- **Developer:** AUTOMATIC1111
- **Reputation:** Unknown
- **Stars:** 164,010
- **Forks:** 30384
- **Recent Activity:** 0 commits in 3 months
- **Credibility Score:** 54.5/100 (Low)
- **Languages:** Python, JavaScript, CSS, HTML, Shell
- **Last Release:** 2025-02-09
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
*Source: [GitHub](https://github.com/AUTOMATIC1111/stable-diffusion-webui)*
