---
tags:
  - ai-agent-learning/production
---

# Latency（延遲）

Learning cluster: [[AI Agent Learning/06 - Production/06 - Production Overview|Production overview]]

## Overview

Elapsed time between a request and an observable response or completed task.

## Key Concepts

**Why it matters:** Responsiveness affects usefulness, especially when agents chain multiple calls.

- **time to first output**（首次輸出時間）
- **tail percentiles**（尾端百分位數）

## How It Works

- Measure end-to-end time and stage timings; distinguish **time to first output** from time to completion and inspect median and **tail percentiles**.

## Example

Three sequential 2-second calls take roughly 6 seconds plus overhead; independent calls may overlap if resources permit.

## Common Pitfalls

> [!warning] Watch for this
> - Streaming can improve perceived responsiveness without reducing completion time.
> - Parallelism can add contention and coordination overhead.

## Related Notes

- [[AI Agent Learning/06 - Production/Observability and Tracing|Observability and Tracing]] — 可觀測性／追蹤
- [[AI Agent Learning/04 - Advanced Knowledge/CAG|CAG]] — 快取增強生成
- [[AI Agent Learning/05 - Agent Systems/Agent Orchestration|Agent Orchestration]] — 代理編排

### Next Topics

[[AI Agent Learning/06 - Production/Cost|Cost]] → [[AI Agent Learning/06 - Production/Agent Evaluation|Agent Evaluation]].
