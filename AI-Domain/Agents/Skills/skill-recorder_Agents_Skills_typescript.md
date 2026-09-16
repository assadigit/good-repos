---
source: https://github.com/microsoft/skill-recorder
aliases:
  - skill-recorder
  - microsoft/skill-recorder
tags: [typescript, electron, ai-agents, agent-skills, copilot-cli, screen-recording, automation, copilot, copilot-cowork, copilot-studio, microsoft-scout, javascript]
category: Agents/Skills
stars: 3728
org: microsoft
primary_language: TypeScript
languages: [TypeScript, JavaScript, CSS, PowerShell, Shell]
credibility_score: 90.0/100
date_processed: 2026-09-01
last_release: 2026-08-12
cover: attachments/banners/skill-recorder_banner.png

---

![banner](attachments/banners/skill-recorder_banner.png)

# skill-recorder

> **TL;DR:** Desktop app that records your screen activity and converts it into reusable AI agent Skills or Automations via GitHub Copilot CLI.

**`microsoft/skill-recorder`** · ⭐ 3,728 · 🔧 TypeScript

## What is it?
Skill Recorder is a Microsoft-built desktop application (built on Electron) that captures a real work session on your screen—clicks, app and window switches, pages visited, and optional spoken narration—and then uses the GitHub Copilot CLI to reconstruct what you actually did into a clear intent plus an ordered list of steps. From that single recording, it can generate two kinds of reusable artifacts: a **Skill** (a `SKILL.md` procedure an agent runs on demand) or an **Automation** (the same procedure bound to a schedule or trigger). Both outputs prefer the agent's native tools (such as the `gh` CLI or `web_fetch`) over replaying raw UI clicks, and they generalize from your one example so that recording yourself submitting one form teaches the agent to submit all of them.

The app ships with a compact capture window (record button, timer, optional narration toggle with language and microphone settings, and readiness checks) and a sessions library view that shows recorded sessions on the left and the reconstructed intent and ordered steps on the right. It targets Microsoft's agent ecosystem—Microsoft Scout, Copilot Cowork, and Copilot Studio—as the primary runtimes for the generated skills and automations.

## How does it work?
Skill Recorder is an Electron-based desktop app that runs locally in the background while you perform a task. It captures screen activity (mouse/keyboard events, window and app switches, browser pages) and, optionally, spoken narration via microphone input. After the session ends, it hands the captured data to the GitHub Copilot CLI, which reconstructs the raw interaction into a structured intent statement and an ordered step list. The result is then packaged either as a `SKILL.md` file (a declarative procedure an agent can invoke on demand) or as an Automation definition (the same procedure wired to a cron-like schedule or event trigger). The generated artifacts deliberately prefer native agent tools—like the `gh` CLI for GitHub operations or `web_fetch` for page retrieval—over brittle UI-click replay, which makes the skills more robust and portable across environments.

Under the hood, the Electron process handles OS-level screen capture, input monitoring, and audio recording, while the Copilot CLI (invoked as a child process) performs the LLM-based reconstruction. The output is consumed by Microsoft's agent platforms (Scout, Copilot Cowork, Copilot Studio), which interpret the `SKILL.md` or Automation config at runtime.

## Why is it important? (Core Value)
Skill Recorder solves a practical gap in the AI-agent toolchain: turning an implicit, one-off human task into a reusable, machine-executable skill without hand-authoring a prompt or procedure. For a software engineer and researcher focused on AI agents, developer tools, and automation, this is directly relevant because it bridges the gap between "I did something manually" and "my agent can do it for me, on demand or on a schedule." It also gives concrete insight into how Microsoft structures its agent skill format (`SKILL.md`) and how native-tool preference (e.g., `gh` CLI over UI clicks) is encoded—knowledge that informs integration with similar agent frameworks and MCP-style tool registries. The screen-recording-to-intent pipeline is a novel approach to skill authoring that complements prompt-engineering workflows, and the fact that it comes from Microsoft makes it a credible reference for how first-party agent platforms expect skills to be shaped.

## Key Features & Technologies
- Electron desktop app with global hotkey (⌘⇧R / Ctrl+Shift+R) to start/stop screen recording
- Captures clicks, app/window switches, browser pages, and optional spoken narration
- Uses GitHub Copilot CLI to reconstruct raw activity into intent + ordered steps
- Generates reusable SKILL.md procedures for Microsoft Scout, Copilot Cowork, or Copilot Studio
- Produces Automation definitions bound to schedules or event triggers
- Prefers native agent tools (gh CLI, web_fetch) over fragile UI-click replay
- Generalizes from a single recorded example to handle broader task families

## Difference from Others
Compared to generic screen-recording or RPA tools (e.g., OBS, ScreenFlow, or UiPath), Skill Recorder does not aim to produce a pixel-perfect replay; it abstracts the session into a semantic intent-and-steps document that an LLM-powered agent can interpret and execute with its own tools. Compared to hand-authored skill/prompt libraries or MCP server repos, it removes the manual authoring step entirely—you demonstrate the task once and the Copilot CLI writes the `SKILL.md` for you. What sets it apart from other agent-skill authoring tools is the closed loop: record → LLM reconstruction → native-tool-first procedure → deploy to a specific Microsoft agent runtime, all in one desktop workflow. It is less a general-purpose skill registry and more a skill *generator* tuned to Microsoft's agent ecosystem.

## 🏢 Organization & Credibility
- **Developer:** microsoft
- **Reputation:** High (Major tech company)
- **Stars:** 3,728
- **Forks:** 373
- **Recent Activity:** 137 commits in 3 months
- **Credibility Score:** 90.0/100 (Excellent)
- **Languages:** TypeScript, JavaScript, CSS, PowerShell, Shell
- **Last Release:** 2026-08-12
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
*Source: [GitHub](https://github.com/microsoft/skill-recorder)*
