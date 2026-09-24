---
tags:
  - ai-agent-learning/fundamentals
---

# AI Agent（人工智能代理）

Learning cluster: [[AI Agent Learning/01 - Fundamentals/01 - Fundamentals Overview|Fundamentals overview]]

## Overview

A system that uses a model to choose actions toward a goal, observe results, and adjust its next step.

## Key Concepts

**Why it matters:** Some tasks require interacting with a changing environment rather than producing one answer.

- **permitted action**（允許的行動）
- **autonomy**（自主性）

## How It Works

1. Receive a goal
2. Inspect available information
3. Choose a **permitted action**
4. Observe the result
5. Continue or stop.

The surrounding software executes actions and enforces limits.

## Example

A study assistant searches your notes, notices a missing definition, retrieves a source, and drafts a cited explanation.

## Common Pitfalls

> [!warning] Watch for this
> - **Autonomy** is a design choice.
> - An agent does not need every component in this course, and more autonomy does not guarantee better results.

## Related Notes

- [[AI Agent Learning/01 - Fundamentals/LLM|LLM]] — 大型語言模型
- [[AI Agent Learning/03 - Agent Core/Tool Calling and Function Calling|Tool Calling and Function Calling]] — 工具／函式調用
- [[AI Agent Learning/05 - Agent Systems/Workflow vs Agent|Workflow vs Agent]] — 工作流與代理

### Next Topics

[[AI Agent Learning/01 - Fundamentals/Context Window|Context Window]] → [[AI Agent Learning/02 - RAG/RAG|RAG]].
