# 🚀 crewai-python-coder-agent

## 📌 Summary

The Autonomous Python Coder Agent is an AI-powered software development assistant built using CrewAI. Given a programming assignment, the agent independently analyzes the problem, plans the solution, generates Python code, executes it in a secure environment, validates the results, and produces a final output containing both the generated code and execution results.

This project demonstrates how Large Language Models (LLMs) and CrewAI can be combined to automate the complete coding workflow, from understanding requirements to delivering verified executable solutions.

---

## 🎯 Project Objectives

- Automate Python code generation from natural language instructions.
- Demonstrate AI agent orchestration using CrewAI.
- Reduce manual effort in solving programming tasks.
- Showcase secure AI-assisted software development workflows.

---

## ⚙️ How the System Works

The workflow follows a simple autonomous development cycle:

1. User provides a programming assignment.
2. CrewAI passes the assignment to the Coding Agent.
3. The agent analyzes and plans the solution.
4. Python code is generated.
5. Generated code is executed automatically.
6. Output is reviewed and validated.
7. Results are stored in a text file.
8. Final response is returned to the user.

---

## 🧠 Agent Architecture

### Python Developer Agent

The project uses a single specialized AI agent configured as an experienced Python developer.

#### Responsibilities

- Understand programming requirements.
- Break down problems into logical steps.
- Plan the implementation strategy.
- Generate clean Python code.
- Execute generated code safely.
- Verify correctness of outputs.
- Produce final deliverables.

#### Agent Configuration

- Role: Python Developer
- LLM: GPT-OSS-120B via Groq
- Code Execution Enabled
- Safe Execution Mode
- Automatic Retry Support
- Execution Time Control

---

## 📋 Task Configuration

### Coding Task

The coding task instructs the agent to:

- Read the assignment.
- Generate a Python solution.
- Execute the generated code.
- Capture program output.
- Save results into a structured file.

### Output Generated

```text
output/code_and_output.txt
```

The output file contains:

- Generated Python code
- Execution results
- Final solution

---

## 📂 Project Structure

```text
coder/
│
├── config/
│   ├── agents.yaml
│   └── tasks.yaml
│
├── crew.py
├── main.py
│
├── output/
│   └── code_and_output.txt
│
├── requirements.txt
├── README.md
└── 
```

---

## 🔧 Technologies Used

- Python
- CrewAI
- Groq API
- GPT-OSS-120B
- YAML Configuration
- Docker (Safe Code Execution)

---

## 🔄 Workflow Diagram

```text
User Assignment
       │
       ▼
Python Developer Agent
       │
       ▼
Problem Analysis
       │
       ▼
Solution Planning
       │
       ▼
Code Generation
       │
       ▼
Code Execution
       │
       ▼
Output Validation
       │
       ▼
Result File Creation
```

---


## 👨‍💻 Author

**Zeba Fathima**

Computer Science Student | AI & Machine Learning Enthusiast | Generative AI Developer

This project was developed to explore autonomous AI agents capable of performing end-to-end software development tasks using CrewAI and Large Language Models.
