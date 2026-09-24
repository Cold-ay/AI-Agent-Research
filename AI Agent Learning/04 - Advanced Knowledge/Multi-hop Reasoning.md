---
tags:
  - ai-agent-learning/advanced-knowledge
---

# Multi-hop Reasoning（多跳推理）

Learning cluster: [[AI Agent Learning/04 - Advanced Knowledge/04 - Advanced Knowledge Overview|Advanced Knowledge overview]]

## Overview

Combining multiple evidence steps to answer a question whose answer is not in one isolated fact.

## Key Concepts

**Why it matters:** Many relationship questions require connecting sources.

- **intermediate facts**（中間事實）
- **supported steps**（有證據支持的步驟）

## How It Works

- Break the question into **intermediate facts**, verify each connection, and combine only **supported steps**.

## Example

- Source A says Team A owns Atlas; source B says Atlas uses PostgreSQL.
- Together they identify a database used by Team A.

## Common Pitfalls

> [!warning] Watch for this
> - A missing or ambiguous link breaks the conclusion.
> - Multiple searches alone do not guarantee valid multi-hop reasoning.

## Related Notes

- [[AI Agent Learning/04 - Advanced Knowledge/Knowledge Graph|Knowledge Graph]] — 知識圖譜
- [[AI Agent Learning/04 - Advanced Knowledge/Graph RAG|Graph RAG]] — 圖譜式檢索增強生成
- [[AI Agent Learning/03 - Agent Core/Task Decomposition|Task Decomposition]] — 任務分解

### Next Topics

[[AI Agent Learning/04 - Advanced Knowledge/Agentic RAG|Agentic RAG]] → [[AI Agent Learning/06 - Production/Groundedness|Groundedness]].
