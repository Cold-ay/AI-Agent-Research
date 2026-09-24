---
tags:
  - ai-agent-learning/agent-systems
aliases: ["SQL Agent", "Data Agent"]
---

# SQL and Data Agent（資料庫／資料代理）

Learning cluster: [[AI Agent Learning/05 - Agent Systems/05 - Agent Systems Overview|Agent Systems overview]]

## Overview

An agent that inspects **schemas** and uses queries or analysis tools to answer questions about structured data.

## Key Concepts

**Why it matters:** Aggregation and filtering are often more accurately performed by a database than by reading retrieved prose.

- **schemas**（結構描述）
- **join keys**（連接鍵）

## How It Works

1. Inspect schema and definitions
2. Generate a bounded query
3. Validate
4. Execute with appropriate permissions
5. Check results
6. Explain them.

## Example

For highest sales by product, group records by product and sum revenue within an explicitly defined date interval.

## Common Pitfalls

> [!warning] Watch for this
> - Define time zones, refunds, currencies, and **join keys**.
> - A syntactically valid query can still double-count rows or answer the wrong business question.

## Related Notes

- [[AI Agent Learning/03 - Agent Core/Tool Calling and Function Calling|Tool Calling and Function Calling]] — 工具／函式調用
- [[AI Agent Learning/01 - Fundamentals/Structured Output|Structured Output]] — 結構化輸出
- [[AI Agent Learning/05 - Agent Systems/Guardrails|Guardrails]] — 行為與安全限制

### Next Topics

[[AI Agent Learning/04 - Advanced Knowledge/Agentic RAG|Agentic RAG]] → [[AI Agent Learning/06 - Production/Agent Evaluation|Agent Evaluation]].
