---
source: https://github.com/garrytan/gbrain
aliases:
  - gbrain
  - garrytan/gbrain
tags: [typescript, python, llm, agent, knowledge-graph, synthesis, shell, javascript, plpgsql, html]
category: Agents/Skills
stars: 25276
org: garrytan
primary_language: TypeScript
languages: [TypeScript, Shell, JavaScript, PLpgSQL, HTML]
credibility_score: 70.5/100
date_processed: 2026-07-07

cover: attachments/banners/gbrain_banner.png

---

![banner](attachments/banners/gbrain_banner.png)

# gbrain

**`garrytan/gbrain`** · ⭐ 25,276 · 🔧 TypeScript

## What is it?
GBrain is a production-grade knowledge brain built by Garry Tan (YC President/CEO) that transforms raw web pages into synthesized answers via graph traversal, entity linking, and gap analysis. It runs autonomously with cron jobs, ingesting meetings, emails, tweets, voice calls, and original ideas while you sleep, then consolidates memory overnight.

Designed as a brain layer for AI agents, it can be used standalone or wired into Claude Code/Codex as a supercharged retrieval layer. It supports multi-user access with per-login scopes, fuzz-tested to prevent data leaks, and serves as an institutional memory for teams — the "company-brain" shape YC added to its Request for Startups.

Currently powering Garry's OpenClaw and Hermes deployments, it indexes 146,646 pages across 24,585 people and 5,339 companies, demonstrating enterprise-scale readiness for self-hosted AI agent stacks.

## How does it work?
GBrain ingests raw content via scheduled cron jobs that pull web pages, emails, tweets, and voice calls (transcribed with Whisper). Each piece is parsed and entities (people, companies) are extracted using LLM-powered classification, then stored in a hybrid retrieval layer combining a vector store for semantic similarity and a graph database for entity relationships. When a query arrives, GBrain traverses the graph, synthesizes answers, fixes citations, and consolidates memory overnight. Access control enforces per-login scopes, ensuring zero leaks across all read paths.

## Why is it important? (Core Value)
GBrain solves the amnesiac agent problem by providing a self-hosted synthesis layer that turns raw search results into curated answers, directly addressing your interest in AI/LLM tooling and self-hostable alternatives to SaaS retrieval services. It offers production-grade multi-user isolation without data leaks, which aligns with your goal of building secure team knowledge bases. As an opinionated brain built by YC's Garry Tan, it demonstrates enterprise-scale readiness, making it a credible reference for your personal knowledge base and a potential component in your MCP or agent frameworks.

## Key Features & Technologies
- Synthesizes answers from raw web pages
- Graph traversal across people/companies
- Ingests emails, meetings, tweets, voice calls
- Self-hosted multi-user knowledge graph
- Cron-driven autonomous data ingestion
- Citation fixing and memory consolidation
- Zero-leak access isolation

## Difference from Others
Unlike generic search wrappers or chatbot APIs, GBrain provides synthesized answers and graph-based entity linking, runs autonomously with cron jobs, and offers scoped multi-user access, making it a production brain layer rather than a simple retrieval tool. It also integrates directly with Y Combinator's own agent stack (OpenClaw/Hermes) and is self-hosted, giving you full control over data privacy and scaling.

## 🏢 Organization & Credibility
- **Developer:** garrytan
- **Reputation:** Unknown
- **Stars:** 25,276
- **Forks:** 3649
- **Recent Activity:** 331 commits in 3 months
- **Credibility Score:** 70.5/100 (Average)
- **Languages:** TypeScript, Shell, JavaScript, PLpgSQL, HTML
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
*Source: [GitHub](https://github.com/garrytan/gbrain)*
