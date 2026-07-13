# Retrieval

Retrieval is one of the core capabilities of modern AI systems.

Rather than generating answers solely from model parameters, retrieval systems identify relevant information from external knowledge sources and incorporate it into downstream tasks such as search, question answering, Retrieval-Augmented Generation (RAG), recommendation systems, and AI agents.

Within the Multilingual Benchmark Explorer, retrieval is studied across multiple languages, writing systems, language families, and resource settings to better understand how multilingual AI systems access and rank information.

---

# Research questions

This repository investigates questions such as:

- How does retrieval performance vary across languages?
- How do writing systems influence retrieval quality?
- How does morphology affect semantic search?
- Which multilingual embedding models perform best?
- How should multilingual retrieval systems be evaluated?
- How does language relatedness influence cross-lingual retrieval?
- How does historical language contact influence multilingual retrieval?

---

# Retrieval architectures

Modern retrieval systems commonly include:

- lexical retrieval
- dense retrieval
- sparse retrieval
- hybrid retrieval
- neural retrieval
- reranking pipelines

Each approach has different strengths depending on the language, corpus, and application.

---

# Lexical retrieval

Traditional retrieval relies primarily on matching words or tokens.

Examples include:

- BM25
- TF-IDF
- inverted indexes

Advantages:

- fast
- interpretable
- effective for exact terminology

Challenges:

- vocabulary mismatch
- morphology
- multilingual search
- synonym handling

---

# Dense retrieval

Dense retrieval represents documents and queries as vector embeddings.

Advantages include:

- semantic similarity
- multilingual search
- synonym matching
- robust cross-lingual retrieval

Representative embedding models include:

- multilingual-e5
- BGE
- GTE
- Jina embeddings
- multilingual Sentence Transformers

---

# Hybrid retrieval

Many production AI systems combine lexical and dense retrieval.

Potential pipeline:

```
Query
   ↓
Lexical Retrieval
   ↓
Dense Retrieval
   ↓
Hybrid Ranking
   ↓
Reranker
   ↓
LLM
```

Hybrid systems often outperform either approach used independently.

---

# Cross-lingual retrieval

One of the most important areas of multilingual AI.

Research questions include:

- Can a query written in one language retrieve documents written in another?
- Which multilingual embedding models best support cross-lingual retrieval?
- How does retrieval differ between related and unrelated languages?
- How much does language contact influence retrieval quality?

Example comparisons:

- Finnish ↔ Estonian
- Finnish ↔ Russian
- Dutch ↔ German
- Russian ↔ Ukrainian
- Azerbaijani ↔ Turkish
- North Sámi ↔ Norwegian

---

# Factors influencing retrieval

Retrieval performance depends on many linguistic characteristics, including:

- morphology
- writing system
- tokenization
- vocabulary overlap
- orthographic variation
- language relatedness
- historical language contact
- corpus size
- training data availability

These factors are explored throughout the repository using comparative multilingual experiments.

---

# Evaluation

Common retrieval metrics include:

- Recall@K
- Precision@K
- Mean Reciprocal Rank (MRR)
- nDCG
- Hit Rate
- latency
- throughput

Evaluation should consider both retrieval accuracy and system performance.

---

# Example datasets

Potential datasets include:

- MIRACL
- BEIR
- Mr. TyDi
- MKQA
- XOR QA
- MASSIVE
- FLORES-200
- OPUS

Additional datasets may be incorporated as the repository evolves.

---

# Future experiments

Potential investigations include:

- Compare dense retrieval across language families.
- Measure retrieval quality for morphologically rich languages.
- Compare lexical and dense retrieval for Finnish compounds.
- Evaluate multilingual retrieval across related languages.
- Compare retrieval across languages with historical language contact.
- Compare retrieval performance for underrepresented languages.
- Visualize multilingual embedding neighborhoods used for retrieval.
- Benchmark multilingual reranking models.

---

# Repository connections

General concepts:

- `embeddings.md`
- `tokenization.md`
- `evaluation.md`
- `retrieval-augmented-generation.md`

Comparative methodology:

- `comparative-methodology.md`
- `language-families.md`
- `language-contact.md`
- `underrepresented-languages.md`

Language-specific case studies:

See the individual language profiles in `docs/languages/` for language-specific retrieval considerations.