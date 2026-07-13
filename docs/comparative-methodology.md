# Comparative Methodology

The Multilingual Benchmark Explorer investigates multilingual AI through carefully designed comparative experiments.

Rather than comparing languages at random, each comparison is selected to isolate one or more variables that influence multilingual AI systems.

The goal is not simply to compare languages, but to better understand how linguistic, historical, and computational factors affect tokenization, embeddings, retrieval, evaluation, and cross-lingual transfer.

---

# Guiding principles

Comparisons should:

- investigate meaningful AI engineering questions
- isolate one or more linguistic or computational variables
- be reproducible
- encourage qualitative and quantitative evaluation
- improve understanding of multilingual AI systems

---

# Dimensions of comparison

The repository organizes multilingual comparisons across several complementary dimensions.

## Language family relationships

Languages within the same language family often share historical ancestry and structural similarities.

Examples include:

- Finnish ↔ Estonian
- Finnish ↔ Meänkieli
- Dutch ↔ German
- Russian ↔ Ukrainian
- Turkish ↔ Azerbaijani

Research questions:

- How well do multilingual models transfer within the same language family?
- How similar are multilingual embeddings?
- Does tokenizer behavior differ?
- How much vocabulary is shared?

---

## Language contact

Languages may influence one another through long-term historical interaction, even when they belong to different language families.

Examples include:

- Finnish ↔ Russian
- Estonian ↔ German
- Estonian ↔ Russian
- Meänkieli ↔ Swedish
- Erzya ↔ Russian
- Azerbaijani ↔ Persian

Research questions:

- Does language contact improve multilingual retrieval?
- Can multilingual models exploit borrowed vocabulary?
- Does historical interaction influence embeddings?

---

## Resource availability

Comparisons across different levels of digital resource availability help evaluate multilingual robustness.

Examples include:

- Finnish ↔ Livonian
- Finnish ↔ Karelian
- Russian ↔ Erzya
- Norwegian ↔ North Sámi

Research questions:

- Can higher-resource languages improve performance for lower-resource languages?
- Which multilingual models transfer knowledge most effectively?
- How does performance change as available resources decrease?

---

## Morphological complexity

Languages differ significantly in how they express grammatical information.

Examples include:

- Finnish
- Estonian
- Erzya
- Turkish
- Hungarian

Research questions:

- How does morphology influence tokenization?
- Which embedding models best preserve morphological information?
- How robust are multilingual tokenizers?

---

## Writing systems

Writing systems introduce additional multilingual engineering challenges.

Examples include:

- Latin
- Cyrillic
- Georgian
- Arabic

Research questions:

- How does script influence multilingual retrieval?
- How does tokenizer performance vary?
- Do embeddings behave differently across scripts?

---

# Comparative experiments

Each experiment should clearly identify:

- languages being compared
- research question
- variables being investigated
- datasets
- models
- evaluation metrics
- expected observations

---

# Example comparison template

```text
Comparison

Research question

Languages

Variables

Dataset(s)

Model(s)

Evaluation metrics

Results

Observations

Future work
```

---

# Evaluation

Comparative experiments should combine both quantitative and qualitative evaluation.

Possible quantitative metrics include:

- Recall@K
- Mean Reciprocal Rank (MRR)
- nDCG
- Precision
- Recall
- F1
- cosine similarity
- BLEU
- COMET
- BERTScore

Qualitative evaluation may include:

- nearest-neighbor inspection
- embedding visualization
- tokenization analysis
- retrieval examples
- translation examples
- error analysis

---

# Future directions

Potential future investigations include:

- multilingual embedding alignment
- multilingual retrieval
- multilingual RAG
- tokenizer comparison
- language contact and multilingual AI
- evaluation of Indigenous languages
- evaluation of national minority languages
- benchmark design for lower-resource languages

---

# Repository connections

Related documentation:

- `language-families.md`
- `language-contact.md`
- `low-resource-languages.md`
- `evaluation.md`
- `tokenization.md`
- `embeddings.md`
- `retrieval.md`

This document defines *how* multilingual comparisons are designed. Individual language profiles and experiments apply these principles to specific languages and AI engineering questions.