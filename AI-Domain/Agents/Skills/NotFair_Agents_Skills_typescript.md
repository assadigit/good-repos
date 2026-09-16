---
source: https://github.com/nowork-studio/NotFair
aliases:
  - NotFair
  - nowork-studio/NotFair
tags: [typescript, claude-skills, mcp, seo, google-ads, meta-ads, claude-code-plugin, geo, googleads, metaads, googleadsmcp, python]
category: Agents/Skills
stars: 3063
org: nowork-studio
primary_language: TypeScript
languages: [TypeScript, Python, CSS, Shell, JavaScript]
credibility_score: 62.0/100
date_processed: 2026-07-06

cover: attachments/banners/NotFair_banner.png

---

![banner](attachments/banners/NotFair_banner.png)

# NotFair

> **TL;DR:** Open-source Claude Code skills for SEO, Google & Meta Ads auditing and fixing.

**`nowork-studio/NotFair`** · ⭐ 3,063 · 🔧 TypeScript

## What is it?
NotFair is an open-source plugin that provides AI agents (specifically Claude Code) with direct access to Google Search Console, Google Ads, and Meta Ads (Facebook + Instagram). It enables data-driven decisions by analyzing traffic, surfacing ranking issues, finding wasted ad spend, diagnosing creative fatigue, and suggesting fixes—going as far as rewriting meta tags, fixing headings, and adding structured data when repository access is granted.

The project offers both a CLI interface (the actual skills that run inside AI agent hosts) and a companion web app (notfair.co). Both sides share the same engine, so audits performed via CLI use identical tooling as those executed through the browser UI. This unified architecture ensures consistency across different usage contexts while maintaining full transparency and control over the data flow.

NotFair is free, open-source, and installs quickly (30 seconds). It's maintained by nowork-studio and has garnered significant community interest with 3,063 stars and 374 forks, indicating strong adoption among developers seeking reliable SEO and advertising analytics tools that integrate seamlessly with modern AI agent ecosystems.

## How does it work?
NotFair leverages Claude Code—a specialized AI agent platform—to execute its skills directly within agent workflows. The plugin implements Model Context Protocol (MCP) servers that expose Google Ads, Meta Ads, and Google Search Console APIs to the agent, enabling natural language queries like `/notfair:google-ads-audit` to trigger authenticated requests and retrieve real-time data. Authentication is handled via OAuth flows integrated into the MCP layer, allowing agents to connect to users' Google and Meta accounts without storing credentials locally.

The architecture is split between CLI and web interfaces but shares a single underlying engine. The CLI side runs inside Claude Code (or any compatible AI agent host), while the web app provides a browser UI for signing in once and connecting accounts. Both sides communicate through the same data structures and tool definitions, ensuring that an audit run from the CLI produces identical results to one executed via the web app. This design choice reduces duplication and simplifies maintenance, making NotFair both robust and developer-friendly.

## Why is it important? (Core Value)
The core value of NotFair lies in bridging the gap between AI agents and real-world advertising/SEO data. Most existing tools are either proprietary SaaS platforms (like Google's own dashboards) or generic scraping utilities that lack deep API integration. NotFair offers an open-source alternative that gives agents direct, authenticated access to Google Search Console, Google Ads, and Meta Ads—enabling data-driven decisions without relying on opaque dashboards. This is particularly valuable for developers building autonomous agents who need reliable, up-to-date advertising metrics to optimize campaigns, fix ranking issues, and reduce wasted ad spend.

For the specific user context: As a software engineer and researcher focused on AI agents, developer tools, and automation, NotFair aligns perfectly with your objectives. It provides self-hostable MCP-based skills you can integrate into your own agent workflows, giving you full control over data and avoiding vendor lock-in. The open-source nature means you can audit the code, extend its capabilities (e.g., adding new Google APIs), and potentially contribute improvements. Additionally, the project's focus on SEO and advertising analytics directly supports your interest in developer productivity tools and automation—particularly the ability to automate meta tag rewriting, heading fixes, and structured data additions. This makes NotFair a high-confidence addition to your knowledge base under categories like AI-Domain or Tools, with strong credibility given its 3,063 stars and active community (Discord channel).

## Key Features & Technologies
- Claude Code integration
- Model Context Protocol (MCP) servers
- Google Search Console API access
- Google Ads API access
- Meta Ads (Facebook + Instagram) API access
- CLI and web interface with shared engine
- Open-source, self-hostable

## Difference from Others
NotFair distinguishes itself from traditional SEO tools like Screaming Frog or generic scraping bots by offering native API-level access to Google and Meta advertising platforms—capabilities that most open-source alternatives simply don't provide. While many MCP servers expose only read-only data, NotFair can also execute write operations (meta tag rewriting, heading fixes) when the agent has repository access, making it a truly actionable tool rather than just a passive observer. Compared to commercial SaaS solutions like Semrush or Moz, NotFair is free, open-source, and integrates directly with AI agents via Claude Code, enabling autonomous workflows without subscription fees.

## 🏢 Organization & Credibility
- **Developer:** nowork-studio
- **Reputation:** Unknown
- **Stars:** 3,063
- **Forks:** 374
- **Recent Activity:** 233 commits in 3 months
- **Credibility Score:** 62.0/100 (Average)
- **Languages:** TypeScript, Python, CSS, Shell, JavaScript
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
*Source: [GitHub](https://github.com/nowork-studio/NotFair)*
