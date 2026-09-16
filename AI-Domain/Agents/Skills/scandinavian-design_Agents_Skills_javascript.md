---
source: "https://github.com/ericzakariasson/scandinavian-design"
aliases:
  - scandinavian-design
  - ericzakariasson/scandinavian-design

tags: [javascript, cursor, agent-skill, design-system, css, ui-redesign, typescript, html, url]
category: "Agents/Skills"
stars: 386
org: "ericzakariasson"
primary_language: JavaScript
languages: [JavaScript, CSS, TypeScript, HTML, url]
credibility_score: 46.5/100
date_processed: 2026-09-16

cover: attachments/banners/scandinavian-design_banner.png

---

![banner](attachments/banners/scandinavian-design_banner.png)

# scandinavian-design

> **TL;DR:** A Cursor agent skill that applies a restrained Scandinavian visual design system to redesign website UIs.

**`ericzakariasson/scandinavian-design`** · ⭐ 386 · 🔧 JavaScript

## What is it?
Scandinavian Design is a Cursor agent skill that injects a specific visual design language into AI-driven code refactoring. It defines a restrained Scandinavian aesthetic—black-and-white foundations, sans-serif typography, generous spacing, and purposeful product imagery—and instructs the Cursor AI agent to apply it when invoked on a target surface.

The repo includes an evaluation suite of ten live sites restyled through a CSS-override fallback, with before/after captures at desktop and mobile breakpoints. A feedback log records what each demo taught the skill, including claims that were checked and rejected, giving the project an iterative, test-driven refinement loop.

## How does it work?
The skill lives in `skills/scandinavian-design/` and is installed into Cursor's skills directory via `npx skills add` or a manual copy. Once installed, invoking `/scandinavian-design` on a UI surface triggers the agent to rewrite styles according to the embedded design rules. A CSS-override fallback mechanism handles cases where direct style edits are insufficient, and an eval pipeline (`npm run eval`) re-captures all ten demo sites for regression checking.

The project uses Node.js tooling, with Remotion for rendering a before/after showcase video and a local viewer on port 4173. The `feedback.md` file documents lessons learned from each demo iteration, feeding corrections back into the skill definition.

## Why is it important? (Core Value)
For a developer focused on AI agent skills and Cursor integrations, this project is a concrete, installable example of how to package a domain-specific capability as a Cursor skill. It demonstrates the skill anatomy (directory layout, install command, invocation syntax) and shows an eval-driven development loop for prompt-based skills—useful patterns when building or evaluating other agent skills.

It also fits the user's interest in design-system tooling: rather than a generic UI library, it encodes a specific aesthetic as agent instructions, illustrating how LLMs can be constrained to produce consistent visual output across a codebase.

## Key Features & Technologies
- Cursor agent skill installed via npx skills add
- Encodes a Scandinavian design system (B&W palette, sans-serif type, spacing rules)
- CSS-override fallback for applying styles where direct edits fail
- Eval suite of 10 before/after site captures at desktop and mobile breakpoints
- Remotion-based showcase video rendering pipeline
- Feedback-driven skill refinement logged in feedback.md
- Invoked with /scandinavian-design command inside Cursor

## Difference from Others
Unlike generic UI component libraries or broad design-token systems, this project packages a narrow aesthetic as a single agent skill rather than a runtime library. Compared to other Cursor skills or prompt collections, it includes an automated eval loop and a documented feedback cycle, making it closer to a tested capability than a static prompt file. It also differs from full design frameworks (e.g., Tailwind, Chakra) in that it operates through an AI agent's rewrite pass rather than providing CSS classes at build time.

## 🏢 Organization & Credibility
- **Developer:** ericzakariasson
- **Reputation:** Unknown
- **Stars:** 386
- **Forks:** 18
- **Recent Activity:** 43 commits in 3 months
- **Credibility Score:** 46.5/100 (Low)
- **Languages:** JavaScript, CSS, TypeScript, HTML, url
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
*Source: [GitHub](https://github.com/ericzakariasson/scandinavian-design)*
