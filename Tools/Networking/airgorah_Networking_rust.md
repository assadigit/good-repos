---
source: https://github.com/martin-olivier/airgorah
aliases:
  - airgorah
  - martin-olivier/airgorah
tags: [rust, rust, wifi, security, aircrack-ng, gui, security-audit, wifi-security, wireless, kali, linux-app, dockerfile]
category: Networking
stars: 749
org: martin-olivier
primary_language: Rust
languages: [Rust, Dockerfile, url]
credibility_score: 41.0/100
date_processed: 2026-07-05
last_release: 2025-09-04
cover: attachments/banners/airgorah_banner.png

---

![banner](attachments/banners/airgorah_banner.png)

# airgorah

> **TL;DR:** Rust WiFi security auditing tool that captures traffic, performs deauth attacks, and cracks passwords.

**`martin-olivier/airgorah`** · ⭐ 749 · 🔧 Rust

## What is it?
Airgorah is a WiFi security auditing software built on the aircrack-ng tools suite with a graphical interface. It can capture nearby WiFi traffic, discover clients connected to access points, perform deauthentication attacks, capture handshakes, and crack the password of access points. The project provides installation documentation for various platforms including crates.io and AUR.

## How does it work?
Airgorah is written in Rust and uses GTK4 for the graphical interface. It integrates with aircrack-ng tools to perform WiFi security operations, likely invoking them through subprocess calls or Rust bindings. The workflow involves monitoring WiFi interfaces to capture packets, identifying associated clients, sending deauthentication frames to disconnect them from access points, capturing the four-way handshake when they reconnect, and then using password cracking algorithms against the captured handshake data.

## Why is it important? (Core Value)
This project provides a self-hosted alternative for WiFi security auditing that aligns with your interest in self-hostable software and developer productivity tools. The Rust implementation ensures performance and safety while the GTK4 GUI simplifies what would otherwise be complex command-line operations with aircrack-ng. Since you curate GitHub projects into an Obsidian vault, this tool could be added as a reference note under 'Networking' or 'Security' categories, with links to its wiki for installation and usage documentation.

## Key Features & Technologies
- Rust-based core
- GTK4 GUI
- aircrack-ng integration
- WiFi traffic capture
- Deauthentication attack support
- Handshake capturing
- Password cracking (dictionary/brute-force)

## Difference from Others
Compared to other WiFi auditing tools like Kismet (packet capture only), Wireshark (general traffic analysis), or the aircrack-ng CLI suite, Airgorah stands out by providing a GUI that abstracts away the complexity of command-line usage. It's also written in Rust rather than C/C++, offering better safety guarantees and performance. The project includes wiki documentation for installation and usage, making it more approachable for users who prefer graphical interfaces over raw terminal commands.

## 🏢 Organization & Credibility
- **Developer:** martin-olivier
- **Reputation:** Unknown
- **Stars:** 749
- **Forks:** 74
- **Recent Activity:** 0 commits in 3 months
- **Credibility Score:** 41.0/100 (Low)
- **Languages:** Rust, Dockerfile, url
- **Last Release:** 2025-09-04
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
*Source: [GitHub](https://github.com/martin-olivier/airgorah)*
