---
source: https://github.com/google-labs-code/design.md
aliases:
  - design.md
  - google-labs-code/design.md
tags: [typescript, yaml, markdown, design-systems, ai-agents, open-source, mdx, javascript, url]
category: LLM-Tools
stars: 25234
org: google-labs-code
primary_language: TypeScript
languages: [TypeScript, MDX, JavaScript, url]
credibility_score: 94.0/100
date_processed: 2026-07-07
last_release: 2026-06-15
cover: attachments/banners/design_md_banner.png

---

![banner](attachments/banners/design_md_banner.png)

# design.md

> **TL;DR:** Specification format for describing visual design systems to coding AI agents using YAML tokens and markdown prose.

**`google-labs-code/design.md`** · ⭐ 25,234 · 🔧 TypeScript

## What is it?
A specification for describing visual design systems to coding AI agents. It combines machine-readable design tokens (YAML front matter) with human-readable design rationale (markdown prose). Tokens give exact values; prose tells why those values exist and how to apply them.

The format includes colors, typography, rounded corners, and spacing units defined in YAML, followed by markdown explaining the design philosophy and specific color usage. This dual-layer approach ensures both precision and rationale for agents consuming the file.

## How does it work?
DESIGN.md is a single markdown file with YAML front matter containing design tokens (colors, typography, rounded, spacing). Agents parse the YAML to extract exact values, then read the prose for context on why those values were chosen and how to apply them.

This architecture separates machine-readable data from human-readable explanation, enabling agents to reliably consume design specifications while maintaining transparency for developers reviewing the file.

## Why is it important? (Core Value)
The user's interest in AI/LLM tooling (agents, skills, MCP) aligns directly with this project's purpose: providing structured design specifications for coding agents. As a software engineer building tools and curating GitHub projects for an Obsidian vault, they can add DESIGN.md to their knowledge base under 'AI-Domain' or 'Tools'. It offers a standardized way to pass design context (colors, typography, rationale) to agents, enabling more sophisticated UI generation workflows. Being open-source from Google labs code also satisfies their interest in credible projects from major tech companies.

## Key Features & Technologies
- YAML front matter
- Markdown prose
- Design tokens (colors, typography, spacing)
- Structured format specification
- Open-source from Google labs code
- Dual machine/human-readable layers

## Difference from Others
Unlike static design system files (CSS custom properties, Tailwind config), this specification is explicitly designed for consumption by coding AI agents. It provides both exact token values and prose rationale, whereas other formats typically only expose tokens or require manual interpretation. The Google labs code origin also adds credibility compared to community-maintained alternatives.

It stands out because it targets the agent workflow directly, enabling persistent context transfer rather than just UI styling. This makes it uniquely positioned for integrating design understanding into autonomous agent systems.

## 🏢 Organization & Credibility
- **Developer:** google-labs-code
- **Reputation:** High (Major tech company)
- **Stars:** 25,234
- **Forks:** 1960
- **Recent Activity:** 49 commits in 3 months
- **Credibility Score:** 94.0/100 (Excellent)
- **Languages:** TypeScript, MDX, JavaScript, url
- **Last Release:** 2026-06-15
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
*Source: [GitHub](https://github.com/google-labs-code/design.md)*
