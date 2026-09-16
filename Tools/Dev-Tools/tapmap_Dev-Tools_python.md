---
source: https://github.com/olalie/tapmap
aliases:
  - tapmap
  - olalie/tapmap
tags: [python, python, network, visualization, docker, geolocation, network-visualization, dash, plotly, real-time, interactive-map, internet-observability]
category: Dev-Tools
stars: 1156
org: olalie
primary_language: Python
languages: [Python, CSS, JavaScript, PowerShell, Dockerfile]
credibility_score: 62.0/100
date_processed: 2026-07-13
last_release: 2026-06-29
cover: attachments/banners/tapmap_banner.png

---

![banner](attachments/banners/tapmap_banner.png)

# tapmap

**`olalie/tapmap`** · ⭐ 1,156 · 🔧 Python

## What is it?
TapMap is a self-hosted, real-time internet observability tool that visualizes your computer's network connections on an interactive geolocated map. It inspects local socket data, enriches IP addresses with geolocation, and builds a local activity history to reveal patterns in your network traffic over time.

## How does it work?
TapMap runs a local Python service that monitors active sockets on your machine, extracting remote IP addresses from connection data. It then enriches these IPs with geolocation information (likely using a GeoIP database) and renders them on an interactive map built with Dash and Plotly. The tool maintains a local history of connections, allowing you to analyze trends over time. No external telemetry is sent; everything runs locally, with Docker support on Linux for easy deployment.

## Why is it important? (Core Value)
TapMap is valuable because it gives developers visibility into their network activity without relying on cloud services or sending data externally—perfect for privacy-conscious users and self-hosters. For someone focused on developer productivity tools and self-hosted software, TapMap directly addresses the need to understand external dependencies, debug connectivity issues, and identify security patterns in real-time traffic. Its awareness-tool positioning means it complements existing security suites rather than replacing them, making it a low-overhead addition to any homelab or development environment.

## Key Features & Technologies
- Uses Python
- Docker support (Linux)
- Real-time visualization
- Geolocation
- Local activity history
- Interactive map (Dash, Plotly)
- Self-hosted
- No telemetry
- MIT license

## Difference from Others
Unlike commercial network monitoring tools that require cloud accounts or send telemetry, TapMap runs entirely locally with no external data leakage. It differs from firewall or intrusion detection systems by focusing on awareness rather than enforcement—providing visibility without adding security rules. Compared to generic socket inspection utilities, TapMap adds geolocation and interactive visualization, making it uniquely suited for developers seeking to map their real-world internet connections.

## 🏢 Organization & Credibility
- **Developer:** olalie
- **Reputation:** Unknown
- **Stars:** 1,156
- **Forks:** 71
- **Recent Activity:** 70 commits in 3 months
- **Credibility Score:** 62.0/100 (Average)
- **Languages:** Python, CSS, JavaScript, PowerShell, Dockerfile
- **Last Release:** 2026-06-29
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
*Source: [GitHub](https://github.com/olalie/tapmap)*
