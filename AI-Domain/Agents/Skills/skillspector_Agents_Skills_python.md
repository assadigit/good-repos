---
source: https://github.com/nvidia/skillspector
aliases:
  - skillspector
  - NVIDIA/skillspector
tags: [python, python, security, ai-agent, scanner, nvidia, yara, makefile, typescript, shell]
category: Agents/Skills
stars: 12121
org: NVIDIA
primary_language: Python
languages: [Python, YARA, Makefile, TypeScript, Shell]
credibility_score: 100.0/100
date_processed: 2026-07-06

cover: attachments/banners/skillspector_banner.png

---

![banner](attachments/banners/skillspector_banner.png)

# skillspector

> **TL;DR:** Scans AI agent skills for security vulnerabilities and malicious patterns before installation.

**`NVIDIA/skillspector`** · ⭐ 12,121 · 🔧 Python

## What is it?
SkillSpector is a security scanner designed specifically for AI agent skills, which are code snippets or modules that AI agents like Claude Code, Codex CLI, and Gemini CLI execute with implicit trust. Research shows that over 26% of these skills contain vulnerabilities, and about 5% exhibit malicious intent, making thorough vetting essential before installation. The tool helps developers answer the critical question: "Is this skill safe to install?" It provides a structured analysis pipeline that can be extended for custom vulnerability patterns and integrates with NVIDIA's Pi platform for in-session scanning.

## How does it work?
SkillSpector operates through a two-stage analysis process. First, it performs fast static analysis using pattern matching (including YARA signatures) to detect known vulnerabilities across 17 categories like prompt injection, data exfiltration, and excessive agency. This stage is efficient and doesn't require LLM involvement, making it suitable for large-scale scanning. Second, the tool optionally engages an LLM for semantic evaluation, allowing deeper contextual analysis of detected issues or novel patterns that static analysis might miss. The architecture supports multiple input formats—Git repositories, URLs, zip files, directories, or single files—ensuring flexibility in how skills are provided. Additionally, SkillSpector includes a Pi extension that allows it to be installed as a tool within NVIDIA's Pi agent sessions, enabling real-time scanning during agent interactions.

## Why is it important? (Core Value)
This project directly aligns with my objectives of discovering tools that improve development workflow and finding AI agent frameworks I can integrate. As someone focused on AI/LLM tooling, particularly agents, skills, and MCP, SkillSpector offers a critical layer of security validation for AI agent skills, which are often deployed without thorough vetting. Its ability to scan multiple formats and integrate with NVIDIA's Pi platform makes it especially valuable for self-hosted environments where I can incorporate it into my own workflows. The tool's Apache 2.0 license ensures it is open-source and compatible with my preference for self-hostable software, and its high star count (12,121) indicates strong community interest and trust. By using SkillSpector, I can systematically assess the safety of AI agent skills before integrating them into projects, reducing the risk of introducing vulnerabilities or malicious behavior. This directly supports my interest in automation and workflow orchestration, as well as my desire to learn about new approaches to security in AI systems.

## Key Features & Technologies
- Multi-format input (Git repos, URLs, zip files, directories, single files)
- 68 vulnerability patterns across 17 categories (prompt injection, data exfiltration, privilege escalation, supply chain, excessive agency, output handling, system prompt leakage, memory poisoning, tool misuse, rogue agent, anti-refusal, trigger abuse, dangerous code (AST), taint tracking, YARA signatures, MCP least privilege, and MCP tool poisoning)
- Two-stage analysis (fast static analysis + optional LLM semantic evaluation)
- Pi extension for in-session scanning
- Apache 2.0 license

## Difference from Others
Compared to other AI agent security tools, SkillSpector stands out by focusing specifically on AI agent skills—a niche that most general-purpose scanners overlook. While tools like Snyk or Trivy scan code repositories for vulnerabilities, they don't specialize in the unique patterns and risks inherent in AI agent skills (e.g., prompt injection, excessive agency). Additionally, SkillSpector's integration with NVIDIA's Pi platform offers a seamless way to scan skills directly within an agent session, which is a feature not commonly found in other security tools. Its two-stage analysis approach, combining static pattern matching with optional LLM semantic evaluation, provides both speed and depth, whereas many tools rely solely on static analysis or require separate LLM calls. This makes SkillSpector particularly valuable for developers who need to vet AI agent skills before deployment.

## 🏢 Organization & Credibility
- **Developer:** NVIDIA
- **Reputation:** High (Major tech company)
- **Stars:** 12,121
- **Forks:** 999
- **Recent Activity:** 239 commits in 3 months
- **Credibility Score:** 100.0/100 (Excellent)
- **Languages:** Python, YARA, Makefile, TypeScript, Shell
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
*Source: [GitHub](https://github.com/nvidia/skillspector)*
