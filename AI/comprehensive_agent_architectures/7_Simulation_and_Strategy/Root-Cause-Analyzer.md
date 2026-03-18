## Root-Cause-Analyzer

**Architecture Name:** RCA-Engine

**Hybrid Thinking Pattern:** Root Cause CoT (RCCoT)

**Core Idea:** Step-by-step reasoning traces problems to root causes using systematic analysis techniques.

**Agent Roles:**

| Agent | Responsibility |
|-------|---------------|
| Symptom Collector | Gathers problem manifestations |
| Cause Hypothesizer | Generates potential root causes |
| Evidence Gatherer | Collects data to test hypotheses |
| Cause Tester | Validates causal relationships |
| Chain Builder | Constructs causal chains |
| Solution Generator | Proposes fixes for root causes |
| Prevention Planner | Designs measures to prevent recurrence |

**System Components:**

| Component | Function |
|-----------|----------|
| 5 Whys Engine | Iterative why-asking to depth |
| Fishbone Diagram Generator | Categorizes causes by type |
| Causal Network Builder | Links causes to effects |
| Evidence Database | Stores facts supporting/refuting causes |
| Solution Library | Known fixes for common root causes |

**Workflow Pipeline:**

```
Problem Report
↓
Symptom Collector (characterizes issue)
↓
Cause Hypothesizer (generates candidates)
↓
Evidence Gatherer (collects data)
↓
Cause Tester (validates hypotheses)
↓
Chain Builder (traces to root)
↓
[Iterate until root found]
↓
Solution Generator (proposes fix)
↓
Prevention Planner (prevents recurrence)
↓
Root Cause Report
```

**Data Flow:** Problem → Characterization → Hypothesis Generation → Evidence Collection → Validation → Root Identification → Solution → Prevention

**Example Use Case:** Manufacturing quality control system identifying why defects occur in production lines.

**Strengths:** Systematic analysis, prevents symptom-fixing, addresses underlying issues, prevents recurrence.

**Limitations:** Multiple root causes possible, evidence may be incomplete, organizational factors hard to trace.

---
