---
source: https://github.com/jxlarrea/voice-satellite-card-integration
aliases:
  - voice-satellite-card-integration
  - jxlarrea/voice-satellite-card-integration
tags: [javascript, python, homeassistant, voice-assistant, llm, hacs, hacs-integration, homeassistant-integration, voice-control, hacs-plugin, lovelace, css]
category: LLM-Tools
stars: 464
org: jxlarrea
primary_language: JavaScript
languages: [JavaScript, Python, CSS, url]
credibility_score: 55.5/100
date_processed: 2026-07-06
last_release: 2026-06-18
cover: attachments/banners/voice-satellite-card-integration_banner.png

---

![banner](attachments/banners/voice-satellite-card-integration_banner.png)

# voice-satellite-card-integration

> **TL;DR:** HACS plugin that adds hands-free voice control to Home Assistant via Voice Satellite integration.

**`jxlarrea/voice-satellite-card-integration`** · ⭐ 464 · 🔧 JavaScript

## What is it?
Voice Satellite Card Integration is a Home Assistant Community Store (HACS) plugin that enables hands-free voice control within the Home Assistant ecosystem. By connecting to the Voice Satellite API, it transforms tablets, phones, and browsers into voice assistants that can trigger Home Assistant actions, query device states, and manage automation routines. The integration leverages speech recognition models to convert spoken commands into structured text, which is then processed—often via a lightweight LLM or rule-based parser—to identify intents such as 'turn on lights', 'show weather', or 'play music'.

## How does it work?
The plugin installs as a standard Home Assistant component and registers custom cards in LoVeLaCe (the frontend UI). At runtime, it listens for voice input through the Voice Satellite service, which streams audio to a speech-to-text model. The resulting transcript is sent to an NLU module that maps natural language phrases to Home Assistant service calls. All communication happens over local APIs (MQTT or REST), ensuring privacy and low latency. Because it runs entirely within the user's Home Assistant instance, no cloud APIs are required beyond the Voice Satellite backend.

## Why is it important? (Core Value)
For a self-hosted enthusiast focused on AI agents and developer tools, this project offers a privacy-friendly, self-hosted voice assistant that can be combined with any LLM or agent framework you already use. Unlike commercial solutions (Amazon Alexa, Google Assistant), it keeps all processing local or on your own server, aligning perfectly with the goal of finding self-hostable alternatives to SaaS products. Additionally, because it integrates via HACS, it's easy to deploy and update alongside other Home Assistant add-ons, making it a practical building block for automating voice-controlled workflows in a homelab.

## Key Features & Technologies
- HACS integration
- Voice Satellite API
- Speech-to-text integration
- Natural language understanding
- Home Assistant service calls
- LoVeLaCe UI cards
- Self-hosted

## Difference from Others
Other Home Assistant voice integrations typically rely on the built-in 'voice_assistant' component or commercial cloud services like Amazon Alexa or Google Assistant. This project differentiates itself by using Voice Satellite as a dedicated backend, which may offer more flexible prompt handling and better privacy guarantees. It also provides a HACS plugin format, making installation one-click through the community store rather than manual YAML editing. The integration is specifically designed to work with LoVeLaCe cards, giving a modern UI experience compared to older Lovelace dashboards.

## 🏢 Organization & Credibility
- **Developer:** jxlarrea
- **Reputation:** Unknown
- **Stars:** 464
- **Forks:** 16
- **Recent Activity:** 208 commits in 3 months
- **Credibility Score:** 55.5/100 (Low)
- **Languages:** JavaScript, Python, CSS, url
- **Last Release:** 2026-06-18
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
*Source: [GitHub](https://github.com/jxlarrea/voice-satellite-card-integration)*
