## Scenario-Based-Reflection-Planner

**Architecture Name:** Scenario-Based Reflection Planner (SBRP)

**Hybrid Thinking Pattern:** Scenario-Based Reflection (SBR)

**Core Idea:** Reflects on performance across multiple future scenarios to identify robust strategies that work well despite uncertainty about which future unfolds.

**Agent Roles:**

| Agent | Responsibility |
|-------|---------------|
| Scenario Generator Agent | Creates diverse plausible futures |
| Strategy Proposer Agent | Generates candidate strategies |
| Scenario Tester Agent | Evaluates strategies in each scenario |
| Performance Reflector Agent | Analyzes why strategies succeed/fail |
| Robustness Identifier Agent | Finds strategies performing well across scenarios |
| Adaptation Marker Agent | Identifies when to switch strategies |
| Learning Integrator Agent | Extracts general principles from scenario analysis |

**System Components:**

| Component | Function |
|-----------|----------|
| Scenario Ensemble | Diverse future projections |
| Strategy Library | Alternative approaches to test |
| Performance Dashboard | Metrics per strategy-scenario pair |
| Robustness Metrics | Minimax, regret, satisficing measures |
| Adaptation Trigger Rules | When to abandon current strategy |
| Scenario Discovery Engine | Identifies critical uncertainties |
| Cross-Scenario Learning Module | Generalizes from specific cases |

**Workflow Pipeline:**

```
Strategic Planning Under Uncertainty
↓
Scenario Generator Agent creates futures
↓
Strategy Proposer Agent generates alternatives
↓
Scenario Tester Agent evaluates all combinations
↓
Performance Reflector Agent analyzes patterns
↓
Robustness Identifier Agent selects resilient strategies
↓
Adaptation Marker Agent defines switching rules
↓
Robust plan with scenario contingencies
```

**Example Use Case:** Climate adaptation planning where strategies must work across multiple warming scenarios, with triggers for strategy shifts as future clarifies.

**Strengths:**

- Future-proofing through diversity
- Explicit uncertainty handling
| Adaptive strategy design |
| Learning from hypothetical failures |

**Limitations:**
| Scenario generation bias |
| Computational explosion |
| False confidence from limited scenarios |
| Adaptation trigger design difficulty |

---
