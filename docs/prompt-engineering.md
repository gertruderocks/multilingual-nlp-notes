# Prompt Engineering

## What is prompt engineering?

Prompt engineering is the practice of designing prompts that help AI systems produce useful, reliable, and accurate outputs.

A prompt is more than a question. It provides instructions, context, constraints, examples, and goals that guide the behavior of a language model.

Modern prompt engineering is closely connected to retrieval, system design, evaluation, and human-computer interaction.

---

## Why does prompt engineering matter?

Prompt engineering influences the quality, consistency, and reliability of AI systems.

Applications include:

- AI assistants
- Retrieval-Augmented Generation (RAG)
- Software development
- Technical writing
- Code generation
- Document summarization
- Customer support
- Enterprise AI
- Agentic AI systems
- Multilingual AI

Good prompts improve output quality while reducing ambiguity and hallucinations.

---

## Questions I want to explore

- Which prompting techniques produce the most reliable outputs?
- How much context should a prompt include?
- How does retrieval influence prompt design?
- How should prompts be evaluated?
- How do multilingual prompts differ from monolingual prompts?
- How should prompts support morphologically rich languages?
- How should prompts support Indigenous and endangered languages?
- How do prompts influence downstream AI system behavior?

---

## Anatomy of a prompt

A well-designed prompt often contains several components.

### Objective

What should the model accomplish?

Examples:

- Summarize a document.
- Retrieve relevant information.
- Explain a technical concept.
- Translate text.
- Generate code.

---

### Context

What background information should the model know?

Examples:

- Project documentation
- Product requirements
- Conversation history
- Retrieved documents
- User profile

---

### Instructions

How should the model behave?

Examples:

- Be concise.
- Explain your reasoning.
- Produce Markdown.
- Cite sources.
- Use bullet points.
- Do not speculate.

---

### Constraints

What limitations should the model follow?

Examples:

- Maximum length
- Required format
- Supported languages
- Output schema
- Safety requirements

---

### Examples

Examples often improve consistency by demonstrating the desired behavior.

Questions to explore:

- When do examples improve performance?
- How many examples are helpful?
- When do examples become unnecessary?

---

## Common prompting techniques

### Zero-shot prompting

Provide only instructions.

Questions to explore:

- When is zero-shot sufficient?
- Which tasks require additional context?

---

### One-shot prompting

Provide one example.

Questions to explore:

- When does one example improve quality?
- Which tasks benefit most?

---

### Few-shot prompting

Provide multiple examples demonstrating the desired behavior.

Questions to explore:

- How many examples are optimal?
- How do examples influence multilingual tasks?

---

### Role prompting

Assign the model a role.

Examples:

- Technical writer
- AI engineer
- Product manager
- Software architect
- Language tutor

Questions to explore:

- When does role prompting improve outputs?
- How should roles be evaluated?

---

### Structured prompting

Specify a required output format.

Examples:

- JSON
- Markdown
- Tables
- XML
- YAML

Questions to explore:

- Which structured formats are easiest for downstream systems?
- How does structured output improve automation?

---

## Prompt engineering within AI systems

Prompt engineering is only one component of a larger AI pipeline.

```text
User
    ↓
Prompt
    ↓
Tokenization
    ↓
Embedding (optional)
    ↓
Retrieval (optional)
    ↓
Context assembly
    ↓
Large Language Model
    ↓
Output
    ↓
Evaluation
```

Every stage influences the final response.

---

## Prompt engineering and Retrieval-Augmented Generation

Prompt engineering becomes especially important in RAG systems.

Questions include:

- How should retrieved documents be organized?
- How much retrieved context should be included?
- How should citations be incorporated?
- How should conflicting retrieved information be handled?
- How should prompts encourage grounded responses?

---

## Prompt engineering and multilingual AI

Prompt engineering becomes more challenging when multiple languages are involved.

Research questions include:

- Should prompts be written in the user's language?
- Should retrieval occur in one language or many?
- How does prompt language affect answer quality?
- How should multilingual prompts be evaluated?

---

## Comparative case studies

| Comparison | Comparison type | Engineering question |
|------------|----------------|----------------------|
| Finnish ↔ Russian | Neighboring language families | Does prompt language influence multilingual reasoning? |
| Finnish ↔ Estonian | Closely related languages | Does language similarity improve prompt effectiveness? |
| Finnish ↔ Karelian | Low-resource language | Can multilingual prompting improve low-resource performance? |
| Finnish ↔ Meänkieli | Language contact | How should prompts support closely related minority languages? |
| North Sámi ↔ Norwegian | Indigenous language support | How should prompts support Indigenous language users? |
| Russian ↔ Estonian | Language contact | Does multilingual prompting improve retrieval? |
| Russian ↔ Latvian | Language contact | How should multilingual prompts support multilingual societies? |
| Russian ↔ Azerbaijani | Regional multilingualism | How should multilingual prompts adapt across language families? |
| Persian ↔ Azerbaijani | Cross-border multilingualism | How should prompts support bilingual communities? |
| Dutch ↔ German | Closely related languages | Can prompts transfer effectively across related languages? |
| German ↔ Estonian | Historical language contact | Does prompt language influence multilingual retrieval? |
| Russian ↔ Ukrainian | Closely related Slavic languages | How robust are prompts across similar languages? |
| Turkish ↔ Azerbaijani | Closely related Turkic languages | How should prompts leverage shared linguistic structure? |
| Georgian ↔ Armenian | Neighboring language families | How should prompts support distinct writing systems? |
| Russian ↔ Georgian | Neighboring language families | How do script differences influence prompting? |
| Azerbaijani ↔ Lezgin | Minority language contact | How should prompting support minority languages? |

---

## Engineering considerations

Effective prompt engineering requires balancing:

- Clarity
- Precision
- Context length
- Token usage
- Cost
- Latency
- Grounding
- Safety
- User experience
- Maintainability

Prompt engineering should be treated as an engineering discipline rather than trial and error.

---

## Engineering implications

Prompt engineering influences:

- Answer quality
- Hallucination rate
- Cost
- Latency
- Context utilization
- Evaluation
- Reliability
- User trust

Prompt design should therefore be evaluated as part of the complete AI system.

---

## Future experiments

Examples include:

- Compare zero-shot and few-shot prompting.
- Compare prompts across multiple languages.
- Evaluate prompt length versus answer quality.
- Compare multilingual prompt strategies.
- Investigate prompt engineering for morphologically rich languages.
- Evaluate prompts for Indigenous language support.
- Measure token usage across languages.
- Compare prompt engineering strategies in RAG systems.

---

## Open questions

- Which prompting techniques generalize best?
- How should prompt quality be evaluated?
- Which prompting strategies scale best?
- How should multilingual prompts be designed?
- How should prompt engineering evolve as agentic AI systems become more common?
- Which prompt engineering practices remain useful as models continue to improve?

---

## References

(To be added.)