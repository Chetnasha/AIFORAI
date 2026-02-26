# 🤖 AIFORAI – AutoDev AI Framework

AIFORAI is an **AI-powered automated development framework** designed to execute tasks intelligently using a **multi-agent architecture**.  
The system focuses on modularity, scalability, and seamless integration with Large Language Models (LLMs).

It simulates how AI agents can collaborate to analyze tasks, plan execution, and deliver results autonomously.

---

## 🎯 Project Intent

The goal of **AIFORAI** is to:
- Explore **agent-based AI systems**
- Automate task execution using AI reasoning
- Build a foundation for **future autonomous developer tools**
- Demonstrate real-world application of **LLMs + agents**

This project is ideal for:
- AI/ML learning
- Agentic AI research
- Internship & portfolio demonstration

---

## ✨ Key Features

✅ **Multi-Agent System**  
Each agent is responsible for a specific role (planning, execution, coordination).

✅ **Task-Based Execution**  
Tasks are modular and dynamically assigned to agents.

✅ **LLM Integration Ready**  
Designed to easily plug into OpenAI / other LLM APIs.

✅ **Scalable Architecture**  
New agents and tasks can be added without changing core logic.

✅ **Clean Code Separation**  
Clear division between agents, tasks, and execution flow.

---

## 🧠 System Architecture (Visual)
┌───────────────────┐
│ User Input │
└─────────┬─────────┘
│
▼
┌───────────────────┐
│ Main Controller │ (main.py)
└─────────┬─────────┘
│
▼
┌───────────────────────────┐
│ Task Manager │ (tasks.py)
└─────────┬─────────┬───────┘
│ │
▼ ▼
┌────────────────┐ ┌────────────────┐
│ AI Agent 1 │ │ AI Agent 2 │ (agents.py)
└─────────┬──────┘ └─────────┬──────┘
│ │
▼ ▼
┌───────────────┐ ┌───────────────┐
│ LLM Wrapper │ │ LLM Wrapper │ (llm_wrapper.py)
└───────────────┘ └───────────────┘


---

## 🛠️ Tech Stack

| Category | Technology |
|--------|-----------|
| Language | Python |
| AI Concept | Multi-Agent Systems |
| LLM Support | OpenAI / LLM APIs (extensible) |
| Architecture | Modular, Task-based |
| Tools | VS Code, Git, GitHub |

---

## 📂 Project Structure
AIFORAI/
├── README.md
└── src/
├── agents.py # Defines AI agents and their behavior
├── tasks.py # Task definitions and management
├── llm_wrapper.py # Interface to interact with LLMs
├── main.py # Entry point of the application
└── demo.py # Demo / example execution

---

## ▶️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/ChetnaSha/AIFORAI.git
cd AIFORAI
python src/main.py