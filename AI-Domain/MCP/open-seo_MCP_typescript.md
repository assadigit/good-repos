---
source: https://github.com/every-app/open-seo
aliases:
  - open-seo
  - every-app/open-seo
tags: [typescript, seo, mcp, self-hosted, dataforseo, google-search-console, backlink-analysis, keyword-research, seo-tools, site-audit, google-search-console-mcp, css]
category: MCP
stars: 4148
org: every-app
primary_language: TypeScript
languages: [TypeScript, CSS, MDX, JavaScript, url]
credibility_score: 60.5/100
date_processed: 2026-07-07
last_release: 2026-07-06
cover: attachments/banners/open-seo_banner.png

---

![banner](attachments/banners/open-seo_banner.png)

# open-seo

**`every-app/open-seo`** · ⭐ 4,148 · 🔧 TypeScript

## What is it?
OpenSEO is an open-source SEO tool positioned as a pay-as-you-go alternative to premium SaaS platforms like Semrush and Ahrefs. It functions primarily as a Model Context Protocol (MCP) server that exposes SEO analysis capabilities as tools for AI agents. The project provides pre-built skills covering keyword research, backlink analysis, site audits, and Google Search Console data retrieval. Unlike traditional SEO tools that require manual API calls or subscription payments, OpenSEO integrates directly with any MCP-compatible agent such as Claude Code, OpenClaw, or Hermes, allowing automated workflows without human intervention. The tool supports both cloud-hosted and self-hosted deployments via Docker or Cloudflare Workers, giving users full control over their data and pricing.

The project includes a modern web interface for manual SEO tasks alongside its agent capabilities. It emphasizes simplicity and focused workflows rather than the feature-bloat typical of enterprise SEO platforms. Pricing is transparent, combining free tiers with API cost references (primarily DataForSEO), making it accessible for both individual developers and organizations. The README indicates active development with a roadmap, community resources, and self-hosting guides for various deployment scenarios.

## How does it work?
OpenSEO operates as an MCP server that communicates with AI agents using the Model Context Protocol standard. When an agent queries OpenSEO, it exposes specific "skills" or tools corresponding to SEO operations such as keyword research, backlink checking, and site audits. These skills are implemented via backend services that interact with external APIs—primarily DataForSEO for comprehensive SEO metrics and Google Search Console MCP for indexing data. The architecture is designed to be modular: agents can discover available tools through standard MCP discovery protocols, then invoke them with appropriate parameters.

Self-hosting is supported through Docker containers and Cloudflare Workers deployments. The Docker implementation likely packages the backend services along with any necessary API client libraries into a portable image that can run on any infrastructure. Cloudflare Workers support enables edge deployment for lower-latency responses and reduced infrastructure costs. Users who self-host manage their own API keys and data storage, while the cloud-hosted version offers convenient access without setup. The project's README includes detailed guides for both deployment options, suggesting a well-structured codebase with clear build and run instructions.

## Why is it important? (Core Value)
OpenSEO solves two major problems: the high cost of enterprise SEO tools and the lack of native integration with AI agents. For users seeking alternatives to Semrush and Ahrefs, it offers a pay-as-you-go model that's both cheaper (free tier + transparent API costs) and more flexible (self-hosting options). Its MCP-based architecture is particularly valuable for developers and researchers working with AI agents—it enables automated SEO workflows without requiring custom API wrappers or manual data extraction. The project aligns perfectly with interests in self-hostable software, open-source alternatives to SaaS products, and AI/LLM tooling.

For your specific context as a software engineer focused on AI agents and developer productivity, OpenSEO provides immediate utility: it's an MCP server you can integrate into your agent ecosystem right away using pre-built skills. You could build custom SEO analysis agents that leverage OpenSEO's tools for keyword research, backlink tracking, or site audits as part of larger automation pipelines. The self-hosting capability means you control the data and pricing, which matters when building production-ready systems. Additionally, the transparent API cost model helps with budget planning in agent deployments.

## Key Features & Technologies
- MCP server exposing SEO analysis skills for AI agents
- DataForSEO API integration for keyword research and backlink data
- Google Search Console MCP support for indexing metrics
- Self-hosting via Docker containers or Cloudflare Workers
- Modern web UI with focused SEO workflows
- Pay-as-you-go pricing with transparent API cost references
- Pre-built skills plus custom skill development capability

## Difference from Others
Compared to Semrush and Ahrefs, OpenSEO is fundamentally different: it's open-source, self-hostable, and built specifically for MCP agent integration rather than manual dashboard usage. While other open-source SEO tools exist (like simple crawlers or backlink checkers), they typically lack the structured skill interface that MCP provides—no standardized discovery protocol, no tool invocation via natural language prompts. OpenSEO fills this gap by implementing the MCP standard for its skills, allowing any compatible agent to use them without custom adapters.

The project also differs from other self-hosted SEO alternatives in its primary focus: it centers on agent automation rather than just providing raw data endpoints. Some tools offer API access but require developers to build their own orchestration logic; OpenSEO abstracts this through MCP skills that agents can call directly. This makes it uniquely positioned for users building AI-driven SEO workflows who want both flexibility (self-hosting) and ease of integration (MCP standard).

## 🏢 Organization & Credibility
- **Developer:** every-app
- **Reputation:** Unknown
- **Stars:** 4,148
- **Forks:** 460
- **Recent Activity:** 272 commits in 3 months
- **Credibility Score:** 60.5/100 (Average)
- **Languages:** TypeScript, CSS, MDX, JavaScript, url
- **Last Release:** 2026-07-06
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
*Source: [GitHub](https://github.com/every-app/open-seo)*
