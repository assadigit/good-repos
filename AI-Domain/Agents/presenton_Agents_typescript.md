---
source: https://github.com/presenton/presenton
aliases:
  - presenton
  - presenton/presenton
tags: [typescript, python, ai-agent, api, self-hosted, docker, powerpoint-automation, powerpoint-free, powerpoint-generation, presentation, ai-presentation, gamma]
category: Agents
stars: 8929
org: presenton
primary_language: TypeScript
languages: [TypeScript, Python, JavaScript, CSS, Shell]
credibility_score: 67.0/100
date_processed: 2026-07-05
last_release: 2026-07-03
cover: attachments/banners/presenton_banner.png

---

![banner](attachments/banners/presenton_banner.png)

# presenton

> **TL;DR:** Self-hosted AI presentation generator API offering alternatives to Gamma, Canva, Beautiful AI, and Decktopus.

**`presenton/presenton`** · ⭐ 8,929 · 🔧 TypeScript

## What is it?
Presenton is an open-source AI-powered tool that generates, edits, and exports presentations programmatically. It serves as a self-hosted alternative to commercial services like Gamma, Canva, Beautiful AI, and Decktopus, giving users full control over their data and model choices without SaaS lock-in or subscription fees. The project exposes a REST API for interacting with its AI generation engine, allowing developers to send prompts, outlines, or content specifications and receive back formatted presentation files (e.g., PPTX, PDF) or editable slide decks.

Key capabilities include interpreting user-provided text or structured inputs to produce slide content, selecting appropriate visuals, and applying layouts automatically. It supports multiple AI model providers, enabling users to plug in their preferred LLM or vision-language models for generation tasks. The codebase is Apache 2.0 licensed, ensuring freedom to modify and redistribute.

Presenton runs natively on Windows, macOS, and Linux, packaged as a Docker container for easy deployment. This cross-platform compatibility makes it suitable for both personal homelab setups and enterprise environments where self-hosting policies may be required.

## How does it work?
Presenton is architected as a self-contained service that runs inside a Docker container, exposing an HTTP API endpoint for presentation generation and manipulation. When a client sends a request (e.g., a JSON payload containing a prompt, outline, or content), the service routes it to its internal AI generation pipeline, which likely leverages one of several configurable model providers (LLMs, vision-language models). The generation process involves parsing the input, invoking the selected model to produce slide content and visuals, then assembling the output into a standard presentation format.

The API also supports editing existing presentations—clients can upload or reference prior slides and modify them via additional prompts. Export functionality allows downloading results as various formats (PowerPoint, PDF, etc.). Because the core logic is containerized, users can deploy it on any supported OS without installing dependencies manually, making it straightforward to integrate into custom workflows or orchestration systems.

## Why is it important? (Core Value)
For a software engineer and researcher focused on AI agents, developer tools, and automation, Presenton directly addresses several key interests: it provides a self-hostable alternative to SaaS presentation tools, aligning with the goal of finding open-source, homelab-friendly solutions that avoid vendor lock-in. Its API-first design makes it easy to embed into larger automation pipelines or build custom presentation-generation agents on top of existing LLM toolkits.

The project's Apache 2.0 license ensures free use and modification, which is valuable for building a personal knowledge base of reusable tools. Additionally, its support for multiple model providers gives flexibility in choosing AI backends—important when experimenting with different LLMs or vision-language models as part of research or development work. By offering full control over data and models, Presenton enables secure, privacy-conscious workflows, especially useful for those concerned about data leakage to third-party SaaS services.

## Key Features & Technologies
- Self-hosted via Docker
- AI-powered presentation generation
- REST API for creation/editing/export
- Multiple model providers support
- Apache 2.0 open-source license
- Cross-platform (Windows/macOS/Linux)
- No SaaS lock-in

## Difference from Others
Presenton stands apart from commercial alternatives like Gamma, Canva, Beautiful AI, and Decktopus by being fully open-source and self-hostable. Those services typically require subscriptions, store user data on their servers, and limit customization. Presenton removes these constraints entirely: users retain ownership of their presentations, can plug in any AI model they prefer, and have complete control over deployment environments.

Another key distinction is its API-first approach. While Gamma and Canva offer web UIs with limited programmatic access, Presenton exposes a clean REST API designed for integration into custom workflows. This makes it suitable for developers who want to build presentation-generation agents or automate slide creation as part of larger software pipelines.

Furthermore, Presenton's Docker packaging simplifies deployment compared to the often complex installation requirements of other tools, and its cross-platform support means it can run in homelab setups, cloud VMs, or on-premises servers without vendor-specific dependencies.

## 🏢 Organization & Credibility
- **Developer:** presenton
- **Reputation:** Unknown
- **Stars:** 8,929
- **Forks:** 1393
- **Recent Activity:** 525 commits in 3 months
- **Credibility Score:** 67.0/100 (Average)
- **Languages:** TypeScript, Python, JavaScript, CSS, Shell
- **Last Release:** 2026-07-03
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
*Source: [GitHub](https://github.com/presenton/presenton)*
