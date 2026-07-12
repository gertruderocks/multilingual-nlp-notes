# Estonian

## AI engineering profile

Estonian is a Finnic language within the Uralic language family and one of the closest living relatives of Finnish. Although it has fewer speakers than many major European languages, Estonian benefits from strong national investment in digital infrastructure, language technology, and open linguistic resources.

Within this repository, Estonian serves as one of the primary benchmark languages for studying:

- multilingual embeddings
- tokenization
- morphology
- retrieval
- cross-lingual transfer
- multilingual evaluation

Estonian is particularly valuable because it enables comparisons between:

- closely related languages (Estonian ↔ Finnish)
- related languages with different national histories
- higher-resource and lower-resource settings
- shared vocabulary versus divergent morphology
- multilingual embedding alignment across the Finnic branch

These comparisons help isolate the effects of language relatedness on multilingual AI systems.

## Language family

Uralic

→ Finnic

Related languages include:

- Finnish
- Karelian
- Livonian
- Veps
- Võro
- Seto

Useful comparison languages:

- Finnish
- Meänkieli
- Russian
- Latvian

---

## Writing system

Modern Estonian uses the Latin alphabet.

Topics of interest include:

- Unicode normalization
- diacritics
- orthographic consistency
- multilingual search

Research questions:

- How do multilingual tokenizers segment Estonian words?
- Do diacritics influence retrieval quality?
- How well do multilingual systems normalize orthographic variation?

---

## Morphology

Estonian exhibits rich inflectional morphology while generally having less productive agglutination than Finnish.

Topics of interest include:

- noun case system
- verb inflection
- derivational morphology
- compound formation

Research questions:

- How does Estonian morphology influence multilingual embeddings?
- How does it compare with Finnish?
- Which morphological features are preserved after tokenization?

---

## Tokenization

Potential investigations:

- Byte Pair Encoding (BPE)
- SentencePiece
- WordPiece

Research questions:

- How frequently are Estonian words fragmented?
- How does tokenizer efficiency compare with Finnish?
- Which tokenizer best preserves meaningful morphemes?

---

## Embeddings

Potential investigations:

- nearest-neighbor inspection
- semantic similarity
- multilingual alignment
- clustering analysis

Research questions:

- How closely do Estonian embeddings align with Finnish?
- Can multilingual models distinguish Estonian from Latvian?
- How do embeddings represent cognates across Finnic languages?

---

## Retrieval

Potential investigations:

- semantic search
- multilingual retrieval
- Retrieval-Augmented Generation (RAG)
- cross-lingual retrieval

Research questions:

- Can Finnish improve retrieval performance for Estonian?
- How well do multilingual embedding models retrieve Estonian documents?
- Which embedding models perform best?

---

## Translation

Interesting language pairs:

- Estonian ↔ Finnish
- Estonian ↔ English
- Estonian ↔ Russian
- Estonian ↔ Latvian

Research questions:

- Which language pairs demonstrate the strongest transfer?
- How does translation quality compare between related and unrelated languages?

---

## Language resources

Potential resources for future investigation:

- Universal Dependencies
- spaCy
- Hugging Face models
- OPUS
- Estonian National Corpus
- Wikipedia
- Common Crawl

---

## Example datasets

Potential datasets for evaluation:

- Universal Dependencies
- FLORES-200
- MASSIVE
- MIRACL
- OPUS
- custom multilingual benchmarks

---

## Interesting research papers

Future bibliography.

Potential topics include:

- multilingual embeddings
- Finnic language NLP
- low-resource NLP
- multilingual retrieval
- language technology for Estonian

---

## Future experiments

- Compare Finnish and Estonian tokenization.
- Compare multilingual embeddings across Finnic languages.
- Measure cross-lingual retrieval between Finnish and Estonian.
- Evaluate multilingual LLM reasoning in Estonian.
- Visualize multilingual embedding neighborhoods.
- Compare retrieval performance across Uralic languages.

---

## Repository connections

Related language profiles:

- Finnish
- Meänkieli
- Karelian
- Livonian
- Seto
- Võro
- Russian
- Latvian

Related documentation:

- `language-families.md`
- `comparative-methodology.md`
- `tokenization.md`
- `embeddings.md`
- `retrieval.md`
- `evaluation.md`
- `low-resource-languages.md`