## Recursive-Subgoal-Planner

**Architecture Name:** RSP-Hierarchy

**Hybrid Thinking Pattern:** Recursive Subgoal Planning (RSP)

**Core Idea:** Breaks goals into subgoals that can spawn their own planning agents, creating adaptive hierarchical execution.

**Agent Roles:**

| Agent | Responsibility |
|-------|---------------|
| Root Planner | Handles top-level goal decomposition |
| Subgoal Agent | Manages specific subgoal (can spawn children) |
| Dependency Manager | Tracks dependencies between subgoals |
| Resource Coordinator | Allocates compute across hierarchy |
| Integration Agent | Merges subgoal results into coherent whole |
| Termination Checker | Detects when all subgoals are satisfied |

**System Components:**

| Component | Function |
|-----------|----------|
| Goal Hierarchy Tree | Dynamic tree of goals and subgoals |
| Dependency Graph | Tracks which subgoals block others |
| Resource Scheduler | Allocates agents to subgoals |
| Result Cache | Stores completed subgoal solutions |
| Recursion Controller | Limits recursion depth to prevent infinite loops |

**Workflow Pipeline:**

```
Top-Level Goal
↓
Root Planner (decomposes)
↓
Subgoal Agents spawned (parallel)
↓
[If subgoal complex] Recursive decomposition
↓
Dependency Manager (coordinates)
↓
Subgoal Execution
↓
Integration Agent (merges results)
↓
Termination Check
↓
Final Solution
```

**Data Flow:** Goal → Decomposition → Parallel Subgoal Processing → [Recursive Expansion] → Dependency Resolution → Result Aggregation → Validation

**Example Use Case:** Automated software engineering breaking down feature implementation into recursive coding tasks.

**Strengths:** Handles arbitrary complexity, parallel execution, natural problem decomposition, scalable.

**Limitations:** Overhead from coordination, dependency management complexity, potential for excessive recursion.

---
