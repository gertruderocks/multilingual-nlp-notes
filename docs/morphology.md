# Morphology

Morphology studies how words are formed and how their internal structure conveys meaning.

For multilingual AI systems, morphology is far more than a linguistic concept—it directly influences tokenization, embeddings, retrieval, translation, language modeling, and overall system performance.

Within the Multilingual Benchmark Explorer, morphology is studied as one of the key variables that helps explain why multilingual AI systems behave differently across languages.

---

# Research questions

This repository investigates questions such as:

- How does morphology influence tokenization?
- Which multilingual models best support morphologically rich languages?
- How does morphology affect multilingual embeddings?
- How does morphology influence semantic retrieval?
- How well do multilingual LLMs generalize across different morphological systems?
- How should morphology be considered when evaluating multilingual AI?

---

# Why morphology matters

Morphology affects many downstream AI tasks, including:

- tokenization
- embeddings
- semantic search
- Retrieval-Augmented Generation (RAG)
- multilingual retrieval
- machine translation
- reasoning
- evaluation

Rich morphology often increases vocabulary diversity, introduces many surface forms for the same lexical item, and influences how efficiently language models represent meaning.

---

# What is morphology?

Morphology examines how meaningful units (morphemes) combine to form words.

These units include:

- roots
- prefixes
- suffixes
- infixes
- clitics
- compounds

Languages differ substantially in how they construct words, making morphology one of the defining challenges for multilingual NLP.

---

# Morphological typology

Languages can be grouped according to their dominant morphological characteristics.

## Analytic

Words contain relatively little inflection.

Examples include:

- English
- Mandarin Chinese

---

## Fusional

Single affixes often express multiple grammatical features simultaneously.

Examples include:

- Russian
- German
- Spanish
- Ukrainian

---

## Agglutinative

Words are formed by combining sequences of morphemes, with each morpheme typically expressing a single grammatical function.

Examples include:

- Finnish
- Estonian
- Meänkieli
- North Sámi
- Turkish
- Azerbaijani
- Hungarian

---

## Polysynthetic

Words may encode information that would require an entire sentence in many other languages.

These languages remain an important area for future multilingual AI research.

---

# Morphology and tokenization

Morphological structure strongly influences tokenizer behavior.

Research questions include:

- Which tokenizers preserve meaningful morphemes?
- Which languages experience the greatest token fragmentation?
- How does morphology influence sequence length?
- Which tokenization algorithms best support agglutinative languages?

---

# Morphology and embeddings

Embedding models must learn semantic representations despite potentially large numbers of word forms.

Research questions include:

- Can embeddings preserve relationships between inflected forms?
- How well do multilingual embeddings represent productive morphology?
- How closely are morphologically related words clustered?

---

# Morphology and retrieval

Morphology also affects multilingual retrieval.

Potential challenges include:

- inflectional variation
- derivational variation
- compound words
- lexical sparsity

Research questions include:

- Can dense retrieval overcome morphological variation?
- Which embedding models best support morphologically rich languages?
- How should multilingual retrieval systems evaluate inflected languages?

---

# Morphology case studies

The following languages illustrate different engineering challenges for multilingual AI systems.

Rather than ranking languages by complexity, these examples highlight opportunities for comparative experiments.

| Language | Research opportunities |
|----------|------------------------|
| Finnish | Compare BPE vs SentencePiece, measure compound fragmentation, evaluate embedding neighborhoods |
| Estonian | Compare tokenization with Finnish, investigate historical orthographic influence, evaluate multilingual retrieval |
| Meänkieli | Study language contact with Swedish, minority-language retrieval, multilingual embeddings |
| North Sámi | Evaluate multilingual transfer from Norwegian and Finnish, benchmark tokenizer performance |
| Erzya | Compare multilingual transfer from Finnish and Russian, investigate embedding alignment |
| Hungarian | Measure tokenizer efficiency for long agglutinative words |
| Russian | Evaluate fusional morphology, grammatical aspect, and cross-script retrieval |
| Dutch | Compare compound segmentation with German, evaluate multilingual educational AI |
| German | Investigate compound formation, multilingual embeddings, and retrieval |
| Turkish | Benchmark agglutinative tokenization and multilingual transfer |
| Azerbaijani | Compare multilingual embeddings with Turkish and investigate regional language contact |

---

# Comparative multilingual analysis

Rather than studying morphology in isolation, this repository investigates how morphological structure interacts with other factors that influence multilingual AI.

Comparative experiments may consider:

- language family relationships
- language contact
- writing systems
- tokenization
- embeddings
- retrieval
- resource availability

The objective is to understand which combinations of linguistic and computational factors best explain multilingual AI behavior.

---

# Measuring morphological effects

Potential evaluation approaches include:

- token fragmentation
- average tokens per word
- vocabulary coverage
- embedding similarity
- retrieval performance
- downstream task accuracy
- qualitative error analysis

Morphology should be evaluated through practical AI tasks rather than in isolation.

---

# Example datasets

Potential datasets include:

- Universal Dependencies
- FLORES-200
- OPUS
- MASSIVE
- XNLI
- OSCAR
- Wikipedia

Additional datasets may be incorporated as the repository evolves.

---

# Future experiments

Potential investigations include:

- Compare tokenizer efficiency across morphological types.
- Measure token fragmentation for agglutinative languages.
- Compare embedding quality across morphological systems.
- Evaluate multilingual retrieval for morphologically rich languages.
- Compare multilingual reasoning across different morphological typologies.
- Build an interactive morphology explorer.
- Visualize relationships between morphology and embedding quality.

---

# Repository connections

General concepts:

- `tokenization.md`
- `embeddings.md`
- `retrieval.md`
- `retrieval-augmented-generation.md`
- `evaluation.md`
- `multilingual-llms.md`

Comparative methodology:

- `comparative-methodology.md`
- `language-families.md`
- `language-contact.md`
- `underrepresented-languages.md`

Language-specific case studies:

See the individual language profiles in `docs/languages/` for language-specific morphological characteristics and AI engineering considerations.