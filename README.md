# 📚 Knowledge-Augmented-Reasoning-in-LLMs

This repository accompanies our tutorial of **structured, unstructured, and signal knowledge** in large language models (LLMs). It aggregates key research papers referenced in our tutorial and organizes them by knowledge type and theme.

---

## 🧩 Structured Knowledge

Structured knowledge refers to information organized in a structural, machine-readable format, such as relational databases, knowledge graphs, and ontologies. Unlike unstructured text, this format enables precise querying and supports logical inference over clearly defined semantic representations.

### Explicit Structured Knowledge
This refers to structural representations derived from explicit textual content, such as dictionaries, encyclopedias, or document databases. This section also includes algorithms for integrating this knowledge into LLMs.

| Category | Paper | Citation |
|-----------|--------|-----------|
| **Knowledge Graphs** | *LLMs for knowledge graph construction and reasoning: Recent capabilities and future opportunities* | Zhu et al., 2024 |
| **Semantic Triples** | *Zero-shot fact-checking with semantic triples and knowledge graphs* | Yuan and Vlachos, 2024 |
| **Tabular Data** | *Table meets LLM: Can large language models understand structured table data?* | Sui et al., 2024 |
| **Relational Databases** | *Relational database augmented large language model* | Qin et al., 2024 |
| **Ontologies** | *From human experts to machines: An LLM supported approach to ontology and knowledge graph construction* | Kommineni et al., 2024 |
| **Retrieval Augmentation** | *Fine-tuning vs. retrieval augmented generation for less popular knowledge* | Soudani et al., 2024 |
| **Knowledge Embeddings** | *Soft knowledge prompt: Help external knowledge become a better teacher to instruct LLM in knowledge-based VQA* | Wang et al., 2024 |
| **Prompt-based Integration** | *LLM as Prompter: Low-resource inductive reasoning on arbitrary knowledge graphs* | Wang et al., 2024 |
| **External Adapters** | *KG-adapter: Enabling knowledge graph integration in LLMs through parameter-efficient fine-tuning* | Tian et al., 2024 |
| **Knowledge Fusion** | *Efficient knowledge infusion via KG-LLM alignment* | Jiang et al., 2024 |
---

### Implicit Structured Knowledge
Implicit structured knowledge refers to the underlying structures embedded beneath the surface of text, capturing latent semantic or logical connections. This is essential for deep reasoning tasks that require understanding hidden relationships.

| Category | Paper | Citation |
|-----------|--------|-----------|
| **Logical Structure** | *Boosting Logical Fallacy Reasoning in LLMs via Logical Structure Tree* | Lei and Huang, 2024a |
| **Discourse Structure** | *Discourse structures guided fine-grained propaganda identification* | Lei and Huang, 2023a |
| **Narrative Flow** | *Sentence-level media bias analysis with event relation graph* | Lei and Huang, 2024b |
| **Logical Reasoning** | *A Closer Look at Logical Reasoning with LLMs: The Choice of Tool Matters* | Lam et al., 2024 |
| **Factuality Reasoning** | *Identifying conspiracy theories news based on event relation graph* | Lei and Huang, 2023b |
| **Factuality Reasoning** | *Sentence-level media bias analysis informed by discourse structures* | Lei et al., 2022 |
| **Causal Reasoning** | *Is Knowledge All Large Language Models Needed for Causal Reasoning?* | Cai et al., 2024 |
| **Temporal Reasoning** | *zrLLM: Zero-shot relational learning on temporal knowledge graphs with large language models* | Ding et al., 2024 |
---

## 🗞️ Unstructured Knowledge
Unstructured knowledge refers to information in free-form formats, such as natural language text from documents, conversations, and the web. This knowledge is abundant, up-to-date, and semantically rich, enabling reasoning in open-ended and dynamic settings.

### Contextual Knowledge
This refers to free-form text and contextual prompts that influence model behavior, such as guiding LLMs to reason step-by-step using natural language.

