# 🤖 AI Agents

> A hands-on exploration of production AI agent architectures — from single agents to multi-agent systems, MCP tooling, and cloud deployment.

---

## Overview

This repository documents my end-to-end learning journey building AI agents using the **Google Agent Development Kit (ADK)**. Each notebook covers a distinct concept in modern agentic system design, progressing from basic single-agent setups to full multi-agent deployments on Google Cloud.

---

## Notebooks

| Notebook | Description |
|---|---|
| `singleagent` | First agent built using Gemini and Google ADK |
| `multiagent` | Multi-agent systems using ADK orchestration |
| `multi-tool-agent` | Extending agent capabilities with multiple tools |
| `agents-with-mcp` | Tool extension via Model Context Protocol (MCP) |
| `agentsession` | Stateful agents and context engineering |
| `agentmemory` | Memory patterns for long-running agents |
| `agentobservability` | Logging and debugging with observability tooling |
| `agenteval` | Evaluating agent performance and output quality |

---

## Concepts Covered

- **Single & Multi-Agent Systems** — Building coordinated agent networks with ADK
- **Tool Extension** — Adding custom tools and integrating MCP for long-running operations
- **Context Engineering** — Managing session state across multi-turn interactions
- **Agent Memory** — Implementing short-term and long-term memory patterns
- **Observability** — Tracing, logging, and debugging agent behavior in production
- **Agent Evaluation** — Systematic evaluation of agent outputs and reliability
- **A2A Protocol** — Agent-to-Agent communication for cross-agent task delegation
- **Cloud Deployment** — Deploying agents to Agent Engine on Google Cloud

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat&logo=python&logoColor=white)
![Google ADK](https://img.shields.io/badge/Google_ADK-Agent_Development_Kit-4285F4?style=flat&logo=google&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-LLM-8E44AD?style=flat)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat&logo=jupyter&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-Agent_Engine-4285F4?style=flat&logo=googlecloud&logoColor=white)

---

## Getting Started

```bash
git clone https://github.com/shoumik27/AI-Agents.git
cd AI-Agents
pip install google-adk jupyter
jupyter notebook
```

Open any `.ipynb` file and run cells sequentially. A Gemini API key is required — set it as an environment variable:

```bash
export GOOGLE_API_KEY=your_api_key_here
```

---

## Author

**Shoumik Chandra** — AI Security Researcher   
[GitHub](https://github.com/shoumik27)
