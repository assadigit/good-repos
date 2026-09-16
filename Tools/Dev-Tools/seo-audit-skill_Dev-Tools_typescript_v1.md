---
source: https://github.com/seo-skills/seo-audit-skill
aliases:
  - seo-audit-skill
  - seo-skills/seo-audit-skill
tags: [typescript, seo, cli, electron, claude-code-skill, website-audit, claude, claude-skills, seo-audit, seo-audit-skill, css, javascript]
category: Dev-Tools
stars: 381
org: seo-skills
primary_language: TypeScript
languages: [TypeScript, CSS, JavaScript, HTML, url]
credibility_score: 41.0/100
date_processed: 2026-08-19



---

# seo-audit-skill

> **TL;DR:** CLI and Electron tool that audits websites against 251 SEO rules across 20 categories, with a Claude Code skill for AI-assisted audits.

**`seo-skills/seo-audit-skill`** · ⭐ 381 · 🔧 TypeScript

## What is it?
SEOmator (seo-audit-skill) is a comprehensive, open-source SEO audit tool that scans any website against 251 rules across 20 categories, including technical SEO, Core Web Vitals, structured data, accessibility, security headers, and AI/GEO search readiness. It produces a prioritized, actionable report with findings ranked by severity and impact.

The project ships in three formats: a command-line tool (npm package @seomator/seo-audit), an Electron desktop app with a visual dashboard, and a Claude Code skill that lets you run audits directly inside an AI coding agent. It also offers a free browser-based web tool at seomator.com for those who prefer a visual interface.

The tool supports multiple output formats, CI/CD integration, and programmatic usage via its Node.js API, making it suitable for both one-off audits and automated pipelines.

## How does it work?
The core engine is a Node.js package that fetches and analyzes target websites, evaluating them against a rules engine covering 20 SEO categories. Each rule checks a specific best practice (e.g., meta tags, canonical URLs, Core Web Vitals thresholds, structured data validity, security headers like CSP and HSTS). Results are scored, prioritized, and rendered into a report.

The tool is distributed as an npm CLI for terminal use, an Electron desktop app for a visual dashboard, and a Claude Code skill that wraps the CLI so an AI agent can invoke audits and interpret results conversationally. CI/CD integration allows the audit to run as part of deployment pipelines, and a programmatic API enables embedding audits in custom workflows.

## Why is it important? (Core Value)
For a software engineer focused on developer tools and AI agent skills, this project is valuable on two fronts. First, it provides a self-hostable, open-source alternative to expensive SaaS SEO tools (Screaming Frog, Ahrefs, etc.), aligning with the interest in self-hostable alternatives to SaaS products. Second, the Claude Code skill component makes it a concrete example of how domain-specific tools are being packaged as agent skills, which is directly relevant to exploring AI/LLM tooling and agent skill architectures.

The CI/CD integration and programmatic API also make it a practical addition to a development workflow for automating SEO checks in CI pipelines, fitting the interest in developer productivity and automation.

## Key Features & Technologies
- 251 audit rules across 20 categories (technical SEO, Core Web Vitals, structured data, accessibility, security headers, AI/GEO readiness)
- Ships as CLI (npm), Electron desktop app, and Claude Code skill
- CI/CD integration and programmatic Node.js API for automated pipelines
- Prioritized, actionable report output with severity ranking
- MIT-licensed and open-source, installable via @seomator/seo-audit on npm
- Free browser-based web tool at seomator.com for visual analysis

## Difference from Others
Unlike Chrome Lighthouse, which focuses primarily on performance, accessibility, and best practices, SEOmator targets a much broader SEO-specific rule set (structured data, security headers, GEO/AI search readiness) and is purpose-built for SEO auditing rather than general web performance. Compared to SaaS SEO platforms like Screaming Frog or Ahrefs, it is fully open-source, self-hostable, and integrates directly into developer workflows via CLI and CI/CD rather than requiring a paid subscription and browser-based dashboard.

The inclusion of a Claude Code skill as a first-class delivery format is a distinguishing feature: most SEO tools do not offer an agent-integrated interface, making this one of the early examples of domain tools being packaged for AI coding agents.

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
