---
tags:
  - ai-agent-learning/production
---

# Agent Evaluation（代理評估）

Learning cluster: [[AI Agent Learning/06 - Production/06 - Production Overview|Production overview]]

## Overview

Systematic measurement of whether an agent behaves correctly and completes intended tasks under defined conditions.

## Key Concepts

**Why it matters:** A convincing demonstration may hide fragile retrieval, tool use, or failure handling.

- **held-out cases**（保留測試案例）
- **calibration**（校準）

## How It Works

- Build representative cases with expected outcomes, run repeatable evaluations, inspect failures, and compare quality, latency, and cost across revisions.

## Example

Test a study agent on answerable questions, missing evidence, conflicting notes, and tool failures; score source support and successful completion separately.

## Common Pitfalls

> [!warning] Watch for this
> - One score hides tradeoffs.
> - Use **held-out cases** and repeat stochastic runs; human or model judges need clear rubrics and **calibration**.

## Related Notes

- [[AI Agent Learning/06 - Production/Accuracy|Accuracy]] — 準確率
- [[AI Agent Learning/06 - Production/Retrieval Recall|Retrieval Recall]] — 檢索召回率
- [[AI Agent Learning/06 - Production/Precision|Precision]] — 精確率
- [[AI Agent Learning/06 - Production/Groundedness|Groundedness]] — 證據支持程度
- [[AI Agent Learning/06 - Production/Task Success|Task Success]] — 任務成功率

### Next Topics

[[AI Agent Learning/06 - Production/Observability and Tracing|Observability and Tracing]] → [[AI Agent Learning/06 - Production/Latency|Latency]] → [[AI Agent Learning/06 - Production/Cost|Cost]].
