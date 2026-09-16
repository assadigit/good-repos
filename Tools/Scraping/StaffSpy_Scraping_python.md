---
source: https://github.com/cullenwatson/StaffSpy
aliases:
  - StaffSpy
  - cullenwatson/StaffSpy
tags: [python, python, linkedin, scraping, pandas, automation, company-data, linkedin-api, linkedin-bot, linkedin-profile, linkedin-scraper, linkedin-profile-scraper]
category: Scraping
stars: 312
org: cullenwatson
primary_language: Python
languages: [Python, url]
credibility_score: 41.0/100
date_processed: 2026-07-05
last_release: 2025-01-01
cover: attachments/banners/StaffSpy_banner.png

---

![banner](attachments/banners/StaffSpy_banner.png)

# StaffSpy

> **TL;DR:** Python library that scrapes LinkedIn staff profiles (skills, experiences) using browser automation.

**`cullenwatson/StaffSpy`** · ⭐ 312 · 🔧 Python

## What is it?
StaffSpy is a Python library designed to fetch staff information from LinkedIn companies. It allows you to scrape employee data including skills, experiences, certifications, and more, then aggregates all results into a Pandas DataFrame for easy analysis. The library handles the complexity of LinkedIn's UI by using browser automation rather than relying on API endpoints.

## How does it work?
The library creates a LinkedInAccount object that manages browser driver configuration (Selenium/Playwright) and maintains persistent login sessions via cookies saved to a session file. When you call scrape_staff, it navigates to the target company's LinkedIn page using the configured browser, extracts profile data through DOM parsing or selectors, and constructs structured records that are returned as a Python list/dict which can be converted to a Pandas DataFrame. It supports parameters for company name, search term, location, max_results, and extra_profile_data flags.

## Why is it important? (Core Value)
This project is valuable because it provides an out-of-the-box solution for scraping LinkedIn staff data without having to build custom scrapers from scratch. For the user specifically: StaffSpy aligns perfectly with their interest in scraping tools and automation—it's a self-hostable Python library that can be integrated into larger pipelines (e.g., feeding an AI agent that builds professional network graphs or lead-generation workflows). The Pandas DataFrame output makes it easy to import into downstream analysis, and the persistent session feature reduces manual re-login overhead. As a developer tool, it saves significant time compared to writing raw Selenium code.

## Key Features & Technologies
- Uses Selenium for browser automation
- Persists login via cookies in a pickle file
- Returns data aggregated into a Pandas DataFrame
- Supports specifying company name, search term, location
- Extra profile data flag to fetch certifications, schools, etc.
- Maximum results parameter (up to 100)
- Python >= 3.10 required

## Difference from Others
StaffSpy differs from other LinkedIn scrapers in several ways: many alternatives rely on API keys or headless browsers without session persistence, requiring re-login each run. Some use requests-only approaches that break when LinkedIn changes UI—StaffSpy's browser automation makes it more resilient. It also stands out by returning Pandas DataFrames rather than raw lists/dicts, simplifying data analysis. Unlike generic scrapers, it includes built-in support for extra profile metadata (certifications, schools) via the extra_profile_data flag.

## 🏢 Organization & Credibility
- **Developer:** cullenwatson
- **Reputation:** Unknown
- **Stars:** 312
- **Forks:** 43
- **Recent Activity:** 0 commits in 3 months
- **Credibility Score:** 41.0/100 (Low)
- **Languages:** Python, url
- **Last Release:** 2025-01-01
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
*Source: [GitHub](https://github.com/cullenwatson/StaffSpy)*
