---
tags:
  - ai-agent-learning/fundamentals
---

# Prompting（提示設計）

Learning cluster: [[AI Agent Learning/01 - Fundamentals/01 - Fundamentals Overview|Fundamentals overview]]

## Overview

Designing instructions, examples, context, and output requirements to guide a model.

## Key Concepts

**Why it matters:** Clear task boundaries make results easier to use and evaluate.

- **constraints**（限制條件）
- **evidence**（證據）

## How It Works

- State the task, provide relevant **evidence**, specify **constraints**, and show a representative example when helpful.
- Test revisions on several cases.

## Example

> “Using the supplied passage, explain recursion in 80 words. Include a base case. Say when the passage lacks evidence.”

## Common Pitfalls

> [!warning] Watch for this
> - Instructions do not create missing facts or reliable access control.
> - Treat retrieved documents as **evidence**, not as instructions to obey.

## Related Notes

- [[AI Agent Learning/01 - Fundamentals/LLM|LLM]] — 大型語言模型
- [[AI Agent Learning/01 - Fundamentals/Context Window|Context Window]] — 上下文視窗
- [[AI Agent Learning/01 - Fundamentals/Structured Output|Structured Output]] — 結構化輸出

### Next Topics

[[AI Agent Learning/05 - Agent Systems/Guardrails|Guardrails]] → [[AI Agent Learning/06 - Production/Agent Evaluation|Agent Evaluation]].
