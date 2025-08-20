# Domain-Specific RAG Pipeline

This folder contains the Retrieval-Augmented Generation (RAG) pipeline specific to our chosen domain (e.g., education, health).

## Structure
- `data/` – Knowledge base documents (PDFs, FAQs, text files, etc.).
- `notebooks/` – Experiments and exploration notebooks for rapid prototyping.
- `pipeline/` – Core RAG code (document ingestion, retrieval, and generation modules).
- `results/` – Evaluation outputs (CSV, JSON, plots).

## Notes
- The domain knowledge base is not finalized yet — will be added here once selected.
- All pipeline code will be modular to allow swapping knowledge bases easily.
- Results should be versioned (e.g., `v1_eval.json`, `v2_eval.json`) for reproducibility.
