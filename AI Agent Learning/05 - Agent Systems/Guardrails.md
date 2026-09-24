---
tags:
  - ai-agent-learning/agent-systems
---

# Guardrails（行為與安全限制）

Learning cluster: [[AI Agent Learning/05 - Agent Systems/05 - Agent Systems Overview|Agent Systems overview]]

## Overview

Checks and restrictions that constrain model inputs, outputs, and available actions.

## Key Concepts

**Why it matters:** They reduce invalid operations and help enforce system requirements.

- **tool allowlists**（工具允許清單）
- **access-control boundary**（存取控制邊界）

## How It Works

- Combine validation, **tool allowlists**, permissions, resource limits, and approval gates.
- Enforce critical rules outside the language model.

## Example

A database agent uses read-only credentials and a query timeout; a model request to drop a table cannot execute.

## Common Pitfalls

> [!warning] Watch for this
> - A prompt saying “be safe” is not an **access-control boundary**.
> - A content filter alone does not cover operational security.

## Related Notes

- [[AI Agent Learning/06 - Production/Security|Security]] — 安全性
- [[AI Agent Learning/01 - Fundamentals/Structured Output|Structured Output]] — 結構化輸出
- [[AI Agent Learning/03 - Agent Core/Tool Calling and Function Calling|Tool Calling and Function Calling]] — 工具／函式調用

### Next Topics

[[AI Agent Learning/05 - Agent Systems/Human-in-the-loop|Human-in-the-loop]] → [[AI Agent Learning/06 - Production/Agent Evaluation|Agent Evaluation]].
