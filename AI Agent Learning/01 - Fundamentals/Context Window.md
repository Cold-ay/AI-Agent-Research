---
tags:
  - ai-agent-learning/fundamentals
---

# Context Window（上下文視窗）

Learning cluster: [[AI Agent Learning/01 - Fundamentals/01 - Fundamentals Overview|Fundamentals overview]]

## Overview

The bounded amount of information a model can consider during a request, measured in tokens.

## Key Concepts

**Why it matters:** Instructions, messages, retrieved passages, and tool results compete for available space.

- **output budget**（輸出預算）
- **conversation summary**（對話摘要）

## How It Works

- The application assembles relevant input and reserves an **output budget**.
- It may trim, summarize, or retrieve older information before the next request.

## Example

A study chat includes the current question, five relevant passages, and a short conversation summary instead of every PDF.

## Common Pitfalls

> [!warning] Watch for this
> - A large window does not ensure attention to every detail.
> - Input/output accounting and other token categories depend on the model.

## Related Notes

- [[AI Agent Learning/01 - Fundamentals/LLM|LLM]] — 大型語言模型
- [[AI Agent Learning/01 - Fundamentals/Tokens|Tokens]] — 詞元
- [[AI Agent Learning/03 - Agent Core/Short-term Memory|Short-term Memory]] — 短期記憶

### Next Topics

[[AI Agent Learning/02 - RAG/Chunking|Chunking]] → [[AI Agent Learning/04 - Advanced Knowledge/CAG|CAG]].
