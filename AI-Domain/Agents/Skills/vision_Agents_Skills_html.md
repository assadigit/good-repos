---
source: https://github.com/kunchenguid/vision
aliases:
  - vision
  - kunchenguid/vision
tags: [html, python, agent-skill, documentation, github-api, vision, css, url]
category: Agents/Skills
stars: 275
org: kunchenguid
primary_language: HTML
languages: [HTML, CSS, url]
credibility_score: 41.0/100
date_processed: 2026-08-19



---

# vision

> **TL;DR:** Agent skill that mines repo history to draft a VISION.md, stress-tests it with hypotheticals, and iterates via interactive review board.

**`kunchenguid/vision`** · ⭐ 275 · 🔧 HTML

## What is it?
vision is an Agent Skill from the Agent Skills ecosystem that automatically mines your repository's Git history—including merged PRs, declined features, and bug fixes—to extract implicit values and principles. It then drafts a VISION.md as a testable acceptance policy for your project.

The tool stress-tests this draft by generating hard hypothetical scenarios—tempting-but-off-mission features, principle collisions, slippery slopes—that only the repository's maintainer can authentically answer. You respond on an interactive review board with yes/no decisions and reasoning, which gets folded back into the vision document edit-by-edit, creating a traceable audit trail of how your values were discovered and codified.

## How does it work?
The tool operates by first parsing your repository's Git history to identify patterns in merged PRs (what you chose to build), declined features (what you consciously rejected), and bug fixes at the root level (what principles guided your engineering decisions). From these signals, it synthesizes a draft VISION.md. This draft is then stress-tested against contrived but realistic scenarios designed to probe edge cases of your stated values. The interactive review board allows you to respond in real-time, with each answer and its reasoning being traced back into the document as an iterative refinement.

## Why is it important? (Core Value)
For a software engineer focused on AI agents and developer tools who curates GitHub projects for personal knowledge building, vision is highly relevant because it directly addresses the documentation gap that plagues long-lived open-source projects. Your objective to find frameworks and MCP servers you can integrate into your projects aligns with this tool's purpose: creating robust agent-friendly project manifests (VISION.md serves as a capability policy). The self-hostable nature of Agent Skills means this could be run locally within your homelab infrastructure.

Specifically, this helps you by: (1) providing a structured way to codify the implicit values embedded in 200+ PRs into an explicit agent-readable policy; (2) serving as a reference for how AI agents should interact with your codebase—critical for your interest in MCP servers and agent integration; (3) creating a reusable template you can share or adapt when building your own agent systems. The stress-testing aspect is particularly valuable for ensuring your project's stated values hold up under adversarial questioning, which matters both for documentation credibility and for training agents on your codebase.

## Key Features & Technologies
- Mines Git history (PRs, commits, bug fixes) to extract implicit values
- Generates testable VISION.md acceptance policies from historical signals
- Stress-tests with hard hypothetical scenarios (off-mission features, principle collisions)
- Interactive review board for yes/no + reasoning responses
- Traceable edit history showing how the vision evolved through iteration

## Difference from Others
Unlike generic documentation generators or README writers that produce static markdown from templates, vision is explicitly designed as an Agent Skill—meaning it's built to be consumed by AI agents as a capability. It doesn't just write documentation; it mines *behavioral evidence* from your actual commit history and uses hypothetical adversarial questioning to stress-test the resulting policy. The interactive review board with traceable edits creates an audit trail that distinguishes it from one-pass tools.

## 🏢 Organization & Credibility
- **Developer:** kunchenguid
- **Reputation:** Unknown
- **Stars:** 275
- **Forks:** 11
- **Recent Activity:** 1 commits in 3 months
- **Credibility Score:** 41.0/100 (Low)
- **Languages:** HTML, CSS, url
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
*Source: [GitHub](https://github.com/kunchenguid/vision)*
