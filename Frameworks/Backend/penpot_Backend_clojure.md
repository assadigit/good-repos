---
source: https://github.com/penpot/penpot
aliases:
  - penpot
  - penpot/penpot
tags: [clojure, clojure, clojurescript, design, open-source, self-hosted, ux-design, ux-experience, prototyping, ui, javascript, rust]
category: Backend
stars: 56727
org: penpot
primary_language: Clojure
languages: [Clojure, JavaScript, Rust, SCSS, TypeScript]
credibility_score: 70.5/100
date_processed: 2026-07-17
last_release: 2026-07-01
cover: attachments/banners/penpot_banner.png

---

![banner](attachments/banners/penpot_banner.png)

# penpot

> **TL;DR:** Open-source design platform for collaborative UI/UX prototyping with self-hostable deployment.

**`penpot/penpot`** · ⭐ 56,727 · 🔧 Clojure

## What is it?
Penpot is a web-based design platform built for product teams that need scalable collaboration. It provides vector drawing tools, real-time multiplayer editing, and design token management, all running entirely in the browser. The project is open-source under the MPL-2.0 license and is verified as a Digital Public Good (DPG) by the Mozilla Foundation.

## How does it work?
Penpot runs as a client-side web application that renders vector graphics directly in the browser using Canvas API and SVG. The server side is implemented in Clojure, managing persistent state for each design file, handling WebSocket connections for real-time collaboration, and providing REST endpoints for asset upload/download. Files are stored either locally on the server or on object storage (e.g., S3) depending on deployment configuration. Authentication uses OAuth providers (Google, GitHub) and stores user sessions in Redis or database. The architecture is containerized with Docker images that can be orchestrated via Kubernetes, making it suitable for self-hosted environments.

## Why is it important? (Core Value)
Penpot directly addresses your interest in self-hostable alternatives to SaaS products. Unlike Figma or Adobe XD which require paid subscriptions, Penpot can be deployed on your own infrastructure, eliminating recurring costs and giving you full control over data privacy. Its Clojure/ClojureScript backend is unusual for a design tool, providing a strong codebase you can inspect, extend, or integrate into your own workflow. The verified DPG badge and community-driven development (Taiga.io) align with your goal of curating credible open-source tools. Additionally, Penpot's real-time collaboration features support team workflows without needing third-party plugins, making it a valuable addition to your Obsidian knowledge base under the 'Tools' or 'Infrastructure' category.

## Key Features & Technologies
- Uses Clojure and ClojureScript
- Runs entirely in browser
- Real-time multiplayer editing via WebSockets
- Self-hostable deployment (Docker/Kubernetes)
- Open-source MPL-2.0 license
- Community-driven development on Taiga.io
- Verified Digital Public Goods (DPG) certification

## Difference from Others
Penpot stands out from other design platforms like Figma, Adobe XD, and Sketch because it is open-source and can be self-hosted, whereas those tools require paid subscriptions and keep all data in the cloud. Most competitors use JavaScript/TypeScript for both client and server; Penpot's Clojure backend offers a polyglot approach that may appeal to developers interested in functional programming languages. Additionally, Penpot's verified DPG status indicates adherence to open standards and community governance, which is not a feature of proprietary tools.

## 🏢 Organization & Credibility
- **Developer:** penpot
- **Reputation:** Unknown
- **Stars:** 56,727
- **Forks:** 3736
- **Recent Activity:** 1470 commits in 3 months
- **Credibility Score:** 70.5/100 (Average)
- **Languages:** Clojure, JavaScript, Rust, SCSS, TypeScript
- **Last Release:** 2026-07-01
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
*Source: [GitHub](https://github.com/penpot/penpot)*
