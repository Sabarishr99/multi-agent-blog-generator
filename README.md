# Multi-Agent Blog Automation

This is a Python project that demonstrates how there can be job losses due to the introduction of AI, where conventional human jobs are replaced by small AI agents.  
Imagine a world where a blog post is created entirely by AI.  
In this AI project, a manager transfers tasks to smaller AI agents.  
The system is built using the OpenAI Swarm framework and uses OOP-style agent functions.


# Architecture Features :

### Agent Specialization
Each agent focuses on its own task, which increases efficiency and improves quality.

### Parallelization
This is handled by Swarm AI. We only need to provide the framework.

### Scalability
The system can be expanded by adding new agents.

### Robustness
If one agent fails, other agents can compensate and complete the task.

## How to run the project
1. Open the terminal inside this folder  
2. Add your API key in the code 
3. Run the command:

## What this program does

### 1. Agent Configuration
Each agent is given a specific role and behavior, such as setting the agent’s name, instructions, and the functions it can call to interact with other agents.

### 2. Role Assignments
1. Admin → oversees the project and provides guidance  
2. Researcher → gathers data on the given topic  
3. Planner → organizes the research into an outline  
4. Writer → drafts the blog post based on the outline  
5. Editor → reviews and edits the final content  

### 3. Interaction Management
Defines the allowed communication between agents to maintain orderly coordination.

### 4. Task Execution
The Admin initiates the task, and agents collaboratively work through researching, planning, writing, and editing.


## Files in this project
- `multiagent.py` → main Python file  
- `README.md` → explanation of the project  
- `requirements.txt` → libraries needed  
- `.gitignore` → files ignored by git  


## Agents in this project
- **Admin Agent** → starts the project  
- **Planner Agent** → creates the blog outline  
- **Researcher Agent** → gathers information  
- **Writer Agent** → writes the blog content  
- **Editor Agent** → edits and saves the final blog  

## Author
**Sabarish R**