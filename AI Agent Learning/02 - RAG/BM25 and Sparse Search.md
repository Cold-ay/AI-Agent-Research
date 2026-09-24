---
tags:
  - ai-agent-learning/rag
aliases: ["BM25", "Sparse Search"]
---

# BM25 and Sparse Search（BM25／稀疏搜尋）

Learning cluster: [[AI Agent Learning/02 - RAG/02 - RAG Overview|RAG overview]]

## Overview

BM25 is a lexical ranking function using **term frequency**, inverse document frequency, and document-length normalization. Sparse retrieval is a broader family.

## Key Concepts

**Why it matters:** Exact names, product codes, and unusual terms can be highly informative.

- **inverted index**（倒排索引）
- **term frequency**（詞頻）

## How It Works

- An **inverted index** finds documents containing analyzed query terms; BM25 scores them, tempering repeated terms and adjusting for length.
- Learned sparse models can also expand or weight terms.

## Example

Searching “XJ-29181” can find the matching error manual when a dense embedding search returns generic error pages.

## Common Pitfalls

> [!warning] Watch for this
> - Tokenization may split identifiers.
> - BM25 is not an exact-string filter, and sparse retrieval is not limited to BM25.

## Related Notes

- [[AI Agent Learning/02 - RAG/Semantic Search|Semantic Search]] — 語義搜尋
- [[AI Agent Learning/02 - RAG/Hybrid Search|Hybrid Search]] — 混合搜尋

### Next Topics

[[AI Agent Learning/02 - RAG/Metadata Filtering|Metadata Filtering]] → [[AI Agent Learning/02 - RAG/Reranking|Reranking]].

## Reference

[Elasticsearch similarity reference](https://www.elastic.co/docs/reference/elasticsearch/index-settings/similarity) — primary reference; consulted 2026-09-25.
