# smart-civil-engineer-rag
AI assistant that answers civil engineering questions using Nigerian Building Codes

# Smart Civil Engineer – RAG System

An AI assistant that answers civil engineering questions using the
Nigerian National Building Code with page citations.

## What it does
- Loads a 476-page building code PDF
- Splits it into semantic chunks
- Stores embeddings in a vector database (ChromaDB)
- Retrieves relevant sections for any query
- Generates grounded answers with cited pages

## Example Query
"What does the code say about foundation requirements?"

## Tech Stack
- Python
- LangChain
- Hugging Face (MiniLM embeddings, FLAN-T5)
- ChromaDB
- Google Colab

## Use Cases
- Civil engineering compliance checks
- Design review
- Construction audits
- Education & training

