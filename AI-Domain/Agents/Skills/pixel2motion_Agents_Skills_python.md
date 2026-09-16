---
source: "https://github.com/nolangz/pixel2motion"
aliases:
  - pixel2motion
  - nolangz/pixel2motion

tags: [python, svg, claude-skill, logo-animation, creative-coding, codex, ai-design-tools, animated-logo, codex-skill, html-animation, motion-design, raster-to-svg]
category: "Agents/Skills"
stars: 2280
org: "nolangz"
primary_language: Python
languages: [Python, JavaScript, url]
credibility_score: 48.5/100
date_processed: 2026-09-16

cover: attachments/banners/pixel2motion_banner.png

---

![banner](attachments/banners/pixel2motion_banner.png)

# pixel2motion

> **TL;DR:** AI agent skill that converts raster logos into animated SVGs with HTML demos, GIF/video previews, and motion QA evidence.

**`nolangz/pixel2motion`** · ⭐ 2,280 · 🔧 Python

## What is it?
Pixel2Motion is an open-source AI skill (designed for Claude and Codex agents) that transforms raster logo images—PNG, JPG, WebP, or screenshots—into clean, motion-ready SVG vector graphics. It then generates animated SVG logo reveals, interactive HTML motion demos, GIF/video previews, and structured motion QA evidence. The project positions itself as a developer-friendly workflow for brand motion design, logo reveals, and pixel-to-vector reconstruction, with a companion skill called Pixel2SVG-HTML for related workflows. A commercial service (pixel2motion.com) is launching to offer polished logo-to-motion delivery and production support beyond the open-source skill.

The project ships with a SKILL.md file containing structured instructions that AI agents follow to execute the raster-to-SVG-to-animation pipeline, making it plug-and-play within Claude or Codex agent sessions. A live interactive demo is hosted on GitHub Pages, and the README includes both English and Chinese documentation.

## How does it work?
Pixel2Motion operates as a structured skill module (SKILL.md) that AI agents like Claude or Codex load and execute step by step. The pipeline takes a raster logo input, reconstructs it as smooth vector SVG geometry, applies motion/animation properties to the SVG elements, and then renders the result in multiple formats: an interactive HTML page with CSS/JS animation, exported GIF or video previews, and QA artifacts that document the motion behavior. The architecture is intentionally lightweight—no heavy runtime framework—relying on the agent's ability to follow the skill instructions and produce code (SVG, HTML, CSS) as output.

The companion Pixel2SVG-HTML skill handles adjacent pixel-to-SVG-HTML conversion tasks, suggesting a modular skill ecosystem where each skill covers a specific stage of the design pipeline. The project leverages generative AI's creative-coding capabilities to perform vector reconstruction and motion design that would traditionally require manual Illustrator or After Effects work.

## Why is it important? (Core Value)
For a software engineer and researcher focused on AI agents and developer tools, Pixel2Motion is a concrete example of how "agent skills" work in practice: a SKILL.md file that an LLM agent loads and executes to produce multi-format creative output. It demonstrates the pattern of packaging domain expertise (logo vectorization, SVG animation, motion QA) as a structured prompt/instruction module rather than a traditional software library, which is directly relevant to anyone exploring MCP servers, agent skill architectures, or Claude/Codex tooling.

The project also intersects with the user's interest in self-hostable alternatives and creative coding: the core skill is fully open-source and runs locally through an agent session, while the commercial tier (pixel2motion.com) represents the SaaS upsell. Studying its SKILL.md structure and output pipeline offers a practical reference for designing similar skill modules in one's own agent stack, and the SVG/HTML animation workflow is a reusable pattern for any team needing programmatic brand motion without After Effects licenses.

## Key Features & Technologies
- Claude/Codex agent skill (SKILL.md instruction format)
- Raster-to-SVG vector reconstruction (PNG/JPG/WebP to clean vectors)
- SVG logo animation and brand motion generation
- Interactive HTML motion demo export
- GIF/video preview rendering
- Motion QA evidence and structured output artifacts
- Companion Pixel2SVG-HTML skill for adjacent workflows

## Difference from Others
Unlike traditional logo-animation tools (After Effects, Rive, Lottie) that require manual keyframe work or proprietary formats, Pixel2Motion is an AI-agent-native skill: the entire pipeline is driven by an LLM following structured instructions, producing code artifacts (SVG, HTML, CSS) rather than binary files. It also differs from generic SVG converters because it targets motion design specifically—animation timing, reveal sequences, and QA evidence are first-class outputs. Compared to other Claude skills in the ecosystem, its strength is the end-to-end creative workflow (raster → vector → animated demo → preview) in a single skill invocation, plus the companion-skill pattern for modularity.

## 🏢 Organization & Credibility
- **Developer:** nolangz
- **Reputation:** Unknown
- **Stars:** 2,280
- **Forks:** 189
- **Recent Activity:** 8 commits in 3 months
- **Credibility Score:** 48.5/100 (Low)
- **Languages:** Python, JavaScript, url
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
*Source: [GitHub](https://github.com/nolangz/pixel2motion)*
