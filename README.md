# AI-Agents
Lablab AI Agents hackathon

**Aim**
Build an agentic workflow for the software development life cycle (SDLC)

**Approach**
- Break the workflow into four separate tasks, and use one agent per task
- Use crew.ai for the agents and llama 3.1 or Gemma-2-7b for the llms
- Use colab notebooks for the coding
- Use other tools as necessary, e.g., agentops, autogen, mindsdb, upstage, composio, etc.

**Tasks**
Build a PoC in a sandbox (dev) environment

**Agents**
- Requirements Agent: Understand requirements from requirements doc
- Design Agent: Create high level design doc
- Software Development Agent: Generate codebase to build PoC (small project)
- Code Test Agent: Generate code tests

**Other ideas**
- Agents for MLOps life cycle

**Workflow Steps**

a. Requirements Gathering
Task: Extract key requirements from a document.
Goal: Create a concise summary of the CRM system's required features.
Outcome: Defines the project scope (authentication, CRUD operations, task management, reporting).

b. High-Level System Design
Task: Design the architecture of the CRM system.
Diagrams Generated:
Use Case Diagram
Class Diagram
Entity-Relationship Diagram (ERD)
UI Design for Dashboard
Outcome: A document detailing the architecture, components, and visual diagrams of the system.

c. Code Generation
Task: Develop the Code for the system.
Goal: Create functional code that implements core features.
Outcome: Working code implementing authentication, database operations, and reporting.

d. Code Testing
Task: Run test cases to verify code functionality.
Goal: Ensure the system meets the requirements and works as expected.
Outcome: A detailed test report highlighting results and potential issues.

**Workspaces**
- Our Group: https://lablab.ai/event/ai-agents-hack-with-lablab-and-mindsdb/the-synapses
- Discord: https://discord.com/channels/@me/1284526772720898198

**Colab Notebooks**
- https://colab.research.google.com/drive/1vsYzaJSXERfU-uEXuK2aD4HA9QbEIVUl?usp=sharing
- https://colab.research.google.com/drive/1j9OTh4ridFnq6XQReiYcItzG9yi3Ydwh?usp=sharing

**Future Work**
- Improvements in Design Diagrams: Explore more AI-driven tools for automated generation of detailed design diagrams.
- Customization: Enable more advanced configurations for tasks such as adding new agents or expanding CRM functionality.
- Agent Testing: Add test, debug and monitoring features to our platform, such as AgentOps.ai
- Deployment: Plan for deployment of the final CRM system in a production environment.

**References**
- Developing a Multi-Agent System with CrewAI, https://lablab.ai/t/crewai-multi-agent-system,
- Mastering AI Agent Management with AgentOps: An In-Depth Guide, https://lablab.ai/t/agentops-tutorial 
