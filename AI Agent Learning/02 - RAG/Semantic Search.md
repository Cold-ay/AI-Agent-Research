---
tags:
  - ai-agent-learning/rag
---

# Semantic Search（語義搜尋）

Learning cluster: [[AI Agent Learning/02 - RAG/02 - RAG Overview|RAG overview]]

## Overview

Retrieval based on meaning or **learned relevance** rather than only literal term overlap.

## Key Concepts

**Why it matters:** Users often ask questions with different words from the source.

- **learned relevance**（學習所得的相關性）
- **exact identifiers**（精確識別碼）

## How It Works

- One common implementation embeds a query and passages, finds nearby vectors, and returns corresponding source text.
- Other semantic methods also exist.

## Example

“Can I take a day off?” retrieves “Annual leave entitlement” even without exact phrase overlap.

## Common Pitfalls

> [!warning] Watch for this
> - It can confuse similar topics and miss **exact identifiers**.
> - Measure performance with domain-specific questions.

## Related Notes

- [[AI Agent Learning/02 - RAG/Embeddings|Embeddings]] — 向量嵌入
- [[AI Agent Learning/02 - RAG/Cosine Similarity|Cosine Similarity]] — 餘弦相似度
- [[AI Agent Learning/02 - RAG/Vector Database|Vector Database]] — 向量資料庫

### Next Topics

[[AI Agent Learning/02 - RAG/Hybrid Search|Hybrid Search]] → [[AI Agent Learning/02 - RAG/Reranking|Reranking]].
