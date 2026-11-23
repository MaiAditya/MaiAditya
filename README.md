## Hi, I'm Aditya Gupta

AI engineer working on agentic systems, retrieval and LLM applications for healthcare and fintech. I build production pipelines end to end: data extraction, RAG, multi-agent orchestration, evaluation and deployment. I also contribute bug fixes to open-source AI/ML libraries.

**Currently**
- Data Scientist at **Martlet AI**, building clinical document classification and an AI assistant for medical coders and physicians.
- Co-founder and CTO of **Causal Markets**, building AI analytics and agent tooling for prediction-market traders.
- Contributing to open-source AI/ML projects: docling, sentence-transformers, MTEB, txtai, PEFT and more ([full log](https://github.com/MaiAditya/oss-contributions)).

### Open-source contributions

<!-- oss-contributions:start -->

41 merged, 45 in review across 35 repositories. Full log with commits and diffs: [MaiAditya/oss-contributions](https://github.com/MaiAditya/oss-contributions)

| Project | PR | What I fixed |
|---|---|---|
| [comet-ml/opik](https://github.com/comet-ml/opik) | [#9548](https://github.com/comet-ml/opik/pull/9548) | Capped the n-gram order at the shorter text's length so only orders both sides can produce are averaged. |
| [huggingface/sentence-transformers](https://github.com/huggingface/sentence-transformers) | [#4420](https://github.com/huggingface/sentence-transformers/pull/4420) | Made `prompt` and `task` reserved column names for the CrossEncoder trainer, so such datasets now fail with a clear error. |
| [neuml/txtai](https://github.com/neuml/txtai) | [#1648](https://github.com/neuml/txtai/pull/1648) | Stopped forwarding `stream` and `maxlength` to `search()` and `workflow()`, and sent streamed string results as one chunk. |
| [neuml/txtai](https://github.com/neuml/txtai) | [#1640](https://github.com/neuml/txtai/pull/1640) | Added `OpenAI` LLM and vectors providers on the OpenAI client, with LiteLLM still checked first in autodetect. |
| [neuml/txtai](https://github.com/neuml/txtai) | [#1638](https://github.com/neuml/txtai/pull/1638) | Forwarded any parameter that is not `None` in the LLM and RAG routers, so `False` reaches the pipeline. |
| [medplum/medplum](https://github.com/medplum/medplum) | [#11539](https://github.com/medplum/medplum/pull/11539) | Mapped Act status through `PROCEDURE_STATUS_MAPPER` and mapped `active` to `in-progress`, with tests. |
| [neuml/txtai](https://github.com/neuml/txtai) | [#1624](https://github.com/neuml/txtai/pull/1624) | Set the configured `name` and `description` on tools built by `smolagents.tool`, keeping the function values if unset. |
| [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) | [#9595](https://github.com/crewAIInc/crewAI/pull/9595) | Opted `SaveArtifactTool` out of caching with `_never_cache_function`, so each call saves a new version. |
| [reflex-dev/reflex](https://github.com/reflex-dev/reflex) | [#7880](https://github.com/reflex-dev/reflex/pull/7880) | Added `_forwarded_client_ip()` to strip ports and brackets, normalise addresses and fall back to the peer address if invalid. |
| [Arize-ai/openinference](https://github.com/Arize-ai/openinference) | [#4416](https://github.com/Arize-ai/openinference/pull/4416) | Mapped cached prompt and cache creation tokens to `llm.token_count.prompt_details.cache_read` and `cache_write` when non-zero. |
| [huggingface/sentence-transformers](https://github.com/huggingface/sentence-transformers) | [#4410](https://github.com/huggingface/sentence-transformers/pull/4410) | Replaced constructor `assert`s with `ValueError`s for empty input, length mismatch and non-0/1 binary labels. |
| [neuml/txtai](https://github.com/neuml/txtai) | [#1621](https://github.com/neuml/txtai/pull/1621) | Caught the `smolagents` exception in `ToolFactory.createtool` so the docstring fallback runs, and added tests. |
| [Arize-ai/openinference](https://github.com/Arize-ai/openinference) | [#4367](https://github.com/Arize-ai/openinference/pull/4367) | Recorded `cached_tokens` and `reasoning_tokens` as span attributes, matching the groq instrumentor. |
| [huggingface/sentence-transformers](https://github.com/huggingface/sentence-transformers) | [#4354](https://github.com/huggingface/sentence-transformers/pull/4354) | Used the untruncated embedding dimension in `MatryoshkaLoss` and `EmbedDistillLoss`. |
| [neuml/txtai](https://github.com/neuml/txtai) | [#1602](https://github.com/neuml/txtai/pull/1602) | Returned an empty result per query in the Faiss ANN backend's `search` when the limit is 0, and added dense and hybrid tests. |
| [embeddings-benchmark/mteb](https://github.com/embeddings-benchmark/mteb) | [#5929](https://github.com/embeddings-benchmark/mteb/pull/5929) | Materialized `models` and `tasks` into lists once at entry so iterators and empty inputs work. |
| [PostHog/posthog-python](https://github.com/PostHog/posthog-python) | [#1277](https://github.com/PostHog/posthog-python/pull/1277) | Matched the project root on directory boundaries: the path equals the root or starts with the root plus `os.sep`. |
| [embeddings-benchmark/mteb](https://github.com/embeddings-benchmark/mteb) | [#5906](https://github.com/embeddings-benchmark/mteb/pull/5906) | Added an `evaluated_splits` argument to `save_to_cache` so only subsets that were actually run get run settings. |
| [huggingface/sentence-transformers](https://github.com/huggingface/sentence-transformers) | [#4397](https://github.com/huggingface/sentence-transformers/pull/4397) | Resolved the default similarity function names on each call and rebuilt the CSV headers when they changed. |
| [neuml/txtai](https://github.com/neuml/txtai) | [#1592](https://github.com/neuml/txtai/pull/1592) | Pinned `llama-cpp-python==0.3.36` in the Windows dependency step of the build workflow. |
| [neuml/txtai](https://github.com/neuml/txtai) | [#1579](https://github.com/neuml/txtai/pull/1579) | Added `Cluster.limit` to slice merged results by the query's `LIMIT`, falling back to the request limit. |
| [neuml/txtai](https://github.com/neuml/txtai) | [#1577](https://github.com/neuml/txtai/pull/1577) | Added `Indexes.implements` and checked subindex ANNs up front so these calls raise `NotImplementedError` first. |
| [neuml/txtai](https://github.com/neuml/txtai) | [#1571](https://github.com/neuml/txtai/pull/1571) | Added `case` keywords as conditionals and stopped treating the token after `and`/`or` as an alias. |
| [neuml/txtai](https://github.com/neuml/txtai) | [#1569](https://github.com/neuml/txtai/pull/1569) | Moved `null` from `Token.OPERATORS` to the literals, next to `true` and `false`. |
| [PostHog/posthog-python](https://github.com/PostHog/posthog-python) | [#1267](https://github.com/PostHog/posthog-python/pull/1267) | Marked the resolved `exc_info` as captured and skipped already-marked ones in `Client` and `AsyncClient`. |
| [huggingface/sentence-transformers](https://github.com/huggingface/sentence-transformers) | [#4383](https://github.com/huggingface/sentence-transformers/pull/4383) | Added the main similarity to the STS and triplet evaluators, and made IR evaluators raise a `ValueError` at construction. |
| [PostHog/posthog-python](https://github.com/PostHog/posthog-python) | [#1256](https://github.com/PostHog/posthog-python/pull/1256) | Appended output blocks and tool results per generation and promoted queued input at the next `message_start`. |
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
