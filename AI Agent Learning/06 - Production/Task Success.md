---
tags:
  - ai-agent-learning/production
---

# Task Success（任務成功率）

Learning cluster: [[AI Agent Learning/06 - Production/06 - Production Overview|Production overview]]

## Overview

Whether a run achieves the user’s specified outcome under its constraints; success rate aggregates this across runs.

## Key Concepts

**Why it matters:** Correct-looking text is insufficient when the goal is an actual completed action or artifact.

- **completion criteria**（完成準則）
- **constraint compliance**（遵守限制條件）

## How It Works

- Define observable **completion criteria**, verify the final state, and count successful runs while recording partial failures separately.

## Example

For creating study notes, success requires all requested files, complete sections, and resolvable links—not merely a message claiming completion.

## Common Pitfalls

> [!warning] Watch for this
> - Avoid grading only the final answer.
> - Check external state and **constraint compliance**, including whether unintended changes occurred.

## Related Notes

- [[AI Agent Learning/06 - Production/Agent Evaluation|Agent Evaluation]] — 代理評估
- [[AI Agent Learning/06 - Production/Accuracy|Accuracy]] — 準確率
- [[AI Agent Learning/05 - Agent Systems/Code Agent|Code Agent]] — 程式代理

### Next Topics

[[AI Agent Learning/06 - Production/Observability and Tracing|Observability and Tracing]] → [[AI Agent Learning/06 - Production/Cost|Cost]].
