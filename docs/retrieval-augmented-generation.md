# Retrieval-Augmented Generation (RAG)

## What is Retrieval-Augmented Generation?

Retrieval-Augmented Generation (RAG) combines information retrieval with large language models.

Rather than relying only on knowledge stored in model parameters, a RAG system retrieves relevant information from an external knowledge source and provides it to the language model before generating a response.

This architecture allows AI systems to answer questions using current, domain-specific, or private information while reducing hallucinations and improving transparency.

RAG has become one of the foundational architectures for modern AI applications.

---

## Why does RAG matter?

Retrieval-Augmented Generation enables language models to reason over information that exists outside the model itself.

Applications include:

- Enterprise AI assistants
- Knowledge management
- Technical documentation
- Customer support
- Internal company copilots
- Semantic search
- Question answering
- Multilingual AI systems

Well-designed RAG systems improve answer quality, reduce hallucinations, and allow knowledge bases to evolve without retraining the language model.

---

## Questions I want to explore

- How does retrieval quality influence answer quality?
- Which embedding models produce the strongest multilingual RAG systems?
- How should multilingual RAG systems be evaluated?
- How does tokenization influence multilingual retrieval?
- How does morphology influence RAG performance?
- How do writing systems influence multilingual RAG?
- How does language contact influence multilingual retrieval?
- How should AI systems support Indigenous and endangered languages?
- Which language comparisons best reveal strengths and weaknesses in multilingual RAG?

---

# RAG pipeline

A modern Retrieval-Augmented Generation system consists of multiple interconnected components.

```text
Documents
      ↓
Chunking
      ↓
Tokenization
      ↓
Embeddings
      ↓
Vector Database
      ↓
Retrieval
      ↓
(Optional) Reranking
      ↓
Large Language Model
      ↓
Evaluation
```

Each component influences downstream system performance.

---

## Documents

The knowledge base contains the information available to the AI system.

Examples include:

- Technical documentation
- Wikis
- Research papers
- PDFs
- Product manuals
- Internal company documentation

Questions to explore:

- How should multilingual documents be organized?
- How should multilingual knowledge bases be maintained?
- How should document quality be evaluated?

---

## Chunking

Large documents are divided into smaller chunks before indexing.

Chunk size influences retrieval quality, latency, context utilization, and answer quality.

Questions to explore:

- What chunk size performs best?
- How should chunk size vary across languages?
- How does morphology influence chunk boundaries?

---

## Tokenization

Each chunk is tokenized before being processed by the embedding model.

Questions to explore:

- How do different tokenizers influence multilingual RAG?
- Which languages experience the greatest token fragmentation?
- How does tokenization affect inference cost?

---

## Embeddings

Each document chunk is converted into a vector representation.

Questions to explore:

- Which embedding models perform best for multilingual RAG?
- How well do multilingual embeddings transfer across language families?
- How do embeddings influence retrieval quality?

---

## Vector databases

Embedding vectors are stored in a vector database for efficient similarity search.

Topics to explore:

- Approximate nearest neighbor search
- Indexing strategies
- Metadata filtering
- Hybrid search
- Scalability

Questions to explore:

- Which indexing strategies provide the best tradeoffs?
- How do vector databases influence latency?

---

## Retrieval

Relevant document chunks are retrieved using semantic similarity or hybrid retrieval.

Questions to explore:

- How many chunks should be retrieved?
- How should multilingual retrieval be evaluated?
- When does hybrid retrieval outperform semantic retrieval?

---

## Reranking

Many production RAG systems rerank retrieved documents before generation.

Questions to explore:

- When does reranking improve answer quality?
- Which reranking models work best for multilingual retrieval?
- How much latency does reranking introduce?

---

## Generation

The language model combines retrieved context with the user's query to generate a response.

Questions to explore:

- How much retrieved context improves answer quality?
- When does too much context become harmful?
- How should prompts be designed for multilingual RAG?

