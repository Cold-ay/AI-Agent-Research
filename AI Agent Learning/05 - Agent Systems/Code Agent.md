---
tags:
  - ai-agent-learning/agent-systems
---

# Code Agent（程式代理）

Learning cluster: [[AI Agent Learning/05 - Agent Systems/05 - Agent Systems Overview|Agent Systems overview]]

## Overview

An agent that works with code through file inspection, editing, execution, and **verification**.

## Key Concepts

**Why it matters:** Many programming tasks require iterative feedback from the actual project.

- **verification**（驗證）
- **controlled execution environment**（受控執行環境）

## How It Works

1. Inspect relevant code
2. Plan a scoped change
3. Edit
4. Run meaningful checks
5. Inspect failures
6. Revise and report results.

## Example

Fix a parser bug, run tests covering the failing input and a normal input, then summarize the change and any remaining limitation.

## Common Pitfalls

> [!warning] Watch for this
> - Passing tests proves only what they cover.
> - Use a **controlled execution environment** and avoid exposing secrets to generated commands.

## Related Notes

- [[AI Agent Learning/03 - Agent Core/ReAct|ReAct]] — 推理與行動
- [[AI Agent Learning/03 - Agent Core/Tool Calling and Function Calling|Tool Calling and Function Calling]] — 工具／函式調用
- [[AI Agent Learning/03 - Agent Core/Reflection and Critic|Reflection and Critic]] — 反思／評審

### Next Topics

[[AI Agent Learning/06 - Production/Security|Security]] → [[AI Agent Learning/06 - Production/Task Success|Task Success]].
