---
source: "https://github.com/nektos/act"
aliases:
  - act
  - nektos/act
tags: [cicd, docker, github-actions, testing]
category: "Automation"
stars: 59834
org: ""
primary_language: Go
languages: [Go]
credibility_score: 78/100
date_processed: 2026-09-16
---

# act

> **TL;DR:** Run GitHub Actions locally in Docker before you push — CI feedback in seconds.

**`nektos/act`** · ⭐ 59,834 · 🔧 Go

## What is it?
Run your GitHub Actions locally with a single command — the exact same runners, in containers, before you push.

## How does it work?
Parses your workflow YAML and maps each job/step onto Docker containers that emulate the GitHub runner environment.

## Why is it important? (Core Value)
CI feedback loops drop from minutes to seconds. No more push-to-see-what-breaks.

## Key Features & Technologies
- Drop-in GitHub runner emulation
- Docker-based isolation
- Workflow dry-runs
- Matrix build support
