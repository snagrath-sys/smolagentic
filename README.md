# SmolAgents Playground: Exploring CodeAgents, Actions, and Multi-Agent Systems

This project is a playground to explore the capabilities of [`smolAgents`](https://github.com/smol-ai/smol-developer), a lightweight framework for building intelligent agents that reason and act using code.

We deep-dive into:

- CodeAgents for task execution via Python code  
- Writing actions as code snippets or JSON blobs  
- Retrieval Agents for contextual information lookup  
- Multi-Agent Systems for collaboration between specialized agents  

---

## Features

### 1. CodeAgent Basics

- Create agents that interpret and execute Python code as actions
- Use custom tools (decorated functions) that are exposed to the agent
- Example use case: a digital butler (`Alfred`) who plans a party and uses tools to create menus, schedule tasks, etc.

### 2. Actions as Code and JSON

- Agents can represent decisions in:
  - Executable code snippets
  - Structured JSON blobs
- This flexibility allows switching between symbolic and executable reasoning.

### 3. Retrieval Agents

- Agents that query external sources or vector stores for context
- Can answer questions using knowledge bases or search
- Example use case: answering questions from a company knowledge base

### 4. Multi-Agent Systems

- Orchestrate multiple agents with specialized roles:
  - Planner agent
  - Execution agent
  - Verifier agent
- Agents communicate and delegate tasks to each other
- Example use case: an AI assistant team for event planning or software development

---
