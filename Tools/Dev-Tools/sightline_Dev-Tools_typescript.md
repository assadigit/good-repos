---
source: https://github.com/ni5arga/sightline
aliases:
  - sightline
  - ni5arga/sightline
tags: [typescript, openstreetmap, osint, overpass-turbo, geo-osint, python, openstreetmap-api, openstreetmap-data, geoint, css, javascript, url]
category: Dev-Tools
stars: 498
org: ni5arga
primary_language: TypeScript
languages: [TypeScript, CSS, JavaScript, url]
credibility_score: 39.5/100
date_processed: 2026-07-06

cover: attachments/banners/sightline_banner.png

---

![banner](attachments/banners/sightline_banner.png)

# sightline

> **TL;DR:** OSINT platform mapping real-world infrastructure from OpenStreetMap data with 200+ searchable assets.

**`ni5arga/sightline`** · ⭐ 498 · 🔧 TypeScript

## What is it?
Sightline is a geospatial infrastructure intelligence platform that enables searching, monitoring, and analyzing real-world physical assets using OpenStreetMap data. It covers telecommunications towers, power plants, airports, ports, warehouses, pipelines, military installations, hospitals, surveillance cameras, transportation hubs, and more—spanning 30+ categories with over 200 searchable infrastructure types.

The platform combines a frontend search UI with a backend that uses NLP parsing and geocoding to correlate assets with user queries. It integrates with Overpass Turbo API for querying OSM data and provides Leaflet.js-based mapping visualization. Architecture includes modular route handling, parser logic, geo-referencing components, and asset-specific handlers.

## How does it work?
Sightline follows a full-stack architecture: the frontend provides search UI elements (SearchBar, Filters, ResultList) powered by Leaflet.js for mapping; the backend routes queries via route.ts, uses NLP parser.ts to extract assets from natural language requests, applies geo.ts for geocoding, and interacts with Overpass Turbo API through overpass.ts handlers. Each asset category has dedicated parsing logic that maps query terms to OSM tags and ways nodes.

## Why is it important? (Core Value)
Sightline provides a self-hosted OSINT platform for analyzing real-world infrastructure from OpenStreetMap data without relying on SaaS products. It covers 30+ categories with 200+ searchable assets, making it useful for geospatial intelligence tasks, critical infrastructure mapping, and security analysis. For your research workflow, it could serve as a foundational tool for agent systems that need to map physical infrastructure (e.g., power grids, telecom towers) or support OSINT analysis pipelines. Its Overpass Turbo integration allows automated queries—potentially combined with LLM-based reasoning to correlate infrastructure events. The modular architecture means you can extend asset handlers or integrate into existing geospatial toolchains.

## Key Features & Technologies
- Uses Overpass Turbo API for OSM data querying
- Leaflet.js mapping visualization
- 30+ infrastructure categories with 200+ searchable types
- Self-hosted platform architecture
- NLP parser for natural language asset discovery
- Modular route handling (route.ts, parser.ts, geo.ts, overpass.ts)
- Search UI with filters and result lists

## Difference from Others
Unlike generic OSM query tools like osmquery or raw Overpass API clients, Sightline focuses specifically on OSINT use cases with 200+ predefined asset types. It provides a full-stack platform rather than just an API client, integrating NLP parsing and geocoding into a cohesive workflow. The self-hosted design contrasts with cloud-based geospatial SaaS offerings, making it suitable for privacy-sensitive infrastructure analysis.

## 🏢 Organization & Credibility
- **Developer:** ni5arga
- **Reputation:** Unknown
- **Stars:** 498
- **Forks:** 66
- **Recent Activity:** 1 commits in 3 months
- **Credibility Score:** 39.5/100 (Low)
- **Languages:** TypeScript, CSS, JavaScript, url
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
*Source: [GitHub](https://github.com/ni5arga/sightline)*
