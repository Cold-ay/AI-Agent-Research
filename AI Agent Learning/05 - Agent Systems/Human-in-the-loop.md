---
tags:
  - ai-agent-learning/agent-systems
---

# Human-in-the-loop（人工介入）

Learning cluster: [[AI Agent Learning/05 - Agent Systems/05 - Agent Systems Overview|Agent Systems overview]]

## Overview

A design where a person supplies information, reviews output, or approves a specified action at a meaningful point.

## Key Concepts

**Why it matters:** Human judgment can resolve ambiguity and control consequential actions.

- **pending state**（待處理狀態）
- **approval**（核准）

## How It Works

- Pause with the concrete proposal and evidence, retain **pending state**, collect a decision, and resume or revise based on that decision.

## Example

An assistant drafts an email and shows its recipients and body; sending happens only after the required approval.

## Common Pitfalls

> [!warning] Watch for this
> - **Approval** applies to the reviewed action.
> - If recipients or content materially change, old approval may no longer cover it.

## Related Notes

- [[AI Agent Learning/03 - Agent Core/Agent State|Agent State]] — 代理狀態
- [[AI Agent Learning/05 - Agent Systems/Guardrails|Guardrails]] — 行為與安全限制
- [[AI Agent Learning/05 - Agent Systems/Workflow vs Agent|Workflow vs Agent]] — 工作流與代理

### Next Topics

[[AI Agent Learning/05 - Agent Systems/Agent Orchestration|Agent Orchestration]] → [[AI Agent Learning/06 - Production/Security|Security]].
