# GreatLLM

Some free LLM, vision models, image... All free.

Curated directory of **free or free-tier LLM / multimodal APIs**. Quotas change often — treat numbers as snapshots, not contracts. Prefer official docs over aggregators.

## New this pass (2026-09-17 night)

Research: freellm.net providers + changelog 2026-09-17, open-free-llm-api/awesome-freellm-apis (refreshed 2026-09-17), mvalentsev/awesome-free-ai-coding probes 2026-09-17 (LLM7.io + Nous Portal added the same day), nejib1/Free-LLM / free-llm.com, ClawLabsAI/free-ai-models daily dump, AIHubMix free-catalog blog, Pollinations / SambaNova / Hetzner experiment pages, community reviews on r/LLMDevs and r/LocalLLM (Gemini / Groq / OpenRouter still the reliable core; new names are the long tail).
Reviews: mvalentsev last-verified 2026-09-17 for LLM7.io, SambaNova, Hetzner Inference, Pollinations.AI, AIHubMix, Freebuff, Routeway, LLMTR, Nous Portal, opencode, Cline, Vercel AI Gateway, Regolo AI, Alibaba DashScope international, Hugging Face Inference, FreeInference. Cerebras and Infomaniak stay delisted. Aggregators marked as such.
**New names only** — none of these rows were provider lines in the evening README (`6b9c920`).

