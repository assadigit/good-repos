---
source: https://github.com/mudler/LocalRecall
aliases:
  - LocalRecall
  - mudler/LocalRecall
tags: [go, go, vector-db, api, agent, self-hosted, html, javascript, makefile, shell]
category: Agents/Implementations
stars: 897
org: mudler
primary_language: Go
languages: [Go, HTML, JavaScript, Makefile, Shell]
credibility_score: 45.0/100
date_processed: 2026-07-22
last_release: 2026-07-19
cover: attachments/banners/LocalRecall_banner.png

---

![banner](attachments/banners/LocalRecall_banner.png)

# LocalRecall

**`mudler/LocalRecall`** · ⭐ 897 · 🔧 Go

## What is it?
LocalRecall is a lightweight, no-frills RESTful API designed to manage knowledge bases and files stored in vector databases without requiring GPUs, internet, or cloud services. It provides a simple, generic abstraction layer that lets AI agents and chatbots handle both long‑term and short‑term memory seamlessly—perfect for self‑hosted environments and homelabs.

The project ships with “batteries included”: out of the box it supports multiple vector database engines, including Chromem (a local file‑based store) and PostgreSQL with TimescaleDB, pgvector, and pgvectorscale for hybrid search combining BM25 text similarity with vector embeddings. This dual‑engine approach lets you choose between pure vector search or hybrid retrieval depending on your data.

Beyond the API, LocalRecall includes an intuitive web UI for convenient file management, raw text inputs, and easy integration with LocalAI, LocalAGI, and other agent frameworks. All of this is written in Go, ensuring strong static typing and performance on modest hardware.

## How does it work?
At its core, LocalRecall exposes a clean HTTP/REST API that wraps one of two vector stores: Chromem, which stores embeddings in plain files on disk, or PostgreSQL with pgvector/TimescaleDB for production‑grade scaling and hybrid search. The Go code handles embedding computation, index management, and query routing, while a small web UI built with vanilla HTML/JS lets you browse, upload, and delete documents without touching the API directly.

Because the project is written in Go, it compiles to a single binary (or container) that can run on any Linux/macOS host without extra dependencies. This makes LocalRecall ideal for homelab setups where you want zero GPU usage and no cloud egress. The hybrid search path in PostgreSQL combines BM25 (lexical) with vector similarity, giving you the best of both worlds for retrieval tasks.

## Why is it important? (Core Value)
LocalRecall matters because it gives you a self‑hosted, GPU‑free memory layer that plugs directly into any AI agent stack (LocalAI, LocalAGI, etc.). For a researcher who curates tools for an Obsidian vault, this means you can replace SaaS vector DB services with a locally maintained knowledge base, keeping your context on your own hardware and respecting your “Your AI. Your Hardware. Your Rules.” ethos. It also aligns with your interest in self‑hostable alternatives to cloud products, providing a concrete way to keep your long‑term memory on premises without paying for GPU instances or relying on internet access.

For your developer workflow, LocalRecall’s REST API lets you script document ingestion and retrieval from any language, while its web UI gives you quick visual inspection of your knowledge base. Because it’s written in Go, it integrates cleanly with other Go tooling you may already use for agent infrastructure (e.g., LocalAI server). This makes LocalRecall a natural fit for building or enhancing your personal AI assistant stack without introducing new dependencies or vendor lock‑in.

## Key Features & Technologies
- RESTful API for knowledge bases
- Chromem (local file‑based vector store)
- PostgreSQL with TimescaleDB, pgvector, pgvectorscale
- Hybrid search (BM25 + vector similarity)
- Web UI for file management
- Raw text input support
- Integration with LocalAI/LocalAGI

## Difference from Others
Compared to cloud‑first solutions like Pinecone, Weaviate, or LangChain’s built‑in memory modules, LocalRecall stands out because it requires no GPU, runs entirely on your hardware, and includes a ready‑to‑use web UI. While Pinecone and Weaviate are great for production clusters, they depend on internet egress and often need managed Kubernetes deployments. LangChain’s memory components are language‑specific (Python) and lack a native UI. LocalRecall is written in Go, which gives it strong static typing and performance on modest servers—ideal for homelab or Obsidian vault users who want a self‑contained knowledge base without vendor lock‑in.

## 🏢 Organization & Credibility
- **Developer:** mudler
- **Reputation:** Unknown
- **Stars:** 897
- **Forks:** 109
- **Recent Activity:** 10 commits in 3 months
- **Credibility Score:** 45.0/100 (Low)
- **Languages:** Go, HTML, JavaScript, Makefile, Shell
- **Last Release:** 2026-07-19
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
*Source: [GitHub](https://github.com/mudler/LocalRecall)*
