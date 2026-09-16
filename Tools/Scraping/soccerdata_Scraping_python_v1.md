---
source: https://github.com/probberechts/soccerdata
aliases:
  - soccerdata
  - probberechts/soccerdata
tags: [python, python, scraping, soccer, sports-data, data-extraction, soccer-analytics, soccer-data, elo-rating, espn, fbref, fivethirtyeight]
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

> **TL;DR:** Python library for scraping soccer/football data from Club Elo, ESPN, FBref, Sofascore, SoFIFA, Understat, and WhoScored.

**`probberechts/soccerdata`** · ⭐ 2,020 · 🔧 Python

## What is it?
soccerdata is a Python library that aggregates soccer/football data from multiple popular sources, including Club Elo, ESPN, FBref, Football-Data.co.uk, Sofascore, SoFIFA, Understat, and WhoScored. It provides a unified API to access match results, player statistics, Elo ratings, and other soccer data that would otherwise require separate scraping scripts for each source. The library is published on PyPI, Apache-2.0 licensed, and well-documented via Read the Docs.

The project is maintained with modern development practices, including CI/CD workflows, Codecov coverage tracking, pre-commit hooks, and Black formatting. It serves as a one-stop shop for soccer analytics in Python, abstracting away the complexity of querying heterogeneous data providers behind a consistent interface.

Key capabilities include access to Elo ratings, player and club information, match statistics, and transfer data across all supported sources, enabling analysts and researchers to build soccer analytics pipelines without writing custom scrapers for each provider.

## How does it work?
The project is structured as a Python package with dedicated modules for each data source. Each source adapter handles HTTP requests to the respective API or web pages, parses the responses (JSON, XML, or HTML), and returns structured data, typically as pandas DataFrames. Users can query specific endpoints for matches, players, ratings, and other entities through a consistent API. The library relies on standard Python web scraping techniques (requests, HTML/XML parsing) to extract and normalize data from each provider into a common format.

## Why is it important? (Core Value)
For the user, this project is directly relevant to their stated interest in learning about new approaches to scraping. It demonstrates a well-structured, maintainable pattern for building a multi-source data scraping library in Python, with clean abstractions over heterogeneous data sources—useful as a reference architecture for building similar data aggregation tools. Additionally, if the user ever needs sports data for analysis, ML experiments, or a personal project, this library provides ready-made access to that data. The project's focus on scraping aligns with the user's objective to identify tools and approaches in the scraping and automation space.

## Key Features & Technologies
- Multi-source scraping: Club Elo, ESPN, FBref, Sofascore, SoFIFA, Understat, WhoScored
- Python package published on PyPI with Read the Docs documentation
- Apache-2.0 licensed open-source project
- Elo rating, player, club, and match statistics access
- CI/CD with GitHub Actions, Codecov, pre-commit, and Black
- pandas DataFrame output for analytics workflows

## Difference from Others
Compared to ad-hoc scraping scripts or general-purpose frameworks like Scrapy, soccerdata provides a domain-specific, unified interface across 8+ soccer data sources, eliminating the need to write and maintain separate scrapers for each provider. Compared to paid sports data APIs, it is free and open-source. Its niche focus on soccer makes it more opinionated and convenient than generic scraping tools, while its multi-source coverage sets it apart from single-source data providers.

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
