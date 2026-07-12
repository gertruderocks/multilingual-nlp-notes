# Comparative Methodology

## Purpose

The goal of this repository is not to compare languages for their own sake.

Instead, it uses carefully selected language comparisons to investigate engineering questions about modern multilingual AI systems.

Every language, language pair, and experiment included in this repository should help answer a meaningful question about tokenization, embeddings, retrieval, Retrieval-Augmented Generation (RAG), evaluation, or multilingual reasoning.

This document describes the principles used to design those comparisons.

---

# Guiding principles

## AI systems first

This repository is organized around modern AI systems rather than individual languages.

Topics include:

- Tokenization
- Embeddings
- Retrieval
- Retrieval-Augmented Generation (RAG)
- Prompt engineering
- Evaluation
- Multilingual large language models

Languages serve as engineering test cases rather than ends in themselves.

---

## Every language should earn its place

Languages are selected because they illustrate important engineering challenges.

Examples include:

- Morphological complexity
- Writing systems
- Language contact
- Low-resource NLP
- Indigenous language support
- Cross-lingual transfer
- Semantic retrieval

The repository does not attempt to cover every language equally.

---

## Every comparison should answer an engineering question

Rather than asking:

> How are these languages similar?

the repository asks questions such as:

- How does morphology influence tokenization?
- How do writing systems affect embeddings?
- How does language contact influence retrieval?
- Which language pairs best reveal strengths and weaknesses in multilingual AI systems?
- How should multilingual AI systems support Indigenous and endangered languages?

---

## Engineering over memorization

The objective is not to memorize benchmark scores or model names.

Instead, the goal is to understand:

- Why systems behave the way they do
- Which engineering decisions matter
- Which tradeoffs influence performance
- How AI systems can be evaluated fairly

---

# Comparison taxonomy

Language comparisons are grouped according to the engineering questions they investigate.

## Closely related languages

Purpose:

Investigate cross-lingual transfer and shared linguistic structure.

Examples:

- Finnish ↔ Estonian
- Finnish ↔ Karelian
- Russian ↔ Ukrainian
- Turkish ↔ Azerbaijani
- Dutch ↔ German

Engineering questions:

- Does language relatedness improve multilingual transfer?
- How transferable are embeddings?
- How should multilingual evaluation account for related languages?

---

## Closely related low-resource languages

Purpose:

Investigate multilingual transfer in languages with limited training resources.

Examples:

- North Sámi ↔ Inari Sámi
- North Sámi ↔ Skolt Sámi

Engineering questions:

- Can multilingual models transfer knowledge between closely related low-resource languages?
- Which embedding models perform best?

---

## Language contact

Purpose:

Investigate the effects of historical interaction between neighboring languages.

Examples:

- Finnish ↔ Russian
- Russian ↔ Estonian
- Russian ↔ Latvian
- German ↔ Estonian
- Finnish ↔ Meänkieli

Engineering questions:

- Does language contact improve multilingual retrieval?
- How do multilingual embeddings represent lexical borrowing?

---

## Cross-border multilingualism

Purpose:

Study multilingual communities that span political borders.

Examples:

- Persian ↔ Azerbaijani
- Russian ↔ Azerbaijani

Engineering questions:

- How should multilingual AI support bilingual users?
- How does multilingual retrieval perform across neighboring countries?

---

## Minority language support

Purpose:

Evaluate multilingual AI systems for minority languages.

Examples:

- Azerbaijani ↔ Lezgin
- Finnish ↔ Meänkieli

Engineering questions:

- How well do multilingual models support minority language communities?
- How should evaluation account for limited resources?

---

## Indigenous language deployment

Purpose:

Investigate multilingual AI in real-world Indigenous language settings.

Examples:

- North Sámi ↔ Norwegian

Engineering questions:

- How should multilingual AI systems support communication between Indigenous and national languages?
- How should multilingual retrieval support public services?
- How should RAG support multilingual government documentation?

---

## Writing systems

Purpose:

Investigate multilingual AI across different scripts.

Examples:

- Finnish ↔ Russian
- Russian ↔ Georgian
- Georgian ↔ Armenian

Engineering questions:

- How do writing systems influence tokenization?
- How do scripts influence multilingual embeddings?
- How does script affect retrieval?

---

## Morphological complexity

Purpose:

Investigate how word formation influences AI systems.

Examples:

- Finnish
- Estonian
- Turkish
- Azerbaijani
- Russian

Engineering questions:

- How does morphology influence tokenization?
- How does morphology influence retrieval?
- Which models perform best on morphologically rich languages?

---

## Low-resource NLP

Purpose:

Evaluate multilingual AI beyond high-resource languages.

Examples:

- Karelian
- Meänkieli
- North Sámi
- Inari Sámi
- Skolt Sámi
- Lezgin

Engineering questions:

- Which multilingual models generalize best?
- How should low-resource languages be evaluated?
- What benchmarks are appropriate?

---

# Designing experiments

Every experiment in this repository should begin with a clear engineering question.

Recommended workflow:

1. Engineering question
2. Hypothesis
3. Language selection
4. Model selection
5. Dataset
6. Implementation
7. Evaluation
8. Analysis
9. Limitations
10. Future work

---

# Engineering principles

This repository follows several core engineering principles.

## Systems thinking

Modern AI systems should be understood as interconnected components rather than isolated technologies.

## Comparative evaluation

Language comparisons should answer meaningful engineering questions rather than simply comparing linguistic features.

## Reproducibility

Experiments should be well documented, repeatable, and easy for others to extend.

## Engineering tradeoffs

Engineering decisions involve balancing competing priorities. Understanding tradeoffs is often more valuable than memorizing architectures, models, or benchmark scores.

## Continuous improvement

This repository is intended to evolve over time as new experiments are completed, new models become available, and the field of multilingual AI continues to advance.

---

# Long-term vision

This repository aims to become a practical framework for exploring how modern AI systems represent, retrieve, evaluate, and transfer meaning across languages.

The emphasis is on building production-oriented engineering knowledge through careful experimentation, rigorous evaluation, and clear technical documentation.

The long-term goal is to better understand multilingual AI systems while contributing practical, reproducible experiments that others can learn from and build upon.