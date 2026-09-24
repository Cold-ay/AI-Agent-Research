---
tags:
  - ai-agent-learning/fundamentals
---

# Tokens（詞元）

Learning cluster: [[AI Agent Learning/01 - Fundamentals/01 - Fundamentals Overview|Fundamentals overview]]

## Overview

Tokens are the units a model encodes and generates: words, word fragments, punctuation, or other representations.

## Key Concepts

**Why it matters:** Context limits, processing time, and many usage charges depend on token counts.

- **tokenizer**（詞元化器）
- **token IDs**（詞元識別碼）

## How It Works

- A **tokenizer** maps text to **token IDs**.
- The model processes these IDs and generates more IDs, which are decoded into text.

## Example

“unbelievable” may be one token or several, depending on the tokenizer; Chinese characters also have tokenizer-dependent splits.

## Common Pitfalls

> [!warning] Watch for this
> - A token is not reliably one English word or one Chinese character.
> - Count with the actual model **tokenizer** when exact budgets matter.

## Related Notes

- [[AI Agent Learning/01 - Fundamentals/LLM|LLM]] — 大型語言模型
- [[AI Agent Learning/01 - Fundamentals/Context Window|Context Window]] — 上下文視窗
- [[AI Agent Learning/06 - Production/Cost|Cost]] — 成本

### Next Topics

[[AI Agent Learning/02 - RAG/Chunking|Chunking]] → [[AI Agent Learning/01 - Fundamentals/Prompting|Prompting]].
