---
source: "https://github.com/drivebase/drivebase"
aliases:
  - drivebase
  - drivebase/drivebase

tags: [typescript, react, self-hosted, file-management, storage, docker, dropbox, file-manager, google-drive, nodejs, vite]
category: "Dev-Tools"
stars: 585
org: "drivebase"
primary_language: TypeScript
languages: [TypeScript, CSS, Shell, Dockerfile, HTML]
credibility_score: 38.0/100
date_processed: 2026-09-16
last_release: 2026-06-03
cover: attachments/banners/drivebase_banner.png

---

![banner](attachments/banners/drivebase_banner.png)

# drivebase

> **TL;DR:** Self-hosted, cloud-agnostic file manager unifying Google Drive, S3, Dropbox, and local storage in a desktop-style browser UI.

**`drivebase/drivebase`** · ⭐ 585 · 🔧 TypeScript

## What is it?
Drivebase is an open-source, self-hosted file management platform that connects multiple cloud storage providers—Google Drive, S3, Dropbox, FTP, and local filesystems—under a single unified interface. Users can browse, upload, transfer, and manage files across all connected providers without juggling separate services or dashboards. The project is built with React, Vite, Bun, and Node.js, and is deployable via Docker for self-hosting.

The standout design choice is its UI: a virtual desktop OS shell running in the browser, where apps (Files, Providers, Settings) open as draggable, resizable windows. This gives it a native-desktop feel rather than a typical web dashboard. A hosted cloud option is also available at cloud.drivebase.io for users who prefer managed hosting.

## How does it work?
Drivebase acts as an abstraction layer over multiple storage backends. It integrates with provider-specific APIs (Google Drive API, S3-compatible endpoints, Dropbox OAuth, FTP) and presents a unified file-browsing and transfer interface on top. The frontend is a React/Vite/Bun application rendered as a windowed desktop OS metaphor, while the Node.js backend handles authentication, file operations, and provider orchestration.

Deployment is containerized via Docker for self-hosting, making it suitable for homelab or team environments. The e2e testing infrastructure (noted in topics) suggests a focus on reliability across provider integrations.

## Why is it important? (Core Value)
For a software engineer focused on self-hosted alternatives and developer productivity, Drivebase solves the fragmentation problem of managing files scattered across multiple cloud providers from one place. Its self-hosted Docker deployment fits directly into homelab infrastructure workflows, eliminating dependency on SaaS file managers. The unified provider API layer could also serve as a convenient integration point when building AI agents or automation pipelines that need to read/write files across different storage backends—abstracting away provider-specific SDK calls.

The desktop-OS UI concept is a creative approach to file management UX that could inspire similar patterns in other developer tools. As a self-hosted, open-source project with active releases, it's a credible option for team or personal use without per-seat licensing.

## Key Features & Technologies
- Multi-provider storage abstraction (Google Drive, S3, Dropbox, FTP, local filesystem)
- Desktop OS shell UI with draggable, resizable windowed apps
- Self-hosted via Docker with no vendor lock-in
- Built with React, Vite, Bun, and Node.js
- Cross-provider file browsing, upload, and transfer
- Optional hosted cloud tier at cloud.drivebase.io

## Difference from Others
Compared to single-provider tools (e.g., a pure S3 browser or Google Drive client), Drivebase is genuinely cloud-agnostic, treating all providers as peers under one interface. Against other multi-provider file managers like FileBrowser or Filestash, Drivebase differentiates with its desktop OS shell metaphor—windowed apps rather than a flat dashboard—which makes multi-pane workflows (e.g., comparing two provider folders side by side) more natural. The emphasis on the browser-as-desktop experience sets it apart from typical admin-panel-style file managers.

## 🏢 Organization & Credibility
- **Developer:** drivebase
- **Reputation:** Unknown
- **Stars:** 585
- **Forks:** 52
- **Recent Activity:** 0 commits in 3 months
- **Credibility Score:** 38.0/100 (Low)
- **Languages:** TypeScript, CSS, Shell, Dockerfile, HTML
- **Last Release:** 2026-06-03
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
*Source: [GitHub](https://github.com/drivebase/drivebase)*
