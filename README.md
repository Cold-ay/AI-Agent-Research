# AI Agent Research

A public collection of interconnected learning notes about AI agents—from large language model fundamentals and retrieval-augmented generation to agent systems and production evaluation.

This project shares AI agent knowledge openly to help learners and developers understand the concepts, explore their connections, and build a foundation for practical experiments. It contains **62 Markdown notes**, written primarily in English with Traditional Chinese terminology for key concepts.

## Start here

Read the [AI Agent Knowledge Map](AI%20Agent%20Learning/00%20-%20AI%20Agent%20Knowledge%20Map.md) for the full topic index and suggested learning route. Begin with the fundamentals, or jump to the cluster that matches your current project.

## Learning path

| Stage | Topics |
| --- | --- |
| [1. Fundamentals](AI%20Agent%20Learning/01%20-%20Fundamentals/01%20-%20Fundamentals%20Overview.md) | AI agents, LLMs, tokens, context windows, prompting, and structured output |
| [2. RAG](AI%20Agent%20Learning/02%20-%20RAG/02%20-%20RAG%20Overview.md) | Chunking, embeddings, vector databases, semantic and sparse search, hybrid retrieval, and reranking |
| [3. Agent Core](AI%20Agent%20Learning/03%20-%20Agent%20Core/03%20-%20Agent%20Core%20Overview.md) | Tool calling, planning, task decomposition, ReAct, state, memory, and reflection |
| [4. Advanced Knowledge](AI%20Agent%20Learning/04%20-%20Advanced%20Knowledge/04%20-%20Advanced%20Knowledge%20Overview.md) | Knowledge graphs, Graph RAG, agentic and multimodal RAG, CAG, and multi-hop reasoning |
| [5. Agent Systems](AI%20Agent%20Learning/05%20-%20Agent%20Systems/05%20-%20Agent%20Systems%20Overview.md) | Workflows, orchestration, multi-agent systems, MCP, guardrails, human review, and specialized agents |
| [6. Production](AI%20Agent%20Learning/06%20-%20Production/06%20-%20Production%20Overview.md) | Evaluation, retrieval quality, groundedness, task success, tracing, latency, cost, and security |

## Explore the notes

**On GitHub:** use the links above or browse the [`AI Agent Learning`](AI%20Agent%20Learning) folder. The notes use Obsidian-style `[[wikilinks]]`, which GitHub may display as plain text.

**In Obsidian:** clone or download this repository and open the repository root as a vault. Keep the `AI Agent Learning` folder inside that root so the internal paths resolve. Follow the [Graph View Guide](AI%20Agent%20Learning/01%20-%20Graph%20View%20Guide.md) to explore topic clusters and relationships.

```bash
git clone https://github.com/Cold-ay/AI-Agent-Research.git
```

A few links reference original notes in the source author's wider vault; those notes are outside this collection.

## Learn by building

Try building a small study assistant as you progress:

1. Retrieve passages from a small collection of notes.
2. Compare lexical and semantic search.
3. Add a read-only search tool and retain task state.
4. Review answers against their cited passages.
5. Evaluate results on a fixed question set before adding more complexity.

These are suggested exercises; this repository contains learning material rather than a runnable agent implementation. Examples are illustrative unless a source is explicitly named, and selected primary references appear in the relevant notes.

## Contributing

Corrections, clearer explanations, practical examples, and primary-source references are welcome through issues and pull requests. Keep additions focused, link related concepts, and distinguish sourced claims from illustrative examples.
