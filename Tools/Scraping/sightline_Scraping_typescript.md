---
source: https://github.com/ni5arga/sightline
aliases:
  - sightline
  - ni5arga/sightline
tags: [typescript, openstreetmap, osint, overpass-turbo, geo-osint, leaflet, openstreetmap-api, openstreetmap-data, geoint, css, javascript, url]
category: Scraping
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

**`ni5arga/sightline`** · ⭐ 498 · 🔧 TypeScript

## What is it?
An OSINT search engine that discovers and analyzes physical-world infrastructure assets using OpenStreetMap data.

## How does it work?
Sightline uses a two-tier architecture with a frontend built around Leaflet.js for interactive map visualization and a backend that handles requests through TypeScript modules. The frontend provides a search bar, filter UI, result list, and map view to display geospatial data. When a user submits a query, the backend's route handler processes it and passes it to an NLP parser component that translates natural language descriptions into structured Overpass API queries. The geo module handles coordinate transformations and geocoding, while the overpass module communicates with Overpass Turbo servers to fetch OSM data. Results are then rendered on the map, with filtering applied in real time.

## Why is it important? (Core Value)
For a software engineer and researcher focused on AI agents, developer tools, automation, self-hostable software, and OSINT/scraping workflows, Sightline is highly relevant. It's an open-source, self-hosted project that can be deployed on your own infrastructure—aligning with your interest in homelab tools and avoiding vendor lock-in to SaaS geospatial services. The platform could serve as a foundational tool for building custom OSINT pipelines, feeding intelligence into AI agents that analyze geopolitical or security-relevant physical assets (e.g., data centers, military sites, power infrastructure), or integrating with your own automation workflows. Its NLP-based query parsing means you can plug it directly into LLM-powered systems without manually crafting Overpass queries. Additionally, its focus on real-world infrastructure makes it valuable for security research, competitive intelligence, and any work requiring geospatial data extraction at scale.

## Key Features & Technologies
- Leaflet.js map visualization
- Overpass Turbo API integration
- NLP engine for query parsing
- Geocoding functionality
- 30+ infrastructure categories (200+ asset types)
- Self-hosted backend/frontend architecture
- Search bar and filters UI

## Difference from Others
Compared to generic OSM querying tools or raw Overpass Turbo usage, Sightline stands out by offering a curated interface focused on infrastructure intelligence rather than general-purpose mapping. While projects like GeoOSINT focus on broader OSINT capabilities or tools like Overpass Turbo are lower-level APIs, Sightline bridges the gap by providing specialized categories (e.g., military installations, surveillance cameras) and natural language query support. Its UI-driven approach means users don't need to write custom Overpass queries to explore OSM data—they can search in plain English and get structured results mapped on Leaflet.

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
