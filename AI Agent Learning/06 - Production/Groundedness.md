---
tags:
  - ai-agent-learning/production
---

# Groundedness（證據支持程度）

Learning cluster: [[AI Agent Learning/06 - Production/06 - Production Overview|Production overview]]

## Overview

The degree to which generated claims are supported by the evidence supplied or cited.

## Key Concepts

**Why it matters:** It distinguishes a plausible answer from one that can be checked against sources.

- **supporting evidence**（支持證據）
- **factual claims**（事實主張）

## How It Works

- Break the answer into **factual claims**, map each to **supporting evidence**, and mark unsupported or contradicted claims with a consistent rubric.

## Example

A note says refunds apply within 30 days. “You can refund within 30 days” is supported; “refunds are always instant” is not.

## Common Pitfalls

> [!warning] Watch for this
> - A claim can be grounded in an outdated or false source.
> - Grounding and real-world correctness are related but different.

## Related Notes

- [[AI Agent Learning/02 - RAG/RAG|RAG]] — 檢索增強生成
- [[AI Agent Learning/03 - Agent Core/Reflection and Critic|Reflection and Critic]] — 反思／評審
- [[AI Agent Learning/06 - Production/Accuracy|Accuracy]] — 準確率

### Next Topics

[[AI Agent Learning/06 - Production/Agent Evaluation|Agent Evaluation]] → [[AI Agent Learning/04 - Advanced Knowledge/Multimodal RAG|Multimodal RAG]].