| Provider | Free access | RPD | TKPD | Best for | Notes |
| --- | --- | ---: | ---: | --- | --- |
| [LLM7.io](https://llm7.io) | Anonymous + free token | ~60/h anon; token lifts RPM | 500k anon / 1M with token | No-account OpenAI-compat | Added on awesome-free-ai-coding 2026-09-17; `https://api.llm7.io/v1`. Operator does not name upstreams. |
| [SambaNova Cloud](https://cloud.sambanova.ai) | Free while no card linked | 20 / model | 200k / model | gpt-oss / Gemma 4 / DeepSeek on RDU | Probe 2026-09-17: 20 RPM + 20 RPD per model. Linking a card ends the free lane. |
| [Hetzner Inference API](https://docs.hetzner.com/general/company-and-policy/experiments/inference/) | EU experiment, OpenAI-compat | Experiment-capped | Experiment-capped | Qwen 3.6 / 3.8 on Hetzner metal | Free only while the experiment runs. Good EU residency option. |
| [Pollinations.AI](https://pollinations.ai) | Keyless text API | ~1 req / 15s anonymous | Not published | gpt-oss + image/text toys | `POST https://text.pollinations.ai/openai`. Catalog is thin; no signup. |
| [AIHubMix](https://aihubmix.com) | Signup, $0 catalog rows | ~5 RPM / ~500 RPD cited | Not published | One key, subsidized frontier + OSS | Probe 2026-09-17 added glm-5.3 + kimi-k3. Aggregator — treat as unstable. |
| [Freebuff](https://freebuff.com) | Listed $0 coding lane | Not published | Not published | glm-5.3-flash / deepseek-v4.1-flash / mimo-v2.5 | Model set rotated 2026-09-17 (dropped v4-flash). Confirm live ids. |
| [Token Harbor](https://tokenharbor.com) | Listed $0 host | Not published | Not published | mimo-v2.5 / deepseek-v4.1-flash | Appears as sibling host to Freebuff on the 2026-09-17 family map. |
| [Routeway](https://routeway.ai) | `:free` suffix only | Catalog-capped | Catalog-capped | deepseek-v4-flash free ids | Only `:free` rows are $0; rest is metered. |
| [LLMTR](https://llmtr.com) | Public $0 chat rows | Not published | Not published | qwen3.6 / nemotron-3-ultra / Ling 3.0 | 13 $0 chat ids on 2026-09-16; some Ling / Dots rows expire late Sep 2026. |
| [Nous Portal](https://portal.nousresearch.com) | $0 Hermes Agent plan | Plan-capped | Plan-capped | Step 3.7 Flash / Laguna S 2.1 | Added 2026-09-17. OpenAI-compat; eight $0 ids on 2026-09-16. |
| [opencode](https://opencode.ai) | Keyless Zen gateway | Session / tool-capped | Session / tool-capped | Agent + raw $0 ids (mimo, nemotron, ling) | No card. Gateway also usable from other OpenAI clients. |
| [Cline](https://cline.bot) | Free agent + some $0 gateway ids | Tool-capped | Tool-capped | Laguna / Union Alpha via Cline | Dropped deepseek-v4-flash on 2026-09-17. More agent than raw SaaS. |
| [Vercel AI Gateway](https://vercel.com/ai-gateway) | Hobby / listed $0 rows | Plan-capped | Plan-capped | Laguna S 2.1 among free ids | Vercel account. Confirm which ids stay $0 vs credit. |
| [Regolo AI](https://regolo.ai/pricing/) | Registration, EU | See pricing page | See pricing page | gpt-oss / qwen3.8 / glm-5 / apertus-70b | EU host on the 2026-09-17 family map. |
| [Alibaba Cloud Model Studio](https://www.alibabacloud.com/help/en/model-studio/) | International DashScope signup | See DashScope free column | See DashScope free column | qwen3-coder / qwen3.8-max | Distinct from ModelScope (already listed). Phone / region checks apply. |
| [Hugging Face Inference](https://huggingface.co/docs/api-inference) | Account, no card | ~300 / hour cited | Credit-shaped routing | OSS routers + serverless | Free routing credit is small; not a fat RPD pool. |
| [FreeInference](https://freeinference.org) | Harvard SEAS listed host | Shared academic pool | Shared academic pool | qwen3.6 / deepseek-v4-flash / glm-5.3-flash | Academic / research-shaped capacity. Confirm ToS before bots. |

## Previous pass (2026-09-17 evening)

Kept from the prior commit. Same columns. See git history for the evening table (`6b9c920`) if this file is viewed in isolation.

Evening rows (do not re-add): Requesty, Kilo Code, OVHcloud AI Endpoints, SiliconFlow, ModelScope, Amazon Q Developer, AnyRouter, Google Antigravity, CodeGPT, QwenCloud, ZenMux, Kluster AI, Upstage, Featherless.ai, FriendliAI, Baseten.

Historical first-party + gateway list lives in earlier commits on `main` (Google AI Studio, Groq, NVIDIA NIM, OpenRouter `:free`, Cloudflare Workers AI, Z.AI GLM Flash, Mistral, Cohere, Ollama Cloud).

Start with **Google AI Studio**, **Groq**, **NVIDIA NIM**, **OpenRouter `:free`**, **Cloudflare Workers AI**, **Z.AI GLM Flash**, then **LLM7.io**, **SambaNova**, **Hetzner**, **opencode**, **AIHubMix**, **Requesty**.

* Approximate daily figures. Quotas change often.

### How this list is built

1. Scan public directories (FreeLLM, awesome-free lists).
2. Cross-check community reviews and official docs.
3. Keep **new providers only** when extending.
4. Flag aggregators and experiments: they disappear first.

### Sources checked

- [FreeLLM](https://freellm.net/providers/)
- [freellm.site](https://www.freellm.site/)
- [awesome-freellm-apis](https://github.com/open-free-llm-api/awesome-freellm-apis)
- [awesome-free-ai-api](https://github.com/YoannDev90/awesome-free-ai-api)
- [awesome-free-ai-coding](https://github.com/mvalentsev/awesome-free-ai-coding)
- [awesome-free-byok-models](https://github.com/velo4705/awesome-free-byok-models)
- [freeinference.dev](https://freeinference.dev/)
- [nejib1/Free-LLM](https://github.com/nejib1/Free-LLM)
- [awesome-free-inference](https://github.com/bradAGI/awesome-free-inference)
- [ClawLabsAI/free-ai-models](https://github.com/ClawLabsAI/free-ai-models)
