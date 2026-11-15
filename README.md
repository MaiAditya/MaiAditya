## Hi, I'm Aditya Gupta

AI engineer working on agentic systems, retrieval and LLM applications for healthcare and fintech. I build production pipelines end to end: data extraction, RAG, multi-agent orchestration, evaluation and deployment. I also contribute bug fixes to open-source AI/ML libraries.

**Currently**
- Data Scientist at **Martlet AI**, building clinical document classification and an AI assistant for medical coders and physicians.
- Co-founder and CTO of **Causal Markets**, building AI analytics and agent tooling for prediction-market traders.
- Contributing to open-source AI/ML projects: docling, sentence-transformers, MTEB, txtai, PEFT and more ([full log](https://github.com/MaiAditya/oss-contributions)).

### Open-source contributions

<!-- oss-contributions:start -->

14 merged, 27 in review across 19 repositories. Full log with commits and diffs: [MaiAditya/oss-contributions](https://github.com/MaiAditya/oss-contributions)

| Project | PR | What I fixed |
|---|---|---|
| [huggingface/peft](https://github.com/huggingface/peft) | [#4157](https://github.com/huggingface/peft/pull/4157) | Fixed BOFT kernel shapes and made OFT Conv2d rotate the weight in forward, matching its merged output. |
| [neuml/txtai](https://github.com/neuml/txtai) | [#1561](https://github.com/neuml/txtai/pull/1561) | Routed a `[` after an operator to `bracket()` in `compound()` so these expressions translate correctly. |
| [reflex-dev/reflex](https://github.com/reflex-dev/reflex) | [#7866](https://github.com/reflex-dev/reflex/pull/7866) | Split strings by Unicode code points when the separator is empty, including runtime separators. |
| [embeddings-benchmark/mteb](https://github.com/embeddings-benchmark/mteb) | [#5880](https://github.com/embeddings-benchmark/mteb/pull/5880) | Returned an empty `ModelResult` with the model name and revision, without loading the model. |
| [embeddings-benchmark/mteb](https://github.com/embeddings-benchmark/mteb) | [#5879](https://github.com/embeddings-benchmark/mteb/pull/5879) | Filtered cached and merged results to the task's splits and subsets after saving, leaving the cache file intact. |
| [docling-project/docling](https://github.com/docling-project/docling) | [#5244](https://github.com/docling-project/docling/pull/5244) | Joined the section label and title into one heading, e.g. `## 1. Introduction`. |
| [neuml/txtai](https://github.com/neuml/txtai) | [#1550](https://github.com/neuml/txtai/pull/1550) | Counted nested parentheses in function arguments so each function ends at its own closing paren. |
| [neuml/txtai](https://github.com/neuml/txtai) | [#1535](https://github.com/neuml/txtai/pull/1535) | Split signs from operators when tokenizing SQL. |
| [embeddings-benchmark/mteb](https://github.com/embeddings-benchmark/mteb) | [#5870](https://github.com/embeddings-benchmark/mteb/pull/5870) | Added euclidean and manhattan support to `AbsEncoder` and a memory-bounded chunked `manhattan_sim`. |
| [docling-project/docling](https://github.com/docling-project/docling) | [#5283](https://github.com/docling-project/docling/pull/5283) | Added `<preformat>` and `<code>` blocks as code items, keeping line breaks and the code language. |
| [embeddings-benchmark/mteb](https://github.com/embeddings-benchmark/mteb) | [#5864](https://github.com/embeddings-benchmark/mteb/pull/5864) | Delegated pairwise similarity to the sentence-transformers model's own `similarity_pairwise`. |
| [huggingface/sentence-transformers](https://github.com/huggingface/sentence-transformers) | [#4313](https://github.com/huggingface/sentence-transformers/pull/4313) | Scored paraphrase mining with the model's own similarity function. |
| [docling-project/docling](https://github.com/docling-project/docling) | [#5078](https://github.com/docling-project/docling/pull/5078) | Kept image-only tables as pictures with their labels and captions. |
| [neuml/txtai](https://github.com/neuml/txtai) | [#1523](https://github.com/neuml/txtai/pull/1523) | Made each `similar()` clause keep its own number of results when clauses are batched. |

<!-- oss-contributions:end -->

### Experience

**Data Scientist, Martlet AI** · Jun 2026 – present
- Production agentic architecture combining classical ML and deep learning to identify and classify medical documents for patient charts (93.58% accuracy).
- AI assistant for medical coders and physicians to explore patient cohorts, clinical histories and coding workflows in natural language.
- Both systems are deployed with US pharmaceutical companies and healthcare organisations.

**Co-founder and CTO, Causal Markets** · Jan 2026 – present
- AI analytics, agentic automation and trading-intelligence products for prediction-market traders: 100+ DAU and 524+ users within weeks of launch.
- Three AI microtools (insider-trading detection, copy-trading intelligence, wallet analytics) serving 1,500+ users in the Polymarket community.
- Selected for Entrepreneur First, Antler founder cohorts and the Polymarket Builder Program.

**Jr. Data Scientist, John Snow Labs** · Jan 2025 – Jan 2026
- Multimodal agentic pipeline extracting images, tables and text from medical research PDFs for downstream NLP, retrieval and QA.
- LLM-powered SQL QueryBot over the OMOP clinical database using MCP, for natural-language querying of patient data.
- Reinforcement-learning-based guardrails framework against prompt-injection attacks, shipped as a private installable module.
- AI orchestration with Pydantic-AI, OpenAI APIs and Hugging Face models for RAG and structured generation.

**Co-founder and CTO, SummonLM** · Aug 2025 – Dec 2025
- AI-powered GEO automation and agentic content intelligence; 15+ product development contracts in the first months.

**ML Engineer Intern, Nurix AI** · Jul 2024 – Dec 2024
- LLM-powered agentic chatbot with Temporal and Conductor orchestration (20% faster responses).
- RAG-based agentic framework for API management (95% accuracy) using better chunking and re-ranking.
- Custom Airbyte source connector used in 10+ projects; copilot tools handling 80% of customer queries.

### Education

**Indian Institute of Technology, Roorkee** · 2020 – 2024
B.Tech, Metallurgical and Materials Engineering · CGPA 8.00/10

### Skills

- **Languages:** Python, C++, SQL
- **AI/ML:** PyTorch, TensorFlow, Hugging Face, LangChain, Pydantic-AI, RAG, agentic and multi-agent systems, LLM evaluation and guardrails
- **Models and APIs:** OpenAI, Claude, Gemini, Mistral, Llama
- **Infrastructure:** AWS, Google Cloud, Docker, Redis, Temporal, Airbyte

### Contact

[LinkedIn](https://www.linkedin.com/in/aditya-gupta-b0ab75200/) · [GitHub](https://github.com/MaiAditya)
