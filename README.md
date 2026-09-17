# GreatLLM

Some free LLM, vision models, image... All free.

Curated directory of **free or free-tier LLM / multimodal APIs**. Quotas change often — treat numbers as snapshots, not contracts. Prefer official docs over aggregators.

First commit of this repo started from [FreeLLM](https://freellm.net/) and the awesome free-LLM lists. Each pass: research → check reviews / official pages → commit **README only**, **new provider names only**.

## New this pass (2026-09-17 evening-2)

Research: freeinference.dev (33 hosts, snapshot 2026-09-16/17), mvalentsev/awesome-free-ai-coding (SEA-LION, ArliAI, Zed), velo4705/awesome-free-byok-models (AnyAPI, ElectronHub, FastRouter, MegaNova, Mixlayer, Intern AI, Naga AI), freellm.net changelog 2026-09-17, klymentiev.com/blog/free-llm-api (Cerebras now $5+card; GitHub Models retired 2026-07-30 — keep historical row, do not re-list as live).
Reviews: product-bundled builders (Bolt / Lovable / v0 / Replit / Cursor / Windsurf / Devin) are usable for artifacts, not raw multi-tenant SaaS. DeepInfra / Lambda / Modal / Parasail are credit or cheap-metered, not Groq-class permanent pools. SEA-LION and ArliAI are first-party or RP-shaped OSS hosts. Cerebras / Infomaniak / Kenari stay delisted.
**New names only** — none of these rows were provider lines in the late-afternoon README (`990580ad`).

| Provider | Free access | RPD | TKPD | Best for | Notes |
| --- | --- | ---: | ---: | --- | --- |
| [DeepInfra](https://deepinfra.com) | Signup credit then pay | After credit: paid | Trial-shaped | DeepSeek / Qwen / GLM OSS | `https://api.deepinfra.com/v1/openai`. High concurrency while credits last. |
| [Parasail](https://www.parasail.io) | Registration / cheap $0 rows | Catalog-capped | Catalog-capped | Private serverless OSS | OpenAI-compat. Some directories list a free lane; verify live ids. |
| [Lambda AI](https://lambda.ai) | ~$10 signup credit (hubs) | After credit: paid | Trial-shaped | GPU inference cluster | One-shot credit in awesome lists. Card after burn. |
| [Modal](https://modal.com) | ~$30/mo platform credit (hubs) | Credit-shaped | Credit-shaped | Run your own weights | Compute credit, not a hosted chat catalog. |
| [SEA-LION (AI Singapore)](https://sea-lion.ai) | Registration, no card | ~10 RPM cited | Unpublished | SEA languages + OSS | First-party OpenAI-compat API. Prototyping, not a production SLA. |
| [ArliAI](https://www.arliai.com) | Keyless catalog + keyed tier | Catalog-capped | Catalog-capped | RP / fine-tunes (Gemma, Qwen, MiMo) | `api.arliai.com` listed ~92 models on 2026-09-17. |
| [Zed](https://zed.dev) | Editor account, no card | Product-capped | Product-capped | gpt-5.6-luna class in IDE | Bundled agent models (cited on model maps). Not a public gateway. |
| [Bolt.new](https://bolt.new) | Login, no card | ~300k tok/day cap cited | ~1M tok/mo cited | Full-stack app builder | Frontier models bundled in the product. Artifact-first. |
| [Lovable](https://lovable.dev) | Login, no card | ~5 build credits/day cited | Product-capped | App builder (Fable 5.1) | Credits, not raw tokens. |
| [v0 by Vercel](https://v0.app) | Vercel login, no card | ~7 msgs/day cited | ~$5 credits/mo cited | UI generation | Distinct from Vercel AI Gateway (already listed). |
| [Replit Starter](https://replit.com) | Login, no card | Daily Agent allowance | Unpublished cloud credits | Cloud IDE agent | Bundled frontier models. 1 published app on Starter. |
| [Cursor Hobby](https://cursor.com) | Login, no card | Unpublished Agent + Tab | Product-capped | Composer 2 + Auto | Quota unpublished. Fine to try; poor as an SDK. |
| [Windsurf](https://windsurf.com) | Login, no card | Light unpublished quota | Unlimited Tab cited | Cascade / Auto frontier | Product inference, not embeddable API. |
| [Devin Free](https://devin.ai) | Login, no card | Light unpublished quota | Product-capped | SWE-1.7 / SWE-2 agents | Autonomous SWE agent, not a chat API. |
| [Qoder](https://qoder.com) | Login, no card + BYOK | Unpublished NES / completions | Product-capped | Completions + BYO key | Free basic models; serious work needs BYOK. |
| [Google Colab](https://colab.research.google.com) | Google login, no card | Session-capped (~12h) | GPU hours unpublished | Run local / OSS weights | Not an API host. Free GPU/TPU for notebooks. |
| [Kaggle Notebooks](https://www.kaggle.com) | Account; phone may apply | Weekly GPU hours | ~30 GPU-h/week cited | Train / infer OSS on P100/T4 | Self-load weights. Resets weekly. |

## Previous pass (2026-09-17 late afternoon)

Late-afternoon rows (do not re-add): Agnes AI, VLM Run Gateway, Novita AI, Scaleway Generative APIs, Hyperbolic, Lepton AI, Avian.io, Inception Labs (Mercury), Opper, Kiro, Google Jules, GitHub Copilot Free, Trae, Poe, Dify Cloud, Replicate.

## Previous pass (2026-09-17 afternoon)

Afternoon rows (do not re-add): GitHub Models, Aion Labs, Chutes.ai, Nscale, Nebius Token Factory, DeepSeek, xAI, AI21 Labs, glhf.chat, Moonshot / Kimi, MiniMax, Venice.ai, Together AI, Fireworks AI, Inference.net, AI Horde.

## Previous pass (2026-09-17 night)

Night rows (do not re-add): LLM7.io, SambaNova Cloud, Hetzner Inference API, Pollinations.AI, AIHubMix, Freebuff, Token Harbor, Routeway, LLMTR, Nous Portal, opencode, Cline, Vercel AI Gateway, Regolo AI, Alibaba Cloud Model Studio, Hugging Face Inference, FreeInference.

## Previous pass (2026-09-17 evening)

Evening rows (do not re-add): Requesty, Kilo Code, OVHcloud AI Endpoints, SiliconFlow, ModelScope, Amazon Q Developer, AnyRouter, Google Antigravity, CodeGPT, QwenCloud, ZenMux, Kluster AI, Upstage, Featherless.ai, FriendliAI, Baseten.

Historical first-party + gateway list lives in earlier commits on `main` (Google AI Studio, Groq, NVIDIA NIM, OpenRouter `:free`, Cloudflare Workers AI, Z.AI GLM Flash, Mistral, Cohere, Ollama Cloud).

Start with **Google AI Studio**, **Groq**, **NVIDIA NIM**, **OpenRouter `:free`**, **Cloudflare Workers AI**, **Z.AI GLM Flash**, then **LLM7.io**, **SambaNova**, **DeepSeek** (while the grant lasts), **Aion Labs** for RP, **Agnes AI** / **VLM Run** for a thin extra lane. Treat **GitHub Models** as retired (2026-07-30) unless NVIDIA/GitHub reverse it.

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
- [klymentiev free LLM API review](https://klymentiev.com/blog/free-llm-api)
