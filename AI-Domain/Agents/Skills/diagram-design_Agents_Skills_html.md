---
source: "https://github.com/cathrynlavery/diagram-design"
aliases:
  - diagram-design
  - cathrynlavery/diagram-design

tags: [html, svg, agent-skills, claude-code, diagrams, codex, data-visualization, drawio, mermaid, python, url]
category: "Agents/Skills"
stars: 40251
org: "cathrynlavery"
primary_language: HTML
languages: [HTML, Python, Mermaid, url]
credibility_score: 72.0/100
date_processed: 2026-09-16

cover: attachments/banners/diagram-design_banner.png

---

![banner](attachments/banners/diagram-design_banner.png)

# diagram-design

> **TL;DR:** Editorial diagram generation skill for Claude Code, Codex, and Pi agents producing self-contained HTML+SVG outputs.

**`cathrynlavery/diagram-design`** · ⭐ 40,251 · 🔧 HTML

## What is it?
diagram-design is a skill library that equips AI coding agents (Claude Code, Codex, Factory Droid, Pi, and other Agent Skills-compatible hosts) with the ability to produce publication-quality editorial diagrams. It ships dozens of named diagram types—architecture, loop/flywheel, Sankey, fishbone, Wardley map, kanban, user journey, deployment, dependency graph, UML class, story map, database schema, and more—each rendered as self-contained HTML with inline SVG. The project explicitly positions itself against generic auto-generated diagrams ("No Mermaid slop"), emphasizing clean, shadow-free visual design that a human designer would approve.

## How does it work?
The skill operates as a prompt/behavior module consumed by agent runtimes. When an agent is asked to produce a diagram, the skill selects the nearest matching layout grammar from its catalog and emits self-contained HTML+SVG (static by default). A key architectural choice is separating semantic patterns (behavior: queues, policy traces, trust boundaries) from layout geometry, so new behaviors can map onto existing types without inflating the type count. An optional accessible-motion layer can animate ordered explanations while keeping static output as the default. The skill also accepts draw.io, Mermaid, or Excalidraw source files and re-renders them at a chosen format, size, and detail level.

## Why is it important? (Core Value)
For a software engineer and researcher curating AI-agent tooling, this project is a drop-in capability that makes agent-generated diagrams actually usable in docs, slide decks, or Obsidian notes. It solves the common pain of LLMs producing ugly, shadow-heavy Mermaid diagrams by giving agents a curated design system with editorial-grade SVG output. Because it targets multiple agent hosts (Claude Code, Codex, Pi) via the Agent Skills standard, it integrates directly into the user's existing agent workflows without extra infrastructure. The ability to re-render existing draw.io/Mermaid/Excalidraw sources at a chosen fidelity also makes it a practical migration path for teams that already have diagram assets but want cleaner, self-contained HTML output.

## Key Features & Technologies
- Dozens of named editorial diagram types (architecture, Sankey, Wardley map, UML class, story map, database schema, etc.)
- Self-contained HTML + SVG output with no external dependencies or shadows
- Semantic pattern layer separates behavior from layout to avoid type explosion
- Optional accessible motion for ordered explanations while static remains default
- Re-renders draw.io, Mermaid, and Excalidraw sources at chosen format/size/detail
- Compatible with Claude Code, Codex, Factory Droid, Pi, and Agent Skills hosts

## Difference from Others
Most diagram-generation tools for LLMs default to Mermaid or generic SVG output that looks like a quick prototype. diagram-design takes the opposite stance: it is explicitly anti-Mermaid, shipping a hand-tuned editorial design system where each type has a specific visual grammar (e.g., dashed write-back lines on the Loop/flywheel). Compared to standalone diagram editors (draw.io, Excalidraw) or charting libraries (D3), this project's unique value is that it is an agent skill—it lives inside the LLM's tool-use loop, so a coding agent can produce a polished diagram as part of a code-generation or documentation task without leaving the terminal. The semantic-vs-layout separation is also distinctive: instead of adding a new type for every new behavior, the skill maps behaviors onto existing grammars, keeping the catalog compact and maintainable.

## 🏢 Organization & Credibility
- **Developer:** cathrynlavery
- **Reputation:** Unknown
- **Stars:** 40,251
- **Forks:** 2562
- **Recent Activity:** 154 commits in 3 months
- **Credibility Score:** 72.0/100 (Average)
- **Languages:** HTML, Python, Mermaid, url
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
*Source: [GitHub](https://github.com/cathrynlavery/diagram-design)*
