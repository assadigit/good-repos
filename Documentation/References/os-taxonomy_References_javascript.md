---
source: https://github.com/withmarbleapp/os-taxonomy
aliases:
  - os-taxonomy
  - withmarbleapp/os-taxonomy
tags: [javascript, education, curriculum, graph-data, open-source, taxonomy, url]
category: References
stars: 2764
org: withmarbleapp
primary_language: JavaScript
languages: [JavaScript, url]
credibility_score: 48.5/100
date_processed: 2026-07-13

cover: attachments/banners/os-taxonomy_banner.png

---

![banner](attachments/banners/os-taxonomy_banner.png)

# os-taxonomy

**`withmarbleapp/os-taxonomy`** · ⭐ 2,764 · 🔧 JavaScript

## What is it?
Marble Skill Taxonomy is an open, structured dataset that maps what children learn during primary and elementary education. It decomposes curriculum into fine-grained micro-topics—each representing a single teachable idea such as 'Building sentences' or 'Apparent brightness of stars'. Every micro-topic includes a plain-language description, mastery evidence criteria, a type classification (conceptual/procedural/representational/language/meta), the subject and domain, and an approximate age range.

Beyond individual topics, the dataset encodes 3,221 prerequisite dependencies as a directed acyclic graph. Each edge is tagged hard or soft and carries a concise reason for the dependency, enabling agents to reason about learning pathways and ordering of instruction. The taxonomy aligns with national curriculum standards, making it useful for educators, content creators, and anyone building tools that need structured educational knowledge.

The project is maintained by Marble (withmarble.com) and includes an interactive 3D visualization where each dot is a micro-topic, colored by subject, and linked by prerequisite edges. Height corresponds to the typical age at which the topic is introduced. Users can explore the graph online or download the data for offline use.

## How does it work?
The taxonomy is represented as a directed graph of micro-topics, each node containing metadata fields such as subject, domain, age range, and type. Prerequisite edges are stored with hard/soft tags and short textual reasons, forming a DAG that captures the ordering constraints of learning. The repository likely provides data files (e.g., JSON, CSV) that can be loaded into any graph-processing environment. Marble also supplies an interactive web UI built around the graph, allowing users to click any concept and trace all prior requirements.

## Why is it important? (Core Value)
For a developer interested in AI agents and self-hostable tools, this dataset offers a rich, structured knowledge base that can be combined with LLMs to build educational agents or curriculum mapping services. Because it is open and not locked behind a SaaS product, it can be hosted locally, integrated into personal vaults, or used as reference data for agents that need to reason about learning dependencies. Its prerequisite graph directly supports agents that must plan lesson sequences or verify mastery before advancing topics.

The taxonomy also serves as a self-hostable alternative to proprietary curriculum APIs, aligning with the user's interest in open-source alternatives and developer productivity tools.

## Key Features & Technologies
- open data set
- prerequisite DAG
- micro-topic metadata (type, subject, domain, age)
- hard/soft edge tags with reasons
- curriculum standards alignment
- interactive 3D visualization

## Difference from Others
Most curriculum data is either a flat list of standards or locked inside a product, according to the README. This dataset stands out because it provides a connected graph of learning with prerequisite edges and micro-topic granularity, plus mastery evidence and type classification.

## 🏢 Organization & Credibility
- **Developer:** withmarbleapp
- **Reputation:** Unknown
- **Stars:** 2,764
- **Forks:** 503
- **Recent Activity:** 9 commits in 3 months
- **Credibility Score:** 48.5/100 (Low)
- **Languages:** JavaScript, url
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
*Source: [GitHub](https://github.com/withmarbleapp/os-taxonomy)*
