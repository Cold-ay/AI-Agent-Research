---
tags:
  - ai-agent-learning/agent-core
---

# ReAct（推理與行動）

Learning cluster: [[AI Agent Learning/03 - Agent Core/03 - Agent Core Overview|Agent Core overview]]

## Overview

An agent pattern that interleaves reasoning about next steps, actions, and **observations**.

## Key Concepts

**Why it matters:** Tool results can change what the agent should do next.

- **observations**（觀察結果）
- **bounded loops**（有界迴圈）

## How It Works

1. Assess available evidence
2. Choose an action
3. Receive an observation
4. Update the next step
5. Stop when the task is done or a limit is reached.

## Example

A study assistant searches for “RAG,” finds an unclear acronym, opens the source, and then writes a sourced definition.

## Common Pitfalls

> [!warning] Watch for this
> - Use **bounded loops** and verify **observations**.
> - A readable action summary is useful; an internal reasoning transcript is not required for reliable operation.

## Related Notes

- [[AI Agent Learning/03 - Agent Core/Tool Calling and Function Calling|Tool Calling and Function Calling]] — 工具／函式調用
- [[AI Agent Learning/03 - Agent Core/Agent State|Agent State]] — 代理狀態
- [[AI Agent Learning/03 - Agent Core/Planning|Planning]] — 規劃

### Next Topics

[[AI Agent Learning/04 - Advanced Knowledge/Agentic RAG|Agentic RAG]] → [[AI Agent Learning/06 - Production/Observability and Tracing|Observability and Tracing]].

## Reference

[ReAct research paper](https://arxiv.org/abs/2210.03629) — primary reference; consulted 2026-09-25.
