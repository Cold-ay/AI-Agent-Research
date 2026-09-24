---
tags:
  - ai-agent-learning/agent-core
---

# Episodic Memory（情節記憶）

Learning cluster: [[AI Agent Learning/03 - Agent Core/03 - Agent Core Overview|Agent Core overview]]

## Overview

Memory of specific past events, actions, and **outcomes**.

## Key Concepts

**Why it matters:** Prior experience can help diagnose failures and avoid repeating ineffective actions.

- **outcomes**（結果）
- **context**（情境）

## How It Works

- Store an event with **context**, time, attempted action, outcome, and supporting evidence; retrieve analogous episodes when useful.

## Example

“During task 42, service A timed out twice; switching to service B returned the needed document.”

## Common Pitfalls

> [!warning] Watch for this
> - One successful episode does not establish a general rule.
> - Environment changes can make past strategies unsuitable.

## Related Notes

- [[AI Agent Learning/03 - Agent Core/Memory|Memory]] — 記憶
- [[AI Agent Learning/03 - Agent Core/Long-term Memory|Long-term Memory]] — 長期記憶
- [[AI Agent Learning/06 - Production/Observability and Tracing|Observability and Tracing]] — 可觀測性／追蹤

### Next Topics

[[AI Agent Learning/03 - Agent Core/Reflection and Critic|Reflection and Critic]] → [[AI Agent Learning/06 - Production/Agent Evaluation|Agent Evaluation]].
