kaggle.com/writeups/tmownika/auto-research-with-this-3-ai-agents An automatic research with 3 AI Agents

Introduction: Now large language models (LLMs) like ChatGPT are reactive systems that only react to user questions. However,the future of AI is automatic agents that can think,plan,and execute it independently. My project AgentX is build such a pro-active system.

Problem statement: A single chat board cannot complete a full research project. The core problem is lack of autonomous task decomposition and multi-agent collaboration.

Introduction that 3 ai agents: Planner Agent: Take a main point and breaks it into small parts like tasks using chain of thought reasoning. Researcher Agent: Automatically it searches paper and give extract large information. Executor Agent: Writes a code , testing the code,and create the final report.

AgentX - by Mownika 

"architecture: planner->researcher->executor. Each agent has its own role and talk to each other using structured message "

goal = "Research on Telugu Handwriting"

def agentx_planner(goal):
    print(f"\n[AgentX Thinking for: {goal}]")                                   
    tasks={
           "Research": f"Search papers for {goal}",       
           "Planning": "Create timeline", 
           "Execution": "Write code and test" 
        } 
        return tasks

def agentx_executor(tasks):
      for role, work in tasks.items(): 
          print(f"-> Agent {role} is working on: {work}")

my_tasks = agentx_planner(goal) agentx_executor(my_tasks) 
print("\n AgentX completed planning! Not just a chatbot!")

 OUTPUT: [AgentX Thinking for: Research on Telugu Handwriting]
 -> Agent Research is working on: Search papers for Research on Telugu Handwriting 
-> Agent Planning is working on: Create timeline 
-> Agent Execution is working on: Write code and test

AgentX completed planning! Not just a chatbot!

Expected outcomes : I will develop the proper or full multi-agent communication protocol. The final system will allow a user to give one goal and get a completed project.

Future work:In next 6 months, I will add memory agent, Testing agent and communication protocol between agents.This will make agentX able to handle big projects without human help 

Conclusion: AgentX is not just a chatbot. It is independent team of AI Agents. I think this research will be a step toward true Artificial General Intelligence(AGI).

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