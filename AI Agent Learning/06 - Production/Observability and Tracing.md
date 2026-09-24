---
tags:
  - ai-agent-learning/production
aliases: ["Observability", "Tracing"]
---

# Observability and Tracing（可觀測性／追蹤）

Learning cluster: [[AI Agent Learning/06 - Production/06 - Production Overview|Production overview]]

## Overview

Observability uses **telemetry** to understand system behavior; tracing records related steps within a run.

## Key Concepts

**Why it matters:** It helps locate slow stages, tool failures, missing evidence, and repeated actions.

- **telemetry**（遙測資料）
- **spans**（追蹤區段）

## How It Works

- Assign a run ID, record **spans** for retrieval and tool/model calls, capture outcomes and timing, and correlate logs and metrics.

## Example

A trace shows retrieval took 0.2 seconds, a tool timed out after 5 seconds, and a retry succeeded; the final answer alone would hide that delay.

## Common Pitfalls

> [!warning] Watch for this
> - Traces show recorded execution, not guaranteed access to internal model reasoning.
> - Redact secrets and restrict access to stored user data.

## Related Notes

- [[AI Agent Learning/03 - Agent Core/Agent State|Agent State]] — 代理狀態
- [[AI Agent Learning/03 - Agent Core/Episodic Memory|Episodic Memory]] — 情節記憶
- [[AI Agent Learning/06 - Production/Agent Evaluation|Agent Evaluation]] — 代理評估

### Next Topics

[[AI Agent Learning/06 - Production/Latency|Latency]] → [[AI Agent Learning/06 - Production/Cost|Cost]] → [[AI Agent Learning/06 - Production/Security|Security]].
