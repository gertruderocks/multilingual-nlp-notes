# Multilingual LLMs

Multilingual Large Language Models (LLMs) are trained to understand and generate text across multiple languages.

Within the Multilingual Benchmark Explorer, multilingual LLMs are studied from an AI engineering perspective with an emphasis on evaluation, retrieval, tokenization, multilingual reasoning, and cross-lingual transfer.

Rather than focusing on individual models, this repository investigates the engineering questions that arise when deploying multilingual AI systems across diverse languages and language communities.

---

# Why multilingual LLMs matter

Modern AI systems increasingly serve global users.

Supporting multiple languages requires more than simply translating text. Models must also handle differences in:

- language families
- writing systems
- morphology
- resource availability
- language contact
- cultural context

Understanding these factors is essential for building reliable multilingual AI systems.

---

# Research themes

## Language family relationships

Research questions include:

- How well do multilingual LLMs transfer within the same language family?
- Do closely related languages exhibit similar model behavior?
- How much linguistic similarity is reflected in model outputs?

Examples:

- Finnish ↔ Estonian
- Dutch ↔ German
- Russian ↔ Ukrainian
- Turkish ↔ Azerbaijani

---

## Language contact

Research questions include:

- Does historical language contact influence multilingual reasoning?
- Can multilingual models exploit borrowed vocabulary?
- Does language contact improve retrieval?

Examples:

- Finnish ↔ Russian
- Estonian ↔ German
- Meänkieli ↔ Swedish
- Erzya ↔ Russian

---

## Resource availability

Research questions include:

- How do multilingual LLMs perform on lower-resource languages?
- Which evaluation methods remain reliable?
- Can higher-resource languages improve performance?

Examples:

- North Sámi
- Livonian
- Erzya
- Mari
- Udmurt

---

## Morphology

Research questions include:

- How well do multilingual LLMs handle rich inflection?
- Does morphology influence reasoning?
- How much morphological information survives tokenization?

---

## Writing systems

Research questions include:

- Does script influence multilingual reasoning?
- How robust are multilingual tokenizers across writing systems?
- Do embeddings behave differently across scripts?

Examples include:

- Latin
- Cyrillic
- Georgian
- Arabic

---

# Engineering considerations

Multilingual LLM engineering includes:

- prompt design
- multilingual evaluation
- Retrieval-Augmented Generation (RAG)
- retrieval quality
- hallucination analysis
- observability
- safety
- benchmarking
- regression testing

---

# Evaluation

Potential evaluation areas include:

- multilingual reasoning
- factual accuracy
- semantic similarity
- retrieval quality
- translation quality
- instruction following
- hallucination analysis
- cross-lingual transfer

Possible metrics include:

- Recall@K
- Mean Reciprocal Rank (MRR)
- nDCG
- BLEU
- COMET
- BERTScore
- human evaluation

---

# Example experiments

Potential investigations include:

- Compare multilingual reasoning across language families.
- Compare tokenizer behavior across morphologically rich languages.
- Measure retrieval performance across language contact settings.
- Evaluate multilingual hallucinations.
- Compare multilingual embeddings across writing systems.
- Build multilingual benchmark datasets.
- Investigate prompt robustness across languages.

---

# Future directions

Future work may include:

- multilingual benchmark dashboards
- multilingual evaluation pipelines
- retrieval experiments
- multilingual RAG
- visualization tools
- AI agents
- production evaluation workflows

---

# Repository connections

Related documentation:

- `comparative-methodology.md`
- `evaluation.md`
- `tokenization.md`
- `embeddings.md`
- `retrieval.md`
- `retrieval-augmented-generation.md`
- `language-families.md`
- `language-contact.md`
- `underrepresented-languages.md`

Individual language profiles provide language-specific perspectives for evaluating multilingual LLM behavior.