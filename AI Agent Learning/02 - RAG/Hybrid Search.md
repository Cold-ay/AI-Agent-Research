---
tags:
  - ai-agent-learning/rag
---

# Hybrid Search（混合搜尋）

Learning cluster: [[AI Agent Learning/02 - RAG/02 - RAG Overview|RAG overview]]

## Overview

Combining multiple retrieval signals, commonly **lexical** and **dense semantic retrieval**.

## Key Concepts

**Why it matters:** It covers both wording variations and distinctive exact terms.

- **lexical**（詞彙式）
- **dense semantic retrieval**（密集向量語義檢索）

## How It Works

- Run complementary retrievers, deduplicate results, combine ranks or calibrated scores, and optionally rerank the candidate set.

## Example

For “XJ-29181 login failure,” BM25 finds the code while semantic search finds troubleshooting described as authentication problems.

## Common Pitfalls

> [!warning] Watch for this
> - Raw scores from different retrievers are not directly comparable.
> - Fusion weights and candidate sizes need evaluation.

## Related Notes

- [[AI Agent Learning/02 - RAG/BM25 and Sparse Search|BM25 and Sparse Search]] — BM25／稀疏搜尋
- [[AI Agent Learning/02 - RAG/Semantic Search|Semantic Search]] — 語義搜尋
- [[AI Agent Learning/02 - RAG/Reciprocal Rank Fusion|Reciprocal Rank Fusion]] — 倒數排名融合

### Next Topics

[[AI Agent Learning/02 - RAG/Reranking|Reranking]] → [[AI Agent Learning/06 - Production/Agent Evaluation|Agent Evaluation]].

## Reference

[Elastic hybrid search documentation](https://www.elastic.co/docs/solutions/search/hybrid-search) — primary reference; consulted 2026-09-25.
