# Language Contact

Language families explain historical relationships between languages.

Language contact explains how languages influence one another through interaction.

For multilingual AI systems, both perspectives matter.

Languages that are genetically unrelated may share vocabulary, writing systems, discourse patterns, or semantic concepts because of centuries of contact. These relationships may influence tokenization, multilingual embeddings, retrieval, translation, and evaluation.

This repository treats language contact as an important dimension of multilingual AI alongside language families, morphology, writing systems, and resource availability.

---

# Why language contact matters for AI

Language contact may influence:

- borrowed vocabulary
- named entities
- multilingual embeddings
- semantic similarity
- retrieval performance
- machine translation
- multilingual evaluation

Two unrelated languages may behave more similarly than expected because of long periods of cultural or linguistic interaction.

Conversely, closely related languages may diverge because of different historical influences.

---

# Language family versus language contact

These concepts describe different relationships.

| Language family | Language contact |
|-----------------|------------------|
| Historical ancestry | Historical interaction |
| Shared origin | Shared influence |
| Genetic relationship | Cultural and linguistic exchange |
| Usually stable | Changes over time |

Both perspectives are valuable when designing multilingual AI experiments.

---

# Examples

## Finnish ↔ Swedish

- centuries of bilingualism
- administrative vocabulary
- educational terminology
- loanwords
- public services

Research questions

- Does historical borrowing influence multilingual embeddings?
- Can multilingual retrieval benefit from shared vocabulary?

---

## Finnish ↔ Russian

- geographic neighbors
- centuries of interaction
- historical borrowing
- multilingual communities

Research questions

- How does language contact influence cross-lingual retrieval?
- Does proximity improve multilingual representations?

---

## Estonian ↔ German

German-speaking Lutheran clergy played a major role in the development and standardization of written Estonian beginning in the sixteenth century.

Research questions

- Does historical orthographic influence affect multilingual tokenization?
- How does lexical borrowing appear in embedding space?

---

## Estonian ↔ Russian

- multilingual society
- historical language policy
- cross-border communication

Potential investigations

- retrieval
- translation
- multilingual evaluation

---

## Meänkieli ↔ Swedish

- minority language
- bilingual communities
- education
- public administration

Research questions

- How do multilingual models represent mixed linguistic environments?
- Does bilingual exposure improve multilingual transfer?

---

## North Sámi ↔ Norwegian

- Indigenous language
- multilingual public services
- language revitalization

Research questions

- How do multilingual systems support Indigenous languages?
- How should evaluation account for language revitalization?

---

## Azerbaijani ↔ Persian

- long-term regional interaction
- bilingual communities
- shared cultural vocabulary

Research questions

- How much lexical borrowing is reflected in multilingual embeddings?

---

## Azerbaijani ↔ Russian

- multilingual administration
- education
- historical language policy

Potential investigations

- retrieval
- translation
- semantic similarity

---

## Georgian ↔ Armenian

Neighboring language families with centuries of cultural interaction.

Research questions

- How do multilingual models represent neighboring but unrelated languages?

---

# Engineering implications

Language contact provides opportunities to design richer multilingual benchmarks.

Potential variables include:

- neighboring versus distant languages
- shared writing systems
- borrowed vocabulary
- multilingual communities
- language policy
- bilingual education
- historical orthographic influence

These variables complement traditional comparisons based on language families.

---

# Future experiments

- Compare embeddings for neighboring languages with extensive historical contact.
- Measure retrieval performance across language contact zones.
- Investigate lexical borrowing using embedding neighborhoods.
- Compare translation quality for related versus unrelated neighboring languages.
- Study tokenization behavior for borrowed words.
- Visualize multilingual embedding spaces across language contact zones.

---

# Repository connections

Related documentation:

- `comparative-methodology.md`
- `language-families.md`
- `tokenization.md`
- `embeddings.md`
- `retrieval.md`
- `evaluation.md`
- `low-resource-languages.md`

Related language profiles:

- Finnish
- Estonian
- Meänkieli
- North Sámi
- Russian
- Swedish
- Norwegian
- Azerbaijani
- Persian
- Georgian
- Armenian