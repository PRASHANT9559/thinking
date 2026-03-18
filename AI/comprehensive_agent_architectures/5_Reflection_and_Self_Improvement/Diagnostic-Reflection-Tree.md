## Diagnostic-Reflection-Tree

**Architecture Name:** Diagnostic Reflection Tree (DRT)

**Hybrid Thinking Pattern:** Diagnostic Reflection Tree (DRT)

**Core Idea:** Explores diagnostic hypotheses as a tree structure, reflecting on evidence fit for each branch to systematically narrow down root causes.

**Agent Roles:**

| Agent | Responsibility |
|-------|---------------|
| Symptom Collector Agent | Gathers all observable symptoms and test results |
| Hypothesis Generator Agent | Produces candidate diagnoses at each tree node |
| Evidence Assessment Agent | Evaluates how well evidence supports each hypothesis |
| Reflection Agent | Critiques the diagnostic reasoning process |
| Tree Pruner Agent | Removes low-probability branches |
| Test Recommender Agent | Suggests next diagnostic step |
| Convergence Agent | Determines when diagnosis is sufficiently certain |

**System Components:**

| Component | Function |
|-----------|----------|
| Diagnostic Tree Structure | Hierarchical hypothesis space |
| Evidence Likelihood Model | P(symptom | diagnosis) distributions |
| Prior Probability Database | Base rates of conditions |
| Test Cost-Benefit Model | Value of information calculations |
| Reflection Log | Records reasoning critiques |
| Differential Diagnosis Ranker | Posterior probability calculator |
| Explanation Generator | Narrative of diagnostic reasoning |

**Workflow Pipeline:**

```
Patient/Problem Presentation
↓
Symptom Collector Agent gathers data
↓
Hypothesis Generator Agent creates root candidates
↓
For each branch:
  Evidence Assessment Agent calculates fit
  ↓
  Reflection Agent critiques reasoning
  ↓
  Tree Pruner Agent removes weak candidates
  ↓
  If uncertain:
    Test Recommender Agent suggests next investigation
    ↓
    New evidence → Updated assessments
↓
Convergence Agent selects most likely diagnosis
```

**Example Use Case:** Medical diagnosis system for complex cases with multiple overlapping symptoms, systematically exploring and eliminating possibilities.

**Strengths:**

- Systematic hypothesis exploration
- Evidence-based pruning
- Self-critique of diagnostic reasoning
- Optimal test sequencing

**Limitations:**

- Prior probability specification difficulty
- Rare disease blind spots
| Test result timing delays |
| Multimorbidity complexity |

---
