---
source: https://github.com/pewdiepie-archdaemon/odysseus
aliases:
  - odysseus
  - pewdiepie-archdaemon/odysseus
tags: [python, python, docker, ai, agents, mcp, javascript, css, html, shell]
category: Agents/Implementations
stars: 81142
org: pewdiepie-archdaemon
primary_language: Python
languages: [Python, JavaScript, CSS, HTML, Shell]
credibility_score: 69.0/100
date_processed: 2026-07-06

cover: attachments/banners/odysseus_banner.png

---

![banner](attachments/banners/odysseus_banner.png)

# odysseus

**`pewdiepie-archdaemon/odysseus`** · ⭐ 81,142 · 🔧 Python

## What is it?
Odysseus is a self-hosted AI workspace designed to consolidate chat, agent orchestration, research, document management, email, notes, calendar, and local model workflows into a unified platform. It allows users to run both local models (e.g., Ollama) and API-based models (e.g., OpenAI, Anthropic) within the same environment, with support for tools, MCP servers, file attachments, shell access, skills, and persistent memory.

The workspace is containerized using Docker Compose, making it straightforward to spin up via a single docker compose command. It supports native installs on Linux, Windows, and macOS, with optional HTTPS termination. Users can access the UI at localhost:7000, and the first admin password is printed in the compose logs for initial setup.

Key features include Chat + Agents (local/API models, tools, MCP, files, shell, skills, memory), a hardware-aware model cookbook that recommends appropriate models based on available GPU/CPU resources, Deep Research capabilities, email integration, notes and calendar management, document handling, and self-hosted data privacy.

## How does it work?
Odysseus is containerized using Docker Compose, which orchestrates a set of services (frontend, backend, model server, etc.) into a single workspace. Users clone the repo and copy .env.example to .env, then run docker compose up -d --build. The compose file defines volumes for persistent data and network isolation. The UI is served at localhost:7000, built from a static frontend that communicates with a backend API.

Model handling is split between local inference (e.g., Ollama containerized alongside the workspace) and remote API calls (OpenAI, Anthropic, etc.). The project includes a hardware-aware cookbook that queries GPU/CPU availability to recommend appropriate models and manage downloads/serving. MCP support is implemented via integration with the Model Context Protocol, allowing the workspace to load external MCP servers as tools for agents. Persistent memory is stored in Docker volumes, accessible to both local and remote model calls.

## Why is it important? (Core Value)
Odysseus addresses the growing demand for self-hosted AI solutions by providing a comprehensive workspace that combines chat, agent orchestration, research, document management, email, notes, and calendar under one roof. Its hardware-aware model cookbook and support for both local and API-based models give users flexibility to tailor inference to their infrastructure—crucial for avoiding vendor lock-in and maintaining data privacy.

For a software engineer and researcher focused on AI agents, developer tools, and automation, Odysseus offers a self-contained platform that can be deployed on a homelab without relying on SaaS services. It directly supports the user's objectives of finding self-hostable alternatives to SaaS products and curating useful tools/frameworks. The ability to run local models (e.g., Ollama) alongside remote APIs means the workspace can serve as a sandbox for experimenting with new AI techniques while keeping sensitive data on-premises. Additionally, the inclusion of email, notes, and calendar suggests it can act as a personal productivity hub, which would be valuable for an individual managing research workflows.

## Key Features & Technologies
- Chat + Agents (local/API models, tools, MCP, files, shell, skills, memory)
- Hardware-aware model cookbook
- Docker Compose deployment
- HTTPS support
- Native Linux/Windows/macOS installs
- Self-hosted data privacy
- MCP integration

## Difference from Others
Odysseus stands out among self-hosted AI workspaces by consolidating chat, agent orchestration, research, email, notes, and calendar into a single platform rather than focusing solely on a chat UI like OpenWebUI or AnythingLLM. Its hardware-aware model cookbook provides automated recommendations for local vs. API models based on available GPU/CPU resources—a feature rarely seen in other projects that expect users to manually configure model serving. The built-in MCP support and Docker Compose deployment also simplify extending the workspace with custom tools, whereas many alternatives require manual integration or lack containerization.

## 🏢 Organization & Credibility
- **Developer:** pewdiepie-archdaemon
- **Reputation:** Unknown
- **Stars:** 81,142
- **Forks:** 10641
- **Recent Activity:** 1877 commits in 3 months
- **Credibility Score:** 69.0/100 (Average)
- **Languages:** Python, JavaScript, CSS, HTML, Shell
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
*Source: [GitHub](https://github.com/pewdiepie-archdaemon/odysseus)*
