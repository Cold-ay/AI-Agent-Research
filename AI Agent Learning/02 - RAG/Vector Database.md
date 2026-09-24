---
tags:
  - ai-agent-learning/rag
---

# Vector Database（向量資料庫）

Learning cluster: [[AI Agent Learning/02 - RAG/02 - RAG Overview|RAG overview]]

## Overview

A database or database capability that stores vectors and supports similarity retrieval, often with **metadata** and document references.

## Key Concepts

**Why it matters:** It makes searching a large embedding collection practical.

- **metadata**（元資料）
- **Approximate nearest-neighbor**（近似最近鄰）

## How It Works

- Store IDs, vectors, source references, and **metadata**.
- Build an index; query it with a compatible vector; return matching records.

## Example

Store an embedding for each handbook section, then retrieve sections near the query vector for “holiday allowance.”

## Common Pitfalls

> [!warning] Watch for this
> - **Approximate nearest-neighbor** indexes trade recall for speed.
> - Small collections may only need an in-memory index; a dedicated database is not mandatory.

## Related Notes

- [[AI Agent Learning/02 - RAG/Embeddings|Embeddings]] — 向量嵌入
- [[AI Agent Learning/02 - RAG/Metadata Filtering|Metadata Filtering]] — 元資料過濾
- [[AI Agent Learning/02 - RAG/Semantic Search|Semantic Search]] — 語義搜尋

### Next Topics

[[AI Agent Learning/02 - RAG/Hybrid Search|Hybrid Search]] → [[AI Agent Learning/06 - Production/Retrieval Recall|Retrieval Recall]].
