---
source: https://github.com/danyuchn/asd-ste100-skill
aliases:
  - asd-ste100-skill
  - danyuchn/asd-ste100-skill
tags: [claude-code, skill, asd-ste100, prompt-engineering, multi-agent, url]
category: Agents/Skills
stars: 1661
org: danyuchn

languages: [url]
credibility_score: 50.0/100
date_processed: 2026-09-01

cover: attachments/banners/asd-ste100-skill_banner.png

---

![banner](attachments/banners/asd-ste100-skill_banner.png)

# asd-ste100-skill

> **TL;DR:** Claude Code skill that rewrites ambiguous English into ASD-STE100 Simplified Technical English for agent-to-agent communication.

**`danyuchn/asd-ste100-skill`** · ⭐ 1,661 · 🔧 N/A

## What is it?
asd-ste100-skill is a Claude Code skill that applies the ASD-STE100 Simplified Technical English (STE) standard to rewrite dense, ambiguous English into clear, unambiguous prose. The original STE standard was developed by the aerospace and defense industry to ensure aircraft maintenance instructions cannot be misread—particularly by non-native English speakers with no author available for clarification. This project repurposes that same discipline for a new reader: an AI agent that must parse another agent's output, tool descriptions, error messages, or inter-agent instructions without any human in the loop to resolve ambiguity.

The skill enforces core STE rules including one meaning per word, active voice, simple tenses, one instruction per sentence, short sentences, and no dropped words. It is designed specifically for agent-to-agent communication scenarios where a downstream LLM must interpret upstream output with zero back-channel for clarification.

The project has attracted significant community interest (1661 stars, 85 forks), suggesting strong resonance among developers building multi-agent systems who need reliable inter-agent communication protocols.

## How does it work?
The skill operates as a Claude Code skill module that intercepts and rewrites English text according to ASD-STE100 rules. When an agent produces output intended for another agent's consumption (tool descriptions, error messages, inter-agent instructions), the skill applies controlled-language constraints: eliminates ambiguous pronouns, enforces active voice, limits sentence length, ensures one instruction per sentence, and removes dropped or implicit words.

The underlying architecture is a prompt-engineering layer that encodes STE grammatical rules as transformation instructions. It leverages Claude Code's skill mechanism to make the rewriting available as a composable capability within an agent pipeline. The key insight is that LLM agents occupy the same epistemic position as the original STE readers: they cannot ask for clarification, so the text itself must be unambiguous by construction.

## Why is it important? (Core Value)
This project solves a concrete and growing problem in multi-agent systems: ambiguous natural language between agents causes misinterpretation, cascading errors, and silent failures. Because LLM agents have no back-channel (no way to ask 'did you mean X or Y?'), the same controlled-language discipline that protects aircraft mechanics now protects downstream agents from misreading tool descriptions or inter-agent messages.

For a software engineer focused on AI agents, developer tools, and MCP integration, this skill is directly adoptable as a composable layer in any Claude Code–based agent pipeline. It addresses the user's stated interest in 'AI/LLM tooling (agents, skills, MCP, prompt engineering)' by providing a production-grade, standards-based approach to making agent output deterministic and parseable. The aerospace pedigree of ASD-STE100 also lends credibility—this is not an ad-hoc style guide but a battle-tested standard from safety-critical domains, which aligns with the user's interest in evaluating whether projects are 'credible enough to adopt.'

## Key Features & Technologies
- Applies ASD-STE100 controlled-language rules (one meaning per word, active voice, simple tenses)
- Rewrites ambiguous agent-facing English into deterministic, parseable output
- Designed specifically for inter-agent communication with no human back-channel
- Integrates as a Claude Code skill module for composable agent pipelines
- Enforces one instruction per sentence and eliminates dropped/implicit words
- Based on a safety-critical aerospace standard (ASD-STE100) with proven track record

## Difference from Others
Unlike generic prompt-engineering guides or style linters, this project is grounded in a formal international standard (ASD-STE100) rather than ad-hoc best practices. Most 'clear writing' tools target human readers who can ask questions; this skill explicitly targets machine readers with no clarification channel, which is the actual failure mode in multi-agent systems. Compared to other agent-communication protocols or structured output formats (JSON schemas, function calling), STE preserves natural-language expressiveness while eliminating ambiguity—offering a middle ground between free-form prose and rigid structured data. The aerospace safety pedigree also differentiates it from generic 'simplify your prompts' tips: the rules were designed under conditions where misinterpretation is fatal, not merely inconvenient.

## 🏢 Organization & Credibility
- **Developer:** danyuchn
- **Reputation:** Unknown
- **Stars:** 1,661
- **Forks:** 85
- **Recent Activity:** 19 commits in 3 months
- **Credibility Score:** 50.0/100 (Low)
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
*Source: [GitHub](https://github.com/danyuchn/asd-ste100-skill)*
