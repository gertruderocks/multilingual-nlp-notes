# Tokenization

## What is tokenization?

Tokenization is the process of breaking text into smaller units called tokens.

Large language models do not process raw text directly. Instead, they operate on sequences of tokens, making tokenization one of the foundational components of modern AI systems.

The design of a tokenizer influences model performance, multilingual capabilities, inference cost, context utilization, and downstream AI behavior.

---

## Why does tokenization matter?

Tokenization affects nearly every stage of a modern AI pipeline.

Applications include:

- Large Language Models (LLMs)
- Embeddings
- Semantic search
- Information retrieval
- Retrieval-Augmented Generation (RAG)
- Machine translation
- Text generation
- AI agents
- Multilingual AI systems

Languages differ dramatically in morphology, writing systems, and vocabulary, making tokenization one of the most important challenges in multilingual AI.

---

## Questions I want to explore

- Why is Finnish an interesting tokenization case study?
- How do BPE, WordPiece, SentencePiece, and Unigram differ?
- How do tokenizers handle compound words?
- How does morphology influence tokenization?
- How do different writing systems influence tokenization?
- How does tokenization influence embeddings?
- How does tokenization influence retrieval quality?
- How does tokenization influence RAG?
- How should tokenization be evaluated?
- How should tokenizers support Indigenous and endangered languages?

---

## Common tokenization algorithms

### Byte Pair Encoding (BPE)

Byte Pair Encoding (BPE) is a subword tokenization algorithm originally developed for data compression and later adapted for NLP.

It begins with individual characters and repeatedly merges the most frequent adjacent pairs until a target vocabulary size is reached.

BPE is widely used because it balances vocabulary size with the ability to represent previously unseen words.

Examples include:

- GPT-2
- Many GPT-family models

Questions to explore:

- How does vocabulary size influence BPE?
- How well does BPE support morphologically rich languages?

---

### WordPiece

WordPiece was developed by Google and popularized through BERT.

Rather than selecting merges based only on frequency, WordPiece optimizes vocabulary using a likelihood-based objective.

Questions to explore:

- How does WordPiece differ from BPE?
- Which languages benefit most from WordPiece?

---

### SentencePiece

SentencePiece is a language-independent tokenizer that operates directly on raw text rather than relying on whitespace.

This makes it particularly useful for multilingual AI systems.

Questions to explore:

- Why is SentencePiece well suited for multilingual models?
- How does SentencePiece perform on morphologically rich languages?

---

### Unigram Language Model

The Unigram Language Model begins with a large vocabulary and removes tokens that contribute least to the probability of the training data.

Unlike BPE, vocabulary optimization is probabilistic rather than greedy.

Questions to explore:

- When does Unigram outperform BPE?
- Which languages benefit from probabilistic tokenization?

---

## Engineering considerations

Tokenization decisions influence many downstream AI components.

Important considerations include:

- Vocabulary size
- Token fragmentation
- Writing systems
- Morphological complexity
- Context window utilization
- Embedding quality
- Retrieval quality
- Inference cost
- Latency

Understanding these relationships is essential when designing multilingual AI systems.

---

## Architectural tradeoffs

Modern tokenization systems require balancing competing engineering priorities.

| Tradeoff | Questions to explore |
|----------|----------------------|
| Character-level vs subword tokenization | Which approach generalizes better across languages? |
| BPE vs WordPiece | How do different merge strategies influence multilingual performance? |
| BPE vs SentencePiece | Which tokenizer performs better across writing systems? |
| SentencePiece vs Unigram | When does probabilistic vocabulary optimization improve results? |
| Large vocabulary vs small vocabulary | How does vocabulary size influence efficiency and generalization? |
| Longer tokens vs shorter tokens | How do token lengths affect context utilization? |
| Language-specific tokenizers vs multilingual tokenizers | When should a shared tokenizer be preferred? |

Good engineering requires understanding these tradeoffs rather than searching for a universally best tokenizer.

---

## Engineering implications

Tokenization influences every downstream stage of a modern AI system.

Examples include:

- Embedding quality
- Semantic similarity
- Retrieval quality
- Chunking strategy
- Context window utilization
- Hallucination rate
- Latency
- Inference cost
- Evaluation methodology

Poor tokenization decisions propagate throughout the entire AI pipeline.

---

## Comparative case studies

| Comparison | Comparison type | Engineering question |
|------------|----------------|----------------------|
| Finnish ↔ Russian | Neighboring language families, different scripts | How do morphology and writing systems influence tokenization? |
| Finnish ↔ Estonian | Closely related languages | Does language relatedness improve tokenization efficiency? |
| Finnish ↔ Karelian | Low-resource language | Can multilingual tokenizers generalize to low-resource languages? |
| Finnish ↔ Meänkieli | Language contact | How does lexical similarity influence tokenization? |
| North Sámi ↔ Norwegian | Indigenous language support | How well do multilingual tokenizers support Indigenous languages? |
| Russian ↔ Estonian | Language contact | How do tokenizers perform across neighboring language families? |
| Russian ↔ Latvian | Language contact | How should multilingual tokenizers support multilingual societies? |
| Russian ↔ Azerbaijani | Regional multilingualism | How do tokenizers perform across different language families? |
| Persian ↔ Azerbaijani | Cross-border multilingualism | How should multilingual tokenizers handle bilingual communities? |
| Dutch ↔ German | Closely related languages | How should tokenizers segment compound words? |
| German ↔ Estonian | Historical language contact | How does language contact influence multilingual tokenization? |
| Russian ↔ Ukrainian | Closely related Slavic languages | How well do multilingual tokenizers transfer across similar languages? |
| Turkish ↔ Azerbaijani | Closely related Turkic languages | How does agglutination influence tokenization? |
| Georgian ↔ Armenian | Neighboring language families | How do writing systems influence tokenization? |
| Russian ↔ Georgian | Neighboring language families | How do script differences influence multilingual tokenization? |
| Azerbaijani ↔ Lezgin | Minority language contact | How should multilingual tokenizers support minority languages? |

---

## Future experiments

Examples include:

- Compare BPE, WordPiece, SentencePiece, and Unigram.
- Measure token counts across language families.
- Compare tokenization efficiency for morphologically rich languages.
- Investigate token fragmentation across writing systems.
- Compare multilingual and language-specific tokenizers.
- Measure tokenization effects on retrieval quality.
- Evaluate tokenization strategies for Indigenous languages.
- Compare tokenizer performance across multilingual benchmarks.

---

## Open questions

- Which tokenizer performs best across language families?
- How should tokenization be evaluated?
- Which languages remain difficult for current tokenizers?
- How should multilingual tokenizers support low-resource languages?
- How should tokenization evolve as context windows become larger?
- What new tokenization approaches might emerge for future AI systems?

---

## References

(To be added.)