---
tags:
  - ai-agent-learning/rag
---

# Reciprocal Rank Fusion（倒數排名融合）

Learning cluster: [[AI Agent Learning/02 - RAG/02 - RAG Overview|RAG overview]]

## Overview

A method that combines ranked lists by adding contributions based on each item’s rank.

## Key Concepts

**Why it matters:** It avoids requiring BM25 and vector similarity scores to share a numeric scale.

- **one-based ranks**（從一開始的排名）
- **stable ID**（穩定識別碼）

## How It Works

- For each document, sum 1/(k + rank) over lists containing it, using **one-based ranks** and a chosen positive constant k.
- Sort by the total.

## Example

With k=60, ranks 1 and 3 contribute 1/61 + 1/63 ≈ 0.0323; a document appearing only at rank 1 receives about 0.0164.

## Common Pitfalls

> [!warning] Watch for this
> - Fusion uses positions, not evidence quality.
> - Duplicates must share a **stable ID**; tune and test rather than treating k as universal.

## Related Notes

- [[AI Agent Learning/02 - RAG/Hybrid Search|Hybrid Search]] — 混合搜尋
- [[AI Agent Learning/02 - RAG/BM25 and Sparse Search|BM25 and Sparse Search]] — BM25／稀疏搜尋
- [[AI Agent Learning/02 - RAG/Semantic Search|Semantic Search]] — 語義搜尋

### Next Topics

[[AI Agent Learning/02 - RAG/Reranking|Reranking]] → [[AI Agent Learning/06 - Production/Precision|Precision]].

## Reference

[Elastic RRF reference](https://www.elastic.co/docs/reference/elasticsearch/rest-apis/reciprocal-rank-fusion) — primary reference; consulted 2026-09-25.
