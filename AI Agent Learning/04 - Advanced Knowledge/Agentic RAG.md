---
tags:
  - ai-agent-learning/advanced-knowledge
---

# Agentic RAG（代理式檢索增強生成）

Learning cluster: [[AI Agent Learning/04 - Advanced Knowledge/04 - Advanced Knowledge Overview|Advanced Knowledge overview]]

## Overview

RAG in which an agent dynamically chooses retrieval steps, sources, or follow-up queries.

## Key Concepts

**Why it matters:** Complex questions may require evidence not discoverable with one fixed query.

- **evidence gaps**（證據缺口）
- **stopping rules**（停止規則）

## How It Works

1. Inspect the question
2. Retrieve
3. Assess **evidence gaps**
4. Reformulate or choose another source
5. Stop and answer or report uncertainty.

## Example

To explain a sales change, retrieve the launch date, query sales periods, and inspect feedback; distinguish hypotheses from proven causes.

## Common Pitfalls

> [!warning] Watch for this
> - Adaptive retrieval increases latency and can wander.
> - Set step budgets and evidence-based **stopping rules**.

## Related Notes

- [[AI Agent Learning/02 - RAG/RAG|RAG]] — 檢索增強生成
- [[AI Agent Learning/03 - Agent Core/ReAct|ReAct]] — 推理與行動
- [[AI Agent Learning/04 - Advanced Knowledge/Multi-hop Reasoning|Multi-hop Reasoning]] — 多跳推理

### Next Topics

[[AI Agent Learning/04 - Advanced Knowledge/Graph RAG|Graph RAG]] → [[AI Agent Learning/05 - Agent Systems/SQL and Data Agent|SQL and Data Agent]].
