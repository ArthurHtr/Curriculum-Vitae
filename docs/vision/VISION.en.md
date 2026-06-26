# Build the Team, Not Just Choose the Model

A vision by Arthur Hottier, creator of OpenCode Team Studio.

[Lire la version française →](VISION.fr.md)

---

I start from a simple conviction: the future of artificial intelligence does not rely solely on building increasingly powerful models. It also depends on our ability to organize those models, assign them precise roles, and give them the right tools to work together.

An agentic AI system can be understood as a team.

This team may have a manager responsible for understanding a broader objective, breaking it down, and distributing the work. It may include specialists in software development, research, architecture, security, testing, or documentation. Each agent may use a different model, receive its own instructions, operate under specific permissions, and access only the tools required for its mission.

As in a human team, collective performance does not depend solely on the individual intelligence of its members. It also depends on the quality of their organization.

An excellent specialist, working in isolation or under poor direction, can produce mediocre results. Conversely, several agents that are properly specialized, equipped, and coordinated can address problems that a single model would struggle to solve reliably.

## The next frontier of agentic AI

Part of the progress will naturally continue to come from the models themselves. Companies such as OpenAI, Anthropic, Google, and Mistral AI, together with the open-source community, will continue developing models that are more capable, faster, and more efficient.

But a second frontier is becoming equally important: orchestration.

- Which agent should receive a given task?
- Which model should it use?
- Which tools should it be allowed to access?
- Which actions can it perform autonomously?
- Which actions require human approval?
- Which specialists can it call upon?
- Which instructions, knowledge, and methods should it apply?

These questions are no longer concerned only with the quality of an individual model. They concern the complete architecture of the system surrounding it.

For an individual, this organization may make it possible to accomplish work that would previously have required an entire team. For a company, it may provide a way to introduce agents into an existing infrastructure while respecting its processes, security rules, working methods, and business constraints.

The challenge is therefore no longer simply to use artificial intelligence. We must learn how to build, understand, control, and evolve a genuine team of agents.

## Open source has the components, but not yet the workshop

The open-source ecosystem already provides many of the essential building blocks.

There are open models, agent development tools, MCP servers capable of connecting agents to external services, and libraries of reusable skills and instructions. Tools such as OpenCode already make it possible to create specialized agents, define their permissions, assign models to them, and provide them with additional tools.

OpenCode is a particularly interesting foundation: it is open, extensible, and compatible with many model providers. It offers primary agents and subagents while allowing users to build their own configurations.

However, as this configuration grows, understanding it becomes increasingly difficult.

Agents may be defined across several files. Skills have their own directories. MCP servers are declared separately. Models, tools, permissions, and instructions are distributed across different configuration sections. Each element may remain understandable on its own, but the overall picture quickly disappears.

You may know that an agent exists without immediately understanding its role within the team. You may assign tools to it without clearly seeing the true extent of its capabilities. You may create several subagents without having a simple representation of their hierarchy or the possible delegation paths between them.

The problem is therefore not a lack of power.

The problem is a lack of visibility.

## OpenCode Team Studio

This is precisely where OpenCode Team Studio comes in.

OpenCode Team Studio is a visual workspace for designing, configuring, and managing a team of OpenCode agents.

Instead of manipulating configuration files separately and mentally reconstructing the relationships between them, users can represent their system as a graph.

Agents become visible members of a team. Delegation relationships show which agents can call upon others. Connections identify the skills, tools, MCP servers, and models associated with each agent. Permissions clearly indicate what an agent is allowed to do, what requires approval, and what is forbidden.

The goal is not to replace OpenCode or create a new proprietary format. OpenCode Team Studio works on top of the existing OpenCode configuration. It transforms that configuration into a representation that is understandable, editable, and controllable, then applies the changes to the files actually used by OpenCode.

The configuration remains local, open, and under the user's control.

OpenCode Team Studio is therefore not intended to become another closed artificial intelligence platform. It is intended to become the workshop in which anyone can assemble their own team of agents.

## From a collection of agents to a coherent organization

Creating several agents is not enough to build an effective agentic system.

Users need to be able to answer simple questions quickly:

- What is the exact role of each agent?
- Which agent leads the execution?
- Which specialists can be called upon?
- Which capabilities are available?
- Which external tools are connected?
- Which model is used for each mission?
- What are the limits and permissions of each agent?
- Are some resources unused or assigned to the wrong place?

OpenCode Team Studio makes these relationships visible.

The user no longer sees only a sequence of technical parameters. They see an organization: its members, their responsibilities, their capabilities, their tools, and their relationships.

This representation can also make sharing easier. A well-designed agent team could be documented, versioned, reproduced, and adapted to another project. Specialized configurations could emerge for web development, data analysis, cybersecurity, scientific research, or infrastructure management.

Existing libraries of skills and MCP servers then become catalogs of capabilities and tools from which users can build their own systems.

## Making agentic AI understandable

Agentic AI remains difficult to grasp today because its behavior is mainly described through files, conventions, and technical parameters.

Yet the underlying concepts are natural: roles, responsibilities, capabilities, tools, permissions, and delegation.

By making these concepts visible, OpenCode Team Studio aims to reduce the distance between the idea of an agent team and its concrete implementation.

I believe that this understanding is an essential first step toward agentic open-source AI that is more capable, more accessible, and better suited to the real needs of each user.

Models provide the intelligence of the agents.

Skills and tools provide their capabilities.

Protocols allow them to interact with the outside world.

But organization is what turns them into a team.

OpenCode Team Studio is designed to build that organization.

## About the author

My name is Arthur Hottier. I am an engineer and developer with a particular interest in agentic artificial intelligence, language models, and open-source tools.

I am interested not only in what an individual model can accomplish, but especially in how several agents can be organized, specialized, and equipped to form genuinely useful systems.

I created OpenCode Team Studio after realizing that OpenCode already provided many of the components required to build an agent team, while the resulting organization remained difficult to understand and manage visually.

This project is my contribution to a more open, accessible, and controllable vision of agentic AI.

[My GitHub profile](https://github.com/ArthurHtr)

---

## OpenCode Team Studio

Feedback, contributions, and discussions about the project are welcome.
