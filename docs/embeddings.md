# Embeddings

## What are embeddings?

Embeddings are numerical vector representations of text that capture semantic meaning. Instead of representing words or sentences as discrete symbols, embedding models map them into a high-dimensional vector space where semantically similar concepts are located near one another.

Embeddings are a fundamental building block of modern NLP systems and power applications such as semantic search, Retrieval-Augmented Generation (RAG), clustering, recommendation systems, and multilingual retrieval.

Understanding embeddings is essential for modern AI engineering because they provide the foundation for semantic search, Retrieval-Augmented Generation (RAG), recommendation systems, multilingual retrieval, and many other AI applications.

---

## Why do embeddings matter?

Embeddings allow AI systems to compare meaning rather than exact words.

Applications include:

- Semantic search
- Information retrieval
- Question answering
- Retrieval-Augmented Generation (RAG)
- Recommendation systems
- Text clustering
- Duplicate detection
- Cross-lingual retrieval
- Multilingual AI systems

---

## Questions I want to explore

- How well do multilingual embeddings transfer across related languages?
- How similar are Finnish and Karelian in multilingual embedding space?
- How closely are Finnish and Meänkieli represented?
- Can multilingual embeddings capture language contact and lexical borrowing?
- How do embeddings compare across different language families?
- How well do embedding models support low-resource languages?
- How should multilingual embedding models be evaluated?
- How do different embedding models compare on multilingual retrieval tasks?
- How do different writing systems influence multilingual embedding quality?
- Which language pairs provide the most informative multilingual comparisons?

---

## Common embedding models

### word2vec

word2vec was introduced by Google in 2013 and was one of the first widely adopted neural embedding models.

It learns vector representations by predicting neighboring words, allowing semantically similar words to occupy nearby locations in vector space.

Although newer embedding models have replaced word2vec for many applications, it remains an important foundation for understanding modern embeddings.

Questions to explore:

- How does word2vec differ from modern transformer embeddings?
- What are the limitations of static word embeddings?
- What lessons from word2vec remain relevant today?

---

### fastText

fastText extends word2vec by representing words as collections of character n-grams rather than treating each word as a completely independent token.

Because it incorporates subword information, fastText performs particularly well for morphologically rich languages and can generate embeddings for words that were not seen during training.

Questions to explore:

- Does fastText perform better for Finnish than word2vec?
- How well does fastText represent Karelian?
- How does subword modeling affect low-resource languages?
- Does fastText provide advantages for agglutinative languages?

---

### Sentence Transformers

Sentence Transformers generate embeddings for complete sentences or passages rather than individual words.

They are widely used for semantic search, clustering, retrieval, recommendation systems, and Retrieval-Augmented Generation (RAG).

Sentence embeddings allow entire documents to be compared using cosine similarity.

Questions to explore:

- How well do multilingual Sentence Transformers perform across language families?
- How should sentence embeddings be evaluated?
- How do multilingual sentence embeddings compare with monolingual models?

---

### E5

E5 (Embedding from Text Embeddings) is a family of embedding models optimized for retrieval tasks.

E5 models are trained using contrastive learning to place related queries and documents close together in embedding space.

They achieve strong performance on multilingual retrieval benchmarks.

Questions to explore:

- How does multilingual E5 compare with OpenAI embeddings?
- How well does E5 perform on Finnish retrieval tasks?
- How well does E5 support low-resource languages?

---

### BGE

BGE (BAAI General Embedding) is a family of embedding models developed by the Beijing Academy of Artificial Intelligence.

BGE models are designed for semantic search, retrieval, reranking, and multilingual applications.

Several BGE models achieve state-of-the-art performance on multilingual embedding benchmarks.

Questions to explore:

- How does BGE compare with E5?
- How does BGE perform across different language families?
- How does BGE compare on multilingual benchmarks such as MTEB?

---

### OpenAI embeddings

OpenAI provides general-purpose embedding models designed for semantic search, retrieval, clustering, recommendation systems, and Retrieval-Augmented Generation (RAG).

These models map text into high-dimensional vector spaces where semantically similar passages appear close together.

Questions to explore:

- How well do OpenAI embeddings support multilingual retrieval?
- How well are low-resource languages represented?
- How do OpenAI embeddings compare with open-source embedding models?

---

## Common similarity metrics

### Cosine similarity

Cosine similarity measures the angle between two embedding vectors.

It is one of the most widely used metrics for comparing semantic similarity between words, sentences, or documents.

Questions to explore:

- Why is cosine similarity preferred over Euclidean distance?
- How does cosine similarity behave across different languages?
- Which similarity metrics perform best for multilingual embeddings?

---

## Benchmarks

Examples include:

- MTEB (Massive Text Embedding Benchmark)
- MIRACL
- BEIR
- STS Benchmark
- XTREME

Questions to explore:

- Which benchmarks include low-resource languages?
- Which benchmarks include multilingual retrieval tasks?
- How should multilingual embedding models be compared fairly?
- Which benchmarks best reflect real-world multilingual applications?

---

## Comparative case studies

| Comparison | Research question |
|------------|-------------------|
| Finnish ↔ Estonian | How similar are their embedding spaces? |
| Finnish ↔ Karelian | How does language relatedness influence embeddings? |
| Finnish ↔ Meänkieli | Can embeddings capture language contact? |
| Dutch ↔ German | How does lexical similarity affect embedding quality? |
| Russian ↔ Ukrainian | How do embeddings represent closely related Slavic languages? |
| Turkish ↔ Azerbaijani | How well do embeddings transfer across closely related Turkic languages? |
| Georgian ↔ Armenian | How do neighboring languages from different language families compare? |
| Lezgin ↔ Azerbaijani | How does language contact influence multilingual embeddings? |

---

## Open questions

- Which embedding models perform best across language families?
- How should multilingual embedding quality be measured?
- Which multilingual benchmarks best reflect real-world performance?
- How do embeddings represent language contact?
- Which language pairs reveal the strengths and weaknesses of multilingual embedding models?

---

## References

(To be added.)