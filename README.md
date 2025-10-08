# LangChain Demo: Memory, Agents & RAG

This repository demonstrates **LangChain** capabilities, including memory, agents, tool integration, and retrieval-augmented generation (RAG) using Python.

## Features

- 🧠 **Conversation Memory**  
  Chatbots that remember previous interactions using `ConversationBufferMemory` and `ConversationSummaryBufferMemory`.

- 🔗 **LLM Chains**  
  Sequential chains, few-shot prompting, and chain-of-thought reasoning.

- 🛠️ **Agents & Tools**  
  Integrate tools like calculators, translators, and RAG search within chat agents.

- 💾 **Vector Stores & RAG**  
  Use Chroma and FAISS for document embedding and retrieval.

- ✏️ **Structured Outputs**  
  Generate structured JSON and summaries from LLM responses.

## Installation

```bash
pip install langchain langchain-openai chromadb faiss-cpu
