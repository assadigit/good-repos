---
source: https://github.com/tbxark/mail2telegram
aliases:
  - mail2telegram
  - tbxark/mail2telegram
tags: [typescript, javascript, cloudflare-workers, telegram-bot, email, serverless, mail-bot, cloudflare, telegram-mini-apps, telegram-web-apps, cloudflare-email-routing, cloudflare-mail]
category: Automation
stars: 747
org: tbxark
primary_language: TypeScript
languages: [TypeScript, HTML, JavaScript, url]
credibility_score: 39.5/100
date_processed: 2026-07-05

cover: attachments/banners/mail2telegram_banner.png

---

![banner](attachments/banners/mail2telegram_banner.png)

# mail2telegram

**`tbxark/mail2telegram`** · ⭐ 747 · 🔧 TypeScript

## What is it?
mail2telegram is a self-hosted email forwarding solution built on Cloudflare Workers. It creates a temporary Telegram Bot that serves as an infinite-address mailbox, converting any incoming email to Telegram messages instantly. Users deploy it via wrangler CLI or the Cloudflare dashboard, configure webhooks, and receive all forwarded emails directly in their Telegram client.

## How does it work?
The project uses Cloudflare Email Routing Workers to intercept and forward emails matching configured recipient prefixes. Incoming mail is processed by a Worker that extracts the message content and sends it to a bound Telegram Bot via webhook. A temporary mailbox with an unlimited address is automatically created through Cloudflare's infrastructure, requiring only initial webhook binding via the `init` endpoint and privacy policy setup for mini-app compatibility.

## Why is it important? (Core Value)
For self-hosting enthusiasts, this offers a privacy-focused alternative to SaaS temporary email services like TempMail. It eliminates dependency on third-party providers while delivering immediate notifications through Telegram—a platform many already use heavily. The serverless architecture means zero infrastructure overhead beyond a Cloudflare account, and the wrangler deployment makes it easy to fork, customize, and run in homelab setups. For my objectives of finding self-hostable alternatives and automation tools, this is a practical addition: I can deploy it locally or on a small VPS, forward sensitive emails through my own infrastructure, and avoid vendor lock-in while keeping notifications centralized.

## Key Features & Technologies
- Uses Cloudflare Workers
- Cloudflare Email Routing integration
- Telegram Bot webhook forwarding
- Infinite temporary mailbox addresses
- wrangler CLI deployment
- Privacy policy configuration for mini-apps
- Self-hosted (no SaaS dependency)

## Difference from Others
Unlike generic email forwarding services or SaaS temp-mail providers, this specifically leverages Cloudflare Email Routing and creates a Telegram Bot mailbox rather than just forwarding to a single address. Many self-hosted solutions require an SMTP server or third-party relay—this runs entirely on Cloudflare's edge with no dedicated infrastructure. Telegram integration is its key differentiator, offering persistent, encrypted notifications directly in the client.

## 🏢 Organization & Credibility
- **Developer:** tbxark
- **Reputation:** Unknown
- **Stars:** 747
- **Forks:** 111
- **Recent Activity:** 4 commits in 3 months
- **Credibility Score:** 39.5/100 (Low)
- **Languages:** TypeScript, HTML, JavaScript, url
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
*Source: [GitHub](https://github.com/tbxark/mail2telegram)*
