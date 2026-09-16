---
source: https://github.com/ramonvermeulen/whosthere
aliases:
  - whosthere
  - ramonvermeulen/whosthere
tags: [go, go, lan, networking, tui, scanner, golang, network, network-analysis, tview, makefile, shell]
category: Networking
stars: 2390
org: ramonvermeulen
primary_language: Go
languages: [Go, Makefile, Shell, url]
credibility_score: 54.5/100
date_processed: 2026-07-17
last_release: 2026-05-21
cover: attachments/banners/whosthere_banner.png

---

![banner](attachments/banners/whosthere_banner.png)

# whosthere

> **TL;DR:** Local Area Network discovery tool with interactive Terminal UI that scans via mDNS/SSDP and ARP resolution.

**`ramonvermeulen/whosthere`** · ⭐ 2,390 · 🔧 Go

## What is it?
Whosthere is a LAN discovery tool built with Go that provides an interactive Terminal User Interface for exploring your local network. It's designed to help you discover, explore, and understand what devices are present on your Local Area Network in an intuitive way.

The project performs unprivileged, concurrent scans using mDNS (Multicast DNS) and SSDP (Simple Service Discovery Protocol) scanners. Additionally, it sweeps the local subnet by attempting TCP/UDP connections to trigger ARP resolution, then reads the ARP cache to identify devices on your Local Area Network. This technique populates the ARP cache without requiring elevated privileges.

## How does it work?
Whosthere uses Go's concurrent capabilities to perform multiple scans simultaneously across the network. It leverages mDNS and SSDP protocols—standard discovery mechanisms used by many networked devices—to identify services and devices broadcasting themselves on the LAN.

For ARP-based discovery, it actively sweeps the subnet by attempting TCP/UDP connections to various addresses, which triggers ARP resolution on the local machine. After these connection attempts, it reads the resulting ARP cache entries to extract device information. The TUI component, built with tview, provides an interactive interface for navigating discovery results.

## Why is it important? (Core Value)
This project is particularly valuable as a self-hosted networking tool that brings LAN discovery capabilities to your local infrastructure without dependencies on external services or cloud APIs. For someone focused on developer tools and automation, whosthere offers a clean, dependency-minimal approach to network exploration.

It specifically helps with understanding your homelab or home network topology, which is essential for security awareness and proper device management. The unprivileged scanning approach makes it safe for deployment in production environments where you may not have administrative access. Its Go implementation ensures cross-platform compatibility and easy integration into other automation workflows—perfect for building knowledge bases of useful networking utilities.

## Key Features & Technologies
- Written in Go
- Interactive TUI with tview
- mDNS scanner
- SSDP scanner
- ARP cache-based device identification
- Unprivileged scanning (no sudo required)
- Concurrent network discovery

## Difference from Others
Compared to traditional network scanning tools like nmap, whosthere takes a different approach by focusing on unprivileged scanning that doesn't require elevated privileges. While nmap can discover many devices, it typically requires root/admin access for certain techniques.

Against other LAN discovery utilities like arp-scan or nmap's basic host discovery, whosthere provides an interactive TUI interface rather than just raw output. This makes it more accessible for users who want to visually explore their network without parsing command-line results. The mDNS and SSDP scanning is particularly useful for discovering IoT devices that may not respond to traditional ICMP-based ping sweeps.

## 🏢 Organization & Credibility
- **Developer:** ramonvermeulen
- **Reputation:** Unknown
- **Stars:** 2,390
- **Forks:** 72
- **Recent Activity:** 37 commits in 3 months
- **Credibility Score:** 54.5/100 (Low)
- **Languages:** Go, Makefile, Shell, url
- **Last Release:** 2026-05-21
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
*Source: [GitHub](https://github.com/ramonvermeulen/whosthere)*
