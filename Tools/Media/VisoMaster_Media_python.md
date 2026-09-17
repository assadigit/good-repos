---
source: "https://github.com/visomaster/VisoMaster"
aliases:
  - VisoMaster
  - visomaster/VisoMaster

tags: [python, deep-learning, face-swap, video-editing, tensorrt, ai, deepfake, face-editor, live-portrait, faceswap, video-editor]
category: "Media"
stars: 2081
org: "visomaster"
primary_language: Python
languages: [Python, Batchfile, url]
credibility_score: 46.0/100
date_processed: 2026-09-17
last_release: 2025-03-09
cover: attachments/banners/VisoMaster_banner.png

---

![banner](attachments/banners/VisoMaster_banner.png)

# VisoMaster

> **TL;DR:** AI-powered desktop tool for face swapping/editing in videos with multi-model support, live webcam output, and TensorRT GPU acceleration.

**`visomaster/VisoMaster`** · ⭐ 2,081 · 🔧 Python

## What is it?
VisoMaster is a powerful yet easy-to-use desktop application for AI-driven face swapping and editing in both images and videos. Built on top of the FaceSwapper ecosystem, it provides an intuitive graphical interface that lets casual users and professionals alike produce natural-looking results with minimal effort. It supports multiple face swapper models, including compatibility with DeepFaceLab-trained models (DFM), advanced multi-face swapping with per-part masking, occlusion masking via DFL XSeg, and expression restoration to transfer original expressions onto swapped faces.

Beyond basic swapping, VisoMaster includes a Face Editor powered by LivePortrait models that lets users manually adjust expressions, poses, and colors for face, hair, eyebrows, and lips. Additional capabilities include live playback of processed video before saving, face embeddings using multiple source faces for improved accuracy, real-time webcam streaming to a virtual camera (usable with Twitch, YouTube, Zoom, etc.), per-frame video markers for precise settings control, and TensorRT support for ultra-fast GPU-accelerated processing.

## How does it work?
VisoMaster operates as a desktop application that orchestrates a pipeline of deep-learning models for face detection, landmarking, identity embedding, and image synthesis. It accepts multiple swapper model backends (including DFM) and applies occlusion/multi-face masking to handle complex scenes with several faces or partial occlusions. The LivePortrait component uses generative models to decouple expression and pose from the source identity, enabling manual fine-tuning of facial parts.

For performance, it integrates TensorRT to compile and run inference graphs on supported NVIDIA GPUs, enabling near-real-time processing. The live webcam path captures frames, runs them through the swap pipeline, and outputs to a virtual camera device so downstream apps (Twitch, Zoom, YouTube) see the swapped face in real time. Video markers let users keyframe settings per frame, giving frame-level control over intensity, masking, and model selection.

## Why is it important? (Core Value)
For a software engineer and researcher focused on AI tooling and self-hosted alternatives, VisoMaster is valuable as a locally-run, GPU-accelerated computer-vision pipeline that eliminates any dependency on cloud SaaS services for face manipulation. It demonstrates practical patterns for multi-model orchestration, TensorRT inference optimization, and real-time webcam capture/output—techniques transferable to other CV or media projects. The per-frame marker system and pluggable model architecture also offer architectural lessons for building configurable AI pipelines. As a self-hosted tool, it fits directly into a homelab workflow where data privacy matters (no frames leave the local machine), and its open-source nature allows deep inspection of how face-swap models are loaded, masked, and composited—useful reference material for anyone studying applied computer vision beyond LLM-centric AI.

## Key Features & Technologies
- Multi-model face swapping with DeepFaceLab DFM compatibility
- LivePortrait expression/pose/color editing for face parts
- TensorRT GPU-accelerated inference for real-time processing
- Live webcam streaming to virtual camera (Twitch, Zoom, YouTube)
- Multi-face swapping with occlusion masking (DFL XSeg)
- Per-frame video markers for granular settings control
- Face embeddings with multiple source faces for accuracy

## Difference from Others
Most open-source face-swap projects are either CLI-first (like the original FaceSwapper) or cloud-hosted services that send frames to remote GPUs. VisoMaster differentiates by providing a complete, polished GUI desktop app that runs entirely locally, supports multiple swapper backends simultaneously, and adds real-time webcam output with virtual-camera integration—features absent in most alternatives. Its per-frame video markers give frame-level control over model intensity and masking, which is rare even among paid tools. The TensorRT path for NVIDIA GPUs pushes toward interactive latency, setting it apart from CPU-bound or cloud-dependent competitors.

## 🏢 Organization & Credibility
- **Developer:** visomaster
- **Reputation:** Unknown
- **Stars:** 2,081
- **Forks:** 365
- **Recent Activity:** 0 commits in 3 months
- **Credibility Score:** 46.0/100 (Low)
- **Languages:** Python, Batchfile, url
- **Last Release:** 2025-03-09
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
*Source: [GitHub](https://github.com/visomaster/VisoMaster)*
