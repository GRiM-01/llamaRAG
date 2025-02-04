# LlamaRAG
My RAG application allows you to chat with your pdfs and extract information without having to read the documents yourself.

This was achieved by enhancing the llama 3.2 3b LLM by providing providing it with external data (uploaded pdfs) to allow the model to **retrieve** relevant data before generating a response instead of the LLM relying on its pretrained data.
This ensure that the LLM dynamically fetches up-to-date and domain-specific data thus improving accuracy and context-awareness which lowers the risk of the LLM hallucinating and providing inaccurate answers.

## Features
- PDF document ingestion
- ChromaDB vector storage
- Ollama-powered responses (free and open source LLM)

## Installation
```bash
git clone https://github.com/GRiM-01/llamaRAG.git
cd llamaRAG
