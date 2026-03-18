## Active-Retrieval-Planner

**Architecture Name:** ARP-Researcher

**Hybrid Thinking Pattern:** Active Retrieval Planning (ARP)

**Core Idea:** Strategically plans what information to retrieve based on expected information gain and reasoning needs.

**Agent Roles:**

| Agent | Responsibility |
|-------|---------------|
| Information Need Analyzer | Identifies knowledge gaps |
| Query Optimizer | Formulates queries for maximum information gain |
| Retrieval Executor | Fetches information from sources |
| Information Integrator | Incorporates new info into reasoning |
| Value of Information Calculator | Prioritizes which gaps to fill first |
| Stopping Condition Agent | Decides when enough information is gathered |

**System Components:**

| Component | Function |
|-----------|----------|
| Belief State Tracker | Current knowledge and uncertainty |
| Information Gain Model | Predicts value of potential queries |
| Source Quality Estimator | Reliability of different information sources |
| Query Cost Model | Time/compute cost of retrieval |
| Budget Manager | Allocates retrieval resources optimally |

**Workflow Pipeline:**

```
Research Question
↓
Information Need Analyzer (identifies gaps)
↓
Value of Information Calculator (prioritizes)
↓
Query Optimizer (forms best queries)
↓
Retrieval Executor (fetches data)
↓
Information Integrator (updates beliefs)
↓
Stopping Condition Agent (checks sufficiency)
↓
[If more needed] Iterate
↓
Informed Answer
```

**Data Flow:** Question → Gap Analysis → Prioritization → Query Optimization → Retrieval → Integration → Sufficiency Check → Iteration/Output

**Example Use Case:** Research assistant efficiently gathering information for literature reviews without exhaustive search.

**Strengths:** Efficient information gathering, cost-effective, targeted learning, avoids information overload.

**Limitations:** Information gain estimation is imperfect, may miss crucial but non-obvious sources, exploration-exploitation trade-off.

---
