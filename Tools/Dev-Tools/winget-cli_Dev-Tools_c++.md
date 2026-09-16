---
source: https://github.com/microsoft/winget-cli
aliases:
  - winget-cli
  - microsoft/winget-cli
tags: [c++, windows, cli, package-manager, microsoft, automation, winget, command-line, c#, powershell, c, javascript]
category: Dev-Tools
stars: 26127
org: microsoft
primary_language: C++
languages: [C++, C#, PowerShell, C, JavaScript]
credibility_score: 98.5/100
date_processed: 2026-07-06
last_release: 2026-06-24
cover: attachments/banners/winget-cli_banner.png

---

![banner](attachments/banners/winget-cli_banner.png)

# winget-cli

> **TL;DR:** Windows Package Manager CLI with Microsoft Store and community repository sources for installing apps on Windows 10/11.

**`microsoft/winget-cli`** · ⭐ 26,127 · 🔧 C++

## What is it?
WinGet is the official Windows Package Manager from Microsoft, providing a command-line interface (CLI), PowerShell modules, and a COM API for installing software on Windows. It queries multiple package sources—including the Microsoft Store (msstore) and the community-driven winget repository—to locate available applications and manage installations. The tool is designed to streamline software deployment across Windows 10 and 11 systems.

## How does it work?
The client primarily runs as a C#-based CLI executable distributed via the Microsoft App Installer store. It communicates with package sources through REST APIs or direct file system access, retrieves package metadata, resolves dependencies, and triggers installation mechanisms (e.g., MSI installers, EXE downloads). PowerShell modules expose additional scripting capabilities, while the COM API enables programmatic control from other applications.

## Why is it important? (Core Value)
For a researcher curating developer tools and open-source projects from major tech companies, winget-cli represents Microsoft's official package management solution for Windows. It offers a standardized way to install software without relying on third-party sources, aligning with the user's interest in credible, enterprise-backed tools. Although not self-hostable (it integrates with the Microsoft Store), it is highly relevant for automating software provisioning in developer environments and can be scripted into workflow orchestration pipelines.

## Key Features & Technologies
- CLI interface
- PowerShell modules
- COM API
- Microsoft Store integration
- community repository source

## Difference from Others
Compared to Chocolatey (the other major Windows package manager), winget is officially backed by Microsoft and integrates directly with the Microsoft Store, making it more suitable for enterprise environments. It also provides PowerShell modules and a COM API, which are absent from Chocolatey. Additionally, winget supports group policy configuration, allowing administrators to control sources without manual intervention.

## 🏢 Organization & Credibility
- **Developer:** microsoft
- **Reputation:** High (Major tech company)
- **Stars:** 26,127
- **Forks:** 1763
- **Recent Activity:** 64 commits in 3 months
- **Credibility Score:** 98.5/100 (Excellent)
- **Languages:** C++, C#, PowerShell, C, JavaScript
- **Last Release:** 2026-06-24
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
*Source: [GitHub](https://github.com/microsoft/winget-cli)*
