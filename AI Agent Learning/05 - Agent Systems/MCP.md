---
tags:
  - ai-agent-learning/agent-systems
---

# MCP（模型上下文協議）

Learning cluster: [[AI Agent Learning/05 - Agent Systems/05 - Agent Systems Overview|Agent Systems overview]]

## Overview

Model Context Protocol standardizes communication between AI applications and servers exposing **capabilities** such as tools, resources, and prompts.

## Key Concepts

**Why it matters:** Shared interfaces reduce the need for a separate integration design for every application-service pair.

- **host application**（主機應用程式）
- **capabilities**（功能能力）

## How It Works

- A **host application** uses MCP clients to connect to servers, discover supported **capabilities**, and exchange requests and responses.
- The host controls how capabilities reach the model.

## Example

A notes server exposes a search tool and note resources; a compatible application can retrieve study material through that interface.

## Common Pitfalls

> [!warning] Watch for this
> - MCP is not the model itself, an agent planner, or an automatic permission grant.
> - Authentication and execution policy still require implementation.

## Related Notes

- [[AI Agent Learning/03 - Agent Core/Tool Calling and Function Calling|Tool Calling and Function Calling]] — 工具／函式調用
- [[AI Agent Learning/06 - Production/Security|Security]] — 安全性

### Next Topics

[[AI Agent Learning/05 - Agent Systems/Agent Orchestration|Agent Orchestration]] → [[AI Agent Learning/05 - Agent Systems/Guardrails|Guardrails]].

## Reference

[MCP architecture](https://modelcontextprotocol.io/docs/learn/architecture) — primary reference; consulted 2026-09-25.
