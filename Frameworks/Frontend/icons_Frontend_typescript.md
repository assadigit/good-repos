---
source: https://github.com/persianlabs/icons
aliases:
  - icons
  - persianlabs/icons
tags: [typescript, typescript, react, vue, icons, npm, javascript, css, html, url]
category: Frontend
stars: 185
org: persianlabs
primary_language: TypeScript
languages: [TypeScript, JavaScript, CSS, HTML, url]
credibility_score: 49.5/100
date_processed: 2026-09-01
last_release: 2026-08-17
cover: attachments/banners/icons_banner.png

---

![banner](attachments/banners/icons_banner.png)

# icons

> **TL;DR:** Typed, open-source collection of Iranian bank, payment gateway, and brand logos as React and Vue components.

**`persianlabs/icons`** · ⭐ 185 · 🔧 TypeScript

## What is it?
Persian Icons is an open-source, MIT-licensed icon library that gathers the logos of Iranian banks, payment gateways, and well-known brands into a single typed npm package (@persianlabs/icons). It addresses a specific gap: generic icon sets (Font Awesome, Lucide, etc.) do not include regional financial brands, so developers building fintech, e-commerce, or banking UIs in Iran have to hunt down brand assets and verify their licensing themselves. Persian Icons bundles that work up front.

The project is maintained by persianlabs and described as a "growing" collection, meaning new logos are added over time as the library expands beyond banks and payment gateways into broader Iranian brands. A companion site (icons.persian-labs.ir) lets you browse the available logos before installing.

## How does it work?
The library ships as the npm package @persianlabs/icons and exposes each logo as a typed component for React and Vue, so you import a brand's logo by name and render it directly in your UI with typed props. The "typed" emphasis means consumers get autocomplete and compile-time safety when picking among many brand logos. A documentation site hosts the collection and even publishes an llms.txt file, making the catalog machine-readable for LLM tooling.

Under the hood it is a standard frontend asset pipeline: logo artwork is packaged once and re-exported per framework (React/Vue), with npm handling versioning and distribution. There is no server component or runtime service — you install the package and use the components locally in your app.

## Why is it important? (Core Value)
The core value is niche completeness: it is a one-stop source for Iranian financial brand logos, saving developers from sourcing assets individually and worrying about licensing (MIT means safe commercial reuse). For fintech or e-commerce teams targeting Iran, this removes a real, recurring pain point in UI development.

For you specifically, it fits several of your interests: it is a self-hostable, zero-SaaS npm dependency that slots straight into React/Vue projects; its typed component API is a clean pattern for icon libraries; and the llms.txt on the docs site is a nice example of making an asset catalog LLM-consumable — exactly the kind of modern LLM tooling touch you track. It is a small, credible project (185 stars, MIT license, active npm package) worth noting in your Obsidian vault under Frontend/UI libraries.

## Key Features & Technologies
- Open-source (MIT) npm package: @persianlabs/icons
- Typed React and Vue components for each logo
- Covers Iranian banks, payment gateways, and other brands
- Growing, community-maintained collection
- Browsable docs site (icons.persian-labs.ir) with llms.txt for LLM-friendly access

## Difference from Others
Compared to general-purpose icon libraries like Font Awesome, Lucide, or Heroicons, Persian Icons is the opposite of generic: it targets a specific regional market — Iranian financial brands — that no global icon set covers. Instead of an all-purpose glyph set, each entry is a real brand logo you can trust for production use under MIT terms.

Its other differentiators are modern distribution choices: typed React/Vue components rather than icon fonts or sprite sheets, and an llms.txt file on the docs site that makes the catalog consumable by LLMs — a detail most icon projects don't have. Where generic sets win on breadth, Persian Icons wins on accuracy and legality for its niche.

## 🏢 Organization & Credibility
- **Developer:** persianlabs
- **Reputation:** Unknown
- **Stars:** 185
- **Forks:** 11
- **Recent Activity:** 48 commits in 3 months
- **Credibility Score:** 49.5/100 (Low)
- **Languages:** TypeScript, JavaScript, CSS, HTML, url
- **Last Release:** 2026-08-17
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
*Source: [GitHub](https://github.com/persianlabs/icons)*
