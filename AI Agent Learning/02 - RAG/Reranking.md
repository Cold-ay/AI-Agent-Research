---
tags:
  - ai-agent-learning/rag
---

# Reranking（重新排序）

Learning cluster: [[AI Agent Learning/02 - RAG/02 - RAG Overview|RAG overview]]

## Overview

Scoring an already retrieved **candidate set** again with a more focused relevance method.

## Key Concepts

**Why it matters:** A more expensive model can improve the order of a manageable shortlist.

- **candidate set**（候選集合）
- **cross-encoder**（交叉編碼器）

## How It Works

1. Retrieve broadly
2. Evaluate query-passage pairs, often with a **cross-encoder**
3. Retain the strongest passages within the context budget.

## Example

Retrieve 30 handbook chunks, rerank them for the refund question, and supply the best 5 to the answer model.

## Common Pitfalls

> [!warning] Watch for this
> - A reranker cannot recover a relevant document missing from its candidates.
> - Better ranking also does not guarantee factual support.

## Related Notes

- [[AI Agent Learning/02 - RAG/Hybrid Search|Hybrid Search]] — 混合搜尋
- [[AI Agent Learning/02 - RAG/RAG|RAG]] — 檢索增強生成
- [[AI Agent Learning/06 - Production/Precision|Precision]] — 精確率

### Next Topics

[[AI Agent Learning/06 - Production/Groundedness|Groundedness]] → [[AI Agent Learning/06 - Production/Agent Evaluation|Agent Evaluation]].
