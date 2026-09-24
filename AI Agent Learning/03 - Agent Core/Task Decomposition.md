---
tags:
  - ai-agent-learning/agent-core
---

# Task Decomposition（任務分解）

Learning cluster: [[AI Agent Learning/03 - Agent Core/03 - Agent Core Overview|Agent Core overview]]

## Overview

Breaking a goal into smaller tasks with clear inputs, outputs, and dependencies.

## Key Concepts

**Why it matters:** Small tasks are easier to verify and sometimes can run independently.

- **prerequisites**（先決條件）
- **coordination cost**（協調成本）

## How It Works

- Define the final deliverable, split by meaningful outputs, identify **prerequisites**, and specify how partial results will be integrated.

## Example

- A literature review becomes paper collection, evidence extraction, comparison, and synthesis.
- Comparison depends on extraction.

## Common Pitfalls

> [!warning] Watch for this
> - Splitting too finely adds **coordination cost**.
> - Parallel work helps only when tasks are sufficiently independent.

## Related Notes

- [[AI Agent Learning/03 - Agent Core/Planning|Planning]] — 規劃
- [[AI Agent Learning/05 - Agent Systems/Workflow vs Agent|Workflow vs Agent]] — 工作流與代理

### Next Topics

[[AI Agent Learning/05 - Agent Systems/Multi-Agent Systems|Multi-Agent Systems]] → [[AI Agent Learning/05 - Agent Systems/Agent Orchestration|Agent Orchestration]].
