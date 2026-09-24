---
tags:
  - ai-agent-learning/agent-core
---

# Semantic Memory（語義記憶）

Learning cluster: [[AI Agent Learning/03 - Agent Core/03 - Agent Core Overview|Agent Core overview]]

## Overview

Stored **facts**, concepts, and relationships rather than a record of one particular event.

## Key Concepts

**Why it matters:** It provides reusable knowledge about a user, project, or domain.

- **facts**（事實）
- **provenance**（來源依據）

## How It Works

- Extract a supported fact, preserve its source and scope, resolve conflicts, and retrieve it when answering related questions.

## Example

“Project Atlas uses PostgreSQL” is semantic content; “we migrated it last Tuesday” describes an episode.

## Common Pitfalls

> [!warning] Watch for this
> - Semantic memory is not semantic search.
> - **Facts** need **provenance** and revision when the world changes.

## Related Notes

- [[AI Agent Learning/03 - Agent Core/Memory|Memory]] — 記憶
- [[AI Agent Learning/03 - Agent Core/Long-term Memory|Long-term Memory]] — 長期記憶
- [[AI Agent Learning/04 - Advanced Knowledge/Knowledge Graph|Knowledge Graph]] — 知識圖譜

### Next Topics

[[AI Agent Learning/04 - Advanced Knowledge/LLM Wiki|LLM Wiki]] → [[AI Agent Learning/02 - RAG/RAG|RAG]].
