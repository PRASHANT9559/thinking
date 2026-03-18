## Section 1: Core LLM Reasoning Patterns

| Thinking Pattern | Category | Where It Is Used | Short Explanation |
|------------------|----------|------------------|-------------------|
| **Chain of Thought (CoT)** | LLM reasoning | OpenAI o1/o3, DeepSeek-R1, GPT-4, Claude, math solvers | Breaks problems into sequential intermediate reasoning steps before reaching conclusions, mimicking human logical progression  |
| **Zero-Shot CoT** | LLM reasoning | General LLM applications | Uses trigger phrases like "Let's think step by step" to elicit reasoning without examples |
| **Few-Shot CoT** | LLM reasoning | Complex problem-solving systems | Provides exemplar reasoning chains in prompts to guide the model's step-by-step thinking |
| **Self-Consistency with CoT** | LLM reasoning | Math word problems, commonsense reasoning | Generates multiple reasoning paths independently and selects the most consistent answer via majority voting  |
| **Tree of Thought (ToT)** | LLM reasoning | Game playing, creative writing, strategic planning | Explores multiple reasoning branches in a tree structure, allowing backtracking and evaluation of different solution paths   |
| **Graph of Thought (GoT)** | LLM reasoning | Complex multi-hop reasoning, knowledge synthesis | Represents reasoning as a graph where thoughts can converge, diverge, and form loops, enabling more complex information aggregation |
| **Program of Thought (PoT)** | LLM reasoning | Mathematical computation, algorithmic tasks | Translates natural language problems into executable programs (Python/code) to perform precise calculations |
| **Chain of Verification (CoVe)** | LLM reasoning | Fact-checking systems, hallucination reduction | Drafts an answer, then plans verification questions, answers them independently, and revises the final output |
| **ReAct (Reasoning + Acting)** | LLM reasoning | AI agents, tool-using systems, web browsing | Interleaves reasoning traces with action execution in a loop: Thought → Action → Observation   |
| **Reflexion** | LLM reasoning | Programming agents, decision-making systems | Uses self-evaluation and linguistic feedback to iteratively improve performance through an Actor-Evaluator-Self-Reflection loop  |
| **Self-Ask** | LLM reasoning | Multi-hop question answering | Prompts the model to ask itself follow-up questions before answering the main query |
| **Step-Back Prompting** | LLM reasoning | Scientific reasoning, physics problems | First asks a general principle question, then applies it to the specific problem instance |
| **Analogical Reasoning** | LLM reasoning | Creative problem solving, cross-domain transfer | Solves new problems by drawing parallels to previously solved similar problems |
| **Compositional Reasoning** | LLM reasoning | Visual question answering, scene understanding | Breaks complex queries into sub-problems that can be solved independently and composed |
| **Structured CoT** | LLM reasoning | Formal logic, mathematical proofs | Enforces specific structured formats (equations, logical forms) in reasoning steps |
