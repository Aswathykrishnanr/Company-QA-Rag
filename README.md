# Company QA RAG

A learning project: RAG and a simple agent built **from scratch, without any framework**, to understand how each step works.

## What it does
Answers questions about sample company documents (HR, engineering, onboarding, product, security).

- Splits documents into chunks
- Embeds them with Sentence Transformers and stores them in ChromaDB
- Retrieves relevant chunks and answers with `openai/gpt-oss-20b` via Groq
- Agent layer: [what your agent decides]

## Flow
Documents → chunks → embeddings → ChromaDB → retrieve → LLM → answer

## Run
1. Open `rag_and_agentic_rag.ipynb` in Colab
2. Add your API key in Colab Secrets as `API_KEY`
3. Set the documents folder path and run all cells

*Sample documents, built for learning.*
