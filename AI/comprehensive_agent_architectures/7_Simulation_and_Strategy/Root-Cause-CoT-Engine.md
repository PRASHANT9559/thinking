## Root-Cause-CoT-Engine

**Architecture Name:** Root Cause CoT Engine (RCCE)

**Hybrid Thinking Pattern:** Root Cause CoT (RCCoT)

**Core Idea:** Step-by-step reasoning traces problems to root causes using systematic analysis techniques (5 Whys, fault trees) with verifiable causal chains.

**Agent Roles:**

| Agent | Responsibility |
|-------|---------------|
| Problem Characterizer Agent | Defines symptoms and boundaries |
| Surface Cause Identifier Agent | Identifies immediate triggers |
| Deep Cause Analyzer Agent | Iteratively asks "why" to deepen analysis |
| Evidence Gatherer Agent | Collects data on each causal level |
| Verification Agent | Tests causal hypotheses |
| Categorization Agent | Organizes by cause type (human, machine, etc.) |
| Solution Generator Agent | Proposes interventions at root level |
| Prevention Designer Agent | Creates systemic fixes |

**System Components:**

| Component | Function |
|-----------|----------|
| Causal Chain Tracker | Why-chain documentation |
| Fault Tree Builder | Logical combination of causes |
| Evidence Database | Supporting data per causal link |
| Category Taxonomy | Standard cause classifications |
| Interventions Library | Corrective actions by cause type |
| Prevention Pattern Database | Systemic solutions |
| RCA Report Generator | Structured documentation |

**Workflow Pipeline:**

```
Problem/Observation
↓
Problem Characterizer Agent scopes issue
↓
Surface Cause Identifier Agent finds immediate trigger
↓
Deep Cause Analyzer Agent iterates "why":
  Why 1: Immediate cause
  Why 2: Contributing factor
  Why 3: System condition
  Why 4: Organizational factor
  Why 5: Root cause
↓
Verification Agent tests each link
↓
Categorization Agent organizes findings
↓
Solution Generator Agent proposes fixes
↓
Prevention Designer Agent creates systemic improvements
```

**Example Use Case:** Manufacturing quality control analyzing production defects through systematic root cause analysis to prevent recurrence.

**Strengths:**

- Systematic depth in analysis
- Evidence-based causal chains
| Prevents symptom-level fixes |
| Organizational learning capture |

**Limitations:**
| Stopping rule ambiguity (when is it "root"?) |
| Multiple interacting causes |
| Organizational resistance to findings |
| Evidence availability constraints |

---