| Category | Paper | Citation |
|-----------|--------|-----------|
| **Prompting & CoT** | *Chain-of-Thought Prompting Elicits Reasoning in Large Language Models* | Wei et al., 2022 |
| | *Large Language Models are Zero-Shot Reasoners* | Kojima et al., 2022 |
| | *EchoPrompt: Instructing the model to rephrase queries for improved in-context learning* | Mekala et al., 2024 |
| | *On second thought, let's not think step by step! bias and toxicity in zero-shot reasoning* | Shaikh et al., 2023 |
---

### Personalized Knowledge
This includes user-specific information such as preferences, user profiles, historical interactions, and goals. Integrating this knowledge allows LLMs to provide more tailored and personalized responses.

| Category | Paper | Citation |
|-----------|--------|-----------|
| **Surveys** | *Personalization of Large Language Models: A Survey* | Zhang et al., 2025b |
| | *Two Tales of Persona in LLMs: A Survey of Role-Playing and Personalization* | Tseng et al., 2024 |
| **Personalization** | *Better Zero-Shot Reasoning with Role-Play Prompting* | Kong et al., 2024 |
| | *PersonaMath: Boosting mathematical reasoning via persona-driven data augmentation* | Luo et al., 2024 |
| | *LEGO: A multi-agent collaborative framework... for causality explanation generation* | He et al., 2023 |
| **Bias Analysis** | *Role-Play Paradox in Large Language Models: Reasoning Performance Gains and Ethical Dilemmas* | Zhao et al., 2024 |
| | *Bias runs deep: Implicit reasoning biases in persona-assigned LLMs* | Gupta et al., 2024 |
| **Applications** | *ReasoningRec: Bridging personalized recommendations and... LLM reasoning* | Bismay et al., 2025 |
| | *Leveraging LLM reasoning enhances personalized recommender systems* | Tsai et al., 2024 |
---

## 🔊 Signal Knowledge
Signal knowledge is derived from interactions and external guidance rather than explicitly encoded as symbolic facts or text. These signals, such as logits from expert models or human interaction cues, help models align with human expectations and communicative nuance.

### Model-Derived Signals
This includes signals such as rewards, scores, or corrections from other models (expert, anti-expert, amateur, or reward models). This feedback helps the model refine its outputs or avoid failures.

| Category | Paper | Citation |
|-----------|--------|-----------|
| **Survey** | *A Survey on LLM Inference-Time Self-Improvement* | Dong et al., 2024 |
| **Expert/Anti-Expert** | *DExperts: Decoding-time controlled text generation with experts and anti-experts* | Liu et al., 2021 |
| | *MIL-decoding: Detoxifying language models at token-level...* | Zhang and Wan, 2023 |
| **Amateur Models** | *Jailbreak open-sourced large language models via enforced decoding* | Zhang et al., 2024 |
| | *Contrastive decoding: Open-ended text generation as optimization* | Li et al., 2023 |
| **Reward Models** | *Reward-augmented decoding: Efficient controlled text generation...* | Deng and Raffel, 2023 |
| | *ARGS: Alignment as reward-guided search* | Khanov et al., 2024 |
---

### Human-Interaction Signals
This knowledge includes signals like speech disfluencies, emphasis, pauses, or interaction patterns that reveal user intent, uncertainty, or preferences.

| Category | Paper | Citation |
|-----------|--------|-----------|
| **Theory** | *Preliminaries to a Theory of Speech Disfluencies* | Shriberg, 1994 |
| **Data Generation** | *Analysis and Evaluation of Synthetic Data Generation in Speech Dysfluency Detection* | Zhang et al., 2025a |
| **ASR Integration** | *Dysfluent WFST: A Framework for Zero-Shot Speech Dysfluency Transcription and Detection* | Guo et al., 2025 |
| **Impact on Tasks** | *Quantifying the Impact of Disfluency on Spoken Content Summarization* | Teleki et al., 2024 |
| | *I want a horror–comedy–movie: Slips-of-the-Tongue Impact Conversational Recommender...* | Teleki et al., 2025 |

