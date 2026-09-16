---
source: https://github.com/maillab/cloud-mail
aliases:
  - cloud-mail
  - maillab/cloud-mail
tags: [javascript, cloudflare, email, workers, self-hosted, open-source, cloudflare-email, cloudflare-workers, mail, vue, css, html]
category: Infrastructure/Cloud
stars: 12493
org: maillab
primary_language: JavaScript
languages: [JavaScript, Vue, CSS, HTML, url]
credibility_score: 70.5/100
date_processed: 2026-07-17

cover: attachments/banners/cloud-mail_banner.png

---

![banner](attachments/banners/cloud-mail_banner.png)

# cloud-mail

**`maillab/cloud-mail`** · ⭐ 12,493 · 🔧 JavaScript

## What is it?
Self-hosted email service built on Cloudflare Workers with sending and attachment support.

## How does it work?
The project deploys serverless functions to Cloudflare Workers, leveraging Cloudflare's edge network for handling email traffic. Incoming emails are routed through Cloudflare's DNS and delivered via SMTP or IMAP/POP3 services, while outgoing emails are sent through Cloudflare's edge network. Attachments are stored in Cloudflare R2 object storage. The README emphasizes simplicity with just one domain name required.

## Why is it important? (Core Value)
This project offers a self-hosted email solution that gives users full control over their email data without relying on SaaS providers like Gmail or Outlook. For someone interested in homelab infrastructure and self-hosted software, it provides an alternative email service that can be integrated into a broader self-hosted stack (e.g., combined with a self-hosted web server, DNS management, etc.). It's also open-source under MIT license, making it suitable for adoption and modification.

## Key Features & Technologies
- Uses Cloudflare Workers
- Self-hosted email service
- Supports sending emails and handling attachments
- MIT license
- Open-source
- Cloudflare DNS integration
- Edge email delivery

## Difference from Others
Compared to other self-hosted email services like Mail-in-a-Box or Mailu, Cloud Mail stands out for its minimal setup (only one domain name) and edge-based architecture leveraging Cloudflare Workers. While those projects often require more complex infrastructure (e.g., Docker containers, multiple domain names), Cloud Mail simplifies deployment by relying on Cloudflare's existing infrastructure. Additionally, it may offer better latency due to edge delivery of emails directly from Cloudflare's network.

## 🏢 Organization & Credibility
- **Developer:** maillab
- **Reputation:** Unknown
- **Stars:** 12,493
- **Forks:** 17972
- **Recent Activity:** 51 commits in 3 months
- **Credibility Score:** 70.5/100 (Average)
- **Languages:** JavaScript, Vue, CSS, HTML, url
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
*Source: [GitHub](https://github.com/maillab/cloud-mail)*
