---
tags:
  - ai-agent-learning/agent-core
---

# Agent State（代理狀態）

Learning cluster: [[AI Agent Learning/03 - Agent Core/03 - Agent Core Overview|Agent Core overview]]

## Overview

The explicit working data that describes a task’s current progress and execution status.

## Key Concepts

**Why it matters:** It enables resuming, branching, debugging, and preventing repeated work.

- **checkpoints**（檢查點）
- **pending approvals**（待處理核准）

## How It Works

- Maintain fields such as task ID, evidence, completed steps, **pending approvals**, and tool outcomes.
- Save **checkpoints** at meaningful boundaries.

## Example

```json
{
  "task": "study-guide",
  "sources": 8,
  "draft_complete": true,
  "review_complete": false
}
```

This state tells the next step to review the draft.

## Common Pitfalls

> [!warning] Watch for this
> - State is broader than chat history.
> - Checkpointing alone does not prevent an external action from being repeated after a crash.

## Related Notes

- [[AI Agent Learning/03 - Agent Core/Short-term Memory|Short-term Memory]] — 短期記憶
- [[AI Agent Learning/01 - Fundamentals/Structured Output|Structured Output]] — 結構化輸出
- [[AI Agent Learning/03 - Agent Core/Planning|Planning]] — 規劃

### Next Topics

[[AI Agent Learning/05 - Agent Systems/Agent Orchestration|Agent Orchestration]] → [[AI Agent Learning/05 - Agent Systems/Human-in-the-loop|Human-in-the-loop]].
