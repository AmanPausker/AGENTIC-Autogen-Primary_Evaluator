# Multi Agent:AGENTIC-Autogen-Primary_Evaluator
WHAT IS THIS??
This repository contains an Agentic AI workflow 2 Agents - Primary Agent( Who answers the questions) and Evaluator Agent ( who evaluates the primary agent's response). These agents collaborate with each other to give the user a perfect response using Autogen's multi-agent framework.
The primary agent can web search to get real time information online.
Agentic Architecture- 
<img width="1536" height="1024" alt="system_architecture" src="https://github.com/user-attachments/assets/8745382a-80ec-450a-b223-e42d23db3416" />

WHY DID I BUILD THIS??
Learning the Team Interactions between the multi agents, how they communicate and evaluate.
As part of learning with Autogen and using Langchain's vast community utility library to add tools to the Agent.
I learnt to equip agents with tools that gives the agent resources and tools to actually help them work asynchronously.

HOW TO USE THIS??
There is a simple python notebook that can be run on any IDE after installing the required libraries.
The results are there in the files folders.Name - flights.md
Result in flights.md file
<img width="1288" height="351" alt="image" src="https://github.com/user-attachments/assets/732699dc-968a-4af3-961e-42e0bafa1a3d" />

Note – There are some things that should be taken into consideration here
1. The number of cycles(interactions) between the primary and the evaluator agent needs to be determined early on, so that you don’t use up your resources and the response time is minimal.
2. Agentic specific prompts should be carefully curated so that the agent understands what are its expectations and what is the evaluation criteria.
