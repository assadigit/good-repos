---
source: https://github.com/probberechts/soccerdata
aliases:
  - soccerdata
  - probberechts/soccerdata
tags: [python, python, soccer, sports-data, scraping, pandas, soccer-analytics, soccer-data, elo-rating, espn, fbref, fivethirtyeight]
category: Scraping
stars: 2020
org: probberechts
primary_language: Python
languages: [Python, Makefile, url]
credibility_score: 54.5/100
date_processed: 2026-08-19
last_release: 2026-07-24
cover: attachments/banners/soccerdata_banner.png

---

![banner](attachments/banners/soccerdata_banner.png)

# soccerdata

> **TL;DR:** Python library for scraping soccer data from Club Elo, ESPN, FBref, Sofascore, SoFIFA, Understat, and WhoScored into pandas.

**`probberechts/soccerdata`** · ⭐ 2,020 · 🔧 Python

## What is it?
SoccerData is a Python library for scraping and accessing soccer data from multiple public sports data sources. It covers team and player information, ratings, and Elo ratings from Club Elo, ESPN, FBref, Football-Data.co.uk, Sofascore, SoFIFA, Understat, and WhoScored.

The project is intended for sports analytics, data science, and machine-learning workflows. It provides Python APIs that return pandas-compatible data, making it easier to combine several soccer datasets in one analysis pipeline. Documentation, tests, and pre-commit tooling indicate it is maintained as a reusable open-source package.

## How does it work?
SoccerData acts as a Python wrapper around multiple soccer data providers. Instead of writing separate scrapers, users call source-specific functions or APIs to retrieve team, player, rating, and Elo data. The results are exposed as pandas DataFrames, enabling immediate use with pandas, NumPy, and machine-learning libraries.

It is a client library rather than a generic crawler: it focuses on known soccer data endpoints and datasets, normalizes outputs, and supports common analytics workflows. The project is maintained with CI tests, pre-commit, and Black formatting, and published on PyPI.

## Why is it important? (Core Value)
For a developer focused on scraping, automation, and self-hosted tools, SoccerData is a ready-made sports data extraction layer. It reduces the effort required to build and maintain scrapers for soccer sources, and it demonstrates patterns for combining multiple APIs into pandas workflows. It can be used to build analytics dashboards, prediction models, or automated data pipelines.

Its value is domain-specific: rather than a general scraper, it provides curated soccer datasets and ratings. This helps the user quickly prototype sports analytics or add structured soccer data to AI/LLM agent tools, MCP integrations, or automation workflows.

## Key Features & Technologies
- Python package published on PyPI with Read the Docs documentation.
- Scrapes soccer data from Club Elo, ESPN, FBref, Football-Data.co.uk, Sofascore, SoFIFA, Understat, and WhoScored.
- Provides pandas-compatible outputs for sports analytics and machine learning.
- Includes Elo ratings and soccer-specific datasets.
- Open-source project with CI tests, pre-commit, and Black formatting.

## Difference from Others
Compared with generic web-scraping libraries, SoccerData is specialized for soccer data and provides multiple sources behind one Python interface. Compared with a single sports API, it spans several providers and datasets, including Elo ratings and soccer-specific ratings, which is useful for comparative analytics. It is not an AI agent or agent framework; its strength is reliable, domain-specific data access for sports data pipelines.

## 🏢 Organization & Credibility
- **Developer:** probberechts
- **Reputation:** Unknown
- **Stars:** 2,020
- **Forks:** 313
- **Recent Activity:** 22 commits in 3 months
- **Credibility Score:** 54.5/100 (Low)
- **Languages:** Python, Makefile, url
- **Last Release:** 2026-07-24
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
*Source: [GitHub](https://github.com/probberechts/soccerdata)*
