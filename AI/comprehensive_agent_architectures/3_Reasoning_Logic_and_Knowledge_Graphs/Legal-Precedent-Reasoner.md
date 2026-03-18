## Legal-Precedent-Reasoner

**Architecture Name:** Legal Precedent Reasoner (LPR)

**Hybrid Thinking Pattern:** Legal CoT with Precedent (LCoTP)

**Core Idea:** Step-by-step legal reasoning retrieves and applies precedents at each inference step, ensuring arguments are grounded in established case law.

**Agent Roles:**

| Agent | Responsibility |
|-------|---------------|
| Case Facts Parser Agent | Extracts relevant facts from current situation |
| Issue Spotter Agent | Identifies legal questions raised |
| Precedent Retriever Agent | Searches case law for relevant precedents |
| Analogical Reasoner Agent | Maps precedents to current facts |
| Distinguishing Agent | Identifies differences from unfavorable precedents |
| Rule Synthesizer Agent | Combines precedents into applicable legal rules |
| Prediction Agent | Forecasts likely outcomes based on precedent strength |
| Citation Formatter Agent | Properly cites authorities |

**System Components:**

| Component | Function |
|-----------|----------|
| Case Law Database | Structured legal opinions with embeddings |
| Legal Ontology | Concepts, relationships, legal tests |
| Similarity Scoring | Case-to-case relevance metrics |
| Shepardizing Engine | Checks if precedents are still good law |
| Argument Template Library | Standard legal argument structures |
| Court Level Hierarchy | Weight by jurisdiction and court authority |
| Contradiction Detector | Identifies conflicting precedents |

**Workflow Pipeline:**

```
Legal Question/Case
↓
Case Facts Parser Agent structures input
↓
Issue Spotter Agent identifies legal questions
↓
For each legal issue:
  Precedent Retriever Agent finds relevant cases
  ↓
  Analogical Reasoner Agent maps similarities
  ↓
  Distinguishing Agent addresses differences
  ↓
  Rule Synthesizer Agent extracts governing law
↓
Prediction Agent forecasts outcome
↓
Citation Formatter Agent produces legal memo
```

**Example Use Case:** Legal research assistant helping attorneys find supporting precedents and predict case outcomes based on historical patterns.

**Strengths:**

- Grounded in authoritative sources
- Explainable legal reasoning
- Handles analogical legal argument
- Citation compliance

**Limitations:**

- Precedent database coverage gaps
- Analogical reasoning subjectivity
| Jurisdictional complexity |
| Rapid law change handling |

---
