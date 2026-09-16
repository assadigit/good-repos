---
source: https://github.com/AdguardTeam/AdGuardHome
aliases:
  - AdGuardHome
  - AdguardTeam/AdGuardHome
tags: [typescript, dns, privacy, golang, docker, self-hosted, adblock, adguard, open-source, dns-over-https, dns-over-tls, dns-over-quic]
category: Infrastructure
stars: 35520
org: AdguardTeam
primary_language: TypeScript
languages: [TypeScript, Go, CSS, Shell, JavaScript]
credibility_score: 70.5/100
date_processed: 2026-07-17
last_release: 2026-07-14
cover: attachments/banners/AdGuardHome_banner.png

---

![banner](attachments/banners/AdGuardHome_banner.png)

# AdGuardHome

> **TL;DR:** Self-hosted DNS-based ad-blocking and privacy solution that replaces commercial tools.

**`AdguardTeam/AdGuardHome`** · ⭐ 35,520 · 🔧 TypeScript

## What is it?
AdGuardHome is an open-source, network-wide ad-blocking and privacy protection server that runs directly on your local network devices. It intercepts DNS queries from your devices and blocks requests to known ad servers, trackers, malware domains, and other unwanted destinations using filter lists such as AdGuard's own filters, EasyList, and others.

The project functions as a privacy protection center for your home or office network, giving you full control over what gets resolved by DNS servers. It supports multiple privacy-friendly DNS protocols including DNS-over-HTTPS (DoH), DNS-over-TLS (DoT), and DNS-over-QUIC (DoQ), ensuring encrypted and secure communication while blocking unwanted content.

## How does it work?
AdGuardHome operates primarily through a local DNS server that intercepts all DNS queries from devices on your network. It maintains a database of filter lists containing domains known to serve ads, trackers, malware, and other unwanted content. When a device requests a domain name, AdGuardHome checks the filter lists and returns either the IP address (allowing traffic) or redirects to a sinkhole IP (blocking the request).

The software is written in Go (Golang), making it highly performant and cross-platform. It can be deployed via Docker containers, which is its primary distribution method, allowing seamless integration into homelab setups. The project includes a web-based admin interface that lets you manage filter lists, customize blocking rules, view statistics on blocked domains, and configure DNS settings.

## Why is it important? (Core Value)
AdGuardHome provides significant value by giving users complete control over their network traffic without relying on third-party services that may sell browsing data. Unlike commercial alternatives like AdGuard Premium or Pi-hole, it's entirely free and open-source with no hidden costs or mandatory subscriptions.

For the user specifically, this project directly addresses several key objectives: it serves as an excellent self-hostable alternative to SaaS products (replacing paid DNS ad-blockers), fits perfectly into homelab infrastructure setups, and provides a privacy-first approach to network management. The open-source nature means the code can be audited and modified, aligning with the user's interest in learning about new approaches to automation and infrastructure.

## Key Features & Technologies
- DNS-based blocking with multiple filter lists
- Supports DNS-over-HTTPS/TLS/QUIC protocols
- Docker deployment and container support
- Web-based administration interface
- Statistics and logging of blocked domains
- Open-source written in Go (Golang)
- Self-hostable privacy solution

## Difference from Others
While similar projects exist like Pi-hole (which predates AdGuardHome) or other DNS blockers, AdGuardHome positions itself as a modern, actively maintained replacement with better performance characteristics. The primary differentiators are its Go implementation offering superior speed compared to older Python-based solutions, and its cleaner architecture that separates the filter lists from the DNS server logic more elegantly. Additionally, it provides more granular control over which protocols to use for DNS resolution while maintaining strong privacy guarantees.

## 🏢 Organization & Credibility
- **Developer:** AdguardTeam
- **Reputation:** Unknown
- **Stars:** 35,520
- **Forks:** 2432
- **Recent Activity:** 64 commits in 3 months
- **Credibility Score:** 70.5/100 (Average)
- **Languages:** TypeScript, Go, CSS, Shell, JavaScript
- **Last Release:** 2026-07-14
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
*Source: [GitHub](https://github.com/AdguardTeam/AdGuardHome)*
