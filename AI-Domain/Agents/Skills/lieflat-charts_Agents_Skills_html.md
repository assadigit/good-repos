---
source: "https://github.com/larashero3-dotcom/lieflat-charts"
aliases:
  - lieflat-charts
  - larashero3-dotcom/lieflat-charts

tags: [html, agent-skill, data-visualization, svg, claude-code, agent-skills, charts, codex, moxt, javascript, url]
category: "Agents/Skills"
stars: 5473
org: "larashero3-dotcom"
primary_language: HTML
languages: [HTML, JavaScript, url]
credibility_score: 61.0/100
date_processed: 2026-09-16
last_release: 2026-08-14
cover: attachments/banners/lieflat-charts_banner.png

---

![banner](attachments/banners/lieflat-charts_banner.png)

# lieflat-charts

> **TL;DR:** Agent skill that turns data into polished, interactive HTML charts and publishable reports with editorial visual styles.

**`larashero3-dotcom/lieflat-charts`** · ⭐ 5,473 · 🔧 HTML

## What is it?
Lieflat Charts is a data visualization and report generation skill for AI agents, built to the Agent Skills format (SKILL.md) so it can be used by moxt, Claude Code, Codex, and any other agent runtime that supports SKILL.md. Its core purpose is to turn raw data into polished, interactive HTML charts with genuine editorial design quality rather than default-looking output.

It establishes its own visual grammar through unified typography, whitespace, line work, and motion, organized into three visual systems: Lupi (editorial narrative style with fine lines, dot grids, and generous whitespace for long-form data stories), Glance (quick-judgment style with bold bars, large numbers, and clear sorting for weekly reports and dashboards), and Basics (familiar bar/line/donut outlines with countable scales and hairlines for simpler datasets). It also includes independent interactive charts for network, path, and multi-segment flow data.

Color handling is systematic: Mono black-white-gray is the stable fallback, with color modes including celadon blue, coconut green, and editorial red. The agent automatically selects among these based on data structure and use case, falling back to Mono when context is unclear, and can build a custom palette when users provide brand colors. When users explicitly request reports—annual reports, monthly reports, white papers, posters, or briefs—it generates publishable HTML from 12 Chinese/English full-page templates.

## How does it work?
The project follows the Agent Skills convention: it ships as a SKILL.md-based skill that compatible agent runtimes (moxt, Claude Code, Codex) load and execute. Rather than being a charting library, it encodes design judgment as instructions—the visual grammar, chart construction in HTML/SVG, real data units, annotations, sources, and page structure all participate in the expression.

Operationally, the agent selects among Mono, celadon blue, coconut green, or editorial red based on data structure and scenario; ambiguous cases default to Mono. If a user supplies brand colors or hex values, the skill builds a custom color palette. One HTML output or chart set uses exactly one color system, and after generation the charts can be re-colored while preserving figure structure, proportions, contrast, and the data contract.

## Why is it important? (Core Value)
AI agents routinely produce bland, inconsistent, or mislabeled visualizations; this skill gives agents actual editorial design judgment, so data becomes publication-quality visuals without manual design work. It solves the problem of taking raw numbers to polished HTML charts and reports inside an agent workflow, with a reliable Mono fallback that prevents bad color choices.

For you specifically, this sits squarely in your AI/LLM tooling interests (agents, skills, MCP). You can drop it into Claude Code or Codex to generate charts from any dataset in your development workflow, and the repo doubles as a concrete reference for how SKILL.md-based agent skills are structured—useful for your knowledge base curation and for building or evaluating your own agent skills. Its 5.4k stars and compatibility with multiple agent runtimes make it a credible example of the Agent Skills ecosystem.

## Key Features & Technologies
- Follows the Agent Skills format (SKILL.md) for Claude Code, Codex, moxt, and other compatible agents
- Three visual systems: Lupi (editorial narrative), Glance (quick judgment), Basics (basic editorial)
- Interactive HTML/SVG charts including network, path, and multi-segment flow diagrams
- Automatic color selection among Mono, celadon blue, coconut green, and editorial red with Mono fallback
- Custom brand color palette support when users provide colors or hex values
- 12 Chinese/English full-page templates for publishable HTML reports (annual, monthly, white papers, posters)
- Re-coloring that preserves figure structure, proportions, contrast, and data contracts

## Difference from Others
Compared with charting libraries like D3 or Chart.js, Lieflat Charts is not code you call—it's a skill that teaches an agent design judgment: it chooses among three visual systems and color schemes based on context, keeps real units/sources/annotations in the expression, and allows re-coloring without structural changes. Compared with generic 'make me a chart' prompting or one-off chart prompts, it defines a fixed visual grammar, ships 12 bilingual report templates, and has an explicit auto-selection policy with a stable Mono fallback.

Against other agent skills, its standout is the editorial design system itself—unified typography, whitespace, line work, and motion plus a strict single-color-system-per-output rule—rather than just chart generation mechanics.

## 🏢 Organization & Credibility
- **Developer:** larashero3-dotcom
- **Reputation:** Unknown
- **Stars:** 5,473
- **Forks:** 335
- **Recent Activity:** 50 commits in 3 months
- **Credibility Score:** 61.0/100 (Average)
- **Languages:** HTML, JavaScript, url
- **Last Release:** 2026-08-14
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
*Source: [GitHub](https://github.com/larashero3-dotcom/lieflat-charts)*
