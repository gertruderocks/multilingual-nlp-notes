# Retrieval

## What is retrieval?

Retrieval is the process of finding the most relevant information for a given query.

Modern AI systems often retrieve documents, passages, or structured knowledge before generating a response. Rather than relying only on information stored in model parameters, retrieval allows AI systems to access external knowledge that can be updated independently of the model.

Retrieval is a core component of search engines, enterprise search, Retrieval-Augmented Generation (RAG), recommendation systems, question answering, and multilingual AI.

---

## Why does retrieval matter?

Retrieval enables AI systems to find relevant information efficiently while improving accuracy, transparency, and factual grounding.

Applications include:

- Search engines
- Semantic search
- Enterprise search
- Information retrieval
- Question answering
- Retrieval-Augmented Generation (RAG)
- Recommendation systems
- Knowledge management
- Multilingual search
- AI assistants

Well-designed retrieval systems improve answer quality, reduce hallucinations, and allow language models to work with continuously changing information.

---

## Questions I want to explore

- How does multilingual retrieval differ from monolingual retrieval?
- Which embedding models produce the strongest retrieval performance?
- How does morphology influence retrieval quality?
- How does tokenization affect retrieval performance?
- How does language contact influence multilingual retrieval?
- How do writing systems influence retrieval quality?
- How should multilingual retrieval systems be evaluated?
- How should AI systems retrieve information for Indigenous and endangered languages?
- Which language comparisons best reveal the strengths and weaknesses of multilingual retrieval systems?

---

## Retrieval approaches

### Keyword retrieval

Keyword retrieval matches documents using exact words or phrases.

Traditional search engines commonly use approaches such as TF-IDF or BM25.

Strengths:

- Fast
- Explainable
- Strong lexical precision

Limitations:

- Sensitive to vocabulary mismatch
- Limited semantic understanding

Questions to explore:

- When does keyword retrieval outperform semantic retrieval?
- Which languages benefit most from keyword search?

---

### Semantic retrieval

Semantic retrieval uses embeddings to retrieve documents based on meaning rather than exact word matches.

This allows semantically related documents to be retrieved even when different vocabulary is used.

Strengths:

- Captures semantic similarity
- Supports multilingual retrieval
- Handles vocabulary variation

Limitations:

- Depends on embedding quality
- More computationally expensive

Questions to explore:

- Which embedding models produce the strongest multilingual retrieval?
- How does semantic retrieval perform across language families?

---

### Hybrid retrieval

Hybrid retrieval combines keyword retrieval with semantic retrieval.

Many production AI systems use hybrid retrieval because it balances lexical precision with semantic understanding.

Questions to explore:

- When does hybrid retrieval outperform semantic retrieval?
- How should hybrid retrieval systems be evaluated?

---

### Cross-lingual retrieval

Cross-lingual retrieval allows users to search in one language while retrieving documents written in another.

This capability is increasingly important for multilingual AI systems.

Questions to explore:

- How well do multilingual embeddings support cross-lingual retrieval?
- Which language pairs transfer most effectively?
- How does language relatedness influence retrieval quality?

---

## Common retrieval architectures

Modern AI systems often combine multiple retrieval components.

Examples include:

- Dense retrieval
- Sparse retrieval
- Hybrid retrieval
- Multi-stage retrieval
- Reranking pipelines

Questions to explore:

- When should reranking be introduced?
- What are the tradeoffs between retrieval quality and latency?

---

## Engineering considerations

Retrieval quality depends on many interconnected design decisions.

Important factors include:

- Tokenization
- Embedding model
- Chunk size
- Chunk overlap
- Metadata
- Indexing strategy
- Vector database
- Distance metric
- Reranking
- Context window size

Understanding these tradeoffs is essential for production AI systems.

---

## Engineering implications

Retrieval decisions influence downstream AI behavior.

Examples include:

- Answer quality
- Hallucination rate
- Latency
- Inference cost
- Context utilization
- User experience
- Scalability
- Production reliability

Retrieval should therefore be evaluated as part of the complete AI system rather than as an isolated component.

---

## Common evaluation metrics

### Recall@K

Measures whether relevant documents appear within the top K retrieved results.

Questions to explore:

- Which values of K are most informative?
- How does Recall@K vary across language families?

---

### Mean Reciprocal Rank (MRR)

Measures how highly the first relevant document appears in ranked retrieval results.

Questions to explore:

- How should MRR be interpreted for multilingual retrieval?
- Which retrieval systems consistently achieve higher MRR?

---

### Normalized Discounted Cumulative Gain (nDCG)

Measures both document relevance and ranking quality.

Questions to explore:

- Why is nDCG useful for multilingual retrieval?
- How does nDCG compare with Recall@K and MRR?

---

## Comparative case studies

| Comparison | Comparison type | Engineering question |
|------------|----------------|----------------------|
| Finnish ↔ Russian | Neighboring language families, different scripts | How does morphology influence multilingual retrieval? |
| Finnish ↔ Estonian | Closely related languages | Does language relatedness improve retrieval? |
| Finnish ↔ Karelian | Low-resource language | Can multilingual retrieval transfer effectively to low-resource languages? |
| Finnish ↔ Meänkieli | Language contact | Can retrieval capture lexical borrowing and language contact? |
| North Sámi ↔ Norwegian | Indigenous language support | How well do multilingual retrieval systems support Indigenous languages? |
| Russian ↔ Estonian | Language contact | How does multilingual retrieval perform across neighboring language families? |
| Russian ↔ Latvian | Language contact | How does multilingual retrieval behave in multilingual societies? |
| Russian ↔ Azerbaijani | Regional multilingualism | Can multilingual retrieval transfer across language families? |
| Persian ↔ Azerbaijani | Cross-border multilingualism | How does multilingual retrieval perform across bilingual communities? |
| Dutch ↔ German | Closely related languages | Does lexical similarity improve retrieval quality? |
| German ↔ Estonian | Historical language contact | How does historical language contact influence retrieval? |
| Russian ↔ Ukrainian | Closely related Slavic languages | How effectively do multilingual models transfer retrieval knowledge? |
| Turkish ↔ Azerbaijani | Closely related Turkic languages | How transferable are multilingual retrieval representations? |
| Georgian ↔ Armenian | Neighboring language families | How well do multilingual retrieval systems generalize across unrelated neighboring languages? |
| Russian ↔ Georgian | Neighboring language families | How do language family and script differences influence retrieval? |
| Azerbaijani ↔ Lezgin | Minority language contact | How well do multilingual retrieval systems support minority languages? |

---

## Future experiments

Examples include:

- Compare BM25 and semantic retrieval
- Compare E5, BGE, and OpenAI embeddings
- Evaluate multilingual retrieval across language families
- Measure retrieval quality for morphologically rich languages
- Compare retrieval performance for closely related and unrelated languages
- Investigate multilingual retrieval for Indigenous languages
- Evaluate hybrid retrieval versus semantic retrieval
- Compare reranking strategies across multilingual datasets

---

## Open questions

- Which embedding model produces the strongest multilingual retrieval?
- How much does morphology influence retrieval quality?
- Which language comparisons reveal weaknesses in multilingual retrieval?
- How should multilingual retrieval systems be evaluated fairly?
- How should AI systems support low-resource and Indigenous languages?
- How should retrieval be optimized for production AI systems?

---

## References

(To be added.)