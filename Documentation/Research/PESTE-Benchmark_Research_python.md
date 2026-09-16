---
source: https://github.com/ArmanJR/PESTE-Benchmark
aliases:
  - PESTE-Benchmark
  - ArmanJR/PESTE-Benchmark
tags: [python, asr, speech-to-text, benchmark, persian, whisper, dockerfile, c, url]
category: Research
stars: 57
org: ArmanJR
primary_language: Python
languages: [Python, Dockerfile, C, url]
credibility_score: 47.0/100
date_processed: 2026-09-01
last_release: 2026-08-17
cover: attachments/banners/PESTE-Benchmark_banner.png

---

![banner](attachments/banners/PESTE-Benchmark_banner.png)

# PESTE-Benchmark

> **TL;DR:** Persian speech-to-text benchmark with a leaderboard tracking CER/WER accuracy and RTF speed on a fixed GPU profile.

**`ArmanJR/PESTE-Benchmark`** · ⭐ 57 · 🔧 Python

## What is it?
PESTE (PErsian Speech to Text) is a benchmark and leaderboard for Persian automatic speech recognition. It defines a standardized evaluation suite (fleurs-fa-ir-v1, 871 test recordings) with an immutable fa-v1 normalization scheme so that all models are scored identically. Accuracy is measured primarily by corpus CER, plus WER, deterministic bootstrap uncertainty, and paired CER comparisons; speed is measured as steady-state end-to-end audio throughput and real-time factor (RTF).

The project standardizes the inference and reporting stack: deterministic per-model batching, checkpoint-native precision, automatic native Whisper long-form decoding, offline execution with read-only dataset/checkpoint caches, and a digest-pinned public GHCR container image that provides isolated modern and NeMo environments. The official hardware profile is a single NVIDIA RTX 6000 Ada Generation 48 GB GPU (rtx-6000-ada-v1). The leaderboard displays the top 10 models with full provenance tracking — each row records the model digest, image digest, and source revision — with results generated from pinned benchmark images (v2.0.0 and v2.1.0).

In short, PESTE turns "which Persian ASR model is best?" into a reproducible, comparable experiment rather than ad-hoc per-model evaluation.

## How does it work?
PESTE packages the benchmark as a reproducible runtime: a digest-pinned public GHCR image containing isolated modern and NeMo environments runs inference deterministically (per-model batching, checkpoint-native precision) against the fixed 871-recording Persian test suite on an official single-GPU profile. It supports automatic native Whisper long-form decoding for Whisper-family checkpoints and operates offline with read-only dataset/checkpoint caches.

Evaluation output covers two axes: accuracy (corpus CER as the primary metric, plus WER, deterministic bootstrap uncertainty, and paired CER comparisons) and speed (steady-state end-to-end audio throughput and real-time factor). Results are published to a leaderboard with per-row provenance — model digest, image digest, and source revision — so any published number can be traced back to exact artifacts.

## Why is it important? (Core Value)
The core value is a fair, reproducible comparison platform for Persian ASR models: identical normalization, fixed hardware, deterministic inference, and full artifact provenance remove the confounders that make casual model comparisons unreliable. It also documents a rigorous benchmarking methodology — metric choice (CER vs WER), uncertainty estimation via bootstrap, RTF speed reporting, and container-pinned reproducibility — that is reusable beyond Persian.

For you specifically: as someone who curates AI/LLM tooling and cares about credible, self-hostable infrastructure, PESTE is a strong reference implementation for how to design and operate ML benchmarks. Its digest-pinned GHCR images, offline/cached inference, and provenance tracking are patterns you can lift directly when evaluating or adopting other open-source model stacks (e.g., NeMo-based pipelines), and if your work ever touches multilingual ASR or Whisper checkpoint selection for low-resource languages, it is one of the few ready-made Persian evaluation setups available.

## Key Features & Technologies
- Persian ASR leaderboard with a fixed 871-recording test suite (fleurs-fa-ir-v1) and immutable fa-v1 normalization
- Accuracy metrics: corpus CER (primary), WER, deterministic bootstrap uncertainty, paired CER comparisons
- Speed metrics: steady-state end-to-end audio throughput and real-time factor (RTF)
- Deterministic inference with per-model batching and checkpoint-native precision
- Automatic native Whisper long-form decoding for Whisper checkpoints
- Reproducible digest-pinned public GHCR runtime image with isolated modern and NeMo environments
- Result provenance tracking: model digest, image digest, and source revision per leaderboard row

## Difference from Others
Compared to general ASR benchmarks built around high-resource languages (e.g., LibriSpeech or Common Voice–style leaderboards), PESTE is purpose-built for Persian with a standardized normalization pipeline that makes cross-model comparisons meaningful in a low-resource setting. It also goes further on reproducibility than typical model-card evaluations: a single official hardware profile (RTX 6000 Ada 48 GB), deterministic per-model batching, and per-result provenance (model/image digests plus source revision) rather than just published numbers.

Against ad-hoc Whisper checkpoint comparisons, PESTE's immutable normalization suite and pinned container runtime ensure that differences in reported CER/WER reflect the models themselves, not evaluation drift — making it a stronger reference point for anyone validating speech models before adopting them.

## 🏢 Organization & Credibility
- **Developer:** ArmanJR
- **Reputation:** Unknown
- **Stars:** 57
- **Forks:** 4
- **Recent Activity:** 41 commits in 3 months
- **Credibility Score:** 47.0/100 (Low)
- **Languages:** Python, Dockerfile, C, url
- **Last Release:** 2026-08-17
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
*Source: [GitHub](https://github.com/ArmanJR/PESTE-Benchmark)*
