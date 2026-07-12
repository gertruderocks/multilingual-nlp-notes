# Russian

## Why Russian matters for AI

Russian is one of the most widely represented Slavic languages in multilingual AI datasets and serves as an important benchmark for evaluating morphologically rich languages written in the Cyrillic script.

Russian provides useful comparisons with both closely related Slavic languages and neighboring non-Slavic languages such as Finnish, Estonian, and Turkic languages.

---

## AI relevance

- multilingual language models
- cross-script evaluation
- retrieval across Cyrillic and Latin
- multilingual embeddings
- machine translation
- named entity recognition
- information retrieval

---

## Language family

Indo-European

→ Balto-Slavic

→ Slavic

→ East Slavic

Related languages include:

- Ukrainian
- Belarusian

Useful comparison languages

- Polish
- Czech
- Slovak
- Bulgarian

---

## Writing system

- Cyrillic alphabet
- relatively phonemic orthography
- capitalization rules
- punctuation differences
- Unicode considerations

Possible experiments

- tokenization of Cyrillic text
- multilingual retrieval across scripts
- normalization

---

## Morphology

Russian exhibits rich inflectional morphology.

Topics to investigate

- noun declension
- verbal aspect
- case system
- agreement
- derivational morphology

Research questions

- How much morphology survives subword tokenization?
- How do embeddings represent inflected forms?

---

## Tokenization

Questions

- Does BPE fragment Russian more than English?
- How are prefixes and suffixes segmented?
- What happens with long compound technical terms?

Possible comparisons

- Russian vs Finnish
- Russian vs Polish
- Russian vs English

---

## Embeddings

Research questions

- nearest-neighbor inspection
- semantic similarity
- analogy tests
- cross-lingual alignment

---

## Retrieval

Questions

- retrieval in Cyrillic
- transliterated search
- multilingual RAG
- cross-language retrieval

---

## Translation

Interesting comparisons

Russian ↔ English

Russian ↔ Finnish

Russian ↔ Estonian

Russian ↔ Turkish

---

## Language resources

Possible future additions

- spaCy
- Hugging Face models
- OPUS
- Wikipedia
- Universal Dependencies
- Common Crawl

---

## Example datasets

Future work

- XNLI
- FLORES
- MASSIVE
- MIRACL
- BEIR
- Universal Dependencies

---

## Interesting research papers

Future bibliography

---

## Future experiments

- Compare tokenization with Finnish.
- Compare embeddings with Ukrainian.
- Measure multilingual retrieval performance.
- Compare Cyrillic and Latin retrieval.
- Evaluate multilingual LLM reasoning.