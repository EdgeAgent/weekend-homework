# CLAUDE.md — Second Brain

## Mission

Build a local-first document question-answering system that extracts, chunks and indexes local files, retrieves relevant passages, and answers with traceable citations.

## Stack

- Python 3.11+
- SQLite for metadata
- `pypdf` plus Markdown/TXT extraction
- Local vector index
- Ollama for local embeddings and chat

## Rules

1. Build inventory, extraction, chunking, retrieval and answering as separate testable steps.
2. Retrieval must work before answer generation begins.
3. Every factual answer needs a file and page/section citation.
4. If the retrieved text does not answer the question, say so.
5. Use hashes for incremental indexing.
6. Report scanned or unreadable PDFs instead of indexing empty text.
7. Use fictional documents in examples and public demos.
8. Keep the default implementation local. Label any cloud substitution clearly.

## Definition of done

Five sample documents can be indexed; known questions return grounded, cited answers; unknown questions are refused; edits and deletions update only the affected records.
