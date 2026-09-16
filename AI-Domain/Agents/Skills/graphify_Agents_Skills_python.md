---
source: "https://github.com/safishamsi/graphify"
aliases:
  - graphify
  - Graphify-Labs/graphify

tags: [python, knowledge-graph, tree-sitter, mcp, code-analysis, ast, claude-code, graphrag, codex, openclaw, skills, antigravity]
category: "Agents/Skills"
stars: 118263
org: "Graphify-Labs"
primary_language: Python
languages: [Python, Dockerfile, url]
credibility_score: 72.0/100
date_processed: 2026-09-16
last_release: 2026-09-15
cover: attachments/banners/graphify_banner.png

---

![banner](attachments/banners/graphify_banner.png)

# graphify

> **TL;DR:** Turns any codebase, docs, SQL schemas, and PDFs into a queryable knowledge graph via local AST parsing—no vector store.

**`Graphify-Labs/graphify`** · ⭐ 118,263 · 🔧 Python

## What is it?
Graphify is a developer tool that transforms entire codebases—including source code, documentation files, SQL schemas, configuration files, and even PDFs—into a structured, queryable knowledge graph. Rather than relying on embedding-based retrieval (vector stores), it uses local deterministic AST parsing powered by Tree-sitter to extract relationships between entities in the code, producing an explainable graph where every edge carries a human-readable justification. The tool is packaged as a /graphify skill for popular AI coding assistants (Claude Code, Cursor, Codex, Gemini CLI) and is also available as an MCP server, making it plug-and-play within existing agentic development workflows.

The project emphasizes determinism and explainability: because parsing is AST-based rather than probabilistic, the resulting graph is reproducible and auditable. Community detection (Leiden algorithm) clusters related nodes into meaningful subgraphs, enabling targeted retrieval without the ambiguity typically associated with vector similarity search. With over 118k stars, it has become a trending reference for code-aware RAG pipelines.

## How does it work?
Graphify ingests multiple artifact types—source files, docs, SQL DDL, config YAML/JSON, and PDFs—and runs them through Tree-sitter-based AST parsers to extract nodes (functions, classes, tables, config keys, doc sections) and typed edges (calls, imports, references, dependencies). Because parsing is deterministic and local, no embeddings or vector index are required; instead, the graph itself becomes the retrieval substrate. A Leiden community-detection pass partitions the graph into cohesive clusters so that queries can be scoped to relevant subgraphs. The final artifact is exposed through a /graphify slash-command skill (for Claude Code, Cursor, Codex, Gemini CLI) or an MCP server endpoint, letting an LLM agent query the graph with natural-language prompts and receive structured, edge-explained answers.

The pipeline is entirely on-device: no code leaves the developer's machine, and there is no cloud dependency for parsing or querying. The explainability guarantee—every edge annotated with a rationale string—means an agent (or human) can trace *why* two entities are linked, which is critical for debugging hallucinated or spurious relationships in downstream LLM reasoning.

## Why is it important? (Core Value)
For a developer who builds and curates AI-agent tooling, Graphify solves the problem of giving an LLM-based coding assistant reliable, structured context about a codebase without the opacity and drift of vector RAG. It is self-hosted and local (no SaaS dependency), which aligns directly with the user's interest in self-hostable alternatives. The MCP server surface means it can be dropped into any MCP-capable agent runtime the user is building, while the /graphify skill format lets it slot into Claude Code or Cursor sessions with zero extra plumbing. Compared to generic code-search tools, Graphify's deterministic AST pipeline and per-edge explanations give the user a credible, auditable knowledge graph they can trust when evaluating whether an agent's answer is grounded in actual code structure—exactly the kind of signal needed when curating projects into an Obsidian knowledge base by domain (AI-Domain, Tools, Frameworks).

## Key Features & Technologies
- Deterministic AST parsing via Tree-sitter (no embeddings or vector store)
- Multi-source ingestion: source code, docs, SQL schemas, configs, PDFs
- Explainable edges with human-readable justifications on every relationship
- Leiden community detection to cluster subgraphs for scoped retrieval
- Exposed as a /graphify skill for Claude Code, Cursor, Codex, and Gemini CLI
- MCP server endpoint for integration into arbitrary agent runtimes
- Fully local/on-device—no cloud dependency for parsing or querying

## Difference from Others
Most code-aware RAG pipelines chunk files into text passages and embed them in a vector index, which introduces ambiguity (similar-looking chunks conflate distinct entities) and non-determinism. Graphify sidesteps this entirely: it builds a typed, explainable knowledge graph from ASTs, so every relationship is derived from syntactic structure rather than cosine similarity. The per-edge explanation requirement means an agent can verify *why* two nodes are connected, which is impossible with opaque vector hits. Compared to purpose-built code-search tools (e.g., Sourcegraph-style search), Graphify adds semantic graph traversal and LLM-facing query interfaces. Compared to generic MCP servers for code, it targets the full multi-artifact picture (code + docs + SQL + configs + PDFs) rather than a single file type, and its Leiden-based clustering gives agents a principled way to scope queries to relevant subgraphs without manually specifying search boundaries.

## 🏢 Organization & Credibility
- **Developer:** Graphify-Labs
- **Reputation:** Unknown
- **Stars:** 118,263
- **Forks:** 11431
- **Recent Activity:** 1015 commits in 3 months
- **Credibility Score:** 72.0/100 (Average)
- **Languages:** Python, Dockerfile, url
- **Last Release:** 2026-09-15
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
*Source: [GitHub](https://github.com/safishamsi/graphify)*
