---
source: https://github.com/c2g-dev/city2graph
aliases:
  - city2graph
  - c2g-dev/city2graph
tags: [python, python, geoai, graph-neural-networks, network-analysis, pytorch-geometric, spatial-analysis, geographical-information-system, pytorch, geographic-data-science, graph-representation-learning, mobility]
category: Research
stars: 1320
org: c2g-dev
primary_language: Python
languages: [Python, Dockerfile, url]
credibility_score: 62.0/100
date_processed: 2026-07-09
last_release: 2026-06-11


---

# city2graph

**`c2g-dev/city2graph`** · ⭐ 1,320 · 🔧 Python

## What is it?
City2Graph is a Python library that transforms geospatial datasets into graph representations, integrating GeoPandas, NetworkX, and PyTorch Geometric for domains like streets, transportations, OD matrices, and POI proximities. It enables researchers and practitioners to develop advanced GeoAI and geographic data science applications.

## How does it work?
City2Graph reads geospatial data (e.g., shapefiles, OpenStreetMap extracts) via GeoPandas, constructs graph nodes and edges representing streets, transport routes, origin-destination pairs, and points of interest using NetworkX, then outputs a PyG-compatible edge list or node features that can be consumed by GNN models. It provides utility functions to convert between GeoJSON and graph formats, handling coordinate transformations and attribute mapping.

## Why is it important? (Core Value)
City2Graph offers a self-hosted solution for converting geospatial data into graph representations, reducing reliance on SaaS APIs like Google Maps or OpenStreetMap extraction services. While not an AI agent or MCP server, it can be used as a data pipeline component for custom GeoAI applications, aligning with the user's interest in self-hostable alternatives and developer tools. It enables researchers to develop advanced geographic data science applications without vendor lock-in, making it particularly valuable for open-source geospatial workflows.

## Key Features & Technologies
- Uses GeoPandas
- Uses NetworkX
- Uses PyTorch Geometric
- Python
- Open-source (BSD-3-Clause)
- Self-hostable (PyPI/conda-forge)
- Graph representation for streets, transportations, OD matrices, POI proximities

## Difference from Others
Unlike using GeoPandas, NetworkX, and PyTorch Geometric separately, City2Graph provides a single library that handles the conversion pipeline end-to-end, simplifying graph construction for geospatial data. It also includes domain-specific functions (e.g., OD matrices, POI proximities) that other libraries don't provide.

## 🏢 Organization & Credibility
- **Developer:** c2g-dev
- **Reputation:** Unknown
- **Stars:** 1,320
- **Forks:** 138
- **Recent Activity:** 52 commits in 3 months
- **Credibility Score:** 62.0/100 (Average)
- **Languages:** Python, Dockerfile, url
- **Last Release:** 2026-06-11
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
*Source: [GitHub](https://github.com/c2g-dev/city2graph)*
