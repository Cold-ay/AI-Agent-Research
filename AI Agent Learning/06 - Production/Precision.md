---
tags:
  - ai-agent-learning/production
---

# Precision（精確率）

Learning cluster: [[AI Agent Learning/06 - Production/06 - Production Overview|Production overview]]

## Overview

For retrieval, the fraction of returned items that are **relevant** to the question.

## Key Concepts

**Why it matters:** It measures how much of the retrieved context is useful instead of distracting.

- **relevant**（相關）
- **recall**（召回率）

## How It Works

- Choose a cutoff, label returned items, and divide **relevant** returned items by the number returned.

## Example

If the top five passages contain three relevant passages, precision@5 is 3/5 = 60%.

## Common Pitfalls

> [!warning] Watch for this
> - A system can have high precision while missing important evidence.
> - Interpret it alongside **recall** rather than optimizing it alone.

## Related Notes

- [[AI Agent Learning/06 - Production/Retrieval Recall|Retrieval Recall]] — 檢索召回率
- [[AI Agent Learning/02 - RAG/Reranking|Reranking]] — 重新排序
- [[AI Agent Learning/06 - Production/Agent Evaluation|Agent Evaluation]] — 代理評估

### Next Topics

[[AI Agent Learning/06 - Production/Groundedness|Groundedness]] → [[AI Agent Learning/02 - RAG/Hybrid Search|Hybrid Search]].
