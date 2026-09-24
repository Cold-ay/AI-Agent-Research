---
tags:
  - ai-agent-learning/production
---

# Retrieval Recall（檢索召回率）

Learning cluster: [[AI Agent Learning/06 - Production/06 - Production Overview|Production overview]]

## Overview

The fraction of relevant items retrieved from all relevant items for a query, often measured at a **cutoff** k.

## Key Concepts

**Why it matters:** It reveals whether the answer evidence is missing before generation begins.

- **cutoff**（截斷位置）
- **granularity**（粒度）

## How It Works

- Label relevant documents or passages, retrieve top k, and compute relevant retrieved / all labeled relevant.
- Aggregate across queries consistently.

## Example

If four passages are relevant and the top five contain three, recall@5 is 3/4 = 75%.

## Common Pitfalls

> [!warning] Watch for this
> - Labels may be incomplete and relevance depends on **granularity**.
> - High recall does not imply low noise or a correct answer.

## Related Notes

- [[AI Agent Learning/02 - RAG/RAG|RAG]] — 檢索增強生成
- [[AI Agent Learning/02 - RAG/Vector Database|Vector Database]] — 向量資料庫
- [[AI Agent Learning/06 - Production/Agent Evaluation|Agent Evaluation]] — 代理評估

### Next Topics

[[AI Agent Learning/06 - Production/Precision|Precision]] → [[AI Agent Learning/02 - RAG/Reranking|Reranking]].
