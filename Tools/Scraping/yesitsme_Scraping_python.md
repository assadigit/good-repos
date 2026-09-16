---
source: https://github.com/0x0be/yesitsme
aliases:
  - yesitsme
  - 0x0be/yesitsme
tags: [python, python, osint, instagram, scraping, toutatis, open-source-intelligence, socmint, social-media-intelligence, social-media-analysis, osint-tools, url]
category: Scraping
stars: 2933
org: 0x0be
primary_language: Python
languages: [Python, url]
credibility_score: 44.5/100
date_processed: 2026-07-22

cover: attachments/banners/yesitsme_banner.png

---

![banner](attachments/banners/yesitsme_banner.png)

# yesitsme

**`0x0be/yesitsme`** · ⭐ 2,933 · 🔧 Python

## What is it?
yesitsme is a Python OSINT script that locates Instagram profiles matching a given name and email/phone number. It leverages dumpor.com's indexing capabilities to retrieve all usernames associated with a target name, then compares the fetched toutatis-obfuscated email addresses and phone numbers against user-provided inputs (first/last letter of email, area code + last two digits of phone). This saves significant time during online investigations by automating the cross-referencing process.

## How does it work?
The project is a command-line Python script that requires an Instagram session cookie (socketpuppet) to authenticate requests. It makes HTTP calls to dumpor.com's API endpoints to fetch Instagram usernames matching the provided name, then uses the toutatis library to handle the obfuscated email/phone data returned by dumpor. The script compares these against user-specified partial identifiers and outputs matching accounts. It includes a configurable timeout between requests to avoid rate-limiting issues.

## Why is it important? (Core Value)
For your interests in scraping, automation, and self-hosted alternatives to SaaS products, yesitsme represents a practical OSINT scraping tool that demonstrates the dumpor.com API workflow. It's particularly relevant given your focus on learning new approaches to scraping — this project cleanly encapsulates name-based Instagram data extraction with partial email/phone matching. Additionally, as a self-contained Python script it qualifies as a credible self-hostable alternative to commercial OSINT tools like SocialBlade or specialized SaaS platforms that charge per lookup.

## Key Features & Technologies
- Uses dumpor.com indexing API
- Leverages toutatis obfuscation library for email/phone matching
- Requires Instagram session cookie (socketpuppet)
- CLI interface with -s/-n/-e/-p/-t arguments
- Python implementation
- Self-hostable and open-source
- Includes timeout parameter to prevent rate-limiting

## Difference from Others
Unlike commercial OSINT platforms that charge per lookup or offer bulk account lookups, yesitsme is a free, self-hosted Python script specifically targeting Instagram via dumpor.com. It differs from other OSINT tools by using toutatis obfuscation for email/phone matching rather than direct full-email queries. Compared to broader social media scrapers (e.g., generic Instagram scraping repos), this project focuses narrowly on name-based discovery with partial identifier matching, making it more specialized for investigative workflows.

## 🏢 Organization & Credibility
- **Developer:** 0x0be
- **Reputation:** Unknown
- **Stars:** 2,933
- **Forks:** 301
- **Recent Activity:** 0 commits in 3 months
- **Credibility Score:** 44.5/100 (Low)
- **Languages:** Python, url
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
*Source: [GitHub](https://github.com/0x0be/yesitsme)*
