# Multilingual Large Language Models (LLMs)

## What are multilingual large language models?

Multilingual large language models (LLMs) are language models trained to understand and generate text across many languages.

Unlike monolingual models, multilingual LLMs must represent languages that differ in writing systems, morphology, available training data, syntax, and cultural context.

These models support applications such as multilingual search, translation, Retrieval-Augmented Generation (RAG), question answering, coding assistants, and AI agents.

---

## Why do multilingual LLMs matter?

Modern AI systems increasingly serve users around the world.

Supporting multiple languages requires much more than translation.

Multilingual AI systems must reason across:

- Language families
- Writing systems
- Morphological complexity
- Resource availability
- Language contact
- Cultural context

Building multilingual systems therefore becomes both an engineering and an evaluation challenge.

---

## Questions I want to explore

- How do multilingual LLMs represent multiple languages within a shared model?
- How well do multilingual models transfer knowledge across related languages?
- How do multilingual models perform on low-resource languages?
- How should multilingual LLMs be evaluated?
- How does morphology influence multilingual performance?
- How do writing systems influence multilingual reasoning?
- How does language contact influence multilingual representations?
- How should multilingual AI systems support Indigenous and endangered languages?

---

# Common multilingual LLMs

## GPT

Questions to explore:

- How strong is multilingual reasoning?
- Which languages perform best?
- How does performance vary across resource levels?

---

## Gemini

Questions to explore:

- How does multilingual reasoning compare across language families?
- How does Gemini perform on morphologically rich languages?

---

## Claude

Questions to explore:

- How well does Claude reason across multiple languages?
- How does multilingual reasoning compare with multilingual retrieval?

---

## Llama

Questions to explore:

- How do open-weight multilingual models compare with proprietary models?
- How does fine-tuning influence multilingual performance?

---

## Mistral

Questions to explore:

- How well do Mistral models support European languages?
- How does multilingual performance compare with other frontier models?

---

## DeepSeek

Questions to explore:

- How does multilingual reasoning compare with other open models?
- How well does DeepSeek support multilingual retrieval?

---

## Qwen

Questions to explore:

- How does Qwen perform across diverse writing systems?
- How does multilingual performance vary across language families?

---

## Engineering considerations

Multilingual LLMs depend on many interconnected components.

Examples include:

- Tokenization
- Training corpus
- Vocabulary
- Embeddings
- Context window
- Retrieval
- Prompt engineering
- Evaluation

Understanding these interactions is essential for building robust multilingual AI systems.

---
## Engineering considerations

...

---

## Architectural tradeoffs

Modern multilingual AI systems require balancing competing engineering priorities.

Examples include:

| Tradeoff | Questions to explore |
|-----------|----------------------|
| One multilingual model vs. multiple monolingual models | Which architecture provides better quality, maintainability, and scalability? |
| Shared vocabulary vs. language-specific vocabularies | How does vocabulary design affect multilingual performance? |
| Open-weight vs. proprietary models | What are the tradeoffs between flexibility, transparency, and capability? |
| Fine-tuning vs. prompting | When should model weights be updated instead of improving prompts or retrieval? |
| Retrieval vs. larger context windows | When should external knowledge replace larger prompts? |
| Dense retrieval vs. hybrid retrieval | Which retrieval strategy performs best across languages? |
| Smaller models vs. larger models | When does model size justify increased cost and latency? |
| Specialized multilingual models vs. general-purpose models | When does specialization improve multilingual performance? |

Good engineering requires understanding these tradeoffs rather than assuming there is a single best solution.

---

## Engineering implications

Changes to one component influence the entire system.

Examples include:

- Tokenization influences embeddings.
- Embeddings influence retrieval.
- Retrieval influences generation.
- Prompt engineering influences answer quality.
- Evaluation influences future system improvements.

Thinking in terms of systems rather than individual models leads to stronger engineering decisions.

---

## Common evaluation topics

Examples include:

- Cross-lingual transfer
- Multilingual reasoning
- Translation quality
- Hallucination rates
- Faithfulness
- Retrieval quality
- Robustness
- Low-resource language performance

Questions to explore:

- Which multilingual capabilities are hardest to evaluate?
- Which benchmarks best reflect real-world multilingual usage?

---

## Comparative case studies

| Comparison | Comparison type | Engineering question |
|------------|----------------|----------------------|
| Finnish ↔ Russian | Neighboring language families, different scripts | How well do multilingual LLMs transfer across morphology and writing systems? |
| Finnish ↔ Estonian | Closely related languages | Does language relatedness improve multilingual reasoning? |
| Finnish ↔ Karelian | Low-resource language | Can multilingual LLMs generalize to low-resource languages? |
| Finnish ↔ Meänkieli | Language contact | How well do multilingual models capture language contact? |
| North Sámi ↔ Norwegian | Indigenous language support | How effectively do multilingual LLMs support Indigenous languages? |
| Russian ↔ Estonian | Language contact | How does multilingual reasoning perform across neighboring language families? |
| Russian ↔ Latvian | Language contact | How should multilingual AI support multilingual societies? |
| Russian ↔ Azerbaijani | Regional multilingualism | How well do multilingual LLMs transfer across language families? |
| Persian ↔ Azerbaijani | Cross-border multilingualism | How should multilingual AI support bilingual communities? |
| Dutch ↔ German | Closely related languages | Does lexical similarity improve multilingual reasoning? |
| German ↔ Estonian | Historical language contact | How does language contact influence multilingual understanding? |
| Russian ↔ Ukrainian | Closely related Slavic languages | How robust is multilingual transfer? |
| Turkish ↔ Azerbaijani | Closely related Turkic languages | How transferable are multilingual representations? |
| Georgian ↔ Armenian | Neighboring language families | How do multilingual LLMs reason across distinct language families? |
| Russian ↔ Georgian | Neighboring language families | How do script and language family differences influence multilingual reasoning? |
| Azerbaijani ↔ Lezgin | Minority language contact | How well do multilingual LLMs support minority languages? |

---

## Future experiments

Examples include:

- Compare multilingual reasoning across frontier models.
- Compare multilingual reasoning with multilingual retrieval.
- Evaluate multilingual hallucinations.
- Compare low-resource language performance.
- Compare multilingual summarization.
- Compare multilingual question answering.
- Investigate prompt engineering across multiple languages.
- Evaluate multilingual RAG systems.
- Measure cross-lingual transfer across language families.

---

## Open questions

- What are the limits of multilingual transfer?
- Which multilingual benchmarks best reflect real-world AI systems?
- How should multilingual LLMs be evaluated fairly?
- How should AI systems support endangered and Indigenous languages?
- How should multilingual reasoning be measured?
- What new multilingual capabilities will future models develop?

---

## References

(To be added.)