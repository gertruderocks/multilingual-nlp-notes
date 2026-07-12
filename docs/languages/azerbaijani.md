# Azerbaijani

## Why Azerbaijani matters for AI

Azerbaijani provides an excellent case study for multilingual AI because it combines rich agglutinative morphology, language contact, and multiple writing systems. It also offers an opportunity to evaluate cross-lingual transfer between closely related Turkic languages, particularly Turkish.

Although less represented than English or Turkish, Azerbaijani helps measure how well multilingual AI systems generalize to moderately resourced languages.

---

## AI relevance

Azerbaijani is useful for studying:

- multilingual embeddings
- cross-lingual transfer
- agglutinative morphology
- multilingual retrieval
- machine translation
- low-resource evaluation
- tokenizer behavior

---

## Language family

Turkic

→ Oghuz branch

Closely related languages include:

- Turkish
- Turkmen
- Gagauz

Potential comparison languages:

- Turkish
- Kazakh
- Uzbek
- Finnish (morphology comparison)

---

## Writing system

Modern Azerbaijani primarily uses the Latin alphabet.

Historically it has also been written using:

- Arabic script
- Cyrillic

Possible research questions:

- How does script affect multilingual retrieval?
- How do multilingual models handle historical orthographies?
- Does script influence tokenizer efficiency?

---

## Morphology

Azerbaijani is an agglutinative language.

Characteristics include:

- productive suffixation
- vowel harmony
- relatively regular morphology
- extensive case marking

Research questions:

- How efficiently do tokenizers segment long word forms?
- Does agglutination improve or reduce embedding quality?
- How does morphology compare with Turkish and Finnish?

---

## Tokenization

Potential investigations:

- BPE segmentation
- SentencePiece behavior
- WordPiece behavior

Comparisons:

- Azerbaijani vs Turkish
- Azerbaijani vs Finnish
- Azerbaijani vs English

Questions:

- Which tokenizer produces the fewest fragments?
- Which preserves meaningful morphemes?

---

## Embeddings

Possible experiments:

- nearest-neighbor inspection
- semantic similarity
- cross-lingual alignment

Research questions:

- How closely do Azerbaijani embeddings align with Turkish?
- Does multilingual training capture shared Turkic vocabulary?

---

## Retrieval

Potential investigations:

- multilingual search
- semantic retrieval
- multilingual RAG
- cross-language retrieval

Questions:

- Can Turkish documents improve Azerbaijani retrieval?
- How well do multilingual embedding models retrieve Azerbaijani content?

---

## Translation

Interesting language pairs:

- Azerbaijani ↔ Turkish
- Azerbaijani ↔ English
- Azerbaijani ↔ Russian
- Azerbaijani ↔ Finnish

Research questions:

- Which language pairs perform best?
- How much transfer occurs from Turkish?

---

## Language resources

Possible future additions:

- Universal Dependencies
- Hugging Face models
- OPUS
- FLORES
- Common Crawl

---

## Example datasets

Potential datasets:

- FLORES-200
- MASSIVE
- XNLI
- OPUS
- Universal Dependencies

---

## Interesting research papers

Future bibliography

---

## Future experiments

- Compare Azerbaijani and Turkish embeddings.
- Compare tokenizer efficiency with Finnish.
- Evaluate multilingual retrieval.
- Investigate cross-script transfer.
- Compare multilingual LLM performance across Turkic languages.