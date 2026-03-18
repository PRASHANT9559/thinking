## Process-Supervised-Reflection

**Architecture Name:** PSR-Verifier

**Hybrid Thinking Pattern:** Process-Supervised Reflection (PSR)

**Core Idea:** Reflects on each reasoning step with process-based rewards, learning to recognize valid intermediate steps.

**Agent Roles:**

| Agent | Responsibility |
|-------|---------------|
| Step Generator | Proposes next reasoning step |
| Step Evaluator | Assesses validity of proposed step |
| Process Critic | Provides detailed feedback on step quality |
| Step Selector | Chooses best step from candidates |
| Learning Integrator | Updates step generation from feedback |
| Final Verifier | Checks complete reasoning chain |

**System Components:**

| Component | Function |
|-----------|----------|
| Step Reward Model | Scores individual reasoning steps |
| Process Validator | Checks step logic independent of outcome |
| Candidate Generator | Produces multiple step options |
| Feedback Database | Stores step-level feedback for training |
| Curriculum Manager | Increases problem difficulty gradually |

**Workflow Pipeline:**

```
Problem
↓
Step Generator (proposes steps)
↓
Step Evaluator (assesses each)
↓
Process Critic (detailed feedback)
↓
Step Selector (chooses best)
↓
[Iterate for next step]
↓
Final Verifier (checks chain)
↓
Output with step-by-step validation
```

**Data Flow:** Problem → Step Proposal → Multi-Candidate Generation → Step Scoring → Selection → Iteration → Chain Validation → Output

**Example Use Case:** Mathematical proof assistant where each lemma is validated before proceeding to theorems.

**Strengths:** High reasoning quality, credit assignment to steps, learns from process not just outcome, interpretable errors.

**Limitations:** Expensive step-level supervision, slower than end-to-end, requires reward model training.

---
