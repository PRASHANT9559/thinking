## Section 2: AI Agent Reasoning Patterns

| Thinking Pattern | Category | Where It Is Used | Short Explanation |
|------------------|----------|------------------|-------------------|
| **Plan-and-Execute** | AI agents | Enterprise automation, task planning systems | Separates planning from execution: first generates complete plan, then executes all steps  |
| **ReWOO (Reasoning Without Observation)** | AI agents | Cost-sensitive agent systems | Generates plan with anticipated evidence, executes all tool calls at once, then synthesizes results  |
| **Reflection Pattern** | AI agents | Self-improving agents, code review systems | Agents critique their own outputs and iterate to improve quality before final delivery  |
| **Tool Use Pattern** | AI agents | RAG systems, API agents, calculator agents | Agents select and invoke external tools (search, code execution, databases) to augment capabilities  |
| **Multi-Agent Orchestration** | AI agents | CrewAI, AutoGen, enterprise workflows | Coordinator agent decomposes tasks and delegates to specialized worker agents with different capabilities   |
| **Hierarchical Agent Pattern** | AI agents | Enterprise case management, complex workflows | Top-down control where a managing agent controls case lifecycle and coordinates worker agents-as-a-service  |
| **Peer-to-Peer Collaboration** | AI agents | Distributed problem solving, debate systems | Agents collaborate dynamically without central coordinator, engaging in debate or sequential assembly line processing  |
| **Concurrent/Fan-out Pattern** | AI agents | Azure AI, parallel analysis systems | Multiple agents process the same task simultaneously from different perspectives, results aggregated via voting or synthesis  |
| **Human-in-the-Loop** | AI agents | Critical decision systems, healthcare, finance | Agent escalates to human approval at key decision points or when confidence is low  |
| **Agentic RAG** | AI agents | Advanced retrieval systems | Combines autonomous agent reasoning with retrieval, allowing agents to decide what to retrieve and when |
| **Dynamic Planning** | AI agents | Adaptive robotics, changing environments | Continuously replans based on intermediate observations and changing environmental state |
| **Subgoal Decomposition** | AI agents | Long-horizon tasks, project management | Breaks high-level goals into hierarchical subgoals with dependencies and sequencing |
| **State Machine Agents** | AI agents | Conversational AI, process automation | Agents transition between discrete states based on inputs, with reasoning specific to each state |
| **Event-Driven Agents** | AI agents | Real-time monitoring, trading systems | Agents react to external events and triggers, reasoning about event significance and required actions |
