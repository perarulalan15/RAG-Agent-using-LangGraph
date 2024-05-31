# RAG Agent using LangGraph, ChromaDB, and Tavily AI

This repository contains the implementation of a Retrieval-Augmented Generation (RAG) Agent using LangGraph, ChromaDB, and Tavily AI, based on the article "Build a Reliable RAG Agent using LangGraph" in Medium.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)

## Introduction

This project implements a Retrieval-Augmented Generation (RAG) Agent using LangGraph, ChromaDB, and Tavily AI. RAG combines the capabilities of retrieval-based and generation-based models to provide more accurate and contextually relevant responses.

- **LangGraph**: Provides a framework for building reliable and modular pipelines for natural language processing.
- **Chroma**: An open-source vector database optimized for efficient storage and retrieval of embeddings.
- **Tavily Search API**: A search engine optimized for Large Language Models (LLMs) and RAG, aimed at providing efficient, quick, and persistent search results.

## Features

- **Hybrid Model**: Combines retrieval-based and generation-based approaches.
- **Configurable Pipeline**: Easily modify and extend the agent’s capabilities.
- **Reliable Performance**: Optimized for accuracy and reliability in generating responses.
- **Chroma Integration**: Efficient data retrieval with the open-source vector database.
- **Tavily Search API**: Optimized search engine for LLMs and RAG.

## Installation

To install and run the RAG Agent, follow these steps:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/perarulalan15/RAG-Agent-using-LangGraph.git
    cd RAG-Agent-using-LangGraph
    ```

2. **Set up a virtual environment**:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the required packages**:
    ```sh
    pip install -U langchain-nomic langchain_community tiktoken langchainhub chromadb langchain langgraph tavily-python gpt4all fastembed langchain-groq
    ```
