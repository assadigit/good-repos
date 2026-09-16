---
source: https://github.com/serenakeyitan/awesome-notebookLM-prompts
aliases:
  - awesome-notebookLM-prompts
  - serenakeyitan/awesome-notebookLM-prompts
tags: [markdown, notebooklm, prompt-engineering, google, llm, ai, ai-agents, gemini, nanobananapro, prompt, prompts, url]
category: LLM-Tools
stars: 4063
org: serenakeyitan

languages: [url]
credibility_score: 44.5/100
date_processed: 2026-07-05



---

# awesome-notebookLM-prompts

**`serenakeyitan/awesome-notebookLM-prompts`** · ⭐ 4,063 · 🔧 N/A

## What is it?
awesome-notebookLM-prompts is a curated repository of high-quality prompts for generating slide decks with Google's NotebookLM and the Kael.im alternative. Each prompt has been field-tested by researchers, founders, and designers who need to turn papers, notes, transcripts, or raw brain-dumps into clean, presentation-ready decks that actually look intentional. The repo also includes a citation-checker skill (a separate GitHub package) that can be added to the workflow to detect hallucinated or missing citations in generated slides. All content is released under CC BY 4.0, making it safe for self-hosting and reuse in homelab or personal AI toolchains. Because NotebookLM is powered by Gemini, the prompts effectively serve as a prompt-engineering toolkit for leveraging Google's LLM without building your own agent system. This makes the project especially valuable for users who want to experiment with LLM-driven slide generation while keeping their pipeline simple and open-source.

## How does it work?
Under the hood, the repository is just a static collection of markdown files containing prompt templates and usage instructions. When a user wants slides, they copy a prompt snippet (often a YAML or JSON block) into NotebookLM's slide generation UI; the LLM then produces a structured deck that can be exported as PDF or PPTX. For Kael.im, similar prompts are provided to generate slides on that platform, giving users an alternative if NotebookLM's free quota is exhausted. The citation-checker skill is a separate Python-based module that runs after slide generation; it parses the generated text for missing references and flags hallucinations. The repo README points to this skill, so the workflow can be chained: generate slides → run citation-check → manually fix or re-run with adjusted prompts. No backend or orchestration is required beyond copying the markdown content.

## Why is it important? (Core Value)
As a software engineer and researcher focused on AI agents, developer tools, and automation, you're looking for curated GitHub projects that improve your workflow and provide self-hostable alternatives to SaaS offerings. This repository directly supports that goal by giving you ready-made prompts for NotebookLM—a Google LLM product—so you can automate slide creation from research papers or notes without building a custom agent system. The citation-checker skill also offers a developer tool you can integrate into your own homelab or Obsidian vault, aligning with your interest in open-source tools. Your objectives include discovering workflow tools and learning about new approaches to scraping, automation, and infrastructure. Prompt engineering for LLMs is a cornerstone of modern AI workflows; having a curated set of high-quality prompts reduces the need to spend time on prompt iteration, which is especially valuable when you're juggling multiple research projects. Because the repository is under CC BY 4.0, you can safely adopt these prompts in your personal knowledge base or share them with collaborators, making it a credible addition to your Obsidian vault.

## Key Features & Technologies
- Curated prompt collection for NotebookLM slides
- Kael.im alternative prompts included
- Citation-checker skill integration (separate repo)
- CC BY 4.0 open-source license
- Markdown repository, no dependencies

## Difference from Others
Other NotebookLM prompt repositories tend to be generic collections without field-testing or provenance. This repo stands out because each prompt comes from real creators on Twitter/X, RED, blogs, and WeChat—people who ship fast and have verified that the prompts produce clean decks. Additionally, it offers a citation-checker skill that most other prompt repos lack, giving you a built-in quality-assurance step. Projects like generic LLM prompt libraries (e.g., prompt-library, open-prompt) are often uncurated and may contain outdated or hallucination-prone prompts. This repo's focus on slide generation for NotebookLM and Kael.im makes it domain-specific, while its CC BY license ensures you can self-host without attribution concerns. Compared to other Google AI tools, this is a lightweight, prompt-centric solution rather than a full agent framework, which aligns with users who want minimal integration overhead.

## 🏢 Organization & Credibility
- **Developer:** serenakeyitan
- **Reputation:** Unknown
- **Stars:** 4,063
- **Forks:** 584
- **Recent Activity:** 5 commits in 3 months
- **Credibility Score:** 44.5/100 (Low)
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
*Source: [GitHub](https://github.com/serenakeyitan/awesome-notebookLM-prompts)*
