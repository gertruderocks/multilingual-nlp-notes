# Low-Resource Languages

Low-resource languages present some of the most important challenges in multilingual AI engineering.

Unlike higher-resource languages, many languages have limited digital resources available for training, evaluating, and deploying modern AI systems.

These limitations influence every stage of the AI pipeline, including tokenization, embeddings, retrieval, translation, evaluation, and downstream applications.

Within the Multilingual Benchmark Explorer, resource availability is studied alongside language family relationships, language contact, writing systems, morphology, Indigenous languages, and national minority languages to better understand multilingual AI.

---

# What is a low-resource language?

There is no universal definition.

In this repository, a language may be considered relatively low-resource if it has one or more of the following characteristics:

- limited digital corpora
- relatively few annotated datasets
- limited NLP tooling
- fewer pretrained models
- limited benchmark coverage
- limited publicly available evaluation datasets

Resource availability exists on a continuum rather than as a binary distinction.

---

# Why low-resource languages matter

Modern multilingual AI systems should perform well across a diverse range of languages rather than only those with abundant training data.

Studying lower-resource languages helps researchers investigate:

- multilingual generalization
- cross-lingual transfer
- tokenizer robustness
- multilingual embeddings
- semantic retrieval
- evaluation methodology
- fairness
- language preservation

---

# Research themes

## Cross-lingual transfer between related languages

Can higher-resource languages improve performance for lower-resource languages within the same language family?

Examples include:

- Finnish → Meänkieli
- Finnish → Karelian
- Finnish → Livonian
- Turkish → Azerbaijani

Research questions:

- How much transfer occurs between closely related languages?
- Which multilingual models transfer knowledge most effectively?
- How does morphology influence transfer performance?

---

## Language contact and multilingual transfer

Can long-term language contact improve multilingual AI even when languages belong to different language families?

Examples include:

- Russian → Erzya
- Russian → Moksha
- Swedish → Meänkieli
- Norwegian → North Sámi

See:

- `language-contact.md`

Research questions:

- How do bilingual communities influence multilingual representations?
- Can language contact improve retrieval or translation quality?
- What role do parallel corpora play in multilingual transfer?

---

## Morphology

Many lower-resource languages exhibit rich morphology.

Research questions include:

- How efficiently do tokenizers represent long inflected words?
- How much morphological information survives tokenization?
- Which embedding models best capture morphological similarity?

---

## Evaluation

Benchmark performance on higher-resource languages often fails to predict performance on lower-resource languages.

Potential evaluation areas include:

- retrieval
- multilingual embeddings
- semantic similarity
- translation
- reasoning
- question answering

---

# Languages currently explored

Examples include:

## Indigenous languages

- North Sámi

## National minority languages

- Meänkieli
- Yiddish

## Lower-resource Uralic languages

- Livonian
- Karelian
- Erzya
- Moksha
- Mari
- Udmurt
- Veps
- Võro
- Seto

## Other lower-resource languages

- Lezgin
- Chechen
- Tatar

The authoritative language inventory is maintained in:

- `language-families.md`

---

# Engineering challenges

Lower-resource languages often present challenges including:

- limited training data
- sparse evaluation benchmarks
- limited pretrained models
- tokenizer fragmentation
- multilingual retrieval
- model evaluation
- dataset creation

These challenges also create opportunities to design more robust and inclusive multilingual AI systems.

---

# Future experiments

Potential investigations include:

- Compare tokenizer efficiency across different levels of resource availability.
- Compare multilingual embeddings for higher-resource and lower-resource languages within the same language family.
- Measure cross-lingual transfer across both language family relationships and language contact settings.
- Evaluate retrieval performance for lower-resource languages.
- Compare multilingual LLM reasoning across languages with different levels of digital resource availability.
- Build custom evaluation datasets for underrepresented languages.

---

# Repository connections

Related documentation:

- `language-families.md`
- `language-contact.md`
- `comparative-methodology.md`
- `evaluation.md`
- `tokenization.md`
- `embeddings.md`
- `retrieval.md`

Individual language profiles provide language-specific AI engineering perspectives for many of the lower-resource languages discussed in this repository.