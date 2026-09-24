---
tags:
  - ai-agent-learning/agent-core
aliases: ["Reflection", "Critic"]
---

# Reflection and Critic（反思／評審）

Learning cluster: [[AI Agent Learning/03 - Agent Core/03 - Agent Core Overview|Agent Core overview]]

## Overview

A review step that checks a proposed answer or action against criteria and evidence.

## Key Concepts

**Why it matters:** It can catch omissions and contradictions before delivery.

- **rubric**（評分準則）
- **External evidence**（外部證據）

## How It Works

1. Produce a draft
2. Compare with sources, tests, or a **rubric**
3. Identify specific defects
4. Revise
5. Stop after bounded checks.

## Example

A draft says “30% growth,” but the source table says 13%; the critic points to the table and requests correction.

## Common Pitfalls

> [!warning] Watch for this
> - Self-review can repeat the same error.
> - **External evidence** and executable checks are stronger than unsupported confidence or endless revision.

## Related Notes

- [[AI Agent Learning/06 - Production/Groundedness|Groundedness]] — 證據支持程度
- [[AI Agent Learning/06 - Production/Agent Evaluation|Agent Evaluation]] — 代理評估
- [[AI Agent Learning/03 - Agent Core/Episodic Memory|Episodic Memory]] — 情節記憶

### Next Topics

[[AI Agent Learning/05 - Agent Systems/Code Agent|Code Agent]] → [[AI Agent Learning/05 - Agent Systems/Human-in-the-loop|Human-in-the-loop]].
