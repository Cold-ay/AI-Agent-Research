---
tags:
  - ai-agent-learning/rag
---

# Chunking（文件分塊）

Learning cluster: [[AI Agent Learning/02 - RAG/02 - RAG Overview|RAG overview]]

## Overview

Splitting source material into units suitable for retrieval and model input.

## Key Concepts

**Why it matters:** **Chunk boundaries** affect whether retrieved evidence contains a complete answer.

- **Chunk boundaries**（分塊邊界）
- **Overlap**（重疊）

## How It Works

- Split by headings, paragraphs, token counts, or topic changes.
- Preserve source/page IDs and optionally **overlap** adjacent chunks.
- Evaluate on real questions.

## Example

Keep a refund rule and its exceptions in one section rather than splitting after the word “except.”

## Common Pitfalls

> [!warning] Watch for this
> - Small chunks can lose context; large ones add irrelevant text.
> - **Overlap** creates duplicates and is not a substitute for good boundaries.

## Related Notes

- [[AI Agent Learning/01 - Fundamentals/Tokens|Tokens]] — 詞元
- [[AI Agent Learning/02 - RAG/RAG|RAG]] — 檢索增強生成
- [[AI Agent Learning/01 - Fundamentals/Context Window|Context Window]] — 上下文視窗

### Next Topics

[[AI Agent Learning/02 - RAG/Embeddings|Embeddings]] → [[AI Agent Learning/02 - RAG/Reranking|Reranking]].
