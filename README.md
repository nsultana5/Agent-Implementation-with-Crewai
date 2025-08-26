# Exploring AI Agents: Building a Multi-Agent Blog Writer

[![Python](https://img.shields.io/badge/python-3.13-blue)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## Table of Contents
- [Introduction](#introduction)
- [What is an AI Agent?](#what-is-an-ai-agent)
- [Why AI Agents?](#why-ai-agents)
- [Tools and Workflow](#tools-and-workflow)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Running the Project](#running-the-project)
- [Why Crewai?](#why-crewai)
- [Contributing](#contributing)
- [License](#license)

---

## Introduction
This project demonstrates how multiple AI agents can collaborate to automate research and content creation. It uses a **Researcher Agent** to gather insights and a **Writer Agent** to generate blog posts based on that research.  

---

## What is an AI Agent?
An AI agent is a program that can perform tasks autonomously or semi-autonomously. It observes its environment, makes decisions, and acts to achieve a goal. In real-world applications, AI agents can research, automate tasks, summarize information, or interact with humans or other agents.  

---

## Why AI Agents?
AI agents help break down complex tasks into smaller, manageable actions. In this project:

- **Researcher Agent** – Gathers insights about AI in startup businesses.  
- **Writer Agent** – Writes a blog post based on the research provided by the Researcher Agent.  

This sequential collaboration mimics how teams work together, but automated with AI.

---

## Tools and Workflow
- **Search Engine:** [SerperDev](https://serper.dev/api-key) for retrieving relevant information.  
- **LLM Model:** GPT-4-32k for generating high-quality content.  
- **Project Structure:** `requirements.txt`, `main.py`, `README.md`, `.env`.  

**Workflow:**
1. Libraries are imported, and environment variables are set.  
2. Agents are defined with their tasks, ensuring sequential execution: research first, then writing.  
3. Running `main.py` generates a blog post in Markdown format (`blog.md`).  

---

## Project Structure
```text
.
├── main.py           # Main script to run agents
├── requirements.txt  # Python dependencies
├── README.md         # Project documentation
├── .env              # Environment variables (e.g., SerperDev API key)
└── blog.md           # Generated blog post



---

## Installation

1. **Clone the repository**
```bash
git clone https://github.com/nsultana5/Agent-Implementation-with-Crewai.git
cd your-repo


2.Create Conda environment and activate
conda create -n llmapp python=3.13 -y
conda activate llmapp

3.Install dependencies
pip install -r requirements.txt


Running the Project
1.Set your SerperDev API key
# Windows PowerShell
$env:SERPER_API_KEY="your_api_key_here"

2.Run the main script
python main.py

3.Output
Generates a blog.md file containing a complete blog post ready for use.

Why Crewai?

CrewAI
 simplifies multi-agent orchestration, making it easier to manage communication between agents and ensure tasks are executed efficiently in sequence. It’s a great tool for building collaborative AI systems without manually handling inter-agent logic.

 Contributing

1.Fork the repository

2.Create a new branch (git checkout -b feature-name)

3.Commit your changes (git commit -m 'Add new feature')

4.Push to the branch (git push origin feature-name)

5.Open a Pull Request

License

This project is licensed under the MIT License - see the LICENSE
 file for details.

 
---

If you want, I can also **add a screenshot section showing the workflow or agent output**, which makes your GitHub README much more visually appealing and professional.  

Do you want me to do that next?

