# Morphology

## What is morphology?

Morphology is the study of how words are formed and how their internal structure conveys meaning.

Many languages build words by combining roots, prefixes, suffixes, infixes, and other grammatical elements. These patterns influence how AI systems tokenize text, learn embeddings, retrieve information, and generate language.

Understanding morphology is essential for building multilingual AI systems that perform well across diverse languages, language families, writing systems, and resource levels.

---

## Why does morphology matter?

Morphology influences nearly every stage of a modern AI pipeline.

Applications include:

- Tokenization
- Embeddings
- Information retrieval
- Retrieval-Augmented Generation (RAG)
- Machine translation
- Text generation
- Named Entity Recognition (NER)
- Semantic search
- Cross-lingual retrieval
- Multilingual AI systems

Morphologically rich languages often produce many surface forms for a single lemma, creating unique engineering challenges for tokenization, retrieval, evaluation, and inference.

---

## Questions I want to explore

- Why are morphologically rich languages challenging for language models?
- How does morphology affect tokenization?
- How do embedding models represent inflected words?
- How does morphology influence retrieval quality?
- How does morphology affect Retrieval-Augmented Generation (RAG)?
- How do multilingual models generalize across related languages?
- How does language contact influence morphological variation?
- Which tokenization algorithms perform best for agglutinative languages?
- How should multilingual AI systems be evaluated on morphologically rich languages?
- How should AI systems support Indigenous and endangered languages with limited training data?

---

## Common morphological processes

### Inflection

Inflection changes the grammatical form of a word without changing its core meaning.

Examples include:

- Case
- Number
- Gender
- Person
- Tense
- Mood

Questions to explore:

- How many inflected forms can a Finnish noun have?
- How do multilingual models learn inflectional patterns?
- How does inflection influence retrieval quality?

---

### Derivation

Derivation creates new words by adding prefixes or suffixes that change meaning or grammatical category.

Questions to explore:

- How well do embedding models represent derived words?
- Can multilingual models generalize derivational patterns?
- How does derivation influence semantic similarity?

---

### Compounding

Compounding combines multiple words into a single lexical item.

Common examples occur in:

- Dutch
- German
- Swedish
- Norwegian
- Finnish

Questions to explore:

- How do tokenizers segment compound words?
- How do embeddings represent compound words?
- How does compound splitting affect retrieval?

---

### Agglutination

Agglutinative languages build words by attaching multiple grammatical suffixes in sequence.

Examples include:

- Finnish
- Estonian
- Karelian
- North Sámi
- Turkish
- Azerbaijani
- Hungarian

Questions to explore:

- How does agglutination affect tokenization?
- Which embedding models perform best on agglutinative languages?
- Does retrieval quality decrease as morphological complexity increases?

---

### Fusional morphology

Fusional languages often combine multiple grammatical meanings into a single ending.

Examples include:

- Russian
- Ukrainian
- Polish
- Slovenian

Questions to explore:

- How do transformer models represent fusional morphology?
- How does fusional morphology compare with agglutination?
- How does fusional morphology affect multilingual embeddings?

---

## Morphology across language families

### Uralic

Research languages:

- Finnish
- Estonian
- Karelian
- Meänkieli
- North Sámi

Characteristics:

- Rich case systems
- Agglutination
- Productive word formation
- Long word forms

---

### Germanic

Research languages:

- Dutch
- German
- Swedish
- Norwegian

Characteristics:

- Compound formation
- Derivation
- Moderate inflection

---

### Slavic

Research languages:

- Russian
- Ukrainian
- Polish

Characteristics:

- Rich case systems
- Verbal aspect
- Fusional morphology

---

### Turkic

Research languages:

- Turkish
- Azerbaijani

Characteristics:

- Agglutination
- Vowel harmony
- Long suffix chains

---

### Kartvelian

Research languages:

- Georgian

Characteristics:

- Complex verb morphology
- Rich agreement systems
- Extensive verbal inflection

---

## Engineering implications

Morphology directly affects modern AI systems.

Examples include:

- Token fragmentation
- Context window utilization
- Embedding quality
- Retrieval accuracy
- Chunking strategy
- Vector search
- RAG performance
- Inference cost
- Evaluation methodology

Understanding morphology helps explain why AI systems may perform differently across languages.

---

## Comparative case studies

| Comparison | Comparison type | Engineering question |
|------------|----------------|----------------------|
| Finnish ↔ Estonian | Closely related languages | How similar are their morphological representations? |
| Finnish ↔ Russian | Neighboring language families, different morphology | How do agglutinative and fusional systems affect multilingual AI? |
| Finnish ↔ Karelian | Low-resource language | Can multilingual models transfer morphological knowledge? |
| Finnish ↔ Meänkieli | Language contact | Does language contact influence morphological representations? |
| North Sámi ↔ Norwegian | Indigenous language support | How well do AI systems represent morphology across resource levels? |
| Russian ↔ Estonian | Language contact | How does contact influence multilingual representations? |
| Russian ↔ Latvian | Language contact | How does multilingual morphology influence retrieval? |
| Russian ↔ Azerbaijani | Cross-family language contact | How does morphology affect cross-lingual transfer? |
| Persian ↔ Azerbaijani | Cross-border multilingualism | How do different morphological systems interact? |
| Dutch ↔ German | Closely related languages | How do compound words influence multilingual models? |
| German ↔ Estonian | Historical language contact | Does long-term contact influence multilingual representations? |
| Russian ↔ Ukrainian | Closely related Slavic languages | How well do multilingual models generalize across similar morphological systems? |
| Turkish ↔ Azerbaijani | Closely related Turkic languages | How transferable are agglutinative representations? |
| Georgian ↔ Armenian | Neighboring language families | How do distinct morphological systems compare? |
| Russian ↔ Georgian | Neighboring language families | How do morphology and script jointly affect multilingual AI? |
| Azerbaijani ↔ Lezgin | Minority language contact | Can multilingual models capture language contact across different families? |

---

## Open questions

- Which embedding models best capture morphological information?
- Which tokenization algorithms perform best for agglutinative languages?
- How does morphology influence retrieval quality?
- How should morphology be incorporated into multilingual evaluation?
- How should AI systems support Indigenous and endangered languages?
- Which language comparisons best reveal the strengths and weaknesses of multilingual AI systems?

---

## References

(To be added.)