## Recursive-Memory-Researcher

**Architecture Name:** Recursive Memory Researcher (RMR)

**Hybrid Thinking Pattern:** Recursive Memory Reasoning (RMR)

**Core Idea:** Model recursively calls itself to process external memory, with each call reading from and writing to a shared memory store, enabling deep analysis of long documents and continual learning.

**Agent Roles:**

| Agent | Responsibility |
|-------|---------------|
| Query Analyzer Agent | Determines if query requires recursive memory processing |
| Recursion Controller Agent | Manages depth and termination of recursive calls |
| Memory Reader Agent | Retrieves relevant segments from external memory |
| Processing Agent | Analyzes current memory chunk and produces intermediate results |
| Memory Writer Agent | Stores findings back to external memory for future reference |
| Integration Agent | Combines results from recursive branches |
| Termination Checker Agent | Decides when sufficient information has been processed |

**System Components:**

| Component | Function |
|-----------|----------|
| External Memory Store | Vector database or structured knowledge base |
| Recursion Stack Manager | Tracks call depth and context preservation |
| Chunking Engine | Divides large inputs into processable segments |
| Context Window Manager | Handles token limits across recursive calls |
| Result Cache | Avoids recomputation of similar subproblems |
| Call Graph Visualizer | Shows recursive processing structure |

**Workflow Pipeline:**

```
Long Document/Continual Input
↓
Query Analyzer Agent assesses scope
↓
If recursive needed:
  Recursion Controller Agent initializes
  ↓
  Memory Reader Agent fetches relevant chunk
  ↓
  Processing Agent analyzes chunk
  ↓
  Memory Writer Agent stores intermediate findings
  ↓
  If more chunks needed:
    Recursive call to self with updated context
    ↓
    [Repeat until coverage complete]
  ↓
  Integration Agent merges branch results
↓
Final synthesized answer with full context
```

**Example Use Case:** Legal document review system that recursively processes 10,000-page contract archives, building a comprehensive case history while maintaining cross-reference awareness.

**Strengths:**

- Unlimited effective context window
- Handles documents of arbitrary length
- Maintains coherence across chunks
- Enables true continual learning

**Limitations:**

- Recursion depth limits
- Integration complexity
- Latency from multiple calls
- Context preservation challenges

---
