---
tags:
  - ai-agent-learning/advanced-knowledge
---

# CAG（快取增強生成）

Learning cluster: [[AI Agent Learning/04 - Advanced Knowledge/04 - Advanced Knowledge Overview|Advanced Knowledge overview]]

## Overview

Cache-augmented generation, in the cited research sense, preloads a manageable knowledge corpus into model context and reuses **cached computation**.

## Key Concepts

**Why it matters:** Repeated questions over a small stable corpus may avoid a separate retrieval step.

- **cached computation**（快取計算）
- **cache invalidation**（快取失效處理）

## How It Works

- Load the corpus within the context budget, reuse supported attention/KV or prompt-prefix caching, and invalidate or rebuild the cache when content changes.

## Example

A stable handbook fits in context; several questions reuse its cached prefix instead of retrieving different chunks each time.

## Common Pitfalls

> [!warning] Watch for this
> - Caching is not training or unlimited memory.
> - Serving support, context size, **cache invalidation**, and attention to relevant facts still matter.

## Related Notes

- [[AI Agent Learning/01 - Fundamentals/Context Window|Context Window]] — 上下文視窗
- [[AI Agent Learning/02 - RAG/RAG|RAG]] — 檢索增強生成
- [[AI Agent Learning/06 - Production/Latency|Latency]] — 延遲

### Next Topics

[[AI Agent Learning/06 - Production/Cost|Cost]] → [[AI Agent Learning/06 - Production/Agent Evaluation|Agent Evaluation]].

## Reference

[CAG research paper](https://arxiv.org/abs/2412.15605) — primary reference; consulted 2026-09-25.
