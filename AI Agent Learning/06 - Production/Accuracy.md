---
tags:
  - ai-agent-learning/production
---

# Accuracy（準確率）

Learning cluster: [[AI Agent Learning/06 - Production/06 - Production Overview|Production overview]]

## Overview

The proportion of evaluated predictions or answers that match a defined **correctness criterion**.

## Key Concepts

**Why it matters:** It measures correctness when the task has reliable **reference labels** or a grading rule.

- **correctness criterion**（正確性準則）
- **reference labels**（參考標籤）

## How It Works

- Specify the unit and rubric, compare outputs with references, and divide correct cases by total cases.

## Example

If 18 of 20 factual answers satisfy the correctness rubric, measured accuracy is 90% on that test set.

## Common Pitfalls

> [!warning] Watch for this
> - Accuracy depends on the dataset and grading policy.
> - It can conceal poor performance on rare but important categories.

## Related Notes

- [[AI Agent Learning/06 - Production/Agent Evaluation|Agent Evaluation]] — 代理評估
- [[AI Agent Learning/06 - Production/Groundedness|Groundedness]] — 證據支持程度

### Next Topics

[[AI Agent Learning/06 - Production/Task Success|Task Success]] → [[AI Agent Learning/06 - Production/Precision|Precision]].
