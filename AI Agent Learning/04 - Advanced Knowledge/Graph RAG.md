---
tags:
  - ai-agent-learning/advanced-knowledge
---

# Graph RAG（圖譜式檢索增強生成）

Learning cluster: [[AI Agent Learning/04 - Advanced Knowledge/04 - Advanced Knowledge Overview|Advanced Knowledge overview]]

## Overview

RAG that uses graph structure or graph-derived information to retrieve and organize evidence.

## Key Concepts

**Why it matters:** Relationships and cross-document themes can matter more than passage similarity alone.

- **communities**（社群）
- **community summaries**（社群摘要）

## How It Works

1. Build or access a graph
2. Locate relevant entities, paths, or **communities**
3. Retrieve supporting evidence or summaries
4. Generate a sourced answer.

## Example

Find which Team A projects depend on a deprecated database by following team-to-project and project-to-database edges.

## Common Pitfalls

> [!warning] Watch for this
> - Graph RAG is a family of designs.
> - Microsoft GraphRAG includes **community summaries**; graph retrieval is not simply drawing a visual graph.

## Related Notes

- [[AI Agent Learning/04 - Advanced Knowledge/Knowledge Graph|Knowledge Graph]] — 知識圖譜
- [[AI Agent Learning/04 - Advanced Knowledge/Multi-hop Reasoning|Multi-hop Reasoning]] — 多跳推理
- [[AI Agent Learning/02 - RAG/RAG|RAG]] — 檢索增強生成

### Next Topics

[[AI Agent Learning/04 - Advanced Knowledge/Agentic RAG|Agentic RAG]] → [[AI Agent Learning/06 - Production/Agent Evaluation|Agent Evaluation]].

## Reference

[Microsoft GraphRAG documentation](https://microsoft.github.io/graphrag/) — primary reference; consulted 2026-09-25.
