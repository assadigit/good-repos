---
source: https://github.com/anonymousRAID/OSINT-Mapping-Tool
aliases:
  - OSINT-Mapping-Tool
  - anonymousRAID/OSINT-Mapping-Tool
tags: [javascript, react, vite, osint, privacy, local-first, google-maps-api, mapping, maps, osint-tool, osint-tools, osinttool]
category: Dev-Tools
stars: 474
org: anonymousRAID
primary_language: JavaScript
languages: [JavaScript, CSS, Shell, HTML, Dockerfile]
credibility_score: 43.5/100
date_processed: 2026-07-05

cover: attachments/banners/OSINT-Mapping-Tool_banner.png

---

![banner](attachments/banners/OSINT-Mapping-Tool_banner.png)

# OSINT-Mapping-Tool

> **TL;DR:** Local-first web app for OSINT research. Wire identifiers in a node graph, pin places on maps, and keep data in your browser. React + Vite.

**`anonymousRAID/OSINT-Mapping-Tool`** · ⭐ 474 · 🔧 JavaScript

## What is it?
OSINT Mapping Tool is a privacy-first web application designed to help researchers organize Open Source Intelligence data. The Information tab lets you build a node graph where each node represents an identifier—social handles, phone numbers, license plates, or family members—and you can drag wires between them to reveal connections. The Map tab provides click-to-pin functionality on Google Maps or OpenStreetMap; the geocoder automatically fills in addresses and icons for recognizable places, and pins can be linked back to identifiers.

Everything runs locally with nothing leaving your browser, leveraging React and Vite for a fast, responsive UI. The project is open-source under the GPL-3.0 license, making it suitable for self-hosting and integration into personal research workflows.

## How does it work?
The tool runs entirely in the browser using React and Vite for its UI framework. The Information tab implements a Blender-style node graph where each node is a piece of OSINT data (social handle, phone number, license plate, etc.) and wires are created by dragging between nodes or right-clicking to spawn. The Map tab integrates with Google Maps or OpenStreetMap geocoding APIs; when you place a pin, the geocoder determines the location name, address, and an appropriate icon automatically. All data is stored locally, never transmitted externally, which aligns with its local-first design.

## Why is it important? (Core Value)
This project offers a privacy-first, local-first approach to OSINT research organization—exactly what a researcher building a personal knowledge base needs. Since nothing leaves your browser, it serves as a self-hostable alternative to SaaS tools, aligning with your interest in homelab infrastructure and open-source software. The node graph UI and map integration are developer productivity features that streamline investigative workflows without introducing AI agents or MCP servers, but they complement those interests by providing a clean data model you could later hook into agent systems. For someone curating tools to improve development workflow, this is both a practical utility and an example of good local-first design.

## Key Features & Technologies
- Uses React
- Uses Vite
- Local-first privacy (nothing leaves browser)
- Node graph UI for linking identifiers
- Click-to-pin map integration with geocoder
- GPL-3.0 open-source license

## Difference from Others
Unlike other OSINT mapping tools that send data to external services, this project is designed with a local-first philosophy—nothing leaves your browser.

## 🏢 Organization & Credibility
- **Developer:** anonymousRAID
- **Reputation:** Unknown
- **Stars:** 474
- **Forks:** 90
- **Recent Activity:** 18 commits in 3 months
- **Credibility Score:** 43.5/100 (Low)
- **Languages:** JavaScript, CSS, Shell, HTML, Dockerfile
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
*Source: [GitHub](https://github.com/anonymousRAID/OSINT-Mapping-Tool)*
