# vf-apps-agents
This repo will define some requirements for apps for both individual (personal) agents as well as organizational agents.

Agent apps are required for [agent-centric computing](https://github.com/valueflows/vf-apps-agents/wiki/Agent-centric-computing). They will be the main apps in such configurations, and the agents will be the selectors and users of all the other apps.

[A personal Agent app](https://github.com/opencooperativeecosystem/agent) has already been started and is in daily use in FairCoop, and is now going through feedback loops with users.

![Agent app](https://user-images.githubusercontent.com/117439/43355797-819560f2-9228-11e8-9a42-8ba7ec1a8a34.jpeg)

This diagram shows both the existing personal agent app as well as the planned organizational agent app in the FairCoop context, with some of the existing and planned features and extensions surrounding them.

![agent-centric](https://user-images.githubusercontent.com/117439/43346048-60424b7c-91b5-11e8-9c31-ded327eb5737.jpeg)

An Agent app needs to represent and manage all of the connections that Agents have with other objects in the ValueFlows continuum. Each of the connections listed below will be detailed in a separate app repo, because it makes most sense to have agent apps plus lots of plugins, depending on the agent's needs and preferences.

The diagrams below were excerpted from https://speakerdeck.com/mikorizal/everything-in-valueflows-is-connected-to-everything-else which still shows the datamodel names from NRP, but the relationships are the same as in VF. (Soon we will replace these with the correct VF model names.)

A person or organization is represented by an Agent:

![agent connections 1](https://user-images.githubusercontent.com/117439/43356231-442acea0-9232-11e8-834f-040f5b2aa262.jpg)

One Agent might be connected to others by Agent Relationships. Those will be managed by AgentRelationship apps. Here is a lovely [example of an AgentRelationship app](http://holodex.enspiral.com/) with [code](https://github.com/holodex/holodex).

![agent connections 2](https://user-images.githubusercontent.com/117439/43356250-8461ca32-9232-11e8-88d5-6ae0f554ad1f.jpg)

An Agent is also connected to all the Economic Events they have participated in. Those will be managed by EconomicEvent apps.

![agent connections 3](https://user-images.githubusercontent.com/117439/43356275-f435cdb8-9232-11e8-90c6-4848d09bc00b.jpg)

An Agent might have custody or some other relationship with Economic Resources. Those will be managed by Inventory apps.

![agent connections 4](https://user-images.githubusercontent.com/117439/43356283-3435d930-9233-11e8-8b75-f26097930526.jpg)

An Agent might have Commitments with other Agents about Processes or Exchanges which might be parts of Plans. Those might all be managed by Planning apps. Those get a lot more complicated and will be explained in their own repo or repos.

![agent connections 5](https://user-images.githubusercontent.com/117439/43360938-e5e8a442-9287-11e8-8e0d-68b12ffd1084.png)

You can find data for Agents and AgentRelationships in a variety of formats at the [Vocabulator](http://valueflows.pythonanywhere.com/). More data to come for all those other Agent connections.