---

## Evaluation

Evaluation should consider the complete RAG system rather than only retrieval accuracy.

Examples include:

- Recall@K
- Mean Reciprocal Rank (MRR)
- nDCG
- Precision
- Faithfulness
- Groundedness
- Answer relevance
- Context precision
- Context recall

Questions to explore:

- Which metrics best evaluate multilingual RAG?
- Which metrics correlate most closely with user satisfaction?

---

## Engineering considerations

Production RAG systems require balancing multiple engineering tradeoffs.

Examples include:

- Retrieval quality
- Latency
- Cost
- Context window utilization
- Chunk size
- Embedding model selection
- Vector database choice
- Reranking
- Prompt design
- Scalability

No single configuration is optimal for every application.

---

## Engineering implications

Every component in the RAG pipeline influences downstream system behavior.

Examples include:

- Tokenization influences embeddings.
- Embeddings influence retrieval.
- Retrieval influences answer quality.
- Chunking influences context utilization.
- Reranking influences precision.
- Prompt design influences generation.
- Evaluation influences future system improvements.

Thinking about RAG as an interconnected system rather than a collection of independent components leads to better engineering decisions.

---

## Comparative case studies

| Comparison | Comparison type | Engineering question |
|------------|----------------|----------------------|
| Finnish ↔ Russian | Neighboring language families, different scripts | How does morphology influence multilingual RAG? |
| Finnish ↔ Estonian | Closely related languages | Does language relatedness improve multilingual retrieval? |
| Finnish ↔ Karelian | Low-resource language | Can multilingual RAG transfer effectively to low-resource languages? |
| Finnish ↔ Meänkieli | Language contact | Can RAG capture language contact and lexical borrowing? |
| North Sámi ↔ Norwegian | Indigenous language support | How well can multilingual RAG support Indigenous languages? |
| Russian ↔ Estonian | Language contact | How does multilingual RAG perform across neighboring language families? |
| Russian ↔ Latvian | Language contact | How does multilingual RAG support multilingual societies? |
| Russian ↔ Azerbaijani | Regional multilingualism | How well does multilingual RAG transfer across language families? |
| Persian ↔ Azerbaijani | Cross-border multilingualism | How should multilingual RAG support bilingual communities? |
| Dutch ↔ German | Closely related languages | Does lexical similarity improve multilingual retrieval? |
| German ↔ Estonian | Historical language contact | How does historical language contact influence multilingual retrieval? |
| Russian ↔ Ukrainian | Closely related Slavic languages | How well do multilingual RAG systems generalize across similar languages? |
| Turkish ↔ Azerbaijani | Closely related Turkic languages | How transferable are multilingual RAG representations? |
| Georgian ↔ Armenian | Neighboring language families | How well does multilingual RAG generalize across distinct language families? |
| Russian ↔ Georgian | Neighboring language families | How do language family and script differences influence multilingual RAG? |
| Azerbaijani ↔ Lezgin | Minority language contact | How well can multilingual RAG support minority languages? |

---

## Future experiments

Examples include:

- Build a multilingual RAG system for Finnish and Estonian
- Compare multilingual RAG across related language families
- Evaluate multilingual RAG for Indigenous languages
- Compare E5, BGE, and OpenAI embeddings
- Compare hybrid retrieval and semantic retrieval
- Investigate reranking strategies
- Compare chunking strategies across morphologically rich languages
- Measure latency versus retrieval quality
- Evaluate multilingual RAG on enterprise documentation

---

## Open questions

- Which embedding models produce the strongest multilingual RAG systems?
- Which engineering decisions have the greatest impact on answer quality?
- How should multilingual RAG systems support low-resource and Indigenous languages?
- How should multilingual RAG systems be evaluated fairly?
- Which language comparisons best reveal weaknesses in multilingual RAG?
- Which tradeoffs matter most in production AI systems?

---

## References

(To be added.)