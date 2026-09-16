---
source: https://github.com/seo-skills/seo-audit-skill
aliases:
  - seo-audit-skill
  - seo-skills/seo-audit-skill
tags: [typescript, seo, cli, claude-code, audit, nodejs, claude, claude-skills, seo-audit, website-audit, seo-audit-skill, css]
category: Dev-Tools
stars: 381
org: seo-skills
primary_language: TypeScript
languages: [TypeScript, CSS, JavaScript, HTML, url]
credibility_score: 41.0/100
date_processed: 2026-08-19



---

# seo-audit-skill

> **TL;DR:** CLI and Electron tool auditing websites against 251 SEO, CWV, accessibility, and security rules; ships as a Claude Code skill.

**`seo-skills/seo-audit-skill`** · ⭐ 381 · 🔧 TypeScript

## What is it?
SEOmator (seo-audit-skill) is a comprehensive SEO audit tool that scans any website against 251 rules across 20 categories, covering technical SEO, Core Web Vitals, structured data, accessibility, security headers, and AI/GEO search readiness. It returns a prioritized, actionable report with findings ranked by severity and impact.

The tool is distributed in three formats: a Node.js command-line tool (npm package @seomator/seo-audit), an Electron desktop app with a visual dashboard, and a Claude Code skill that lets you run audits directly inside an AI coding agent. A free browser-based version is also available at seomator.com.

The tool supports CI/CD integration, programmatic usage via API, and multiple output formats, making it suitable for both one-off audits and automated pipeline checks.

## How does it work?
The tool is built on Node.js and published as an npm package. It fetches a target website, runs its 251 audit rules across 20 categories (technical SEO, Core Web Vitals, structured data, accessibility, security headers, AI/GEO readiness), and generates a prioritized report. The rules check for things like meta tags, canonical URLs, structured data validity, Lighthouse-style Core Web Vitals metrics, HTTP security headers, and accessibility attributes.

The Claude Code skill variant wraps the same audit engine as a skill definition, allowing Claude Code to invoke the audit as a tool call within an agent session. The Electron app provides a GUI frontend over the same rule engine. CI/CD integration means the CLI can be dropped into GitHub Actions or similar pipelines to gate deployments on SEO scores.

## Why is it important? (Core Value)
This project is valuable because it consolidates a large, rule-based SEO audit into a single CLI/Electron/skill package rather than requiring separate tools for Lighthouse, meta-tag checks, accessibility scans, and security header validation. For the user described, the Claude Code skill format is particularly relevant: it slots directly into an AI agent workflow, letting an agent run a full SEO audit as part of a development task without leaving the agent context. This aligns with the user's interest in AI/LLM tooling, agent skills, and developer productivity tools. The self-contained npm package also fits the user's preference for self-hostable, open-source alternatives to SaaS SEO platforms.

## Key Features & Technologies
- 251 audit rules across 20 categories (technical SEO, CWV, structured data, accessibility, security, AI/GEO readiness)
- Distributed as CLI, Electron desktop app, and Claude Code skill
- Node.js / npm package (@seomator/seo-audit) with programmatic API
- CI/CD integration for automated SEO scoring in pipelines
- Prioritized, actionable report output with severity ranking
- Free browser-based tool at seomator.com for visual dashboards
- MIT-licensed, open-source

## Difference from Others
Most SEO audit tools are either SaaS dashboards (Ahrefs, Semrush, Screaming Frog) or single-purpose CLI tools (Lighthouse for performance, axe-core for accessibility). SEOmator differentiates by bundling 251 rules into one tool and, critically, shipping as a Claude Code skill—making it one of the few SEO tools that can be invoked as a sub-agent capability within an AI coding session. This means an AI agent can run a full SEO audit mid-task without the developer switching contexts. The Electron app also provides a self-hosted visual alternative to SaaS SEO platforms, which is rare in the open-source SEO tooling space.

## 🏢 Organization & Credibility
- **Developer:** seo-skills
- **Reputation:** Unknown
- **Stars:** 381
- **Forks:** 51
- **Recent Activity:** 3 commits in 3 months
- **Credibility Score:** 41.0/100 (Low)
- **Languages:** TypeScript, CSS, JavaScript, HTML, url
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
*Source: [GitHub](https://github.com/seo-skills/seo-audit-skill)*
