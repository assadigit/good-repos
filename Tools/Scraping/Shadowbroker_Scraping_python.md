---
source: https://github.com/BigBodyCobain/Shadowbroker
aliases:
  - Shadowbroker
  - BigBodyCobain/Shadowbroker
tags: [python, python, nextjs, fastapi, osint, adsb, osint-resources, osint-tool, asdb, cctv, cctv-cameras, cctv-surveillance]
category: Scraping
stars: 9564
org: BigBodyCobain
primary_language: Python
languages: [Python, TypeScript, Rust, JavaScript, Shell]
credibility_score: 67.0/100
date_processed: 2026-07-05
last_release: 2026-06-15
cover: attachments/banners/Shadowbroker_banner.png

---

![banner](attachments/banners/Shadowbroker_banner.png)

# Shadowbroker

> **TL;DR:** Real-time OSINT map aggregating aircraft, satellites, CCTV, and geopolitical feeds for AI-driven threat analysis.

**`BigBodyCobain/Shadowbroker`** · ⭐ 9,564 · 🔧 Python

## What is it?
**ShadowBroker** is a decentralized intelligence platform that aggregates real-time, multi-domain OSINT telemetry from 60+ live feeds into a single dark-ops map interface. It streams data on aircraft, ships, satellites, conflict zones, CCTV networks, GPS jamming, internet-connected devices, police scanners, mesh radio nodes, and breaking geopolitical events — all updating in real time on one screen as well as an obfuscated communications protocol and information exchange infrastructure.

Built with **Next.js**, **MapLibre GL**, **FastAPI**, and **Python**, it offers 40+ toggleable data layers ranging from SAR ground-change detection to Telegram OSINT previews geoparsed onto the map, a server-side recon toolkit (DNS, WHOIS, sanctions, BGP, IP sweep), supply-chain risk overlays, malware/C2 feeds, and CISA KEV cyber threat feeds. Multiple visual modes (DEFAULT / SATELLITE / FLIR / NVG / CRT) let users switch context, while right-click any point on Earth yields a country dossier, head-of-state lookup, entity-graph expansion, and the latest Sentinel-2 satellite photo.

The platform is explicitly designed to be hooked by AI agents, allowing them to parse through the aggregated data and discover previously unseen correlations. Its open design and real-time nature make it a valuable asset for researchers, security analysts, and developers who need a self-hostable OSINT infrastructure that can feed downstream automation pipelines.

## How does it work?
The platform uses a client-server architecture: a Next.js front-end renders the map with MapLibre GL, while a FastAPI back-end in Python ingests streams from 60+ telemetry sources, applies server-side recon logic (DNS, WHOIS, BGP, IP sweep), and serves data layers via REST endpoints. Data pipelines run continuously to update the map in real time; background workers enrich each point with contextual information (e.g., SAR detection, malware C2 feeds). Visual modes are swapped by the UI, and contextual actions (right-click) trigger additional lookups that query external services and return enriched metadata.

## Why is it important? (Core Value)
ShadowBroker directly supports your objective of finding self-hostable alternatives to SaaS by offering a fully open-source geospatial intelligence platform you can run on your own infrastructure. Its server-side recon toolkit (DNS, WHOIS, BGP, IP sweep) gives you a ready-made scraping and automation foundation that integrates with existing AI-agent pipelines, letting you feed real-time telemetry into downstream analysis without relying on commercial OSINT services.

Because the platform is explicitly built to be hooked by AI agents, it fits your interest in AI/LLM tooling: you can plug a research or monitoring agent into ShadowBroker's data streams to discover correlations you would otherwise miss. Its modular architecture (Next.js UI, FastAPI backend, MapLibre GL) means you can extend it with MCP servers, custom tools, or embed it into your Obsidian vault notes as a reference resource.

## Key Features & Technologies
- Built with Next.js and MapLibre GL
- Aggregates 60+ live OSINT feeds (ADS-B, satellite imagery, CCTV)
- Server-side recon toolkit (DNS, WHOIS, BGP, IP sweep)
- 40+ toggleable data layers including SAR detection and Telegram OSINT
- Multiple visual modes (DEFAULT / SATELLITE / FLIR / NVG / CRT)
- Right-click context actions (country dossier, Sentinel-2 photo)
- FastAPI backend in Python

## Difference from Others
Unlike static OSINT dashboards such as Maltego or generic data-aggregation tools, ShadowBroker is purpose-built for real-time multi-domain telemetry and includes 40+ layers ranging from SAR ground-change detection to Telegram channel previews. Its server-side recon toolkit (DNS, WHOIS, BGP) offers deep network-level scraping that many competitors lack, and the obfuscated communications protocol enables secure information exchange between agents.

The platform also integrates AI-agent hooks for correlation analysis, a feature not present in most OSINT tools. This combination of live data streams, extensive layer options, and agent-ready design makes it uniquely positioned for researchers who need both breadth (geopolitical events, aircraft tracking) and depth (network recon, malware C2) in a single interface.

## 🏢 Organization & Credibility
- **Developer:** BigBodyCobain
- **Reputation:** Unknown
- **Stars:** 9,564
- **Forks:** 1489
- **Recent Activity:** 208 commits in 3 months
- **Credibility Score:** 67.0/100 (Average)
- **Languages:** Python, TypeScript, Rust, JavaScript, Shell
- **Last Release:** 2026-06-15
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
*Source: [GitHub](https://github.com/BigBodyCobain/Shadowbroker)*
