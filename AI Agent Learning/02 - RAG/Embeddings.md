---
tags:
  - ai-agent-learning/rag
---

# Embeddings（向量嵌入）

Learning cluster: [[AI Agent Learning/02 - RAG/02 - RAG Overview|RAG overview]]

## Overview

Learned numeric representations that encode useful features of text or other data.

## Key Concepts

**Why it matters:** They make approximate **similarity** comparisons possible even when wording differs.

- **encoders**（編碼器）
- **similarity**（相似度）

## How It Works

- Use compatible **encoders** for documents and queries, then compare vectors with the index’s chosen distance or **similarity** function.

## Example

“car repair” and “fix my automobile” may have nearby vectors, allowing one phrase to retrieve the other.

## Common Pitfalls

> [!warning] Watch for this
> - **Similarity** depends on training and domain.
> - Nearby vectors do not prove factual equivalence; mixing incompatible embedding versions can break retrieval.

## Related Notes

- [[AI Agent Learning/02 - RAG/Semantic Search|Semantic Search]] — 語義搜尋
- [[AI Agent Learning/02 - RAG/Vector Database|Vector Database]] — 向量資料庫
- [[AI Agent Learning/02 - RAG/Cosine Similarity|Cosine Similarity]] — 餘弦相似度

### Next Topics

[[AI Agent Learning/02 - RAG/Hybrid Search|Hybrid Search]] → [[AI Agent Learning/04 - Advanced Knowledge/Multimodal RAG|Multimodal RAG]].
