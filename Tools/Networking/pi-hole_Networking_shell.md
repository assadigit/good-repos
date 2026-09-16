---
source: https://github.com/pi-hole/pi-hole
aliases:
  - pi-hole
  - pi-hole/pi-hole
tags: [shell, php, bash, dnsmasq, ad-blocker, self-hosted, pi-hole, shell, blocker, raspberry-pi, cloud, dhcp]
category: Networking
stars: 59686
org: pi-hole
primary_language: Shell
languages: [Shell, Python, Dockerfile, Roff, url]
credibility_score: 63.0/100
date_processed: 2026-07-05
last_release: 2026-04-24
cover: attachments/banners/pi-hole_banner.png

---

![banner](attachments/banners/pi-hole_banner.png)

# pi-hole

> **TL;DR:** Network-wide ad-blocking DNS sinkhole that replaces browser extensions with a self-hosted server.

**`pi-hole/pi-hole`** · ⭐ 59,686 · 🔧 Shell

## What is it?
The Pi-hole is a DNS sinkhole that protects devices from unwanted content without installing any client-side software. It blocks ads at the network level, intercepting DNS queries and returning a sinkhole IP for known ad domains. The project emphasizes being easy-to-install (dialog walks you through in under ten minutes), resolute (blocks in non-browser locations like mobile apps and smart TVs), responsive (caching DNS queries speeds up browsing), lightweight (runs on minimal hardware/software), robust (CLI quality-assured), insightful (beautiful responsive web dashboard), versatile (optional DHCP server ensures all devices protected), and scalable (handles hundreds of millions of queries).

## How does it work?
Pi-hole runs on a Linux system, typically a Raspberry Pi or any server with sufficient resources. It uses dnsmasq as the DNS forwarder, which is configured to forward queries to upstream DNS servers like Google DNS or Cloudflare. When a query arrives, Pi-hole checks its blocklists (community-maintained and user-defined) against the domain name. If a match is found, it returns a synthetic DNS record pointing to a sinkhole IP address; otherwise it forwards normally. The web dashboard is built with PHP and provides real-time statistics, blocklist management, and DHCP configuration. A command-line interface (CLI) allows scriptable control for automation. The optional DHCP server can be enabled to assign Pi-hole as the default DNS resolver for all devices on the network.

## Why is it important? (Core Value)
For a software engineer focused on AI agents, developer tools, and automation, Pi-hole offers a self-hosted alternative to commercial ad-blocking services, aligning with your interest in homelab infrastructure. By deploying Pi-hole on your own hardware, you avoid reliance on SaaS ad blockers, gain full control over blocklists, and protect privacy across all devices without client software. Its lightweight nature makes it suitable for Raspberry Pi or any Linux server, fitting your goal of discovering self-hostable tools that improve development workflow. Additionally, the CLI and dashboard enable automation scripts to integrate Pi-hole into broader workflows, supporting your objective to find tools that enhance developer productivity.

## Key Features & Technologies
- Uses dnsmasq as DNS forwarder
- Self-hosted PHP dashboard
- CLI for management and scripting
- Optional DHCP server integration
- Community-maintained blocklists
- Caching of DNS queries
- Lightweight (runs on Raspberry Pi)

## Difference from Others
Compared to browser extensions like uBlock Origin or AdGuard, Pi-hole provides network-wide protection that also blocks ads in mobile apps and smart TVs. Unlike other DNS-based blockers such as AdGuard Home or NextDNS, Pi-hole emphasizes a lightweight CLI, built-in DHCP server, and community-driven blocklists. Its sinkhole approach avoids installing client-side software, making it distinct from solutions that require extensions or agent-like behavior.

## 🏢 Organization & Credibility
- **Developer:** pi-hole
- **Reputation:** Unknown
- **Stars:** 59,686
- **Forks:** 3246
- **Recent Activity:** 36 commits in 3 months
- **Credibility Score:** 63.0/100 (Average)
- **Languages:** Shell, Python, Dockerfile, Roff, url
- **Last Release:** 2026-04-24
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
*Source: [GitHub](https://github.com/pi-hole/pi-hole)*
