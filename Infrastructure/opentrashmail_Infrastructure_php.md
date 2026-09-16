---
source: https://github.com/HaschekSolutions/opentrashmail
aliases:
  - opentrashmail
  - HaschekSolutions/opentrashmail
tags: [php, python, php, docker, selfhosted, email, trashmail, email-as-rss, email-as-api, shell, css, dockerfile]
category: Infrastructure
stars: 905
org: HaschekSolutions
primary_language: PHP
languages: [PHP, Python, Shell, CSS, Dockerfile]
credibility_score: 41.0/100
date_processed: 2026-07-22

cover: attachments/banners/opentrashmail_banner.png

---

![banner](attachments/banners/opentrashmail_banner.png)

# opentrashmail

> **TL;DR:** Self-hosted disposable email service with built-in mail server and API access.

**`HaschekSolutions/opentrashmail`** · ⭐ 905 · 🔧 PHP

## What is it?
Open Trashmail is an open-source self-hosted trashmail solution that provides temporary/disposable email addresses directly from your own infrastructure. Unlike most trashmail services that simply forward emails to your real inbox, this project ships its own mail server, giving you full control over the entire stack.

The project offers multiple access methods: RSS feeds for retrieving disposable address emails (email-as-rss), and REST APIs for programmatic access (email-as-api). This makes it particularly useful for privacy-conscious users who want to avoid exposing their primary email addresses when signing up for services, as well as developers building personal dashboards or automation workflows that need to manage multiple temporary addresses.

## How does it work?
The architecture combines PHP 8.1+ for the web interface built with htmx (for client-side interactivity), Python 3.11 for backend processing, and Docker containerization for deployment. The mail server component handles email storage, retrieval, and forwarding operations. Emails received at disposable addresses are stored and can be accessed either through RSS feeds (which periodically fetch new emails) or via REST APIs that provide programmatic access to message data.

## Why is it important? (Core Value)
This project directly aligns with your interests in self-hosted software and homelab infrastructure. For privacy-focused development work, it solves the problem of needing disposable email addresses without relying on SaaS services like Mailinator. The email-as-API feature could be integrated into personal automation dashboards or as part of a credential management system for testing environments. Additionally, the self-contained mail server means you can audit what happens with emails and avoid any third-party tracking that typically accompanies disposable email services.

## Key Features & Technologies
- Self-hosted disposable email addresses
- Built-in mail server (shipped with project)
- Docker containerization
- HTMX-based web interface
- Email-as-RSS feeds
- Email-as-API endpoints
- Apache License

## Difference from Others
Compared to traditional SaaS trashmail services, Open Trashmail stands out because it ships its own mail server rather than relying on external providers. Most disposable email services only forward emails to your real inbox or provide limited API access; this project offers both RSS feeds and REST APIs for full programmatic control. The self-hosted nature also means you have complete visibility into email handling, can customize the stack, and avoid any third-party tracking that typically accompanies privacy-light services.

## 🏢 Organization & Credibility
- **Developer:** HaschekSolutions
- **Reputation:** Unknown
- **Stars:** 905
- **Forks:** 75
- **Recent Activity:** 0 commits in 3 months
- **Credibility Score:** 41.0/100 (Low)
- **Languages:** PHP, Python, Shell, CSS, Dockerfile
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
*Source: [GitHub](https://github.com/HaschekSolutions/opentrashmail)*
