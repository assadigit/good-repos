---
source: "https://github.com/abi/screenshot-to-code"
aliases:
  - screenshot-to-code
  - abi/screenshot-to-code

tags: [python, llm, code-generation, design-to-code, tailwind, self-hosted, typescript, html, css, javascript]
category: "LLM-Tools"
stars: 79022
org: "abi"
primary_language: Python
languages: [Python, TypeScript, HTML, CSS, JavaScript]
credibility_score: 72.0/100
date_processed: 2026-09-16

cover: attachments/banners/screenshot-to-code_banner.png

---

![banner](attachments/banners/screenshot-to-code_banner.png)

# screenshot-to-code

> **TL;DR:** Converts screenshots, mockups, and Figma designs into clean code (HTML/Tailwind/React/Vue) using AI models.

**`abi/screenshot-to-code`** · ⭐ 79,022 · 🔧 Python

## What is it?
Screenshot to Code is an AI-powered tool that transforms visual design inputs—screenshots, mockups, Figma files, and even screen recordings of websites in action—into clean, functional front-end code. It supports a wide range of output stacks including HTML + Tailwind, HTML + CSS, React + Tailwind, Vue + Tailwind, Bootstrap, and Ionic + Tailwind, making it applicable across multiple front-end ecosystems.

The project is available both as a self-hosted local application and as a hosted SaaS product at screenshottocode.com. It is powered by frontier AI models including Gemini 3 Flash/Pro Preview, GPT-5.5/GPT-5.4 Mini, and Claude Opus 4.6/4.8, with z-image-turbo (via Replicate) for image generation. With over 79,000 GitHub stars, it has become one of the most widely adopted design-to-code tools in the open-source community.

Beyond static images, Screenshot to Code uniquely supports screen recordings of a website in action, converting them into functional interactive prototypes rather than just pixel-perfect static layouts.

## How does it work?
The tool ingests visual inputs (screenshots, Figma exports, or video recordings) and processes them through one or more large language models—Gemini, GPT-5.x, or Claude Opus—to generate production-ready front-end code in the user's chosen stack. The AI models interpret layout structure, styling, typography, and component hierarchy from the visual input and emit corresponding HTML, CSS/Tailwind classes, React components, or Vue templates.

For screen recordings, the system analyzes temporal sequences of UI states and interactions to produce a working prototype with navigation, hover states, and dynamic behavior rather than a single static frame. The project can be deployed locally for full customization and self-hosting, or consumed as a managed hosted service, giving teams flexibility in data control and deployment topology.

## Why is it important? (Core Value)
Screenshot to Code eliminates the manual, repetitive work of translating a designer's mockup into hand-written front-end code, collapsing hours of layout coding into seconds. It solves the persistent gap between design handoff and implementation, reducing context-switching for engineers who must interpret pixel-perfect designs line by line.

For a software engineer and researcher focused on AI tooling and developer productivity, this project is directly relevant in several ways. First, it demonstrates practical LLM integration patterns—prompting strategies, multi-model fallbacks, and output validation—that can be studied for building similar AI-assisted workflows. Second, it offers a self-hosted option, aligning with the goal of finding self-hostable alternatives to SaaS products; you can run the full pipeline locally without depending on screenshottocode.com. Third, its support for screen recordings as input is an emerging approach worth tracking for how multimodal models (vision + temporal understanding) are being applied to code generation, a pattern that could inform future agent or automation projects in your knowledge base.

## Key Features & Technologies
- Multi-stack code output: HTML+Tailwind, React+Tailwind, Vue+Tailwind, Bootstrap, Ionic
- Powered by frontier LLMs (Gemini 3, GPT-5.x, Claude Opus) with model fallbacks
- Accepts screen recordings to generate interactive prototypes, not just static layouts
- Self-hostable locally or usable as hosted SaaS at screenshottocode.com
- Supports Figma design imports alongside plain screenshots and mockups

## Difference from Others
Compared to other screenshot-to-code tools like Locofy, Anji, or bolt.new, Screenshot to Code stands out in three ways. First, it supports the broadest set of output frameworks—spanning vanilla HTML/Tailwind through React, Vue, Bootstrap, and Ionic—whereas many competitors target a single stack. Second, its ability to ingest screen recordings and produce interactive prototypes (with navigation and state changes) goes beyond static image-to-code conversion, which most competing tools do not offer. Third, it provides both a fully self-hosted open-source deployment and a managed hosted product, giving teams control over data residency and model selection—something many closed SaaS competitors do not match.

## 🏢 Organization & Credibility
- **Developer:** abi
- **Reputation:** Unknown
- **Stars:** 79,022
- **Forks:** 9645
- **Recent Activity:** 71 commits in 3 months
- **Credibility Score:** 72.0/100 (Average)
- **Languages:** Python, TypeScript, HTML, CSS, JavaScript
- **Last Release:** No releases
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
*Source: [GitHub](https://github.com/abi/screenshot-to-code)*
