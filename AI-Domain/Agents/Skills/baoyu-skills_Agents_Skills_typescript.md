---
source: "https://github.com/JimLiu/baoyu-skills"
aliases:
  - baoyu-skills
  - JimLiu/baoyu-skills

tags: [typescript, agent-skills, claude-code, codex, wechat, content-workflow, claude-skills, codex-skills, openclaw-skills, javascript, css, shell]
category: "Agents/Skills"
stars: 25953
org: "JimLiu"
primary_language: TypeScript
languages: [TypeScript, JavaScript, CSS, Shell, url]
credibility_score: 58.5/100
date_processed: 2026-09-16
last_release: 2026-06-18
cover: attachments/banners/baoyu-skills_banner.png

---

![banner](attachments/banners/baoyu-skills_banner.png)

# baoyu-skills

> **TL;DR:** 20+ installable AI agent skills for Claude Code, Codex, and similar tools to boost daily work efficiency.

**`JimLiu/baoyu-skills`** · ⭐ 25,953 · 🔧 TypeScript

## What is it?
baoyu-skills is a curated collection of 20+ ready-to-use skill modules designed for AI coding agents such as Claude Code, Codex, and OpenClaw. The skills focus heavily on content-creation workflows—particularly WeChat Official Account publishing, including cover image generation, article illustration, Markdown-to-HTML conversion, and direct posting to WeChat. Each skill is packaged as a self-contained directory with a SKILL.md file that the agent runtime can discover and load.

Installation is straightforward via `npx skills add jimliu/baoyu-skills`, though the README recommends installing only the skills you actually need to avoid unnecessary context overhead. For Codex specifically, skills can be placed project-locally in `.agents/skills/` for scoped access without a global install.

The project has earned significant community trust with nearly 26k stars and ~2.9k forks, making it one of the most popular skill collections in the AI agent ecosystem.

## How does it work?
Each skill is a directory containing a SKILL.md file (and supporting assets) that defines the capability, instructions, and any tool calls an agent should perform. The skills plug into existing agent runtimes: Claude Code discovers them via its skills mechanism, Codex scans `.agents/skills/` within a project, and OpenClaw uses a similar convention. Under the hood the skills rely on Node.js and `npx bun` for any script execution (e.g., image generation, API calls to WeChat). The content-creation pipeline chains together—formatting raw text into structured Markdown, generating cover/inline images, converting Markdown to WeChat-ready HTML, and pushing the final article via WeChat's Official Account API using user-supplied credentials.

The architecture is intentionally lightweight: no proprietary framework lock-in, just markdown instruction files plus optional helper scripts. This keeps each skill small, portable, and easy to audit, while still giving agents concrete, repeatable workflows they can invoke on demand.

## Why is it important? (Core Value)
For a software engineer and researcher focused on AI agents and developer tools, baoyu-skills is a directly consumable resource: it provides drop-in skills you can install into your own Claude Code or Codex sessions to automate content pipelines (WeChat publishing, image generation, Markdown formatting) without building those workflows from scratch. It also serves as an excellent reference for how skill modules are structured—SKILL.md conventions, project-level vs. global installs, and credential scoping—which informs how you might design your own agent skills or MCP-style tool integrations. The near-26k-star community signal adds credibility, making it a strong candidate to adopt or fork when experimenting with multi-skill agent workflows in your Obsidian-catalogued knowledge base.

## Key Features & Technologies
- 20+ installable skill modules for Claude Code, Codex, and OpenClaw agents
- WeChat Official Account publishing workflow (cover image, illustration, post)
- Markdown-to-HTML and formatting skills for content pipelines
- Installable globally via `npx skills add` or per-project via `.agents/skills/`
- SKILL.md-based skill discovery convention with minimal context overhead
- Node.js / npx bun runtime for helper scripts and API calls

## Difference from Others
Unlike agent frameworks (LangChain, AutoGen) that build the agent runtime itself, baoyu-skills provides only the capability layer—ready-made skills that plug into existing agents. Compared to a single monolithic plugin, each skill is an independent directory you can cherry-pick, which the README explicitly recommends to avoid context bloat. The WeChat-specific focus (cover images, article illustrations, direct posting) sets it apart from generic prompt libraries or MCP servers: it encodes a complete editorial workflow rather than just exposing raw tools. Its SKILL.md convention and project-scoped installation model also make it a practical reference for anyone designing their own skill packs.

## 🏢 Organization & Credibility
- **Developer:** JimLiu
- **Reputation:** Unknown
- **Stars:** 25,953
- **Forks:** 2870
- **Recent Activity:** 14 commits in 3 months
- **Credibility Score:** 58.5/100 (Low)
- **Languages:** TypeScript, JavaScript, CSS, Shell, url
- **Last Release:** 2026-06-18
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
*Source: [GitHub](https://github.com/JimLiu/baoyu-skills)*
