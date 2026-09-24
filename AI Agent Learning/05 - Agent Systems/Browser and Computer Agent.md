---
tags:
  - ai-agent-learning/agent-systems
aliases: ["Browser Agent", "Computer Agent"]
---

# Browser and Computer Agent（瀏覽器／電腦操作代理）

Learning cluster: [[AI Agent Learning/05 - Agent Systems/05 - Agent Systems Overview|Agent Systems overview]]

## Overview

An agent that observes and interacts with user interfaces using browser elements, **accessibility information**, or screenshots and input actions.

## Key Concepts

**Why it matters:** It can complete tasks in software without a suitable direct API.

- **accessibility information**（無障礙資訊）
- **user authorization**（使用者授權）

## How It Works

1. Observe current UI
2. Identify the intended element
3. Act
4. Inspect the resulting state
5. Continue or stop.

## Example

Open a report page, choose the requested date range, download the report, and confirm the file exists.

## Common Pitfalls

> [!warning] Watch for this
> - UI state changes and pages can contain malicious instructions.
> - Distinguish page content from **user authorization** and verify consequential actions.

## Related Notes

- [[AI Agent Learning/03 - Agent Core/Tool Calling and Function Calling|Tool Calling and Function Calling]] — 工具／函式調用
- [[AI Agent Learning/03 - Agent Core/ReAct|ReAct]] — 推理與行動
- [[AI Agent Learning/05 - Agent Systems/Human-in-the-loop|Human-in-the-loop]] — 人工介入

### Next Topics

[[AI Agent Learning/06 - Production/Security|Security]] → [[AI Agent Learning/06 - Production/Observability and Tracing|Observability and Tracing]].
