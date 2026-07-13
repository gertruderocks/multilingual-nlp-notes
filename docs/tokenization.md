# Tokenization

Tokenization is one of the foundational components of modern AI systems.

Before a language model can represent meaning through embeddings or perform reasoning, text must first be converted into tokens. The quality of tokenization directly influences model efficiency, vocabulary coverage, retrieval performance, translation quality, and downstream AI tasks.

Within the Multilingual Benchmark Explorer, tokenization is studied across language families, writing systems, morphological types, and resource settings to better understand how modern multilingual AI systems process human language.

---

# Research questions

This repository investigates questions such as:

- How do different tokenizers segment morphologically rich languages?
- Which tokenization strategies work best across language families?
- How do writing systems influence tokenization?
- How does tokenization affect multilingual embeddings?
- How does tokenization influence retrieval performance?
- How well do multilingual tokenizers support underrepresented languages?
- How does historical language contact influence tokenizer vocabularies?

---

# What is tokenization?

Tokenization converts raw text into smaller units that language models can process.

These units may include:

- characters
- bytes
- subwords
- words
- phrases

Modern LLMs primarily rely on subword tokenization because it balances vocabulary size with the ability to represent previously unseen words.

---

# Common tokenization algorithms

Representative approaches include:

- Byte Pair Encoding (BPE)
- SentencePiece
- WordPiece
- Unigram Language Model
- Byte-level BPE

Different tokenizers often produce substantially different segmentations for the same text.

---

# Why tokenization matters

Tokenization influences many downstream AI capabilities, including:

- embeddings
- semantic search
- Retrieval-Augmented Generation (RAG)
- multilingual retrieval
- translation
- summarization
- reasoning
- inference cost

Poor tokenization can increase sequence length, fragment meaningful morphemes, and reduce model efficiency.

---

# Morphology and tokenization

Morphological complexity is one of the most important factors influencing tokenization.

Potential comparisons include:

- Finnish
- Estonian
- Meänkieli
- North Sámi
- Turkish
- Azerbaijani
- Russian
- Dutch

Research questions include:

- Which languages produce the greatest token fragmentation?
- Which morphological structures are preserved?
- Which tokenizers best represent productive morphology?

---

# Writing systems

Writing systems also influence tokenizer behavior.

Potential investigations include:

- Latin alphabet
- Cyrillic
- historical orthographies
- diacritics
- Unicode normalization

Research questions include:

- How does script influence vocabulary efficiency?
- How are multilingual vocabularies shared across scripts?
- How do tokenizers handle orthographic variation?

---

# Comparative multilingual analysis

Rather than evaluating tokenizers using only aggregate statistics, this repository investigates why tokenization differs across languages.

Potential comparisons include:

- Finnish ↔ Estonian
- Finnish ↔ Russian
- Dutch ↔ German
- Russian ↔ Ukrainian
- Azerbaijani ↔ Turkish
- North Sámi ↔ Norwegian

These comparisons explore:

- language family relationships
- language contact
- morphology
- writing systems
- vocabulary overlap
- resource availability

---

# Tokenization metrics

Potential evaluation methods include:

- average tokens per word
- token fragmentation
- vocabulary coverage
- unknown token frequency
- sequence length
- compression ratio
- tokenizer efficiency

These metrics help explain downstream model behavior.

---

# Example datasets

Potential datasets include:

- FLORES-200
- MASSIVE
- Universal Dependencies
- OPUS
- OSCAR
- Wikipedia
- Common Crawl

Additional datasets may be incorporated as the repository evolves.

---

# Future experiments

Potential investigations include:

- Compare BPE and SentencePiece across language families.
- Measure token fragmentation for morphologically rich languages.
- Compare tokenizer efficiency across writing systems.
- Evaluate multilingual tokenizer vocabularies.
- Compare tokenization for related and unrelated languages.
- Analyze tokenizer behavior for underrepresented languages.
- Visualize token boundaries across languages.
- Build an interactive tokenizer comparison dashboard.

---

# Repository connections

General concepts:

- `embeddings.md`
- `retrieval.md`
- `retrieval-augmented-generation.md`
- `evaluation.md`

Comparative methodology:

- `comparative-methodology.md`
- `language-families.md`
- `language-contact.md`
- `underrepresented-languages.md`

Language-specific case studies:

See the individual language profiles in `docs/languages/` for language-specific tokenization considerations.