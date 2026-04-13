Medium Blog Link: https://medium.com/@hemashree.n7714/langchain-decoded-building-modular-llm-applications-with-chains-agents-and-memory-a9243f4032a9

# LangChain Offline Demo 

This repository contains a Jupyter Notebook demonstrating LangChain concepts **without requiring API keys**.  
It uses `FakeListLLM` for offline responses and HuggingFace embeddings for local vector search.

## Features
- PromptTemplate + RunnableSequence (replaces old LLMChain)
- FakeListLLM for offline demo
- Custom Tool + Agent
- Document Loader + FAISS Vector Store
- HuggingFace Embeddings (`sentence-transformers/all-MiniLM-L6-v2`)

## Requirements
- Python 3.10+
- Jupyter Notebook
- LangChain 1.2.15
- HuggingFace Transformers

## Installation
```bash
pip install langchain langchain-core langchain-community faiss-cpu chromadb tiktoken transformers
