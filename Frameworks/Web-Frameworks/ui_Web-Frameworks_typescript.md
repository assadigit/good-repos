---
source: https://github.com/persianlabs/ui
aliases:
  - ui
  - persianlabs/ui
tags: [typescript, react, rtl, persian, component-library, tailwindcss, motion, nextjs, shadcn-ui, tailwidcss, ui, ui-components]
category: Web-Frameworks
stars: 49
org: persianlabs
primary_language: TypeScript
languages: [TypeScript, CSS, JavaScript, url]
credibility_score: 51.5/100
date_processed: 2026-08-19

cover: attachments/banners/ui_banner.png

---

![banner](attachments/banners/ui_banner.png)

# ui

> **TL;DR:** RTL-first copy-paste component library built with Base UI and Tailwind v4 for Persian interfaces.

**`persianlabs/ui`** · ⭐ 49 · 🔧 TypeScript

## What is it?
PersianLabs/ui is a RTL-first, copy-paste component registry designed specifically for Persian (Farsi) interfaces. It provides pre-built UI components that are logical-property-aware by default, meaning layout directions are handled natively rather than through CSS transforms or hacks. The library ships as plain React source code following the shadcn-ui model, giving developers full ownership and control over their UI code.

## How does it work?
The project is built on Base UI (a low-level accessible component primitives library) and Tailwind v4 for styling. Components are structured to use logical properties (e.g., `start`, `end` instead of `left`, `right`) which automatically adapt when switching between RTL and LTR layouts. Icons are mirrored by default in RTL mode without requiring developers to manually override each icon's direction. The library follows a copy-paste pattern where developers import individual components directly into their Next.js projects rather than installing a pre-built package.

## Why is it important? (Core Value)
For the user, this project represents a self-hostable alternative for building Persian-language interfaces without relying on SaaS platforms that may not properly support RTL layouts. While it doesn't directly align with AI/agent interests, it exemplifies the 'self-hosted alternatives to SaaS' objective by providing open-source UI components that can be fully integrated into personal projects. The logical-property-first approach demonstrates a principled engineering pattern that could inform similar component libraries for other languages or directionality needs. As a researcher in developer tools, this is an example of how specialized regional tooling fills gaps left by general-purpose frameworks.

## Key Features & Technologies
- RTL-first design with mirrored icons by default
- Built on Base UI primitives and Tailwind v4
- Copy-paste component pattern (shadcn-compatible)
- Full LTR support alongside RTL defaults
- Logical CSS properties for automatic direction switching
- Next.js optimized components
- Plain React source code ownership

## Difference from Others
Unlike generic UI libraries that require manual RTL overrides or CSS transforms, this library has RTL as a first-class design principle. Most component libraries treat LTR as the default and add RTL support as an afterthought requiring per-component workarounds. PersianLabs/ui inverts this paradigm — logical properties and mirrored icons are built-in by default. Compared to shadcn-ui, it adds explicit Persian/Persian-script localization considerations that general-purpose libraries don't address.

## 🏢 Organization & Credibility
- **Developer:** persianlabs
- **Reputation:** Unknown
- **Stars:** 49
- **Forks:** 3
- **Recent Activity:** 208 commits in 3 months
- **Credibility Score:** 51.5/100 (Low)
- **Languages:** TypeScript, CSS, JavaScript, url
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
*Source: [GitHub](https://github.com/persianlabs/ui)*
