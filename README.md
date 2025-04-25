# Effective AI Agent Design Patterns using LangGraph and CrewAI

## Project Overview
This repository contains code, Colab notebooks, and video walkthroughs that demonstrate how to build modular and scalable **AI agents** using modern frameworks such as **LangGraph** and **CrewAI**.

The project showcases several key agent design patterns inspired by the ["Building Effective Agents"](https://www.youtube.com/watch?v=aHCDrAbH_go&t=5s) series by LangChain, adapted and implemented using:
- 🔹 **LangGraph** — a stateful multi-agent orchestration library built on top of LangChain.
- 🔸 **CrewAI** — a simple, modular framework for creating autonomous agent teams.

Each agent pattern includes:
- Step-by-step logic construction
- Execution trace with **LangSmith Studio**
- Equivalent implementation in CrewAI
- Side-by-side behavior comparisons

---

## Frameworks Demonstrated

This project leverages two complementary frameworks for LLM-based agent orchestration:

- **LangGraph**  
  - Enables graph-based execution of agents.
  - Tracks memory, conditional routing, and multi-agent coordination.
  - Integrated with LangSmith Studio for real-time traces and observability.

- **CrewAI**  
  - Focuses on modular task-based agent collaboration.
  - Useful for quick prototyping and team-based workflows.
  - Integrates with tools like Groq and LangChain agents.

---

## Colab Notebooks & Demonstrations

Click below to launch the Colab notebooks demonstrating each agent pattern:

* **A. LangGraph + LangSmith**  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1eySqYSudwl4O1BMlhG142oFFdGu6dRgu?usp=sharing)

* **B. CrewAI**  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/142KaBWUaWW3aPE6indlyUysDuwIFB3q8?usp=sharing)


---

## Key Features Demonstrated

### ✅ LangGraph + LangSmith Studio
- Create stateful graphs of agents with memory and routing logic.
- Visualize execution traces and transitions using **LangSmith Studio**.
- Includes ReAct-based reasoning and tool invocation with feedback loops.

### ✅ CrewAI Equivalent Implementations
- Build equivalent flows using `Agents`, `Tasks`, and `Crew`.
- Compose logic using modular roles and task prompts.
- Run the same pattern for comparative evaluation.

---

## Video Tutorials

Watch walkthroughs of each pattern (with debugging and trace analysis):

[![YouTube Link](https://img.shields.io/badge/YouTube-Watch_Tutorial-red?logo=youtube)](https://youtu.be/qQcb13GtU1E)

---


## Tips & Best Practices

- 🔁 **Reuse Chat Templates**: Ensure consistent formatting across LangGraph and CrewAI runs.
- 🧠 **Use LangSmith Traces**: Great for debugging node outputs and routing issues.
- 🧪 **Experiment with Agents**: Swap tools, memory types, and tasks to observe behavior shifts.
- 💡 **Compare Logs**: Run LangGraph and CrewAI side-by-side and analyze similarities/differences.

---

## References

- [Building Effective Agents – YouTube](https://www.youtube.com/watch?v=aHCDrAbH_go)
- [LangGraph Documentation](https://langchain-ai.github.io/langgraph/tutorials/workflows)
- [LangSmith Studio](https://smith.langchain.com/)
- [CrewAI Docs](https://docs.crewai.com/)
- [DeepLearning.AI: AI Agents in LangGraph](https://www.deeplearning.ai/short-courses/ai-agents-in-langgraph/)
- [Workflow and Patterns Notion](https://mirror-feeling-d80.notion.site/Workflow-And-Agents-17e808527b1780d792a0d934ce62bee6)

