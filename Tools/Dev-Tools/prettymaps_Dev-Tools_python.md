---
source: https://github.com/marceloprates/prettymaps
aliases:
  - prettymaps
  - marceloprates/prettymaps
tags: [python, python, maps, openstreetmap, matplotlib, data-visualization, jupyter-notebook, generative-art, cartography, shell, url]
category: Dev-Tools
stars: 14157
org: marceloprates
primary_language: Python
languages: [Python, Shell, url]
credibility_score: 60.0/100
date_processed: 2026-09-01
last_release: 2025-03-03
cover: attachments/banners/prettymaps_banner.png

---

![banner](attachments/banners/prettymaps_banner.png)

# prettymaps

> **TL;DR:** Minimal Python library that generates customized map visuals from OpenStreetMap data using osmnx, matplotlib, and shapely.

**`marceloprates/prettymaps`** · ⭐ 14,157 · 🔧 Python

## What is it?
prettymaps is a minimal Python library designed to draw customized maps from OpenStreetMap (OSM) data. It wraps the osmnx, matplotlib, shapely, and vsketch packages into a concise API for producing aesthetically styled map visualizations without requiring users to manually orchestrate each rendering step. The project is distributed via PyPI, requires Python 3.11 or later, and is licensed under the GNU AGPL v3.0.

The library targets developers who want quick, reproducible map figures for reports, presentations, or generative-art workflows. It ships with Jupyter Notebook examples and a GitHub Pages documentation site, making it easy to explore styling options interactively. The author emphasizes proper attribution to both the repository and OpenStreetMap's copyright terms, and notably expresses a strong personal stance against NFTs due to environmental and ethical concerns.

With over 14,000 stars and roughly 724 forks, prettymaps has become a go-to reference for programmatic cartography in Python. Its scope is intentionally narrow—focusing on clean, stylized map rendering rather than full GIS analysis—which keeps the dependency footprint small and the learning curve gentle.

## How does it work?
Under the hood, prettymaps pulls geospatial data (roads, waterways, land polygons, etc.) through osmnx's OSM extraction pipeline, applies geometric operations via shapely to clean and style features, and renders the final figure with matplotlib. The vsketch package is used to give outputs a hand-drawn or sketch-like aesthetic. The library exposes a small set of configuration parameters so users can swap color palettes, toggle feature layers, and adjust line weights without touching the underlying rendering code.

Because it sits on top of well-established geospatial and plotting libraries, prettymaps avoids reimplementing map projection or vector-drawing logic. Instead, it acts as a thin orchestration layer that chains those tools together with sensible defaults, which is why the README describes it as "minimal."

## Why is it important? (Core Value)
For a software engineer and researcher focused on developer tools and automation, prettymaps offers a lightweight, self-hosted Python library for producing publication-quality map figures without leaving the Jupyter or script-based workflow. It fits naturally into data-science pipelines where geographic context needs to be rendered alongside other charts, and its small dependency surface (osmnx, matplotlib, shapely, vsketch) makes it easy to pin versions and reproduce outputs in CI.

The project also aligns with the user's interest in self-hostable alternatives: all data comes from the open OpenStreetMap source, no SaaS API keys are required, and the AGPL license permits commercial use as long as the source is disclosed. For someone building an Obsidian-based knowledge base of curated tools, prettymaps serves as a concrete example of how a thin wrapper library can turn multi-step geospatial processing into a one-liner, a pattern that transfers to other domain-specific Python tooling.

## Key Features & Technologies
- Python library distributed on PyPI with Python 3.11+ requirement
- Built on osmnx, matplotlib, shapely, and vsketch for OSM data extraction and rendering
- Customizable map styling (colors, layers, line weights) via a minimal configuration API
- Jupyter Notebook workflow with GitHub Pages-hosted documentation
- AGPL v3.0 open-source license requiring source disclosure for commercial use

## Difference from Others
Compared to using raw osmnx directly, prettymaps abstracts away the multi-step sequence of downloading OSM layers, applying shapely geometry cleanup, and configuring matplotlib artists into a single call, which is especially valuable for developers who need a quick map figure rather than an interactive GIS session. Against full cartography platforms like QGIS or Mapbox Studio, prettymaps deliberately stays in the programmatic, scriptable lane: it produces static vector/raster figures from Python code instead of requiring a GUI.

Its distinguishing niche is the "pretty" factor—styling defaults tuned for visually appealing output (the generative-art topic tag hints at this) rather than technical or analytical cartography. That makes it a complementary tool to heavier GIS stacks: you can run a spatial analysis in GeoPandas and then hand off to prettymaps for the final figure without switching paradigms.

## 🏢 Organization & Credibility
- **Developer:** marceloprates
- **Reputation:** Unknown
- **Stars:** 14,157
- **Forks:** 724
- **Recent Activity:** 9 commits in 3 months
- **Credibility Score:** 60.0/100 (Average)
- **Languages:** Python, Shell, url
- **Last Release:** 2025-03-03
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
*Source: [GitHub](https://github.com/marceloprates/prettymaps)*
