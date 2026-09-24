---
tags:
  - ai-agent-learning/agent-core
---

# Planning（規劃）

Learning cluster: [[AI Agent Learning/03 - Agent Core/03 - Agent Core Overview|Agent Core overview]]

## Overview

Choosing a sequence or structure of actions intended to reach a goal.

## Key Concepts

**Why it matters:** It coordinates **dependencies** and makes missing steps visible.

- **dependencies**（相依關係）
- **observations**（觀察結果）

## How It Works

- Define success, identify needed evidence or actions, order **dependencies**, execute, and revise when **observations** invalidate assumptions.

## Example

To create a study guide: inspect the syllabus, identify topics, retrieve sources, draft explanations, then verify coverage.

## Common Pitfalls

> [!warning] Watch for this
> - A plan is a proposal, not evidence of completion.
> - Simple tasks may need only one action instead of an elaborate plan.

## Related Notes

- [[AI Agent Learning/03 - Agent Core/Task Decomposition|Task Decomposition]] — 任務分解
- [[AI Agent Learning/03 - Agent Core/Agent State|Agent State]] — 代理狀態
- [[AI Agent Learning/03 - Agent Core/ReAct|ReAct]] — 推理與行動

### Next Topics

[[AI Agent Learning/05 - Agent Systems/Agent Orchestration|Agent Orchestration]] → [[AI Agent Learning/03 - Agent Core/Reflection and Critic|Reflection and Critic]].
