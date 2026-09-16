---
source: https://github.com/psalias2006/gpu-hot
aliases:
  - gpu-hot
  - psalias2006/gpu-hot
tags: [javascript, python, docker, flask, monitoring, self-hosted, charts, cuda, gpu, gpu-monitoring, nvidia, nvidia-smi]
category: Infrastructure
stars: 1566
org: psalias2006
primary_language: JavaScript
languages: [JavaScript, Python, CSS, HTML, Dockerfile]
credibility_score: 43.0/100
date_processed: 2026-07-05
last_release: 2026-05-28
cover: attachments/banners/gpu-hot_banner.png

---

![banner](attachments/banners/gpu-hot_banner.png)

# gpu-hot

> **TL;DR:** Self-hosted dashboard that monitors NVIDIA GPU metrics in real-time with Docker.

**`psalias2006/gpu-hot`** · ⭐ 1,566 · 🔧 JavaScript

## What is it?
gpu-hot is a lightweight, web-based dashboard for monitoring NVIDIA GPU metrics such as memory usage, utilization, and temperature in real-time. It uses the nvidia-smi API to collect system-level data and presents it through an interactive Flask web interface. The project is self-hosted under MIT license with Docker deployment support.

## How does it work?
The dashboard queries NVIDIA GPUs via the nvidia-smi command-line tool, which exposes metrics about GPU utilization, memory usage, temperature, and other hardware statistics. These metrics are collected and served through a Flask backend running in a Docker container. For cluster deployments, a hub node aggregates data from multiple worker nodes by fetching their dashboards and combining them into a single unified view.

## Why is it important? (Core Value)
For your interests in self-hosted software and infrastructure, this project provides a privacy-respecting alternative to SaaS GPU monitoring services like NVIDIA DGX Cloud. It's particularly useful for MLOps workflows where you need visibility into GPU resources across your training clusters without relying on external dashboards. The lightweight footprint and MIT license make it easy to deploy in homelab environments or alongside other self-hosted tools. Since you curate developer productivity tools, gpu-hot fits well as part of a homelab monitoring stack—complementary to tools like htop or Prometheus-based solutions.

## Key Features & Technologies
- Real-time GPU metrics via nvidia-smi
- Self-hosted Docker deployment
- Flask web backend
- Cluster/hub mode for multi-node aggregation
- MIT license (open source)
- Lightweight footprint
- Interactive dashboard UI

## Difference from Others
Unlike NVIDIA DGX Cloud's SaaS dashboard or Prometheus + Grafana setups that require external databases and more complex infrastructure, gpu-hot is a single Docker image you can run anywhere with an NVIDIA GPU. It doesn't depend on external services or persistent storage—everything runs in-memory within the container. Compared to other GPU monitoring projects, it offers a minimal, self-contained solution specifically focused on NVIDIA GPUs rather than generic compute metrics.

## 🏢 Organization & Credibility
- **Developer:** psalias2006
- **Reputation:** Unknown
- **Stars:** 1,566
- **Forks:** 78
- **Recent Activity:** 4 commits in 3 months
- **Credibility Score:** 43.0/100 (Low)
- **Languages:** JavaScript, Python, CSS, HTML, Dockerfile
- **Last Release:** 2026-05-28
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
*Source: [GitHub](https://github.com/psalias2006/gpu-hot)*
