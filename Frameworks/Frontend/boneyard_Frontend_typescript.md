---
source: https://github.com/0xGF/boneyard
aliases:
  - boneyard
  - 0xGF/boneyard
tags: [typescript, javascript, typescript, react, vue, ui, svelte, css]
category: Frontend
stars: 6582
org: 0xGF
primary_language: TypeScript
languages: [TypeScript, JavaScript, Vue, Svelte, CSS]
credibility_score: 59.5/100
date_processed: 2026-07-17
last_release: 2026-07-07
cover: attachments/banners/boneyard_banner.png

---

![banner](attachments/banners/boneyard_banner.png)

# boneyard

> **TL;DR:** Pixel-perfect skeleton loading screens for React, Vue, Svelte, Angular, and React Native.

**`0xGF/boneyard`** · ⭐ 6,582 · 🔧 TypeScript

## What is it?
boneyard automatically generates pixel-perfect skeleton loading screens by extracting the exact layout of your real UI components. It removes the need for manual measurement or hand-tuned placeholders, making it ideal for modern web and mobile apps that use React, Preact, Vue, Svelte 5, Angular, or React Native.

The framework includes a CLI that captures skeleton definitions at build time (the `--wait` option lets queries resolve naturally) and provides framework-specific exports such as `Skeleton` for React and Vue, and `<BoneSuspense>` for Suspense boundaries. No `initialData` or `placeholderData` is required; you can pass a fixture if the query cannot finish in time.

Key features include seamless integration with data-fetching patterns (e.g., `useFetch`), a registry of bones for Vue, and support for both server and client rendering contexts.

## How does it work?
boneyard operates by first running its CLI on your project to scan the rendered UI and extract the exact CSS/layout of each component. Those extracted definitions are then emitted as reusable skeleton components that match the real UI pixel-for-pixel. The library provides framework-specific wrappers (e.g., `Skeleton` in React, Vue, Svelte) that accept a `name` prop referencing the captured bone and a `loading` flag. For Suspense boundaries, it offers `<BoneSuspense>` which renders the skeleton as the fallback at runtime while the CLI records the resolved children at build time. No manual CSS or placeholder data is needed; the build-time `--wait` window allows queries to resolve naturally, and a `fixture` can be supplied if a query cannot finish in time.

## Why is it important? (Core Value)
This project directly supports your interest in developer productivity tools and self-hostable alternatives to SaaS products. By automating the creation of pixel-perfect loading skeletons, it saves you time on UI development and reduces reliance on placeholder services that may incur costs or require manual tweaking. As an open-source library, boneyard can be self-hosted in your own repository, aligning with your goal of curating a knowledge base of useful tools and frameworks. Additionally, its multi-framework support means it fits into any project stack you maintain, making it a versatile addition to your developer toolkit.

## Key Features & Technologies
- npm install boneyard-js
- Works with React, Preact, Vue, Svelte 5, Angular, React Native
- BoneSuspense for Suspense boundaries
- CLI captures skeleton bones at build time
- No placeholder data needed
- Supports fixture for slow queries

## Difference from Others
Unlike generic placeholder components that rely on manual CSS or pre-defined sizes, boneyard extracts skeletons from your actual UI layout via a build-time CLI, guaranteeing pixel-perfect matches. It also supports multiple frameworks out of the box, whereas other libraries often target only React or require separate packages for Vue/Svelte. The framework's `<BoneSuspense>` component integrates directly with Suspense boundaries, a feature not present in most skeleton utilities.

## 🏢 Organization & Credibility
- **Developer:** 0xGF
- **Reputation:** Unknown
- **Stars:** 6,582
- **Forks:** 263
- **Recent Activity:** 42 commits in 3 months
- **Credibility Score:** 59.5/100 (Low)
- **Languages:** TypeScript, JavaScript, Vue, Svelte, CSS
- **Last Release:** 2026-07-07
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
*Source: [GitHub](https://github.com/0xGF/boneyard)*
