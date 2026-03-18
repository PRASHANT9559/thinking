## Instruction-Guided-Reflective-Assistant

**Architecture Name:** Instruction-Guided Reflective Assistant (IGRA)

**Hybrid Thinking Pattern:** Instruction-Guided Reflection (IGR)

**Core Idea:** Reflection processes are guided by natural language instructions, enabling user-controlled reasoning where humans specify how the AI should critique and improve its outputs.

**Agent Roles:**

| Agent | Responsibility |
|-------|---------------|
| Instruction Parser Agent | Extracts reflection guidelines from user instructions |
| Initial Generator Agent | Produces first-draft response |
| Guided Critic Agent | Critiques draft according to specified criteria |
| Revision Agent | Implements changes addressing critiques |
| Compliance Checker Agent | Verifies revisions follow instructions |
| Explanation Agent | Articulates what was changed and why |
| Instruction Learning Agent | Generalizes from instruction examples |

**System Components:**

| Component | Function |
|-----------|----------|
| Instruction Schema | Structured representation of reflection guidance |
| Critique Template Engine | Generates critique prompts from instructions |
| Revision Diff Tracker | Highlights changes between versions |
| Compliance Scorer | Measures alignment with instructions |
| Instruction History | Learns user preferences over time |
| Interactive Clarifier | Asks questions when instructions are ambiguous |

**Workflow Pipeline:**

```
User Query + Reflection Instructions (e.g., "Check for bias")
↓
Instruction Parser Agent extracts criteria
↓
Initial Generator Agent creates draft
↓
Guided Critic Agent evaluates per instructions
↓
Revision Agent implements improvements
↓
Compliance Checker Agent verifies instruction satisfaction
↓
If non-compliant: Additional revision rounds
↓
Final output with reflection log showing changes
```

**Example Use Case:** Writing assistant where users specify "Ensure inclusive language" and the system explicitly checks and revises drafts against this criterion.

**Strengths:**

- User-controlled reasoning process
- Transparent reflection criteria
- Adaptable to domain needs
- Educational (shows improvement steps)

**Limitations:**

- Instruction interpretation errors
- Over-fitting to explicit criteria
- Missing implicit requirements
- Instruction complexity limits

---
