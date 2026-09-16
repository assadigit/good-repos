---
source: https://github.com/markuman/sms
aliases:
  - sms
  - markuman/sms
tags: [python, go, docker, osm, tiles, self-hosted, shell, html, dockerfile, url]
category: Infrastructure
stars: 255
org: markuman
primary_language: Python
languages: [Python, Shell, HTML, Dockerfile, url]
credibility_score: 43.5/100
date_processed: 2026-07-10
last_release: 2026-04-18
cover: attachments/banners/sms_banner.png

---

![banner](attachments/banners/sms_banner.png)

# sms

> **TL;DR:** Self-hosted OSM mbtiles server serving vector tiles via HTTP/HTTPS with optional contour layers.

**`markuman/sms`** · ⭐ 255 · 🔧 Python

## What is it?
SMS is a self-hosted server that provides OpenStreetMap tile data in the mbtiles format, specifically optimized for serving vector tiles. It is designed to replace cloud-based mapping services by allowing you to host your own OSM tile server locally or on any infrastructure you control. The project wraps around the existing mbtiles-s3-server codebase and adds convenient containerization support, making it trivial to deploy with a single podman or docker command.

## How does it work?
The server runs as a container (podman or docker) with a persistent volume mounted at /data/ where you place pre-loaded OSM mbtiles files. The container exposes port 9000 and serves tile requests via HTTP/HTTPS endpoints that return vector tiles according to the mbtiles protocol. You can optionally load additional contour layer mbtiles for enhanced rendering. The setup is designed to be minimal: download planet.mbtiles (~100 GB) and optionally contours.mbtiles (~315 GB), then run the container with a simple volume mount. It is intended to be placed behind a reverse proxy (caddy, nginx, traefik) that provides SSL termination.

## Why is it important? (Core Value)
This project directly aligns with your interests in self-hosted alternatives to SaaS products and homelab infrastructure. As a software engineer focused on automation and developer tools, you can integrate SMS into your own mapping workflows—for example, using it as a tile server for GpxPod in automated geospatial pipelines or exposing it via URL parameters in custom web interfaces. Because it is containerized, agents could monitor its health, manage storage usage, and trigger re-downloads of OSM data when tiles become stale. It provides a credible, open-source way to host OSM tiles without relying on third-party services that may change pricing or availability.

## Key Features & Technologies
- Uses Podman/Docker containerization
- Serves OSM vector tiles via HTTP/HTTPS
- Optional contour layer support
- Integrates with GpxPod tile server API
- Supports URL parameter queries (lat/lng)
- Reverse geolocation endpoint
- Self-hosted, no external dependencies beyond storage

## Difference from Others
Compared to other self-hosted tile servers like onthegomap/planetiler or mbtiles-s3-server, this project is specifically containerized for easy deployment and includes built-in support for GpxPod integration. It wraps the original mbtiles-s3-server codebase but adds a simplified setup process (single-line podman commands) and optional contour layers. The container image is hosted on GitLab, making it straightforward to pull into any homelab environment without needing to build from source.

## 🏢 Organization & Credibility
- **Developer:** markuman
- **Reputation:** Unknown
- **Stars:** 255
- **Forks:** 11
- **Recent Activity:** 12 commits in 3 months
- **Credibility Score:** 43.5/100 (Low)
- **Languages:** Python, Shell, HTML, Dockerfile, url
- **Last Release:** 2026-04-18
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
*Source: [GitHub](https://github.com/markuman/sms)*
