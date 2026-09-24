---
tags:
  - ai-agent-learning/agent-core
aliases: ["Tool Calling", "Function Calling"]
---

# Tool Calling and Function Calling（工具／函式調用）

Learning cluster: [[AI Agent Learning/03 - Agent Core/03 - Agent Core Overview|Agent Core overview]]

## Overview

A model requests an operation using a named tool and **structured arguments**; application code decides whether and how to execute it.

## Key Concepts

**Why it matters:** It connects language understanding to live data and actions.

- **structured arguments**（結構化參數）
- **permissions**（權限）

## How It Works

1. Expose tool descriptions and schemas
2. Receive a proposed call
3. Validate **permissions** and arguments
4. Execute
5. Return the result
6. Continue.

## Example

The model requests `get_weather({"city":"Tokyo"})`; the application calls a weather service and provides the actual result.

## Common Pitfalls

> [!warning] Watch for this
> - A generated call is not proof the operation happened.
> - Handle timeouts, invalid parameters, and duplicate calls explicitly.

## Related Notes

- [[AI Agent Learning/01 - Fundamentals/Structured Output|Structured Output]] — 結構化輸出
- [[AI Agent Learning/03 - Agent Core/ReAct|ReAct]] — 推理與行動
- [[AI Agent Learning/05 - Agent Systems/Guardrails|Guardrails]] — 行為與安全限制

### Next Topics

[[AI Agent Learning/05 - Agent Systems/MCP|MCP]] → [[AI Agent Learning/03 - Agent Core/Agent State|Agent State]].
