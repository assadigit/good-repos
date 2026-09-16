---
source: "https://github.com/subsy/skill-cabinet"
aliases:
  - skill-cabinet
  - subsy/skill-cabinet

tags: [javascript, node, agent-skills, local-server, file-management, cli, css, html, url]
category: "Agents/Skills"
stars: 413
org: "subsy"
primary_language: JavaScript
languages: [JavaScript, CSS, HTML, url]
credibility_score: 49.5/100
date_processed: 2026-09-16
last_release: 2026-09-02
cover: attachments/banners/skill-cabinet_banner.png

---

![banner](attachments/banners/skill-cabinet_banner.png)

# skill-cabinet

> **TL;DR:** Local web catalog that indexes, audits, and manages agent skill folders across .claude, .codex, .cursor, and other skill directories.

**`subsy/skill-cabinet`** · ⭐ 413 · 🔧 JavaScript

## What is it?
Skill Cabinet is a local catalog for agent skills installed on your machine. It scans user-level skill drawers such as `.agents`, `.claude`, `.codex`, and `.cursor` (including plugins), Hermes profiles, and other `~/.* /skills` folders, then gives you a readable index of each skill.

The project is designed for inspecting and managing local agent skill files. It can show the rendered or source body of a skill, its YAML frontmatter, extra files, and whether the skill is a folder, file, or symlink. It also supports search and filtering by drawer, origin, copies, frontmatter, risk level, invocation mode, and physical/reference/broken state.

It includes disk-level management actions such as deleting or quarantining skill folders, making it useful for auditing, cleaning up, or safely experimenting with agent skills installed across multiple agent tools.

## How does it work?
Skill Cabinet runs as a Node.js local server, launched via `npx skill-cabinet`. It binds to `127.0.0.1`, typically on port `3781`, and opens a browser interface for inspecting skills found on the local machine.

Under the hood, it scans configured user-level directories and skill folders, indexes each discovered skill, reads its frontmatter and supporting files, and exposes filters for provenance, duplication, risk, and invocation behavior. It can also follow GitHub origins when a skill names one or when the install path encodes one, marking inferred origins from parent plugins or git remotes.

## Why is it important? (Core Value)
For a software engineer and researcher focused on AI agents, developer tools, and automation, Skill Cabinet is a practical self-hosted utility for managing the local agent-skill ecosystem. It helps you see what skills are installed across Claude, Codex, Cursor, and other agent drawers, inspect their frontmatter and source, detect duplicates or broken references, and safely quarantine or delete risky or unwanted skill folders.

This directly supports your goal of curating AI/LLM tooling and building a trustworthy personal knowledge base. Because it runs locally and binds only to localhost, it fits well into a self-hosted developer workflow and gives you a concrete way to audit the agent skills you are experimenting with before integrating them into projects.

## Key Features & Technologies
- Scans local agent skill drawers such as `.claude`, `.codex`, `.cursor`, `.agents`, Hermes profiles, and other `~/.* /skills` folders
- Runs a localhost-only web UI via Node.js after launching with `npx skill-cabinet`
- Searches and filters by drawer, name, description, path, origin, copies, frontmatter, risk, and invocation mode
- Reads skill bodies in rendered or source form, plus YAML frontmatter and extra files
- Tracks whether a skill is a folder, file, or symlink and identifies duplicate or broken copies
- Follows GitHub origins when possible and marks inferred origins from parent plugins or git remotes
- Supports deleting or quarantining skill folders from disk

## Difference from Others
Compared with generic file managers or ad-hoc scripts for inspecting agent directories, Skill Cabinet is purpose-built for the agent-skill format. It understands skill frontmatter, provenance, duplicate copies, invocation modes, and risk states rather than treating skills as ordinary folders.

Its standout value is local-first auditing: it gives a single browser-based view across multiple agent ecosystems on one machine, with safety-oriented actions such as quarantine and deletion. That makes it more useful than a simple directory browser for developers who are actively curating or experimenting with agent skill collections.

## 🏢 Organization & Credibility
- **Developer:** subsy
- **Reputation:** Unknown
- **Stars:** 413
- **Forks:** 30
- **Recent Activity:** 42 commits in 3 months
- **Credibility Score:** 49.5/100 (Low)
- **Languages:** JavaScript, CSS, HTML, url
- **Last Release:** 2026-09-02
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
*Source: [GitHub](https://github.com/subsy/skill-cabinet)*
