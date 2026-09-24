---
tags:
  - ai-agent-learning/advanced-knowledge
---

# Multimodal RAG（多模態檢索增強生成）

Learning cluster: [[AI Agent Learning/04 - Advanced Knowledge/04 - Advanced Knowledge Overview|Advanced Knowledge overview]]

## Overview

RAG that retrieves evidence across **modalities** such as text, images, tables, audio, or video.

## Key Concepts

**Why it matters:** Important evidence may be inside a chart, diagram, or recording.

- **modalities**（模態）
- **OCR**（光學字元辨識）

## How It Works

- Extract modality-aware representations, retain page or time references, retrieve relevant items, and provide compatible evidence to a suitable model.

## Example

Retrieve a revenue chart and inspect its axis labels to identify the largest quarterly decline, citing the page containing the chart.

## Common Pitfalls

> [!warning] Watch for this
> - **OCR** and captions can lose layout or units.
> - Preserve original evidence and check extracted values against it.

## Related Notes

- [[AI Agent Learning/02 - RAG/Embeddings|Embeddings]] — 向量嵌入
- [[AI Agent Learning/02 - RAG/RAG|RAG]] — 檢索增強生成
- [[AI Agent Learning/06 - Production/Groundedness|Groundedness]] — 證據支持程度

### Next Topics

[[AI Agent Learning/04 - Advanced Knowledge/Agentic RAG|Agentic RAG]] → [[AI Agent Learning/06 - Production/Agent Evaluation|Agent Evaluation]].
