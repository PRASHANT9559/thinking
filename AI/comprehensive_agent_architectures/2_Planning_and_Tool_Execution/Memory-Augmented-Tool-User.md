## Memory-Augmented-Tool-User

**Architecture Name:** MATU-Assistant

**Hybrid Thinking Pattern:** Memory-Augmented Tool Use (MATU)

**Core Idea:** Remembers successful tool combinations and failures, using episodic memory to guide future tool selection.

**Agent Roles:**

| Agent | Responsibility |
|-------|---------------|
| Task Analyzer | Understands current task requirements |
| Memory Retriever | Recalls similar past tasks and tool usage |
| Tool Selector | Chooses tools based on memory and current context |
| Execution Agent | Uses selected tools |
| Outcome Recorder | Stores results in episodic memory |
| Pattern Miner | Identifies successful tool combinations |
| Failure Analyzer | Learns from tool failures |

**System Components:**

| Component | Function |
|-----------|----------|
| Episodic Memory | Stores past task-tool-outcome triples |
| Semantic Memory | General knowledge about tool capabilities |
| Tool Success Predictor | Predicts tool effectiveness for new tasks |
| Combination Learner | Discovers effective tool sequences |
| Failure Case Base | Stores and categorizes failure modes |

**Workflow Pipeline:**

```
New Task
↓
Task Analyzer
↓
Memory Retriever (similar past tasks)
↓
Tool Selector (informed by memory)
↓
Execution Agent (uses tools)
↓
Outcome Recorder (stores result)
↓
Pattern Miner (updates success patterns)
↓
[Future tasks benefit from memory]
```

**Data Flow:** Task → Similarity Search → Tool Recommendation → Execution → Outcome Storage → Pattern Learning → Memory Enrichment

**Example Use Case:** Data science assistant that remembers which analysis pipelines worked for similar datasets.

**Strengths:** Personalizes to user patterns, avoids repeated failures, efficient tool selection, continuous improvement.

**Limitations:** Memory can become stale, overfitting to past patterns, storage costs for large histories.

---
