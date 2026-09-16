---
source: https://github.com/opengeos/GeoLibre
aliases:
  - GeoLibre
  - opengeos/GeoLibre
tags: [typescript, rust, geospatial, maplibre, duckdb, tauri, data-science, maplibre-gl-js, tauri-app, python, css, javascript]
category: Dev-Tools
stars: 1754
org: opengeos
primary_language: TypeScript
languages: [TypeScript, Python, Rust, CSS, JavaScript]
credibility_score: 62.0/100
date_processed: 2026-07-17
last_release: 2026-07-14
cover: attachments/banners/GeoLibre_banner.png

---

![banner](attachments/banners/GeoLibre_banner.png)

# GeoLibre

> **TL;DR:** Open-source GIS platform for web, desktop, and notebooks with MapLibre and DuckDB.

**`opengeos/GeoLibre`** · ⭐ 1,754 · 🔧 TypeScript

## What is it?
GeoLibre is a lightweight, cloud-native GIS platform that lets you visualize, explore, and analyze geospatial data directly in your browser, on the desktop, on mobile devices, or inside Jupyter notebooks. It serves as an open-source alternative to heavyweight GIS software, offering a modern web-first experience built on MapLibre for rendering maps and DuckDB for fast in-process SQL queries.

The project provides a rich API for loading GeoJSON, Shapefile, and other common geospatial formats, performing spatial joins, aggregations, and statistical analyses without needing a dedicated GIS server. Its Tauri-based desktop app wraps the same web UI, delivering native performance while keeping the codebase shared across platforms.

Beyond core mapping, GeoLibre includes a plugin system for extending functionality (e.g., custom data sources, analysis tools) and offers shared project hosting so you can collaborate on datasets and visualizations. It is packaged on PyPI and Conda, making it easy to install in any Python environment, and even provides an App Store listing for Windows users.

## How does it work?
The platform is built around three pillars: MapLibre GL JS for rendering interactive maps, DuckDB as the in-process SQL engine for geospatial queries, and Tauri for cross-platform desktop packaging. Data ingestion works via a web API that accepts JSON payloads or file uploads; once loaded, DuckDB indexes the geometry and attribute columns, enabling fast spatial filters and aggregations. The UI layer is a React-based web app that communicates with the backend through WebSockets or HTTP endpoints, while the Tauri wrapper injects the same UI into a native window.

Because the rendering engine runs in the browser, GeoLibre can be embedded directly into Jupyter notebooks (via iframe or JS widget), allowing data scientists to prototype analyses without installing extra software. The plugin architecture lets developers contribute custom widgets or analysis steps that hook into the core API, preserving backward compatibility across versions.

## Why is it important? (Core Value)
GeoLibre matters because it solves the problem of having a GIS tool that works everywhere without requiring a server or heavy dependencies. For developers who want self-hosted alternatives to SaaS GIS platforms, it provides an open-source stack that can be deployed on any machine or homelab. It aligns with your interest in data-science tooling and automation: you can load geospatial datasets into DuckDB inside a notebook, run queries, and instantly visualise results—all without installing QGIS or ArcGIS.

Specifically, the project will help you by giving you a lightweight GIS that integrates cleanly with Python notebooks and can be packaged as a Tauri app for desktop use. Its plugin ecosystem means you can extend it with custom data sources or analysis steps, supporting your goal of discovering tools that improve development workflow. Additionally, GeoLibre's packaging on PyPI and Conda makes it easy to pull into existing projects, while its shared project hosting enables collaboration—matching your interest in self-hostable software and developer productivity.

## Key Features & Technologies
- MapLibre GL JS rendering
- DuckDB in-process SQL engine
- Tauri desktop app framework
- React UI layer
- Plugin system for extensions

## Difference from Others
Similar projects include QGIS (a full-featured desktop GIS), ArcGIS (enterprise solution), GeoPandas (Python library for geospatial data manipulation), and Leaflet (lightweight mapping library). GeoLibre differentiates itself by being cloud-native and web-first, requiring no installation beyond a browser or Conda package. While QGIS is powerful but heavy and desktop-only, GeoLibre runs in notebooks and on mobile devices, making it ideal for exploratory data analysis. Unlike Leaflet which only provides basic map controls, GeoLibre adds DuckDB for SQL queries and Tauri for native desktop apps, offering a more complete GIS pipeline in a single package.

## 🏢 Organization & Credibility
- **Developer:** opengeos
- **Reputation:** Unknown
- **Stars:** 1,754
- **Forks:** 234
- **Recent Activity:** 758 commits in 3 months
- **Credibility Score:** 62.0/100 (Average)
- **Languages:** TypeScript, Python, Rust, CSS, JavaScript
- **Last Release:** 2026-07-14
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
*Source: [GitHub](https://github.com/opengeos/GeoLibre)*
