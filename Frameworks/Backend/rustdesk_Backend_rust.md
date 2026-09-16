---
source: https://github.com/rustdesk/rustdesk
aliases:
  - rustdesk
  - rustdesk/rustdesk
tags: [rust, rust, remote-desktop, self-hosted, vnc, rdp, remote-control, teamviewer, anydesk, p2p, flutter, flutter-apps]
category: Backend
stars: 118154
org: rustdesk
primary_language: Rust
languages: [Rust, Dart, C++, Python, C]
credibility_score: 72.0/100
date_processed: 2026-07-13
last_release: 2026-07-10
cover: attachments/banners/rustdesk_banner.png

---

![banner](attachments/banners/rustdesk_banner.png)

# rustdesk

> **TL;DR:** Open-source remote desktop app with self-hosted server, P2P connections, and multi-platform support.

**`rustdesk/rustdesk`** · ⭐ 118,154 · 🔧 Rust

## What is it?
RustDesk is an open-source remote desktop application designed as a self-hostable alternative to TeamViewer. It enables secure remote access to computers across multiple operating systems including Linux, Windows, macOS, Android, and iOS. The project includes both a server component written in Rust for self-hosting and client applications built with Flutter/Dart for cross-platform compatibility.

Key features include support for VNC and RDP protocols, P2P connections via WebRTC or relay servers, Wayland integration on Linux, and a web-based client interface. The project also provides snapshot functionality to capture screenshots remotely. Documentation is available in over 30 languages with community translation efforts.

## How does it work?
The architecture consists of a Rust-based server that handles remote connections and authentication, communicating with Flutter/Dart-built clients across platforms. P2P connections are established through WebRTC when possible, falling back to relay servers for NAT traversal. The server supports Wayland protocol on Linux systems, enabling screen sharing and input handling.

Clients connect via secure encrypted channels, with the server managing session tokens and permissions. The project includes a web client that runs in browsers without installation, making it accessible from any device. All components are open-source and can be self-hosted on local infrastructure.

## Why is it important? (Core Value)
RustDesk provides significant value by offering a self-hosted remote desktop solution that reduces dependency on proprietary SaaS products like TeamViewer. For developers and researchers interested in homelab infrastructure, this enables secure remote access to development machines without exposing them to public cloud services. The open-source nature allows full inspection of security implementations and customization for specific workflows.

The snapshot feature is particularly useful for debugging sessions or capturing screenshots during remote support. Given the user's focus on developer productivity tools and self-hosted software, RustDesk directly addresses the need for reliable remote access while maintaining control over data privacy.

## Key Features & Technologies
- Self-hosted server
- P2P connections via WebRTC
- Flutter clients
- Rust backend
- Wayland support
- Multi-platform (Linux, Windows, macOS, Android, iOS)
- Snapshot screenshots

## Difference from Others
Compared to TeamViewer and AnyDesk, RustDesk stands out by being completely open-source with self-hosting capabilities, eliminating subscription fees and vendor lock-in. Unlike VNC-only solutions, it includes RDP protocol support and a web-based client interface. The project also emphasizes P2P connectivity over relay servers where possible, reducing reliance on third-party infrastructure.

## 🏢 Organization & Credibility
- **Developer:** rustdesk
- **Reputation:** Unknown
- **Stars:** 118,154
- **Forks:** 17968
- **Recent Activity:** 182 commits in 3 months
- **Credibility Score:** 72.0/100 (Average)
- **Languages:** Rust, Dart, C++, Python, C
- **Last Release:** 2026-07-10
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
*Source: [GitHub](https://github.com/rustdesk/rustdesk)*
