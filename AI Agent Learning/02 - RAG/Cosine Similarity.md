---
tags:
  - ai-agent-learning/rag
---

# Cosine Similarity（餘弦相似度）

Learning cluster: [[AI Agent Learning/02 - RAG/02 - RAG Overview|RAG overview]]

## Overview

A measure of vector direction agreement: cos(a,b) = (a·b) / (||a|| ||b||), for nonzero vectors.

## Key Concepts

**Why it matters:** It is a common way to rank embedding similarity while ignoring **vector magnitude**.

- **dot product**（內積）
- **vector magnitude**（向量大小）

## How It Works

- Compute the **dot product**, divide by both vector lengths, and rank by descending score when the embedding model recommends cosine.

## Example

- For a=(1,0) and b=(1,1), cosine is about 0.707.
- Identical nonzero directions score 1.

## Common Pitfalls

> [!warning] Watch for this
> - The mathematical range is −1 to 1.
> - A score of 0.8 is not an 80% probability of relevance; thresholds need validation.

## Related Notes

- [[AI Agent Learning/02 - RAG/Embeddings|Embeddings]] — 向量嵌入
- [[AI Agent Learning/02 - RAG/Semantic Search|Semantic Search]] — 語義搜尋

### Next Topics

[[AI Agent Learning/02 - RAG/Vector Database|Vector Database]] → [[AI Agent Learning/02 - RAG/Reranking|Reranking]].
