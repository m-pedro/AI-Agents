# AI-Agents
**Lablab AI Agents Hackathon, 13-15th Sept, 2024**

**Aim**: Build an agentic workflow for the software development life cycle (SDLC)

**Approach**
- Build a PoC in a sandbox (dev) environment
- Break the workflow into four separate tasks, and use one agent per task
- Use crew.ai for the agents and llama 3.1 or Gemma-2-7b for the llms
- Use colab notebooks for the coding
- Use other tools as necessary, e.g., agentops, autogen, mindsdb, upstage, langgraph, composio, etc.

**Agents**
- Requirements Agent: Understand requirements from a requirements doc
- Design Agent: Create a high level design doc
- Software Development Agent: Generate codebase to build a PoC (small project)
- Code Test Agent: Generate code tests

**Other ideas**: Agents for MLOps life cycle

**Workflow Steps**

a. Requirements Gathering
- Task: Extract key requirements from a document
- Goal: Create a concise summary of the system's required features
- Outcome: Defines the project scope (e.g., authentication, operations, task management, reporting)

b. High-Level System Design
- Task: Design the architecture of the system
- Diagrams Generated:
    -   Use Case Diagram
    -   Class Diagram
    -   Entity-Relationship Diagram (ERD)
    -   UI Design for Dashboard
- Outcome: A document detailing the architecture, components, and visual diagrams of the system.

c. Code Generation
- Task: Develop the Code for the system
- Goal: Create functional code that implements core features
- Outcome: Working code implementing authentication, database operations, and reporting

d. Code Testing
- Task: Run test cases to verify code functionality
- Goal: Ensure the system meets the requirements and works as expected
- Outcome: A detailed test report highlighting results and potential issues

**Project Page**
- https://lablab.ai/event/ai-agents-hack-with-lablab-and-mindsdb/the-synapses

**Colab Notebooks**
- https://colab.research.google.com/drive/1vsYzaJSXERfU-uEXuK2aD4HA9QbEIVUl?usp=sharing
- https://colab.research.google.com/drive/1j9OTh4ridFnq6XQReiYcItzG9yi3Ydwh?usp=sharing

**Future Work**
- Improvements in Design Diagrams: Explore more AI-driven tools for automated generation of detailed design diagrams
- Customization: Enable more advanced configurations for tasks such as adding new agents or expanding the functionality
- Agent Testing: Add test, debug and monitoring features to our platform, such as AgentOps.ai
- Deployment: Plan for deployment of the final PoC in a production environment

**References**
- Developing a Multi-Agent System with CrewAI, https://lablab.ai/t/crewai-multi-agent-system,
- Mastering AI Agent Management with AgentOps: An In-Depth Guide, https://lablab.ai/t/agentops-tutorial 
