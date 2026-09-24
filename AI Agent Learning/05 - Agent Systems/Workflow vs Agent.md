---
tags:
  - ai-agent-learning/agent-systems
---

# Workflow vs Agent（工作流與代理）

Learning cluster: [[AI Agent Learning/05 - Agent Systems/05 - Agent Systems Overview|Agent Systems overview]]

## Overview

A workflow follows application-defined **control paths**; an agent delegates some next-action decisions to a model.

## Key Concepts

**Why it matters:** The choice affects predictability, flexibility, and testability.

- **control paths**（控制路徑）
- **dynamic action selection**（動態行動選擇）

## How It Works

- Use explicit steps for known processes, **dynamic action selection** for variable tasks, or combine a fixed outer workflow with an agent inside one stage.

## Example

- PDF → extract → summarize is a workflow.
- An assistant that decides whether to search, calculate, or request missing data is more agentic.

## Common Pitfalls

> [!warning] Watch for this
> - This is a spectrum, not a strict product label.
> - A workflow can contain branches, loops, and LLM calls without becoming fully autonomous.

## Related Notes

- [[AI Agent Learning/01 - Fundamentals/AI Agent|AI Agent]] — 人工智能代理
- [[AI Agent Learning/03 - Agent Core/Task Decomposition|Task Decomposition]] — 任務分解
- [[AI Agent Learning/05 - Agent Systems/Agent Orchestration|Agent Orchestration]] — 代理編排

### Next Topics

[[AI Agent Learning/05 - Agent Systems/Multi-Agent Systems|Multi-Agent Systems]] → [[AI Agent Learning/05 - Agent Systems/Human-in-the-loop|Human-in-the-loop]].

## Reference

[Building effective agents](https://www.anthropic.com/engineering/building-effective-agents) — primary reference; consulted 2026-09-25.
