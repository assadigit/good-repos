---
source: https://github.com/wp-statistics/GeoLite2-City
aliases:
  - GeoLite2-City
  - wp-statistics/GeoLite2-City
tags: [geoip, maxmind, cdn, scraping, php, city, ip, location, url]
category: Scraping
stars: 759
org: wp-statistics

languages: [url]
credibility_score: 49.5/100
date_processed: 2026-07-05

cover: attachments/banners/GeoLite2-City_banner.png

---

![banner](attachments/banners/GeoLite2-City_banner.png)

# GeoLite2-City

> **TL;DR:** Free MaxMind GeoLite2-City database for IP geolocation, auto-updated and served via jsDelivr CDN.

**`wp-statistics/GeoLite2-City`** · ⭐ 759 · 🔧 N/A

## What is it?
This project provides a free MaxMind GeoLite2-City database for IP geolocation, allowing users to retrieve city-level location data from any IP address without requiring API keys or authentication. It is automatically updated every Tuesday and Friday, ensuring the data remains current with the latest IP allocations. The database is served via jsDelivr CDN, which caches it at global edge locations for fast delivery worldwide. It is released under the CC BY-SA 4.0 license, making it suitable for both personal and commercial use with proper attribution.

## How does it work?
The project hosts the MaxMind GeoLite2-City.mmdb.gz file on jsDelivr CDN, which handles caching and distribution globally. Updates are automated via a scheduled process (likely GitHub Actions or cron) that fetches new data from MaxMind's repository every Tuesday and Friday. Users can directly download the gzipped .mmdb file from the CDN URL provided in the README, or integrate it into their systems via PHP using MaxMind's library as shown in the example code snippet.

## Why is it important? (Core Value)
For a software engineer focused on self-hosted tools and automation, this project is invaluable because it offers a free, open-source alternative to paid IP geolocation APIs like ipapi.co or ip-api.com. It eliminates the need for API key management, rate limit handling, or subscription costs, making it ideal for building reliable data pipelines. The auto-updated nature ensures minimal maintenance effort, and the jsDelivr CDN guarantees low-latency access globally, which is crucial for distributed systems. Additionally, its permissive license allows seamless integration into commercial products with proper attribution.

## Key Features & Technologies
- Auto-updated every Tuesday & Friday
- Served via jsDelivr CDN
- No authentication required
- Free forever under CC BY-SA 4.0
- City-level accuracy (country, city, coordinates, timezone)

## Difference from Others
Compared to other IP geolocation services, this project stands out for being completely free without API keys or rate limits, unlike ipapi.co or ip-api.com which require subscriptions. It uses jsDelivr CDN for fast global delivery, whereas many alternatives host directly on GitHub, which can be slower and less reliable. Additionally, it is released under a permissive CC BY-SA 4.0 license, making it suitable for commercial use with attribution, unlike some paid services that restrict redistribution.

## 🏢 Organization & Credibility
- **Developer:** wp-statistics
- **Reputation:** Unknown
- **Stars:** 759
- **Forks:** 92
- **Recent Activity:** 26 commits in 3 months
- **Credibility Score:** 49.5/100 (Low)
- **Languages:** url
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
*Source: [GitHub](https://github.com/wp-statistics/GeoLite2-City)*
