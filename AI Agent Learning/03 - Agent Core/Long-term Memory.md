---
tags:
  - ai-agent-learning/agent-core
---

# Long-term Memory（長期記憶）

Learning cluster: [[AI Agent Learning/03 - Agent Core/03 - Agent Core Overview|Agent Core overview]]

## Overview

Information stored for reuse beyond a single interaction or task.

## Key Concepts

**Why it matters:** It supports continuity without reintroducing stable preferences and project facts.

- **persistent storage**（持久儲存）
- **expiration**（到期失效）

## How It Works

- Write selected records to **persistent storage**, assign user/project scope, retrieve relevant records later, and manage updates and **expiration**.

## Example

Save “Project Atlas uses PostgreSQL” with a source and date; retrieve it when planning a later database change.

## Common Pitfalls

> [!warning] Watch for this
> - Persistence does not make a memory accurate or current.
> - Avoid storing everything automatically, especially sensitive or unverified content.

## Related Notes

- [[AI Agent Learning/03 - Agent Core/Memory|Memory]] — 記憶
- [[AI Agent Learning/03 - Agent Core/Semantic Memory|Semantic Memory]] — 語義記憶
- [[AI Agent Learning/03 - Agent Core/Episodic Memory|Episodic Memory]] — 情節記憶

### Next Topics

[[AI Agent Learning/04 - Advanced Knowledge/LLM Wiki|LLM Wiki]] → [[AI Agent Learning/06 - Production/Security|Security]].
