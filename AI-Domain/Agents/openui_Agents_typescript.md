---
source: https://github.com/wandb/openui
aliases:
  - openui
  - wandb/openui
tags: [typescript, python, javascript, openai, tailwindcss, generative-ai, ai, html-css-javascript, html, css]
category: Agents
stars: 22449
org: wandb
primary_language: TypeScript
languages: [TypeScript, HTML, Python, JavaScript, CSS]
credibility_score: 56.0/100
date_processed: 2026-07-06

cover: attachments/banners/openui_banner.png

---

![banner](attachments/banners/openui_banner.png)

# openui

> **TL;DR:** OpenUI lets you describe UI with natural language, generating React/Svelte/Web Components via LLMs. Self-hostable and supports multiple model APIs.

**`wandb/openui`** · ⭐ 22,449 · 🔧 TypeScript

## What is it?
OpenUI is a generative UI tool that lets you describe user interfaces using natural language prompts, then renders them live in the browser. It supports converting generated HTML into React, Svelte, or Web Components, making it flexible for various frontend frameworks. The project is open-source and can be self-hosted, supporting multiple LLM providers including OpenAI, Groq, Gemini, Anthropic, Cohere, Mistral, and OpenAI-compatible APIs via LiteLLM. This makes it a powerful alternative to SaaS UI generators like v0.dev.

Running locally requires setting environment variables for API keys (e.g., OPENAI_API_KEY, GROQ_API_KEY) or using an OpenAI-compatible endpoint. The tool is particularly useful for developers who want to prototype UI components quickly without relying on commercial services.

## How does it work?
OpenUI likely operates by taking natural language prompts describing UI components and using an LLM (via OpenAI API or local models) to generate the corresponding HTML/CSS/JavaScript code. The generated code is rendered in the browser, and users can request modifications, which are processed by the LLM to adjust the output. It supports conversion of the generated HTML into React, Svelte, or Web Components by applying framework-specific transformations. The project uses LiteLLM to abstract model inference across various providers, enabling flexible deployment options.

## Why is it important? (Core Value)
OpenUI provides a self-hostable, open-source alternative to commercial UI generators like v0.dev, aligning with the user's interest in self-hostable software and homelab infrastructure. By supporting multiple LLM APIs and allowing local model inference, it offers flexibility for different development environments. For a researcher focused on AI agents and developer tools, OpenUI represents an innovative approach to generative coding, enabling rapid prototyping of UI components without relying on SaaS services. It also integrates with the user's workflow by providing a tool that can be added to their Obsidian vault under 'AI-Domain' or 'Tools', helping them curate useful generative AI applications.

## Key Features & Technologies
- Uses OpenAI API (and other model providers)
- Converts HTML to React, Svelte, Web Components
- Tailwind CSS integration
- Self-hostable (runs locally)
- Live demo hosted on Fly.io
- Prompt-driven UI generation
- LiteLLM support for various models

## Difference from Others
Unlike commercial UI generators such as v0.dev, OpenUI is open-source and self-hostable, giving users full control over the infrastructure and model choices. It supports a broader range of LLM providers via LiteLLM, whereas v0.dev likely uses its own models or a single provider. Additionally, OpenUI can convert generated HTML into React, Svelte, or Web Components, offering more framework flexibility than typical SaaS tools.

## 🏢 Organization & Credibility
- **Developer:** wandb
- **Reputation:** Unknown
- **Stars:** 22,449
- **Forks:** 2058
- **Recent Activity:** 4 commits in 3 months
- **Credibility Score:** 56.0/100 (Low)
- **Languages:** TypeScript, HTML, Python, JavaScript, CSS
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
*Source: [GitHub](https://github.com/wandb/openui)*
