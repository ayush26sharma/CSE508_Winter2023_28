# Information Retrieval & Graph Ranking Algorithms

Coursework for **CSE508 (Information Retrieval), Winter 2023, IIIT Delhi** — three assignments implementing core IR and graph-ranking algorithms from first principles rather than calling out to black-box libraries for the core logic.

**Team:** Ayush Sharma, Aditya Jain

## Assignment 1 — Inverted, Positional & Biword Indices
[`Assignment - 1/`](<Assignment - 1>)

Built inverted, positional, and biword indices from scratch over the Cranfield collection, with Boolean and phrase query processing and a comparison-count analysis across index types.

## Assignment 2 — Ranked Retrieval, Text Classification & Ranking Metrics
[`Assignment-2/`](Assignment-2)

- **Q1 — TF-IDF & Jaccard ranked retrieval:** a custom inverted index plus TF-IDF scoring and Jaccard similarity for document ranking.
- **Q2 — Naive Bayes text classification:** BBC News dataset, comparing TF-ICF, TF-IDF-ICF, and TF-IDF weighting schemes — the best model reaches ~97.9% test accuracy, with full precision/recall/F1 and confusion-matrix reporting.
- **Q3 — DCG/NDCG:** ranking-quality metrics computed on the Microsoft Learning-to-Rank dataset.

## Assignment 3 — Graph Analysis & Link Ranking
[`Assignment3/`](Assignment3)

Degree distribution and local clustering-coefficient analysis on the Wiki-Vote dataset (7,115 nodes, ~103K edges), plus PageRank and HITS (hub/authority) implemented manually with convergence-error plots.

## Notes

- Each assignment folder includes the notebook(s) plus a PDF report explaining methodology and results in more depth.
- Precomputed index/model artifacts (`.pickle` files) are checked in alongside the notebooks that produce them.
