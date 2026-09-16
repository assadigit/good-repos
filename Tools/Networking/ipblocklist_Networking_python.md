---
source: https://github.com/bitwire-it/ipblocklist
aliases:
  - ipblocklist
  - bitwire-it/ipblocklist
tags: [python, networking, ipblocklist, firewall, security, github-actions, banlist, blocklist, firehol, firehol-blocklist, firehol-blocklist-ipsets, firewall-rules]
category: Networking
stars: 550
org: bitwire-it
primary_language: Python
languages: [Python, url]
credibility_score: 55.5/100
date_processed: 2026-07-05

cover: attachments/banners/ipblocklist_banner.png

---

![banner](attachments/banners/ipblocklist_banner.png)

# ipblocklist

> **TL;DR:** Aggregated inbound/outbound IP blocklists updated every 2 hours for firewall use.

**`bitwire-it/ipblocklist`** · ⭐ 550 · 🔧 Python

## What is it?
This project provides aggregated IP blocklists for inbound and outbound traffic, updated every 2 hours. It includes exclusions for major public DNS resolvers to prevent legitimate services from being blocked. The lists are hosted on GitHub raw files, making them easy to pull into any firewall or network security setup.

A live dashboard shows update frequency, total IPs, and source breakdowns. GitHub Actions workflows automatically fetch and merge blocklists from ThreatFox, Abuse.ch, Spamhaus, and others, ensuring fresh data without manual intervention.

The raw inbound.txt and outbound.txt files are available for direct download or integration with firewall rules. The project also provides an IPSet format version for iptables/nftables users.

## How does it work?
The core workflow uses GitHub Actions to periodically fetch blocklists from multiple sources (ThreatFox, Abuse.ch, Spamhaus, etc.). These lists are merged into a single inbound.txt and outbound.txt file, with exclusions for major DNS resolvers (Cloudflare, Google, OpenDNS) to avoid blocking legitimate traffic. The resulting files are pushed back to the repository's raw branch, making them accessible via raw.githubusercontent.com. A separate stats workflow aggregates update history and displays it on the live dashboard.

The project is intentionally lightweight, relying only on standard Unix tools (curl, awk, sort) for processing. No complex dependencies are required, which makes it easy to self-host or integrate into homelab firewalls like OPNsense, pfSense, FortiGate, Cisco ASA, or Palo Alto Networks.

## Why is it important? (Core Value)
Why this project matters: It solves the problem of keeping firewall blocklists up-to-date without relying on a single external service that may be rate-limited or geographically restricted. By aggregating multiple sources and providing exclusions for DNS resolvers, it reduces false positives and ensures that legitimate traffic isn't blocked. For homelab users, it offers a self-hosted alternative to SaaS blocklist services, aligning perfectly with the goal of reducing reliance on external providers.

For you specifically: As someone focused on AI agents, developer tools, automation, and self-hosted alternatives to SaaS, this project provides a reliable, open-source source of IP blocklists that can be integrated into your homelab firewall (e.g., OPNsense, pfSense, FortiGate). The GitHub Actions workflow demonstrates a simple yet effective automation pattern you could adapt for other security lists or data pipelines. Additionally, the live dashboard gives visibility into update frequency and source breakdowns, which can be useful for auditing or building custom monitoring solutions. It also serves as a reference for designing your own blocklist aggregation service or for testing firewall rules without needing to subscribe to external services.

## Key Features & Technologies
- Aggregated inbound/outbound IP lists
- GitHub Actions automation for updates
- Excludes major public DNS resolvers (Cloudflare, Google, OpenDNS)
- Live dashboard with stats
- Self-hosted raw files on GitHub
- Supports firewall tools (OPNsense, pfSense, FortiGate, Cisco, Palo Alto)
- Includes IPSet format for iptables/nftables

## Difference from Others
Similar to ThreatFox or Abuse.ch blocklist repositories, this project stands out by aggregating multiple sources into a single inbound/outbound set rather than providing raw lists from a single provider. It also includes built-in exclusions for major DNS resolvers, which many other blocklists lack, reducing false positives. While ThreatFox is excellent for threat intelligence, it doesn't cover outbound traffic or provide DNS exclusion logic. Additionally, this project offers a live dashboard with update statistics, which is not typically found in other open-source blocklist projects.

For homelab users, the self-hosted raw files on GitHub make it easier to pull directly into firewall rules without needing to configure API calls or handle rate limits. The project also provides IPSet format versions, which is a niche but valuable feature for iptables/nftables users, unlike many other blocklist repos that only offer plain text lists.

## 🏢 Organization & Credibility
- **Developer:** bitwire-it
- **Reputation:** Unknown
- **Stars:** 550
- **Forks:** 52
- **Recent Activity:** 910 commits in 3 months
- **Credibility Score:** 55.5/100 (Low)
- **Languages:** Python, url
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
*Source: [GitHub](https://github.com/bitwire-it/ipblocklist)*
