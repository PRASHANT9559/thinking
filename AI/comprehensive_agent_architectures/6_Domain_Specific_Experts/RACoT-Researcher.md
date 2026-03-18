## RACoT-Researcher

**Architecture Name:** RACoT-Researcher (Retrieval-Augmented Chain-of-Thought Research System)

**Hybrid Thinking Pattern:** Retrieval-Augmented Chain-of-Thought (RACoT)

**Core Idea:** A research assistant that generates step-by-step reasoning where each step is grounded in retrieved external knowledge, ensuring factual accuracy throughout the reasoning chain.

**Agent Roles:**

| Agent | Responsibility |
|-------|---------------|
| Query Analyzer | Parses user query to identify knowledge needs and reasoning type |
| Retrieval Agent | Searches knowledge bases and web sources for relevant facts |
| Reasoning Agent | Generates step-by-step CoT with citations to retrieved facts |
| Verification Agent | Checks that each reasoning step is supported by evidence |
| Synthesis Agent | Combines verified steps into coherent final answer |

**System Components:**

| Component | Function |
|-----------|----------|
| Vector Knowledge Base | Stores embeddings of documents for semantic search |
| Web Search API | Retrieves real-time information from external sources |
| Citation Manager | Tracks sources and generates proper citations |
| Reasoning Engine | Implements chain-of-thought generation with retrieval hooks |
| Fact Checker | Validates claims against retrieved evidence |

**Workflow Pipeline:**

```
User Query
↓
Query Analyzer (identifies knowledge gaps)
↓
Parallel Retrieval (Vector DB + Web Search)
↓
Reasoning Agent (generates steps with citations)
↓
Verification Agent (checks step validity)
↓
Synthesis Agent (assembles final answer)
↓
Citation Formatter (adds references)
↓
Final Output
```

**Data Flow:** Query → Intent Classification → Knowledge Retrieval → Step Generation → Fact Verification → Answer Synthesis → Citation Integration → Output

**Example Use Case:** Medical diagnosis support system where each diagnostic step is grounded in medical literature and patient records.

**Strengths:** High factual accuracy, traceable reasoning, reduces hallucination, transparent decision-making.

**Limitations:** Latency from retrieval steps, dependency on knowledge base quality, potential for retrieval of outdated information.

---
