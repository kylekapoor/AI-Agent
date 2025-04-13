# 🧠 Open-Source AI Agent

An autonomous AI agent built using Meta Llama 3.1 and Groq for high-context reasoning workflows. Inspired by OpenAI’s O1: Strawberry system, the agent mimics structured thought processes through a planner-executor-evaluator architecture.

---

## 💡 Overview

This project showcases a modular AI agent framework capable of ingesting high-volume context (10K tokens) and executing task flows with minimal hallucination. It supports LLM chaining and integrates with multiple inference endpoints to enhance reasoning reliability.

---

## 🔧 Tech Stack

- **Languages**: Python
- **Models/Backends**: Meta Llama 3.1, OpenAI (via OpenRouter), Groq
- **Frameworks**: LangChain (custom wrappers), OpenRouter SDK
- **Deployment**: Local / Jupyter Notebook

---

## ⚙️ Features

- ✨ Multi-model orchestration via OpenRouter
- 🧩 Agent workflow: Planner → Executor → Evaluator
- 🧠 10K+ token context support via Groq LPU
- 🔄 LLM transformation layer for adaptive reasoning

---

## 🚀 Getting Started

```bash
git clone https://github.com/kylekapoor/ai-agent
cd ai-agent
pip install -r requirements.txt
python agent.py
