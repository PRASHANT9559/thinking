## Hierarchical-Reflective-Team

**Architecture Name:** HRT-Manager

**Hybrid Thinking Pattern:** Hierarchical Reflective Teams (HRT)

**Core Idea:** Manager reflects on team performance while workers reflect on task execution, enabling double-loop learning.

**Agent Roles:**

| Agent | Responsibility |
|-------|---------------|
| Executive Manager | Sets goals and reflects on team effectiveness |
| Team Lead | Coordinates workers and reflects on coordination |
| Specialist Worker A | Executes tasks and reflects on own performance |
| Specialist Worker B | Executes tasks and reflects on own performance |
| Meta-Learning Agent | Identifies patterns across reflection sessions |
| Improvement Planner | Generates organizational improvements |

**System Components:**

| Component | Function |
|-----------|----------|
| Performance Dashboard | Tracks metrics at individual and team levels |
| Reflection Log | Stores structured reflections from all agents |
| Pattern Miner | Finds recurring issues across reflections |
| Knowledge Base | Stores best practices learned from reflections |
| Improvement Tracker | Monitors implementation of changes |

**Workflow Pipeline:**

```
Task Assignment
↓
Team Lead (coordinates)
↓
Specialist Workers (execute + self-reflect)
↓
Team Lead (reflects on coordination)
↓
Executive Manager (reflects on team performance)
↓
Meta-Learning Agent (cross-cutting patterns)
↓
Improvement Planner (organizational changes)
↓
Knowledge Base Update
↓
[Next task uses improved organization]
```

**Data Flow:** Task → Execution + Individual Reflection → Team Reflection → Management Reflection → Pattern Analysis → Organizational Learning → Implementation

**Example Use Case:** Enterprise software development team where agents learn to improve collaboration patterns over projects.

**Strengths:** Multi-level learning, organizational improvement, not just individual optimization, scalable to large teams.

**Limitations:** Reflection overhead at multiple levels, coordination complexity, potential for conflicting improvements.

---
