---
source: https://github.com/cloudflare/agentic-inbox
aliases:
  - agentic-inbox
  - cloudflare/agentic-inbox
tags: [typescript, cloudflare, agents, email, workers, ai, css, url]
category: Agents
stars: 5339
org: cloudflare
primary_language: TypeScript
languages: [TypeScript, CSS, url]
credibility_score: 90.0/100
date_processed: 2026-07-05

cover: attachments/banners/agentic-inbox_banner.png

---

![banner](attachments/banners/agentic-inbox_banner.png)

# agentic-inbox

> **TL;DR:** Self-hosted email client with an AI agent running on Cloudflare Workers.

**`cloudflare/agentic-inbox`** · ⭐ 5,339 · 🔧 TypeScript

## What is it?
Agentic Inbox is a self-hosted email client built entirely on Cloudflare's infrastructure. It provides a modern web interface for sending, receiving, and managing emails while integrating a powerful AI agent that can read your inbox, search conversations, and draft replies.

The project leverages Cloudflare Email Routing to receive incoming emails, isolates each mailbox in its own Durable Object with an embedded SQLite database, and stores attachments in R2 object storage. The AI-powered agent is built using the Cloudflare Agents SDK and Workers AI, enabling intelligent email management capabilities.

## How does it work?
The architecture is cloud-native: incoming emails arrive via Cloudflare Email Routing, which directs them to a Worker that handles the mailbox logic. Each mailbox lives in its own Durable Object—a Cloudflare feature providing stateful, isolated compute—where SQLite serves as the persistent storage for email data. Attachments are stored in R2, Cloudflare's object storage solution. The AI agent runs on Workers AI and uses the Agents SDK to orchestrate tasks like reading emails, searching conversations, and drafting replies, all within the same distributed system.

When you deploy to Cloudflare (via Wrangler CLI or the Deploy button), it automatically provisions R2 and Durable Objects for your mailboxes. The project then provides a web interface for email management, with additional features like AI-driven reply suggestions.

## Why is it important? (Core Value)
This project directly addresses several of your core interests: self-hosted alternatives to SaaS products, open-source projects from major tech companies, and AI agents. As a software engineer focused on developer tools and automation, you'll appreciate that this replaces Gmail with an AI agent while running entirely on Cloudflare—a major tech company's infrastructure. It's perfect for homelab enthusiasts who want to experiment with self-hosted email clients without dealing with complex mail server setups.

The project is particularly valuable because it demonstrates how to use Cloudflare Workers as a platform for building intelligent applications, combining Email Routing with the Agents SDK and Workers AI. This gives you a concrete example of how major cloud providers are enabling new patterns for developer tools—something you can study and potentially build upon in your own projects.

## Key Features & Technologies
- Cloudflare Workers runtime
- R2 object storage for attachments
- Durable Objects as mailbox isolation
- SQLite embedded in Durable Objects
- Cloudflare Agents SDK integration
- Workers AI for email agent intelligence
- Cloudflare Email Routing

## Difference from Others
Unlike traditional self-hosted email clients that typically involve configuring mail servers (Postfix, Dovecot) or using Docker containers, Agentic Inbox runs entirely on Cloudflare's serverless infrastructure. This eliminates the need for managing servers, databases, or networking complexity—you just deploy and configure via Wrangler CLI. The integration of an AI agent is also a significant differentiator; most email clients are purely functional, while this adds intelligent capabilities to read, search, and draft replies.

Compared to Gmail or other SaaS email services, this offers full ownership and privacy with self-hosting, but with the added intelligence of an AI agent that can actively manage your inbox rather than just forwarding emails.

## 🏢 Organization & Credibility
- **Developer:** cloudflare
- **Reputation:** High (Major tech company)
- **Stars:** 5,339
- **Forks:** 725
- **Recent Activity:** 11 commits in 3 months
- **Credibility Score:** 90.0/100 (Excellent)
- **Languages:** TypeScript, CSS, url
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
*Source: [GitHub](https://github.com/cloudflare/agentic-inbox)*
