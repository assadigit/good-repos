---
source: https://github.com/alibaba/zvec
aliases:
  - zvec
  - alibaba/zvec
tags: [c++, python, vector-db, faiss, hnsw, rag, agent-skills, embedded, llm-memory, search-engine, semantic-search, similarity-search]
category: Backend
stars: 12805
org: alibaba
primary_language: C++
languages: [C++, Python, SWIG, C, CMake]
credibility_score: 72.0/100
date_processed: 2026-07-05
last_release: 2026-06-24
cover: attachments/banners/zvec_banner.png

---

![banner](attachments/banners/zvec_banner.png)

# zvec

> **TL;DR:** Lightweight in-process vector database optimized for RAG, semantic search, and agent memory.

**`alibaba/zvec`** · ⭐ 12,805 · 🔧 C++

## What is it?
zvec is a high-performance vector database designed to be fast and lightweight, making it suitable for embedding models and RAG (Retrieval-Augmented Generation) pipelines. It provides efficient similarity search capabilities with support for both FAISS and HNSW indexing methods, enabling rapid nearest-neighbor queries essential for semantic search applications.

## How does it work?
The project operates as an in-process vector database that stores embeddings directly, leveraging FAISS (Facebook AI Similarity Search) and HNSW (Hierarchical Navigable Small World) indexes to accelerate similarity computations. It exposes Python and Node.js packages with PyPI and npm distributions respectively, making it accessible across different development ecosystems while maintaining a local-first architecture for privacy-conscious deployments.

## Why is it important? (Core Value)
For your objectives around AI/LLM tooling and self-hosted alternatives, zvec offers a practical solution that's notably lighter than larger vector databases like ChromaDB or LanceDB. At just 10MB in size, it's ideal for homelab setups and privacy-focused deployments where you want to keep embeddings locally rather than rely on SaaS services. The Apache 2.0 license makes it safe for integration into your knowledge base without legal restrictions, and its focus on agent-skills and llm-memory topics directly aligns with your interest in building robust AI agent tooling.

## Key Features & Technologies
- FAISS indexing
- HNSW graph search
- Python package (PyPI)
- Node.js package (npm)
- Apache 2.0 license
- Local-first architecture
- Lightweight (~10MB)

## Difference from Others
Unlike heavyweight vector databases such as Qdrant or Milvus, zvec prioritizes minimal footprint and in-process operation rather than distributed storage capabilities. It doesn't aim to replace enterprise-grade solutions but serves as a pragmatic choice for lightweight RAG pipelines and semantic search where simplicity and speed matter more than massive scale.

## 🏢 Organization & Credibility
- **Developer:** alibaba
- **Reputation:** Unknown
- **Stars:** 12,805
- **Forks:** 765
- **Recent Activity:** 147 commits in 3 months
- **Credibility Score:** 72.0/100 (Average)
- **Languages:** C++, Python, SWIG, C, CMake
- **Last Release:** 2026-06-24
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
*Source: [GitHub](https://github.com/alibaba/zvec)*
