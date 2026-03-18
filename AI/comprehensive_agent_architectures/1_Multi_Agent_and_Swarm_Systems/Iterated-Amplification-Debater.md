## Iterated-Amplification-Debater

**Architecture Name:** Iterated Amplification Debater (IAD)

**Hybrid Thinking Pattern:** Iterated Amplification with Debate (IAD)

**Core Idea:** Breaks complex problems into simpler subproblems that can be supervised more reliably, with debate phases ensuring distilled knowledge maintains alignment through recursive improvement.

**Agent Roles:**

| Agent | Responsibility |
|-------|---------------|
| Problem Decomposer Agent | Breaks complex queries into simpler subproblems |
| Amplification Agent | Solves subproblems using available resources |
| Debate Initiator Agent | Sets up adversarial examination of solutions |
| Critic Agent | Challenges solution correctness and alignment |
| Defender Agent | Justifies solution against critiques |
| Distillation Agent | Compresses verified knowledge for future use |
| Meta-Supervisor Agent | Evaluates whether amplification improved reliability |
| Recursion Manager Agent | Controls depth of amplification |

**System Components:**

| Component | Function |
|-----------|----------|
| Subproblem Generator | Creates tractable subtasks from complex goals |
| Debate Arena | Structured argumentation environment |
| Solution Verifier | Checks correctness of subproblem solutions |
| Knowledge Distillation Engine | Compresses while preserving reliability |
| Alignment Checker | Ensures distilled knowledge maintains values |
| Amplification Graph | Tracks problem-solution hierarchy |
| Trust Calibration Module | Estimates confidence at each amplification level |

**Workflow Pipeline:**

```
Complex Problem Beyond Direct Solution
↓
Problem Decomposer Agent creates subproblems
↓
For each subproblem:
  Amplification Agent solves with available help
  ↓
  Debate Initiator Agent sets up examination
  ↓
  Critic Agent vs. Defender Agent debate
  ↓
  Solution verified or rejected
↓
Distillation Agent compresses verified solutions
↓
Meta-Supervisor Agent checks if result is trustworthy
↓
If not: Recursion Manager increases amplification depth
↓
Final answer with reliability certification
```

**Example Use Case:** AI safety research where complex ethical scenarios are broken down, debated at each level, and distilled into reliable decision policies.

**Strengths:**

- Scalable oversight
- Maintains alignment through recursion
- Debate ensures thorough examination
- Knowledge compression preserves quality

**Limitations:**

- Exponential decomposition overhead
- Debate quality dependence
- Distillation fidelity risks
- Deep recursion instability

---
