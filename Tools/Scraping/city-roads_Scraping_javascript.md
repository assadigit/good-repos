---
source: https://github.com/anvaka/city-roads
aliases:
  - city-roads
  - anvaka/city-roads
tags: [javascript, javascript, openstreetmap, overpass, visualization, scraping, vue, html, stylus, shell]
category: Scraping
stars: 9414
org: anvaka
primary_language: JavaScript
languages: [JavaScript, Vue, HTML, Stylus, Shell]
credibility_score: 49.5/100
date_processed: 2026-07-05

cover: attachments/banners/city-roads_banner.png

---

![banner](attachments/banners/city-roads_banner.png)

# city-roads

> **TL;DR:** Visualizes every road in any city using OpenStreetMap data with fast cache lookups.

**`anvaka/city-roads`** · ⭐ 9,414 · 🔧 JavaScript

## What is it?
city-roads is a self-hosted web application that renders every single road within any city at once through an interactive map interface. The project fetches geospatial data from OpenStreetMap using the overpass API, which provides free access to OSM data under the ODbL license. The application includes a search box where users can type in city or area names to find and display their road networks.

## How does it work?
The project employs a multi-layered approach to handle large-scale data retrieval efficiently. Data is fetched from OpenStreetMap via the overpass API, though this API can be rate-limited and slow when downloading thousands of roads. To mitigate performance issues, the developer indexed approximately 3,000 cities with populations exceeding 100,000 and stored them in a protobuf format in a separate repository. Name resolution is handled by nominatim - for any search query, it returns area IDs, which are then checked against the cached large cities list before falling back to overpass if not present.

## Why is it important? (Core Value)
This project is particularly valuable for developers interested in self-hosted alternatives to SaaS products and geospatial data visualization tools. As a software engineer focused on developer productivity and open-source projects, city-roads offers a practical example of performance optimization through caching strategies - specifically how to handle rate-limited API calls by pre-indexing frequently accessed data. The project demonstrates useful patterns for web scraping and data extraction workflows, which aligns with interests in automation and infrastructure development. Additionally, the included scripting capabilities via the scene API provide reference material for building custom geospatial applications on top of OSM data.

## Key Features & Technologies
- Uses OpenStreetMap overpass API
- Caches ~3,000 large cities in protobuf format
- Integrates with nominatim for name resolution
- Provides scene API for scripting
- Self-hosted web UI
- Open-source under ODbL license
- GitHub repository with examples

## Difference from Others
Unlike generic OpenStreetMap viewers that may not preload data or offer scripting capabilities, city-roads specifically optimizes for rendering all roads at once with its cache of major cities. It also differs from commercial mapping services by being self-hosted and free. The project stands out as a focused utility rather than a general-purpose OSM frontend - it's designed for developers who need reliable access to OSM road data and want to understand caching strategies for API-heavy workflows.

## 🏢 Organization & Credibility
- **Developer:** anvaka
- **Reputation:** Unknown
- **Stars:** 9,414
- **Forks:** 720
- **Recent Activity:** 0 commits in 3 months
- **Credibility Score:** 49.5/100 (Low)
- **Languages:** JavaScript, Vue, HTML, Stylus, Shell
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
*Source: [GitHub](https://github.com/anvaka/city-roads)*
