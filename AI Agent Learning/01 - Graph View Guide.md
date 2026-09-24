# Graph View Guide

## Overview

Back to [[AI Agent Learning/00 - AI Agent Knowledge Map|00 - AI Agent Knowledge Map]].

## How It Works

### Folder Graph（資料夾圖譜）

Open Obsidian’s Graph view, expand Filters, and enter:

```text
path:"AI Agent Learning"
```

Turn tags and attachments off and enable “Existing files only” if unresolved links are visible. All new concept links use vault-relative paths.

### Cluster Colors（群組顏色）

In Groups, add the following search expressions and choose the suggested colors. These are optional manual settings; existing `.obsidian` files have not been edited.

| Cluster            | Search expression                                  | Suggested color |
| ------------------ | -------------------------------------------------- | --------------- |
| Fundamentals       | `path:"AI Agent Learning/01 - Fundamentals"`       | Blue            |
| RAG                | `path:"AI Agent Learning/02 - RAG"`                | Teal            |
| Agent Core         | `path:"AI Agent Learning/03 - Agent Core"`         | Orange          |
| Advanced Knowledge | `path:"AI Agent Learning/04 - Advanced Knowledge"` | Purple          |
| Agent Systems      | `path:"AI Agent Learning/05 - Agent Systems"`      | Pink            |
| Production         | `path:"AI Agent Learning/06 - Production"`         | Green           |

### Reduce the Central Hub Effect

The MOC intentionally links every topic. To emphasize concept clusters, use:

```text
path:"AI Agent Learning" -file:"00 - AI Agent Knowledge Map" -file:"Overview" -file:"01 - Graph View Guide"
```

Each concept also links its cluster hub and a limited set of related concepts. Cross-cluster edges show genuine dependencies; the graph is not a fully connected mesh. Force-layout positions vary and do not encode a fixed learning order. Use the MOC for sequence.

### Local Graph（局部圖譜）

1. Open a concept such as RAG, then use the command palette’s “Open local graph” command.
2. Begin with **depth 1**; use **depth 2** to explore neighbors of neighbors.
3. Display incoming and outgoing links where those options are available.
 **Obsidian automatically tracks backlinks（反向連結）:** a link from A to B creates an incoming link at B even if B does not explicitly link back. Selected important concept pairs here are explicitly linked both ways.

The note graph is ready from the Markdown links. Color/filter suggestions must be applied in the Obsidian UI if desired; they have not been applied to global settings.

## Reference

[Obsidian Graph view documentation](https://help.obsidian.md/plugins/graph).
