# GreatLLM

Some free LLM, vision models, image... All free.

Curated directory of **free or free-tier LLM / multimodal APIs**. Quotas change often — treat numbers as snapshots, not contracts. Prefer official docs over aggregators.

First commit of this repo started from [FreeLLM](https://freellm.net/) and the awesome free-LLM lists. Each pass: research → check reviews / official pages → commit **README only**, **new provider names only**.

## New this pass (2026-09-17 late afternoon)

Research: freellm.net/providers (31 hosts, 2026-09-17), open-free-llm-api/awesome-freellm-apis, mvalentsev/awesome-free-ai-coding (Kiro / Jules / Copilot Free / VLM Run / Opper / Inception / Agnes), nejib1/Free-LLM + free-llm.com (Novita, Scaleway, Hyperbolic, Lepton), freeinference.dev (Trae, Poe, Dify, Copilot), felipetruman/free-llm-hub (Avian.io).
Reviews: Agnes AI is live on freellm.net with 5 models. VLM Run Gateway is probe-noted as anonymous IP quota. Novita / Scaleway / Hyperbolic / Lepton are credit or $0-token lanes, not Groq-class permanent pools. Kiro / Jules / Copilot Free / Trae are product-bundled inference, not raw multi-tenant SaaS. Cerebras and Infomaniak stay delisted.
**New names only** — none of these rows were provider lines in the afternoon README (`8443c1c`).

| Provider | Free access | RPD | TKPD | Best for | Notes |
| --- | --- | ---: | ---: | --- | --- |
| [Agnes AI](https://platform.agnes-ai.com/settings/apiKeys) | Registration, no card | Catalog-capped | Catalog-capped | agnes-2.x / 3.0 flash multimodal | `https://platform.agnes-ai.com` keys. Listed on freellm.net (~5 models). |
| [VLM Run Gateway](https://docs.vlm.run) | Anonymous IP quota + keyed tier | ~100 / IP (anon) | Anon-capped | Qwen3.8-27B style VL + text | Alpha gateway. ~10 RPM / 30 RPH / 100 RPD per IP without a key. |
| [Novita AI](https://novita.ai) | Signup voucher + some $0 models | After credit: paid | ~$0.50 then pay | OSS + image/GPU sidecar | `https://api.novita.ai/v3/openai`. A few $0/token OSS ids reported; voucher is one-shot. |
| [Scaleway Generative APIs](https://console.scaleway.com/generative-api/models) | Signup token grant (EU) | Grant then pay | ~1M tokens cited | FR / EU OSS (Llama / Qwen / gpt-oss) | `https://api.scaleway.ai/v1`. Credit, not a fat permanent pool. |
| [Hyperbolic](https://hyperbolic.xyz) | Small signup credit | After credit: paid | Trial-shaped | Cheap OSS cluster | One-shot ~$1 class credit in directories. Card for anything serious. |
| [Lepton AI](https://www.lepton.ai) | Signup credit | After credit: paid | Trial-shaped | Fast OSS endpoints | ~$10 trial rows appear in hubs. Not permanent $0. |
| [Avian.io](https://avian.io) | Freemium listing | Catalog-capped | Catalog-capped | Llama / Qwen host | Appears on free-llm-hub as freemium. Verify live models before agents. |
| [Inception Labs (Mercury)](https://www.inceptionlabs.ai) | Registration / trial | Catalog-capped | Catalog-capped | Mercury diffusion LLMs | mercury-2 / 2.5 cited on awesome-free-ai-coding. Diffusion, not a GPT clone. |
| [Opper](https://opper.ai) | Registration | Catalog-capped | Catalog-capped | Gemma-4-31B routing | Named as a free Gemma-4 host on mvalentsev model map. Confirm console. |
| [Kiro](https://kiro.dev) | Social / AWS Builder ID, no card | ~50 credits / mo | Credit-shaped | Qwen Coder / DeepSeek / Claude in IDE | Product quota, not a raw public API you embed everywhere. |
| [Google Jules](https://jules.google) | Google login, no card | Product-capped | Product-capped | Gemini-family coding agent | Bundled Gemini 2.5-class work. Not AI Studio keys. |
| [GitHub Copilot Free](https://github.com/features/copilot) | GitHub account, no card | ~2k completions / mo | Unpublished AI credits | IDE + CLI bundled models | Distinct from GitHub Models inference API. Auto-selected models. |
| [Trae](https://www.trae.ai) | Registration, no card | ~5k autocompletes / mo | Product-capped | ByteDance IDE agent | Frontier models bundled in the product UI. |
| [Poe](https://poe.com) | Login, daily points | Daily reset | Unpublished points | Chat access to many frontier ids | Resale / points. Fine to try models; poor as a production SDK. |
| [Dify Cloud](https://dify.ai) | Sandbox credits | One-shot ~200 msgs | Trial-shaped | Agent builder + routed models | Then BYO key. Good to prototype apps, not a raw LLM host. |
| [Replicate](https://replicate.com) | Tiny signup credit | After credit: paid | Credit-shaped | OSS + image / video models | Pay-per-run after the trial. Useful for multimodal experiments. |

## Previous pass (2026-09-17 afternoon)

Kept from the prior commit. Same columns. See git history (`8443c1c`) if this file is viewed in isolation.

Afternoon rows (do not re-add): GitHub Models, Aion Labs, Chutes.ai, Nscale, Nebius Token Factory, DeepSeek, xAI, AI21 Labs, glhf.chat, Moonshot / Kimi, MiniMax, Venice.ai, Together AI, Fireworks AI, Inference.net, AI Horde.

## Previous pass (2026-09-17 night)

Night rows (do not re-add): LLM7.io, SambaNova Cloud, Hetzner Inference API, Pollinations.AI, AIHubMix, Freebuff, Token Harbor, Routeway, LLMTR, Nous Portal, opencode, Cline, Vercel AI Gateway, Regolo AI, Alibaba Cloud Model Studio, Hugging Face Inference, FreeInference.

## Previous pass (2026-09-17 evening)

Evening rows (do not re-add): Requesty, Kilo Code, OVHcloud AI Endpoints, SiliconFlow, ModelScope, Amazon Q Developer, AnyRouter, Google Antigravity, CodeGPT, QwenCloud, ZenMux, Kluster AI, Upstage, Featherless.ai, FriendliAI, Baseten.

Historical first-party + gateway list lives in earlier commits on `main` (Google AI Studio, Groq, NVIDIA NIM, OpenRouter `:free`, Cloudflare Workers AI, Z.AI GLM Flash, Mistral, Cohere, Ollama Cloud).

Start with **Google AI Studio**, **Groq**, **NVIDIA NIM**, **OpenRouter `:free`**, **Cloudflare Workers AI**, **Z.AI GLM Flash**, then **GitHub Models**, **LLM7.io**, **SambaNova**, **DeepSeek** (while the grant lasts), **Aion Labs** for RP, **Agnes AI** / **VLM Run** for a thin extra lane.

* Approximate daily figures. Quotas change often.

### How this list is built

1. Scan public directories (FreeLLM, awesome-free lists).
2. Cross-check community reviews and official docs.
3. Keep **new providers only** when extending.
4. Flag aggregators, one-shot credits, and experiments: they disappear first.

### Sources checked

- [FreeLLM](https://freellm.net/providers/)
- [freellm.site](https://www.freellm.site/)
- [awesome-freellm-apis](https://github.com/open-free-llm-api/awesome-freellm-apis)
- [mnfst/awesome-free-llm-apis](https://github.com/mnfst/awesome-free-llm-apis)
- [awesome-free-ai-api](https://github.com/YoannDev90/awesome-free-ai-api)
- [awesome-free-ai-coding](https://github.com/mvalentsev/awesome-free-ai-coding)
- [awesome-free-byok-models](https://github.com/velo4705/awesome-free-byok-models)
- [freeinference.dev](https://freeinference.dev/)
- [nejib1/Free-LLM](https://github.com/nejib1/Free-LLM)
- [awesome-free-inference](https://github.com/bradAGI/awesome-free-inference)
- [DataTalksClub awesome-llms](https://github.com/DataTalksClub/llm-zoomcamp/blob/main/awesome-llms.md)
- [ClawLabsAI/free-ai-models](https://github.com/ClawLabsAI/free-ai-models)
- [felipetruman/free-llm-hub](https://github.com/felipetruman/free-llm-hub)
