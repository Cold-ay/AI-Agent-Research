---
tags:
  - ai-agent-learning/advanced-knowledge
---

# Knowledge Graph（知識圖譜）

Learning cluster: [[AI Agent Learning/04 - Advanced Knowledge/04 - Advanced Knowledge Overview|Advanced Knowledge overview]]

## Overview

A representation of **entities** and **typed relationships**, often with attributes and provenance.

## Key Concepts

**Why it matters:** It exposes connections that are difficult to recover from isolated passages.

- **entities**（實體）
- **typed relationships**（具類型的關係）

## How It Works

- Identify **entities**, resolve duplicate names, record relationships and supporting sources, then query or traverse the graph.

## Example

```text
Atlas —uses→ PostgreSQL; Atlas —owned_by→ Team A.
```

A query can find databases used by Team A’s projects.

## Common Pitfalls

> [!warning] Watch for this
> - Extracted relationships can be wrong or stale.
> - Obsidian links form a useful note graph but are not automatically a fully typed knowledge graph.

## Related Notes

- [[AI Agent Learning/03 - Agent Core/Semantic Memory|Semantic Memory]] — 語義記憶
- [[AI Agent Learning/04 - Advanced Knowledge/LLM Wiki|LLM Wiki]] — LLM 維護的知識 Wiki

### Next Topics

[[AI Agent Learning/04 - Advanced Knowledge/Graph RAG|Graph RAG]] → [[AI Agent Learning/04 - Advanced Knowledge/Multi-hop Reasoning|Multi-hop Reasoning]].
