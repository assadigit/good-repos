---
source: https://github.com/C4illin/ConvertX
aliases:
  - ConvertX
  - C4illin/ConvertX
tags: [typescript, typescript, bun, docker, file-conversion, self-hosted, elysia, file-converter, conversion, convert, converter, document-conversion]
category: Dev-Tools
stars: 17289
org: C4illin
primary_language: TypeScript
languages: [TypeScript, JavaScript, Dockerfile, CSS, url]
credibility_score: 60.0/100
date_processed: 2026-07-22
last_release: 2026-06-21
cover: attachments/banners/ConvertX_banner.png

---

![banner](attachments/banners/ConvertX_banner.png)

# ConvertX

> **TL;DR:** Self-hosted web file converter supporting 1000+ formats for PDFs, images, documents, and more.

**`C4illin/ConvertX`** · ⭐ 17,289 · 🔧 TypeScript

## What is it?
ConvertX is a fully self-hosted online file conversion service that provides a free alternative to SaaS converters like CloudConvert or Zamzar. It runs entirely on your infrastructure, giving you complete control over data privacy and eliminating per-use fees. The project maintains a web UI for easy access while also providing CLI usage options for scripting.

The service supports over 1000 file formats including PDFs, images (PNG, JPEG, WEBP), documents, and more. It's built with Bun runtime and Elysia framework, both of which are lightweight modern options that make the converter fast and efficient. The UI is styled with TailwindCSS for a clean experience.

Docker support is emphasized, allowing deployment as a container image published to ghcr.io and Docker Hub, making it easy to integrate into homelab setups or production environments.

## How does it work?
ConvertX likely operates as a Node/Bun server that exposes a simple API for file conversion requests. When a user uploads a file via the web UI or CLI, the server routes the request to appropriate backend tools (such as pdf-lib, ffmpeg, or other format-specific libraries) to perform the conversion. The result is then returned with metadata about success and output size.

The architecture emphasizes simplicity and speed: Bun provides fast JS execution, Elysia offers a minimal framework for handling HTTP requests, and Docker packaging ensures consistent deployment across environments. TailwindCSS is used only for the frontend styling, keeping the backend footprint small.

## Why is it important? (Core Value)
This project directly aligns with your objectives of finding self-hostable alternatives to SaaS products. ConvertX gives you full control over file conversions without paying per-use fees or worrying about privacy when uploading sensitive documents. As someone interested in homelab infrastructure and developer productivity tools, the Docker support makes it easy to deploy as a persistent service or container, and the CLI usage enables automation of conversion tasks.

The open-source nature means you can inspect exactly what's happening with your files, verify data handling practices, and even extend functionality if needed. For users who value privacy and want to avoid vendor lock-in on file conversion services, this is an ideal solution.

## Key Features & Technologies
- Docker support with published containers
- Bun runtime for fast execution
- Elysia framework for lightweight HTTP handling
- TailwindCSS styled web UI
- CLI usage options for scripting
- Supports 1000+ file formats
- Self-hosted (open-source)

## Difference from Others
Unlike many converters that remain SaaS-only or have limited format support, ConvertX is open-source and self-hostable, giving you full control over data privacy and costs. It uses modern runtimes (Bun) rather than Node.js alone, which can provide better performance for heavy conversion workloads. The Docker-first packaging approach also stands out compared to converters that rely on cloud APIs without container support.

## 🏢 Organization & Credibility
- **Developer:** C4illin
- **Reputation:** Unknown
- **Stars:** 17,289
- **Forks:** 947
- **Recent Activity:** 7 commits in 3 months
- **Credibility Score:** 60.0/100 (Average)
- **Languages:** TypeScript, JavaScript, Dockerfile, CSS, url
- **Last Release:** 2026-06-21
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
*Source: [GitHub](https://github.com/C4illin/ConvertX)*
