---
tags:
  - ai-agent-learning/fundamentals
---

# LLM（大型語言模型）

Learning cluster: [[AI Agent Learning/01 - Fundamentals/01 - Fundamentals Overview|Fundamentals overview]]

## Overview

A large language model learns *statistical patterns from **training** data* -> generates *token sequences* conditioned on its current input.

## Key Concepts

**Why it matters:** It supplies language understanding, generation, and useful reasoning capabilities inside an agent.

- **training**（訓練）
- **model parameters**（模型參數）

## How It Works

- Text is tokenized, processed by the model, and extended token by token.
- **Training** changes 
	- parameters; 
	- ordinary prompting supplies temporary context.

## Example

Given “Explain a stack in one sentence,” a model may answer “A stack is a last-in, first-out collection.”

## Common Pitfalls

> [!warning] Watch for this
> - Fluent output can be false.
> - **Model parameters** are not a live database, and access to fresh information requires supplied context or tools.

## Related Notes

- [[AI Agent Learning/01 - Fundamentals/Tokens|Tokens]] — 詞元
- [[AI Agent Learning/01 - Fundamentals/Context Window|Context Window]] — 上下文視窗
- [[AI Agent Learning/01 - Fundamentals/Prompting|Prompting]] — 提示設計

### Next Topics

[[AI Agent Learning/01 - Fundamentals/Structured Output|Structured Output]] → [[AI Agent Learning/02 - RAG/RAG|RAG]].
