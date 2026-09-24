---
tags:
  - ai-agent-learning/agent-core
---

# Short-term Memory（短期記憶）

Learning cluster: [[AI Agent Learning/03 - Agent Core/03 - Agent Core Overview|Agent Core overview]]

## Overview

Task- or conversation-scoped information retained for the current interaction.

## Key Concepts

**Why it matters:** It keeps pronouns, recent tool results, and immediate goals coherent.

- **thread state**（對話執行緒狀態）
- **checkpoint**（檢查點）

## How It Works

- Keep recent messages and relevant state; summarize older steps when context becomes crowded.
- Persist **thread state** if resumption is needed.

## Example

After “Compare RAG with CAG,” a follow-up “Which suits a small handbook?” uses the previous comparison as context.

## Common Pitfalls

> [!warning] Watch for this
> - Short-term does not necessarily mean stored only in RAM.
> - A **checkpoint** can persist a conversation while it remains thread-scoped.

## Related Notes

- [[AI Agent Learning/01 - Fundamentals/Context Window|Context Window]] — 上下文視窗
- [[AI Agent Learning/03 - Agent Core/Agent State|Agent State]] — 代理狀態
- [[AI Agent Learning/03 - Agent Core/Memory|Memory]] — 記憶

### Next Topics

[[AI Agent Learning/03 - Agent Core/Long-term Memory|Long-term Memory]] → [[AI Agent Learning/06 - Production/Observability and Tracing|Observability and Tracing]].
