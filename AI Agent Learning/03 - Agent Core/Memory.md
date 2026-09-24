---
tags:
  - ai-agent-learning/agent-core
---

# Memory（記憶）

Learning cluster: [[AI Agent Learning/03 - Agent Core/03 - Agent Core Overview|Agent Core overview]]

## Overview

Mechanisms for retaining and reusing information across steps or sessions.

## Key Concepts

**Why it matters:** An agent can maintain continuity and reuse relevant facts or past experience.

- **provenance**（來源依據）
- **scope**（適用範圍）

## How It Works

- Select what to store, attach **provenance** and **scope**, retrieve when relevant, update or expire stale entries, and support correction or deletion.

## Example

Remember that the learner prefers English explanations with Traditional Chinese terminology, then retrieve that preference in a later lesson.

## Common Pitfalls

> [!warning] Watch for this
> - Duration and content type are separate axes: an episodic memory can be long-term.
> - Stored application memory is different from model training.

## Related Notes

- [[AI Agent Learning/03 - Agent Core/Short-term Memory|Short-term Memory]] — 短期記憶
- [[AI Agent Learning/03 - Agent Core/Long-term Memory|Long-term Memory]] — 長期記憶
- [[AI Agent Learning/03 - Agent Core/Episodic Memory|Episodic Memory]] — 情節記憶
- [[AI Agent Learning/03 - Agent Core/Semantic Memory|Semantic Memory]] — 語義記憶

### Next Topics

[[AI Agent Learning/04 - Advanced Knowledge/LLM Wiki|LLM Wiki]] → [[AI Agent Learning/06 - Production/Security|Security]].

## Reference

[LangChain memory overview](https://docs.langchain.com/oss/python/concepts/memory) — primary reference; consulted 2026-09-25.
