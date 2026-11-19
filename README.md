# Agentic Library Search

An AI-powered library search system that combines hybrid search with an agentic workflow. It goes beyond plain keyword lookup to understand what the user actually wants and find the most relevant books, papers and resources.

## Key Features
- Hybrid search: BM25 keyword matching plus semantic vector search, merged with Reciprocal Rank Fusion (RRF)
- Agentic reasoning: the agent rewrites the query, picks a tool and refines results over multiple steps
- Natural language queries: e.g. "beginner books on ML with Python examples"
- Metadata filtering by author, genre, year and availability
- Context-aware answers with source citations

## Tech Stack
Python · LangGraph · LangChain · OpenAI · PostgreSQL (pgvector) · Elasticsearch · FastAPI
