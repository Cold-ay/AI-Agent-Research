---
tags:
  - ai-agent-learning/fundamentals
---

# Structured Output（結構化輸出）

Learning cluster: [[AI Agent Learning/01 - Fundamentals/01 - Fundamentals Overview|Fundamentals overview]]

## Overview

Output constrained to a machine-readable structure, often a **JSON schema**.

## Key Concepts

**Why it matters:** Software needs predictable fields and types to process model results reliably.

- **JSON schema**（JSON 結構描述）
- **calibrated**（經過校準）

## How It Works

1. Define the schema
2. Request supported constrained output or validate generated output
3. Handle errors, refusals, and missing information.

## Example

An extraction result is:

```json
{
  "topic": "RAG",
  "confidence": 0.7,
  "sources": [
    "note-12"
  ]
}
```

Validate required fields before storing it.

## Common Pitfalls

> [!warning] Watch for this
> - Valid JSON is not necessarily schema-valid, and a schema-valid answer can still contain false facts.
> - Confidence values are not automatically **calibrated**.

## Related Notes

- [[AI Agent Learning/01 - Fundamentals/Prompting|Prompting]] — 提示設計
- [[AI Agent Learning/03 - Agent Core/Tool Calling and Function Calling|Tool Calling and Function Calling]] — 工具／函式調用
- [[AI Agent Learning/03 - Agent Core/Agent State|Agent State]] — 代理狀態

### Next Topics

[[AI Agent Learning/05 - Agent Systems/Guardrails|Guardrails]] → [[AI Agent Learning/06 - Production/Agent Evaluation|Agent Evaluation]].
