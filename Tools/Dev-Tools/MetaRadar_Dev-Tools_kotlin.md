---
source: https://github.com/BLE-Research-Group/MetaRadar
aliases:
  - MetaRadar
  - BLE-Research-Group/MetaRadar
tags: [kotlin, android, ble, security-scanner, open-source, F-Droid, android-ble, bluetooth, scanner, security-tools, radar, url]
category: Dev-Tools
stars: 1456
org: BLE-Research-Group
primary_language: Kotlin
languages: [Kotlin, url]
credibility_score: 46.0/100
date_processed: 2026-07-07
last_release: 2026-01-10
cover: attachments/banners/MetaRadar_banner.png

---

![banner](attachments/banners/MetaRadar_banner.png)

# MetaRadar

> **TL;DR:** Android BLE scanner that tracks nearby Bluetooth devices and notifies on detection.

**`BLE-Research-Group/MetaRadar`** · ⭐ 1,456 · 🔧 Kotlin

## What is it?
MetaRadar is an open-source Android application designed for Bluetooth Low Energy (BLE) environment monitoring. It allows users to scan for nearby BLE devices, track specific targets by MAC address or RSSI threshold, and receive notifications when a target device is detected. The project includes clear educational disclaimers emphasizing its intended use for security research, personal investigation, and testing lawful purposes only.

The tool is distributed via multiple channels including Google Play (with a release build), F-Droid, and IzzyOnDroid repositories, ensuring accessibility to both paid and open-source app stores. Its design prioritizes privacy and transparency, with no endorsement of unlawful activities and full responsibility placed on the user. This makes it suitable for security professionals, researchers, and developers who need a reliable, self-hosted BLE scanning utility without vendor lock-in or proprietary restrictions.

## How does it work?
At its core, MetaRadar leverages Android's native Bluetooth Low Energy scanning APIs to continuously monitor the BLE radio environment. When enabled, the app initiates a background scanning service that listens for advertisement packets from nearby devices, extracting their MAC addresses, device names, and RSSI (received signal strength indicator) values. The application maintains an internal list of target identifiers, which can be configured through the UI or imported from external sources.

Detection logic compares incoming advertisements against the target list, optionally applying filters such as minimum RSSI thresholds to reduce false positives from distant devices. Upon a match, the app triggers a notification event—either an in-app alert or a system-level push notification—alerting the user that the tracked device has been found. All scanning and detection operations run locally on the device, preserving privacy and ensuring no data is sent to remote servers during normal operation.

## Why is it important? (Core Value)
For a software engineer and researcher focused on developer tools and automation, MetaRadar represents a valuable self-hosted utility that complements the broader ecosystem of open-source networking and security scanning projects. Unlike commercial BLE scanners that may be closed-source or vendor-locked, this tool can be integrated into a homelab or personal network monitoring workflow, providing a reliable source for testing BLE-based device tracking, RSSI mapping, and security scanning scripts.

Its educational disclaimer and emphasis on lawful use align with the user's interest in curating credible tools for their knowledge base. By including MetaRadar, the user gains a concrete example of an open-source Android application that can be documented, tested, and potentially extended—for instance, building a custom automation that logs BLE discoveries to a local database or feeding data into an AI agent that performs network reconnaissance. This makes the tool both a practical resource and a reference for learning about BLE protocol handling in Android development.

## Key Features & Technologies
- Detects nearby Bluetooth devices
- Tracks specific target devices by MAC address or RSSI
- Sends notifications when detection occurs
- Open-source with F-Droid availability
- Uses Android BLE scanning APIs

## Difference from Others
MetaRadar stands out among Bluetooth scanner applications primarily through its focus on security research and educational use cases, rather than commercial device management or IoT provisioning. While tools like nRF Connect or LightBlue Explorer target developers building BLE peripherals, MetaRadar is tailored for users who need to monitor the environment, track specific devices, and receive alerts—ideal for privacy audits, lost device recovery, or detecting unauthorized BLE beacons in a network.

Additionally, its open-source distribution across multiple app stores (including F-Droid) ensures transparency and community review, contrasting with proprietary scanners that may embed telemetry or require paid subscriptions. The project's explicit legal disclaimer also differentiates it from other security tools that might lack such ethical boundaries, making it a trustworthy choice for researchers who require documented, lawful-only usage.

## 🏢 Organization & Credibility
- **Developer:** BLE-Research-Group
- **Reputation:** Unknown
- **Stars:** 1,456
- **Forks:** 107
- **Recent Activity:** 0 commits in 3 months
- **Credibility Score:** 46.0/100 (Low)
- **Languages:** Kotlin, url
- **Last Release:** 2026-01-10
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
*Source: [GitHub](https://github.com/BLE-Research-Group/MetaRadar)*
