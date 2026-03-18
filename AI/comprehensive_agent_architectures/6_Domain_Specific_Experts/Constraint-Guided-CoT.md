## Constraint-Guided-CoT

**Architecture Name:** CGC-Solver

**Hybrid Thinking Pattern:** Constraint-Guided CoT (CGCoT)

**Core Idea:** Reasoning steps must satisfy symbolic constraints, pruning invalid paths early in generation.

**Agent Roles:**

| Agent | Responsibility |
|-------|---------------|
| Constraint Parser | Extracts constraints from problem statement |
| Feasibility Checker | Validates if partial solutions satisfy constraints |
| Step Generator | Proposes reasoning steps within constraints |
| Backjump Agent | Returns to last feasible point when stuck |
| Optimization Agent | Finds best solution among feasible options |
| Explanation Agent | Explains why constraints eliminate alternatives |

**System Components:**

| Component | Function |
|-----------|----------|
| Constraint Solver | CSP/SAT solver for feasibility checking |
| Constraint Propagation | Reduces search space through inference |
| Domain Store | Tracks valid values for variables |
| Search Tree Manager | Maintains partial assignments and backtracking |
| Optimization Engine | Finds optimal solutions within constraints |

**Workflow Pipeline:**

```
Constrained Problem
↓
Constraint Parser (formalizes constraints)
↓
Step Generator (proposes moves)
↓
Feasibility Checker (validates against constraints)
↓
[If valid] Continue
[If invalid] Backjump Agent
↓
Constraint Propagation (prunes search space)
↓
[Iterate until solution found]
↓
Optimization Agent (improves solution)
↓
Constrained Solution with Explanation
```

**Data Flow:** Problem → Constraint Extraction → Step Proposal → Validation → Propagation → Backtracking → Optimization → Solution

**Example Use Case:** Scheduling system for hospital shifts respecting labor laws, staff preferences, and coverage requirements.

**Strengths:** Guarantees constraint satisfaction, efficient pruning, explains infeasibility, finds optimal solutions.

**Limitations:** Constraint formulation is hard, NP-hard problems may be slow, over-constrained systems have no solution.

---
