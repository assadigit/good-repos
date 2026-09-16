---
source: "https://github.com/rockbenben/subtitle-translator"
aliases:
  - subtitle-translator
  - rockbenben/subtitle-translator

tags: [typescript, subtitles, llm, translation, browser, cli, srt, ass, lrc, vtt, batch-translation, bilingual-subtitles]
category: "LLM-Tools"
stars: 1113
org: "rockbenben"
primary_language: TypeScript
languages: [TypeScript, CSS, JavaScript, HTML, Dockerfile]
credibility_score: 56.0/100
date_processed: 2026-09-16
last_release: 2026-09-09
cover: attachments/banners/subtitle-translator_banner.png

---

![banner](attachments/banners/subtitle-translator_banner.png)

# subtitle-translator

> **TL;DR:** Browser-based batch translator for SRT/ASS/VTT/LRC subtitles using 27 LLMs while preserving timing.

**`rockbenben/subtitle-translator`** · ⭐ 1,113 · 🔧 TypeScript

## What is it?
Subtitle Translator is a free, browser-based tool for translating large collections of subtitle files in one pass. It supports .srt, .ass, .vtt, and .lrc formats, and can translate into 120+ languages using either traditional translation APIs or LLM providers/gateways.

Its core workflow is built around batch processing: users can upload an entire season at once, select one or more target languages, and receive separate exported files for each language. The tool emphasizes speed by chunking and compressing subtitle content before sending it to the selected engine, with parallel processing to reduce turnaround time.

Because the app runs locally in the browser, subtitle text and API keys are not sent to a third-party server. This makes it useful for privacy-sensitive translation workflows and for people who want to use their own model providers without exposing media files to an external SaaS backend.

## How does it work?
The application parses supported subtitle formats and separates dialogue from timing metadata. It strips timecodes locally, sends only the text payload to the chosen translation API or LLM gateway, and then reattaches the original timing information. This design prevents the model from rewriting timestamps because the timeline is not part of the translated payload.

For throughput, it uses chunked compression and parallel requests so a season can be processed quickly. Users connect their own keys for traditional services such as DeepL, Google, Azure, or LLM gateways, and can request multiple target languages in one run; each language is exported as its own file.

## Why is it important? (Core Value)
For a developer focused on AI tooling, automation, and self-hosted workflows, this project is valuable because it turns subtitle translation into a repeatable batch operation rather than a manual, file-by-file task. The local browser architecture keeps media content and credentials under user control, while the CLI and multi-provider support make it easier to integrate with existing API keys, model gateways, or post-processing pipelines.

It also solves a common practical problem: general-purpose LLM translation can corrupt subtitle timing. By removing timecodes before inference and restoring them after translation, it preserves editability and playback compatibility. The 120+ language support, multiple subtitle formats, and multi-target output make it a compact utility for localization, media workflow testing, or personal content management.

## Key Features & Technologies
- Supports .srt, .ass, .vtt, and .lrc subtitle files
- Batch-translates an entire season in one pass
- Works with 27 LLM providers/gateways and traditional translation APIs
- Preserves original timing by stripping timecodes before sending text to the model
- Translates into 120+ languages and can export multiple target-language files from one run
- Runs locally in the browser so subtitle content and API keys do not go to a third-party server

## Difference from Others
Compared with pasting subtitle files into a general-purpose chat or translation service, this tool is purpose-built for subtitle workflows. It prevents timing corruption by design, supports batch uploads, and handles multiple subtitle formats natively.

Unlike single-file translators or cloud-only services, it combines local processing, user-supplied API/LLM keys, parallel chunked requests, and multi-target language output in one pass. That makes it more suitable for translating full seasons while keeping files usable for editing or playback.

## 🏢 Organization & Credibility
- **Developer:** rockbenben
- **Reputation:** Unknown
- **Stars:** 1,113
- **Forks:** 147
- **Recent Activity:** 49 commits in 3 months
- **Credibility Score:** 56.0/100 (Low)
- **Languages:** TypeScript, CSS, JavaScript, HTML, Dockerfile
- **Last Release:** 2026-09-09
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
*Source: [GitHub](https://github.com/rockbenben/subtitle-translator)*
