# Languages

This directory contains AI engineering profiles for the languages explored throughout the Multilingual Benchmark Explorer.

Rather than serving as general linguistic references, these documents focus on the language characteristics that influence multilingual AI systems, including tokenization, morphology, embeddings, retrieval, evaluation, translation, and cross-lingual transfer.

Together, these profiles support comparative analysis across language families, language contact zones, writing systems, morphological types, and resource availability.

The authoritative inventory of languages included in this repository is maintained in `language-families.md`. Individual language profiles should complement that document rather than duplicate it.

---

# Goals

Each language profile should help answer questions such as:

- Why is this language important for multilingual AI engineering?
- Which linguistic characteristics influence NLP systems?
- What challenges does the language present for tokenization?
- How might morphology affect multilingual embeddings?
- How well do multilingual models support the language?
- Which datasets, models, and tools are available?
- What experiments would improve our understanding of multilingual AI?

---

# Standard language profile

Each language page should follow a common structure.

```text
# Language

## AI engineering profile

## Language family

## Writing system

## Morphology

## Tokenization

## Embeddings

## Retrieval

## Translation

## Language resources

## Example datasets

## Interesting research papers

## Future experiments

## Repository connections
```

The goal is consistency rather than completeness. Language profiles are living documents that will evolve as new experiments, datasets, benchmarks, and multilingual AI research become available.

---

# Design principles

Language pages should:

- focus on AI engineering rather than general linguistics
- emphasize language-specific characteristics rather than general AI concepts
- encourage comparative analysis across languages
- document linguistic features that influence NLP systems
- identify useful datasets, models, and language resources
- propose reproducible experiments
- avoid duplicating information documented elsewhere in the repository
- reference related documentation where appropriate
- evolve as multilingual AI research advances

---

# Repository connections

Language profiles complement other documentation within this repository.

General concepts such as tokenization, embeddings, retrieval, evaluation, language families, language contact, and comparative methodology should be documented in their dedicated files rather than repeated in every language profile.

In particular:

- `language-families.md` defines the repository's language inventory.
- `language-contact.md` explores historical and sociolinguistic relationships between languages.
- `comparative-methodology.md` explains how multilingual experiments are designed.
- Topic documents such as `tokenization.md`, `embeddings.md`, `retrieval.md`, and `evaluation.md` explain general AI concepts.

Language profiles should build upon these documents by focusing on what is unique or noteworthy about each language from an AI engineering perspective.

---

# Completion criteria

A language profile is considered complete when it:

- explains why the language is relevant to AI engineering
- identifies linguistic characteristics that influence NLP systems
- discusses tokenization, embeddings, retrieval, and translation where applicable
- documents useful datasets, models, tools, and language resources
- proposes concrete experiments or evaluation ideas
- references relevant documentation where appropriate
- follows the standard language profile template

Language profiles are expected to evolve as new research, datasets, models, benchmarks, and experiments become available.