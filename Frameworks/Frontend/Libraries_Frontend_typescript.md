---
source: https://github.com/Jakubantalik/Libraries
aliases:
  - Libraries
  - Jakubantalik/Libraries
tags: [typescript, react, typescript, animation, ui-effects, npm, beam, design, effect, glow, motion, product]
category: Frontend
stars: 2683
org: Jakubantalik
primary_language: TypeScript
languages: [TypeScript, Swift, CSS, Metal, Shell]
credibility_score: 62.0/100
date_processed: 2026-09-01
last_release: 2026-07-02
cover: attachments/banners/Libraries_banner.png

---

![banner](attachments/banners/Libraries_banner.png)

# Libraries

> **TL;DR:** React component libraries for animated UI effects: border beam, liquid gooey morphing, and thinking orb loaders.

**`Jakubantalik/Libraries`** · ⭐ 2,683 · 🔧 TypeScript

## What is it?
Libraries is a monorepo by Jakub Antalik that bundles three focused React effect packages: border-beam (an animated glowing border), liquid-gooey (liquid Morph & Move effects), and thinking-orbs (dotted thought-orb loaders). Each package is published independently to npm with its own README and LICENSE, while demo sites ship alongside in the repo so contributors can preview every effect live. The project has earned 2,683 stars and 156 forks, signalling strong adoption among front-end developers who want polished, production-ready motion primitives without pulling in a heavyweight animation framework.
The collection targets a specific niche: small, self-contained visual effects that drop into React trees with minimal configuration. border-beam adds a traveling light beam along an element's border, liquid-gooey provides fluid morphing and movement between shapes, and thinking-orbs renders staggered dot-based loaders that read as a 'thinking' or 'processing' state. Together they cover three common UI moments—attention-drawing borders, organic shape transitions, and async/loading indicators—so teams can compose a cohesive motion language across a product without custom-building each effect.
Beyond the libraries themselves, the repo doubles as a living demo environment. Each package pairs with a dedicated site that aliases the library to its source, so editing code hot-reloads the demo instantly. This tight loop makes the repo approachable for contributors who want to tweak timing curves, add variants, or port an effect to another framework.

## How does it work?
The repo is structured as an npm-workspaces monorepo: a packages/ directory holds one folder per published library (border-beam, liquid-gooey, thinking-orbs) and a sites/ directory holds the demo app for each. A single npm install at the root resolves every workspace, and scripts like npm run dev -w @sites/beam spin up just that demo with its library aliased to source, giving hot-reload without a rebuild. Build scripts (build:beam, build:gooey, build:orbs) compile individual libraries, while combined scripts (build:site-beam, etc.) mirror the CI pipeline that ships both the package and its demo. A typecheck script runs across all workspaces to catch regressions early.
Under the hood each library is a small React component written in TypeScript that exposes a handful of props for color, speed, size, and state. The border-beam effect animates a conic-gradient or SVG mask along an element's perimeter; liquid-gooey leverages CSS/JS interpolation to morph blob-like shapes with spring physics; thinking-orbs renders a grid of dots that pulse in sequence to simulate 'thinking.' Because the effects are pure component logic plus CSS/SVG, they avoid canvas or WebGL overhead and slot cleanly into any React 18+ tree.

## Why is it important? (Core Value)
For a developer focused on AI agents and tooling, this repo is a compact source of ready-to-embed motion primitives that make agent interfaces feel alive. The thinking-orbs loader is especially relevant: it gives a 'model is reasoning' state without custom animation code, saving hours when wiring up chat or task UIs for LLM products. border-beam and liquid-gooey can elevate the visual polish of dashboards, admin panels, or any developer-facing tool where you want to signal activity or draw attention without adding a heavy dependency.
The monorepo layout also serves as a reference pattern for packaging small npm libraries with co-located demos—useful when the user is prototyping their own MCP server UIs, agent skill galleries, or Obsidian-adjacent web tools and wants a lightweight, self-hostable component story rather than a SaaS design system.

## Key Features & Technologies
- React component libraries published as independent npm packages
- border-beam: animated glowing border effect
- liquid-gooey: liquid Morph & Move shape effects
- thinking-orbs: dotted thought-orb loaders for async states
- npm workspaces monorepo with hot-reload demo sites
- TypeScript with repo-wide typecheck script

## Difference from Others
Compared to general-purpose animation libraries like Framer Motion or React-Spring, Libraries ships purpose-built effect components rather than a generic spring/tween engine. You don't write keyframe timelines; you drop <BorderBeam/> or <ThinkingOrbs/> and tune a few props. That narrow scope makes each package tiny (single-digit KB), easy to audit, and trivially swappable—no global animation registry or provider tree required. The trade-off is flexibility: you can't compose arbitrary path animations, but for the three moments it covers (border glow, organic morph, thinking dots) the out-of-the-box polish beats hand-rolling CSS keyframes. The co-located demo sites and per-package READMEs also lower the onboarding cost versus a framework where docs live in a separate site.

## 🏢 Organization & Credibility
- **Developer:** Jakubantalik
- **Reputation:** Unknown
- **Stars:** 2,683
- **Forks:** 156
- **Recent Activity:** 178 commits in 3 months
- **Credibility Score:** 62.0/100 (Average)
- **Languages:** TypeScript, Swift, CSS, Metal, Shell
- **Last Release:** 2026-07-02
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
*Source: [GitHub](https://github.com/Jakubantalik/Libraries)*
