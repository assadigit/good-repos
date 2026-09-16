---
source: https://github.com/MadsLorentzen/ai-job-search
aliases:
  - ai-job-search
  - MadsLorentzen/ai-job-search
tags: [typescript, claude-code, ai, agents, job-search, self-hosted, python, tex, url]
category: Agents/Implementations
stars: 5345
org: MadsLorentzen
primary_language: TypeScript
languages: [TypeScript, Python, TeX, url]
credibility_score: 53.5/100
date_processed: 2026-07-05

cover: attachments/banners/ai-job-search_banner.png

---

![banner](attachments/banners/ai-job-search_banner.png)

# ai-job-search

> **TL;DR:** AI-powered job application framework built on Claude Code for evaluating jobs, tailoring CVs, writing cover letters, and interview prep.

**`MadsLorentzen/ai-job-search`** · ⭐ 5,345 · 🔧 TypeScript

## What is it?
An AI-powered job application framework built on Claude Code that automates the entire job search workflow. The project uses a structured command-based interface (/setup, /scrape, /apply) to manage profile creation, job portal scraping, and application drafting. Core workflow is language- and country-agnostic, while specific job portal integration skills are designed for the Danish market but can be swapped for other regions' job boards.

## How does it work?
The framework leverages Claude Code as its underlying AI agent to execute a multi-step pipeline: first, users configure their profile data via /setup; then /scrape searches designated job portals and presents matches with fit ratings; finally /apply evaluates each position against the user's criteria, drafts tailored CVs (in LaTeX) and cover letters, and recommends applications. The architecture is modular, allowing replacement of any job portal connector while preserving the core Claude-powered evaluation logic.

## Why is it important? (Core Value)
This project directly aligns with your interests in AI agent frameworks, developer productivity tools, and self-hosted infrastructure. It provides a language-agnostic, Claude Code-based framework you can integrate into your Obsidian vault under your 'AI-Domain' or 'Tools' categories, giving you a reusable, self-hostable workflow for job applications that respects privacy and control—key aspects of homelab philosophy. Unlike generic job search tools, it combines AI evaluation with customizable CV generation, making it a practical productivity enhancement rather than just another agent demo.

## Key Features & Technologies
- Built on Claude Code
- Modular /setup command for profile configuration
- Job portal scraping via /scrape command
- AI-driven fit scoring and recommendations
- LaTeX CV and cover letter drafting
- Language-agnostic core workflow
- Self-hostable framework

## Difference from Others
While other AI-powered job search tools may rely on generic LLM APIs or pre-built templates, this project is specifically architected around Claude Code's capabilities and uses a structured command pipeline. It also emphasizes modularity—the core evaluation logic is separated from job portal connectors, making it easier to adapt to different markets without rewriting the AI pipeline. This contrasts with monolithic solutions that bundle all functionality into one opaque service.

## 🏢 Organization & Credibility
- **Developer:** MadsLorentzen
- **Reputation:** Unknown
- **Stars:** 5,345
- **Forks:** 2290
- **Recent Activity:** 20 commits in 3 months
- **Credibility Score:** 53.5/100 (Low)
- **Languages:** TypeScript, Python, TeX, url
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
*Source: [GitHub](https://github.com/MadsLorentzen/ai-job-search)*
