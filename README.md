# ResearchLens

ResearchLens is a research intelligence system for discovering, understanding,
and evaluating machine learning and AI literature.

The long-term goal is to help researchers move from individual papers to a
structured understanding of a research area: methods, datasets, results,
limitations, evidence, and related work.

## Current milestone

### v0.1 — Corpus Search

The first version focuses on a simple and measurable retrieval baseline.

Input:

- a local collection of ML/AI papers in PDF format;
- a text query.

Output:

- Top-K relevant passages;
- source paper;
- available page or section metadata.

ResearchLens v0.1 intentionally does not use:

- LLMs;
- embeddings;
- vector databases;
- recommendation systems.

These components may be introduced only after the lexical retrieval baseline
can be evaluated.

## Project structure

```text
researchlens/
├── src/
│   └── researchlens/
├── tests/
├── data/
│   └── papers/
├── docs/
├── README.md
├── pyproject.toml
└── .gitignore
