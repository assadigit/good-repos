---
source: "https://github.com/bilawalsidhu/gods-eye-view"
aliases:
  - gods-eye-view
  - bilawalsidhu/gods-eye-view

tags: [javascript, webgl, cesium, geospatial, 3d-globe, osint, flight-tracking, geospatial-intelligence, gis, photogrammetry, satellite-tracking, spatial-intelligence]
category: "Frontend"
stars: 34941
org: "bilawalsidhu"
primary_language: JavaScript
languages: [JavaScript, CSS, HTML, Shell, url]
credibility_score: 70.5/100
date_processed: 2026-09-16
last_release: 2026-09-01
cover: attachments/banners/gods-eye-view_banner.png

---

![banner](attachments/banners/gods-eye-view_banner.png)

# gods-eye-view

> **TL;DR:** Browser-based spy satellite simulator with live real-world geospatial data on a photorealistic 3D globe using Cesium and WebGL.

**`bilawalsidhu/gods-eye-view`** · ⭐ 34,941 · 🔧 JavaScript

## What is it?
God's Eye View is a web-based application that simulates a spy-satellite experience entirely in the browser, but powered by real, publicly available data sources. It renders a photorealistic 3D globe and overlays live feeds of aircraft, ships, satellites, earthquakes, traffic, and public cameras, giving users an immersive open-source spatial intelligence view without any proprietary subscriptions.

The project also includes hands-free voice control driven by a realtime AI agent, letting users navigate and query the globe through speech. Formerly known as "WorldView," it originated from a viral YouTube series (5M+ views) before evolving into a full open-source project that reached #1 on GitHub Trending in August 2026 and was featured as ProductHunt's #8 Product of the Day.

## How does it work?
The application is built on Cesium, an open-source geospatial framework that uses WebGL to render interactive 3D globes directly in the browser. It ingests multiple live public data feeds—ADS-B for aircraft tracking, AIS for ship positions, satellite orbit data, seismic event feeds, traffic sources, and public camera streams—and composites them as toggleable layers on the photorealistic globe. Terrain realism is achieved through photogrammetry-derived imagery and elevation data.

A realtime AI agent handles voice commands, parsing natural speech to control camera movements, layer visibility, and data lookups, enabling fully hands-free interaction with the 3D interface.

## Why is it important? (Core Value)
For a software engineer focused on AI agents, developer tools, and automation, this project offers several practical takeaways. The multi-source live data integration pattern (aircraft, ships, satellites, seismic, traffic, cameras) demonstrates how to architect real-time geospatial data pipelines from public APIs—directly relevant to interests in scraping and automation. The realtime AI voice agent component showcases a working LLM/agent implementation for hands-free control of a complex 3D interface, which could inform work on AI agent frameworks and MCP-style tool integration.

As an open-source, browser-based application with no proprietary data dependencies, it also serves as a self-hostable alternative to commercial geospatial SaaS platforms like Google Earth Pro or Esri ArcGIS Online, aligning with the user's interest in self-hosted alternatives and open-source infrastructure.

## Key Features & Technologies
- Cesium WebGL-based photorealistic 3D globe rendering
- Live ADS-B aircraft and AIS ship tracking overlays
- Real-time satellite orbit and earthquake data layers
- Public camera feed integration for ground-level views
- Hands-free voice control via a realtime AI agent
- Photogrammetry-derived terrain imagery

## Difference from Others
Most geospatial visualization tools—Google Earth, Esri ArcGIS Online, Cesium ion—are either SaaS products with proprietary data pipelines or developer-focused SDKs requiring API keys and subscriptions. gods-eye-view stands out by delivering a complete, consumer-facing spy-satellite simulation using exclusively open-source public data, with no accounts or paid tiers required.

Unlike raw Cesium demos or static GIS web maps, it packages live multi-domain OSINT feeds (air, sea, space, seismic, traffic, video) into a single immersive 3D interface and adds an AI voice agent for natural-language interaction, making it both a functional open-source intelligence tool and a compelling demonstration of real-time browser geospatial architecture.

## 🏢 Organization & Credibility
- **Developer:** bilawalsidhu
- **Reputation:** Unknown
- **Stars:** 34,941
- **Forks:** 6988
- **Recent Activity:** 412 commits in 3 months
- **Credibility Score:** 70.5/100 (Average)
- **Languages:** JavaScript, CSS, HTML, Shell, url
- **Last Release:** 2026-09-01
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
*Source: [GitHub](https://github.com/bilawalsidhu/gods-eye-view)*
