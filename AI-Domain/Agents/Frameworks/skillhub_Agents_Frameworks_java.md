---
source: https://github.com/iflytek/skillhub
aliases:
  - skillhub
  - iflytek/skillhub
tags: [java, java, react, ai-agent, skill-management, self-hosted, openclaw, openclaw-skills, skill, iflytek-astron, skill-hub, skill-manager]
category: Agents/Frameworks
stars: 3762
org: iflytek
primary_language: Java
languages: [Java, TypeScript, Shell, JavaScript, CSS]
credibility_score: 62.0/100
date_processed: 2026-07-05
last_release: 2026-07-03
cover: attachments/banners/skillhub_banner.png

---

![banner](attachments/banners/skillhub_banner.png)

# skillhub

> **TL;DR:** Self-hosted open-source AI agent skill registry with RBAC governance and Docker/K8s deployment.

**`iflytek/skillhub`** · ⭐ 3,762 · 🔧 Java

## What is it?
SkillHub is an enterprise-grade, open-source platform for managing AI agent skills. It enables organizations to publish, discover, and version reusable skill packages across their infrastructure. Built on Java 21 with a React frontend, it offers robust governance via RBAC and audit logging, ensuring compliance and transparency. The system supports self-hosted deployments using Docker or Kubernetes, allowing full control over the stack while maintaining production-grade reliability.

## How does it work?
SkillHub's architecture combines a Java 21 backend with a React frontend. Core services include a skill registry that stores metadata and versions, an RBAC engine that enforces access policies, and an audit logging subsystem that records all administrative actions. Skills are packaged as artifacts (likely JSON/YAML) stored in an object store. The platform exposes RESTful APIs for CRUD operations on skills, permissions, and logs. Deployment is containerized; Docker images are published to ghcr.io, and Kubernetes manifests provide production-grade orchestration. Integration with OpenClaw suggests compatibility with iflytek's agent framework, allowing seamless consumption of skills by downstream agents.

## Why is it important? (Core Value)
SkillHub solves the need for centralized, governable management of AI agent skills in enterprise environments. By providing versioned skill packages, RBAC-based access control, and audit logging, it enables organizations to securely deploy and maintain complex agent workflows without relying on proprietary SaaS solutions. For a developer focused on self-hosted infrastructure, this platform offers a production-ready stack (Java + React) that can be deployed on-premise or in a homelab, aligning perfectly with the goal of building a personal knowledge base of useful tools. The OpenClaw integration hints at compatibility with iflytek's agent framework, making it a strong candidate for inclusion in an Obsidian note under 'Agents/Frameworks' or 'AI-Domain', especially given its Apache 2.0 license and active community (Discord, DeepWiki docs).

## Key Features & Technologies
- Java 21 backend
- React frontend
- RBAC governance
- Audit logging
- Docker deployment
- Kubernetes support
- OpenClaw integration

## Difference from Others
Unlike generic metadata stores or simple registry templates, SkillHub offers full governance (RBAC + audit logs) and production-ready container images. It integrates directly with OpenClaw, iflytek's agent runtime, making it a natural fit for enterprises already using that framework. The React UI provides an out-of-the-box skill discovery portal, whereas many alternatives require custom frontend development.

## 🏢 Organization & Credibility
- **Developer:** iflytek
- **Reputation:** Unknown
- **Stars:** 3,762
- **Forks:** 551
- **Recent Activity:** 351 commits in 3 months
- **Credibility Score:** 62.0/100 (Average)
- **Languages:** Java, TypeScript, Shell, JavaScript, CSS
- **Last Release:** 2026-07-03
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
*Source: [GitHub](https://github.com/iflytek/skillhub)*
