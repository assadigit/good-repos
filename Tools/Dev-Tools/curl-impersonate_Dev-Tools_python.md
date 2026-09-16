---
source: https://github.com/lwthiker/curl-impersonate
aliases:
  - curl-impersonate
  - lwthiker/curl-impersonate
tags: [python, curl, https, tls, security, open-source, ssl, shell, makefile, dockerfile, c]
category: Dev-Tools
stars: 6467
org: lwthiker
primary_language: Python
languages: [Python, Shell, Makefile, Dockerfile, C]
credibility_score: 51.0/100
date_processed: 2026-07-06
last_release: 2024-03-02
cover: attachments/banners/curl-impersonate_banner.png

---

![banner](attachments/banners/curl-impersonate_banner.png)

# curl-impersonate

**`lwthiker/curl-impersonate`** · ⭐ 6,467 · 🔧 Python

## What is it?
A special build of curl that impersonates Chrome, Edge, Safari & Firefox, performing TLS and HTTP handshakes identical to real browsers. It can be used either as a command line tool, similar to the regular curl, or as a library that can be integrated instead of the regular libcurl.

Use cases include testing services that verify browser identity, bypassing fingerprinting defenses, and self-hosted scraping where you need realistic client behavior.

Core functionality: modifies the TLS Client Hello (SNI, ALPN, certificate fingerprints) and HTTP headers to match major browsers; built on libcurl, preserving all original curl features.

## How does it work?
It extends libcurl by modifying the TLS Client Hello messages to match browser fingerprints (e.g., SNI, ALPN, certificate hashes), and sends appropriate HTTP headers (User-Agent, Accept-Language, etc.) that real browsers use. The code is sourced from curl's repository with patches applied; Docker images are provided for easy deployment.

## Why is it important? (Core Value)
curl-impersonate offers a self-hosted, open-source solution for scenarios where you need to access websites that block non-browser clients (e.g., certain APIs, captcha sites, or services that check TLS fingerprints). It can be integrated into existing CLI workflows or as a library replacement, making it useful for developers who want precise control over HTTP client behavior without relying on cloud scrapers. Additionally, because it's built on curl, it inherits all of curl's robustness and can be combined with other tools (e.g., jq, awk) for data extraction pipelines.

## Key Features & Technologies
- Impersonates Chrome, Edge, Safari & Firefox
- Works as a CLI tool (like regular curl)
- Provides a libcurl replacement for integration
- Emulates TLS Client Hello fingerprints (SNI, ALPN, cert hashes)
- Modifies HTTP headers to match browser behavior
- Built on libcurl (inherits all curl functionality)
- Open-source (fork of curl)

## Difference from Others
It's a direct fork of curl, so it retains all curl's capabilities plus browser impersonation; unlike generic HTTP clients or browser automation tools (e.g., Playwright, Selenium), this tool is specifically for command-line and library use with realistic TLS handshakes; it doesn't require running a full browser instance, making it lightweight and privacy-friendly; also provides Docker images for easy deployment.

## 🏢 Organization & Credibility
- **Developer:** lwthiker
- **Reputation:** Unknown
- **Stars:** 6,467
- **Forks:** 510
- **Recent Activity:** 0 commits in 3 months
- **Credibility Score:** 51.0/100 (Low)
- **Languages:** Python, Shell, Makefile, Dockerfile, C
- **Last Release:** 2024-03-02
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
*Source: [GitHub](https://github.com/lwthiker/curl-impersonate)*
