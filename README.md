# SMA LangChain

A simple LangChain project demonstrating how to build and run a basic AI agent using Groq LLMs with LangChain v1.

## Project Overview

This project contains a Jupyter Notebook that shows how to:

- Load environment variables with `python-dotenv`
- Use `ChatGroq` as the LLM provider
- Create a LangChain agent with `create_agent`
- Invoke the agent using a `messages` list
- Reuse the agent for different prompts

The main notebook is `sma.ipynb`.

## Technologies Used

- Python
- Jupyter Notebook
- LangChain
- LangGraph
- Groq
- Ollama
- Tavily
- python-dotenv
- uv

## Project Structure

```text
sma-langchain/
├── sma.ipynb
├── pyproject.toml
├── uv.lock
├── README.md
├── .python-version
├── .gitignore
└── .vscode/
