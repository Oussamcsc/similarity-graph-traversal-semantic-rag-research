# Semantic Similarity Graph Traversal for RAG

**Research workbench for semantic similarity graph traversal algorithms for retrieval-augmented generation.**

This repository explores whether semantic similarity graphs can improve retrieval quality compared with plain vector search. It includes graph construction utilities, traversal algorithms, benchmark scripts, visualization assets, evaluation helpers, and a research notebook.

## Portfolio framing

This is best presented as a research/workbench repository, not a polished SaaS product. It demonstrates algorithmic thinking around retrieval, graph traversal, semantic search, evaluation, and RAG experimentation.

## What it demonstrates

- Semantic similarity graph construction from embedded document chunks
- Query-guided and graph-guided traversal strategies
- Retrieval benchmarking and evaluation workflows
- Visualization of graph structure and traversal paths
- Python research tooling with notebooks, scripts, datasets, and reusable utilities

## Quick start

```bash
git clone https://github.com/Oussamcsc/similarity-graph-traversal-semantic-rag-research.git
cd similarity-graph-traversal-semantic-rag-research
python3.12 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
cp .env.example .env
jupyter notebook research_demonstration.ipynb
```

## Environment variables

```env
OPENAI_API_KEY=replace-with-openai-api-key
OLLAMA_BASE_URL=http://localhost:11434
ANTHROPIC_API_KEY=replace-with-anthropic-api-key
OPENROUTER_API_KEY=replace-with-openrouter-api-key
CONFIDENT_AI_API_KEY=replace-with-deepeval-api-key
```

Never commit real `.env` files.

## Original research notes

The detailed research write-up and visualizations continue below.

---

<h1 align="center">Novel Semantic Similarity Graph Traversal Algorithms for Semantic Retrieval Augmented Generation Systems</h1>