---
tags:
  - ai-agent-learning/agent-systems
---

# Multi-Agent Systems（多代理系統）

Learning cluster: [[AI Agent Learning/05 - Agent Systems/05 - Agent Systems Overview|Agent Systems overview]]

## Overview

Systems with multiple agent roles or instances that coordinate toward an objective.

## Key Concepts

**Why it matters:** Separate contexts or independent subtasks can support **specialization** and parallel work.

- **specialization**（專業分工）
- **conflict resolution**（衝突解決）

## How It Works

- Define responsibilities and interfaces, delegate bounded tasks, share necessary evidence, and integrate results with **conflict resolution**.

## Example

A research agent extracts paper evidence while a data agent analyzes a table; a coordinator combines and checks both results.

## Common Pitfalls

> [!warning] Watch for this
> - More agents can mean duplicated work, inconsistent assumptions, and greater cost.
> - Compare against a simpler single-agent baseline.

## Related Notes

- [[AI Agent Learning/03 - Agent Core/Task Decomposition|Task Decomposition]] — 任務分解
- [[AI Agent Learning/05 - Agent Systems/Agent Orchestration|Agent Orchestration]] — 代理編排
- [[AI Agent Learning/03 - Agent Core/Reflection and Critic|Reflection and Critic]] — 反思／評審

### Next Topics

[[AI Agent Learning/06 - Production/Agent Evaluation|Agent Evaluation]] → [[AI Agent Learning/06 - Production/Cost|Cost]].
