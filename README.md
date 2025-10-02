# Market Intel LLM-Bot

**Market Intel LLM-Bot** is a Competitive Intelligence Assistant that collects online news, stores embeddings in a vector database, and answers company-specific queries using a RAG pipeline and a fine-tuned LLM.

## Features
- Scrape company news and blog posts from online sources
- Chunk, embed, and store documents in **pgvector**
- Retrieve relevant context and generate answers with **LLM**
- Optional **LoRA fine-tuning** for domain-specific summarization
- Dockerized backend and frontend for easy deployment
- Experiment tracking with **Weights & Biases (W&B)**

## Getting Started

### Requirements
- Python 3.10+
- Docker & Docker Compose
- GPU (optional, for fine-tuning)

### Installation
```bash
git clone https://github.com/yourusername/market-intel-llm-bot.git
cd market-intel-llm-bot
pip install -r requirements.txt
