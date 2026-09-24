---
tags:
  - ai-agent-learning/rag
---

# RAG（檢索增強生成）

Learning cluster: [[AI Agent Learning/02 - RAG/02 - RAG Overview|RAG overview]]

## Overview

Retrieval-augmented generation supplies retrieved **external evidence** to a model before it generates an answer.

## Key Concepts

**Why it matters:** It helps answer questions about a specific, changing corpus without putting every document into each request.

- **external evidence**（外部證據）
- **hallucinations**（幻覺）

## How It Works

1. Prepare documents
2. Index searchable units
3. Retrieve candidates for a question
4. Select evidence
5. Generate an answer with source references.

## Example

For “What is the refund period?”, retrieve the current policy paragraph and answer “30 days” with its source, if that is what it says.

## Common Pitfalls

> [!warning] Watch for this
> - RAG is not synonymous with vector search and does not eliminate **hallucinations**.
> - Test retrieval and answer grounding separately.

## Related Notes

- [[AI Agent Learning/02 - RAG/Chunking|Chunking]] — 文件分塊
- [[AI Agent Learning/02 - RAG/Semantic Search|Semantic Search]] — 語義搜尋
- [[AI Agent Learning/02 - RAG/BM25 and Sparse Search|BM25 and Sparse Search]] — BM25／稀疏搜尋
- [[AI Agent Learning/02 - RAG/Reranking|Reranking]] — 重新排序

### Next Topics

[[AI Agent Learning/02 - RAG/Hybrid Search|Hybrid Search]] → [[AI Agent Learning/04 - Advanced Knowledge/Agentic RAG|Agentic RAG]].

## Reference

[Original RAG paper](https://arxiv.org/abs/2005.11401) — primary reference; consulted 2026-09-25.
