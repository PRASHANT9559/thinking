## Feedback-Loop-Planner

**Architecture Name:** FLP-Controller

**Hybrid Thinking Pattern:** Feedback Loop Planning (FLP)

**Core Idea:** Plans explicitly account for feedback effects, with dynamic adjustment as loops activate.

**Agent Roles:**

| Agent | Responsibility |
|-------|---------------|
| System Modeler | Identifies feedback loops in the system |
| Loop Analyzer | Classifies loops as reinforcing or balancing |
| Intervention Designer | Plans considering feedback effects |
| Monitor Agent | Tracks loop activation in real-time |
| Adaptation Agent | Adjusts plan as feedback manifests |
| Stability Checker | Ensures plans don't cause instability |

**System Components:**

| Component | Function |
|-----------|----------|
| Causal Loop Diagram | Visual representation of feedback structures |
| System Dynamics Engine | Simulates feedback effects over time |
| Loop Detection Algorithm | Identifies feedback from system structure |
| Stability Analysis | Checks for runaway positive feedback |
| Adaptive Controller | Adjusts interventions based on observed feedback |

**Workflow Pipeline:**

```
System Description
↓
System Modeler (maps feedback loops)
↓
Loop Analyzer (classifies effects)
↓
Intervention Designer (plans with feedback)
↓
Monitor Agent (watches for activation)
↓
[When feedback detected]
↓
Adaptation Agent (adjusts plan)
↓
Stability Check
↓
Robust Intervention Plan
```

**Data Flow:** System → Feedback Identification → Classification → Feedback-Aware Planning → Monitoring → Adaptation → Stability Maintenance

**Example Use Case:** Economic policy planning accounting for multiplier effects and market reactions.

**Strengths:** Avoids unintended consequences, handles complex dynamics, prevents instability, robust plans.

**Limitations:** Feedback identification is hard, unmodeled feedback loops cause failures, complex interactions.

---
