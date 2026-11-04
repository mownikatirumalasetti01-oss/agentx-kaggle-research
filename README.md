kaggle.com/writeups/tmownika/auto-research-with-this-3-ai-agents An automatic research with 3 AI Agents

Introduction: Now large language models (LLMs) like ChatGPT are reactive systems that only react to user questions. However,the future of AI is automatic agents that can think,plan,and execute it independently. My project AgentX is build such a pro-active system.

Problem statement: A single chat board cannnot complete a full research project. The core problem is lack of autonomous task decomposition and multi-agent collaboration.

Introduction that 3 ai agents: Planner Agent: Take a main point and breaks it into small parts like tasks using chain of thought reasoning. Researcher Agent: Automatically it searches paper and give extract large information. Executor Agent: Writes a code , testing the code,and create the final report.

AgentX - by Mownika - GKS 2027 goal = "Research on Telugu Handwriting"

def agentx_planner(goal): print(f"\n[AgentX Thinking for: {goal}]") tasks = { "Research": f"Search papers for {goal}", "Planning": "Create timeline", "Execution": "Write code and test" } return tasks

def agentx_executor(tasks): for role, work in tasks.items(): print(f"-> Agent {role} is working on: {work}")

my_tasks = agentx_planner(goal) agentx_executor(my_tasks) print("\n AgentX completed planning! Not just a chatbot!") OUTPUT: [AgentX Thinking for: Research on Telugu Handwriting] -> Agent Research is working on: Search papers for Research on Telugu Handwriting -> Agent Planning is working on: Create timeline -> Agent Execution is working on: Write code and test

AgentX completed planning! Not just a chatbot!

Expected outcomes & Timelines: In 6 months at SNU, I will develop the proper or full multi-agent communication protocol. The final system will allow a user to give one goal and give a completed project.

Why SNU & why Korea: South korea is the leader of AI automation and I want to contribute to this vision. Seoul National University's AI lab, especially work on autonomous agents, perfectly matches to my research. I like to learn under that professor at SNU and take this technology to help both korea and india.

Conclusion: AgentX is not just a chatboard. It is independent team of AI Agents. I think this research will be a step toward true Artificial General Intelligence(AGI).

Citation
DOI (Digital Object Identifier)
https://doi.org/10.34740/kaggle/w/123316
Citation Type
BibTeX
APA
@article{t_mownika_2026,
	title={Auto-research with this 3 AI Agents},
	url={https://www.kaggle.com/w/123316},
	DOI={10.34740/KAGGLE/W/123316},
	journal={Kaggle},
	publisher={Kaggle},
	author={T Mownika},
	year={2026}
}
Citation


Project Details
Author
T Mownika