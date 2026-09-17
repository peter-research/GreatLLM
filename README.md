# GreatLLM

Some free LLM, vision models, image... All free.

Curated directory of **free or free-tier LLM / multimodal APIs**. Quotas change often — treat numbers as snapshots, not contracts. Prefer official docs over aggregators.

First commit of this repo started from [FreeLLM](https://freellm.net/) and the awesome free-LLM lists. Each pass: research → check reviews / official pages → commit **README only**, **new provider names only**.

## New this pass (2026-09-17 night-2)

Research: [YoannDev90/awesome-free-ai-api](https://github.com/YoannDev90/awesome-free-ai-api) (78 APIs, last checked 2026-09-16/17), [velo4705/awesome-free-byok-models](https://github.com/velo4705/awesome-free-byok-models) (AnyAPI, ElectronHub, FastRouter, MegaNova, Mixlayer, Intern AI, Naga AI), [freellm.net/providers](https://freellm.net/providers/), [Gratisfy](https://gratisfy.xyz/).
Reviews: community lists mark A4F / AI Pooled / AwanLLM / BazaarLink / BlazeAI / FastRouter / LiteRouter as live OpenAI-compat gateways with thin free lanes. ElectronHub and AnyAPI are credit hubs (free signup, paid catalog after burn). MegaNova is RP-shaped (Manta series). Coze and watsonx are product / cloud consoles, not Groq-class pools. Cerebras stays delisted.
**New names only** — none of these rows were provider lines in the evening-2 README (`208c0062`).

| Provider | Free access | RPD | TKPD | Best for | Notes |
| --- | --- | ---: | ---: | --- | --- |
| [A4F](https://www.a4f.co/models) | Registration, no card cited | Catalog-capped | Catalog-capped | Multi-model gateway | Listed live on awesome-free-ai-api 2026-09-16. OpenAI-compat via Gratisfy maps. |
| [AI Pooled](https://ai.pooled.dev) | Signup | Catalog-capped | Catalog-capped | Shared OSS pool | Community gateway. Treat as experiment, not SLA. |
| [AIchixia](https://www.aichixia.xyz/) | Signup | Catalog-capped | Catalog-capped | Thin OSS catalog | Marked tested 2026-09-16 on the awesome list. |
| [AnyAPI](https://anyapi.ai) | Free plan, no card | Credit-shaped | ~100k tok/day cited on BYOK lists | 400+ model router | `https://api.anyapi.ai/v1`. Free credits then pay. |
| [Apertis](https://apertis.ai) | Signup | Price-sorted catalog | Unpublished | Cheap / free rows | Sort catalog by price_low; verify $0 ids live. |
| [AwanLLM](https://www.awanllm.com/models) | Signup | Catalog-capped | Catalog-capped | Hosted OSS chat | OpenAI-compat listed on Gratisfy. |
| [BazaarLink](https://bazaarlink.ai/free) | Dedicated /free page | Catalog-capped | Catalog-capped | Free-lane hub | Explicit free landing; still an aggregator. |
| [BlazeAI](https://blazeai.boxu.dev/#models) | Signup | Catalog-capped | Catalog-capped | Small public catalog | Hobby host. Check uptime before depending on it. |
| [Coze](https://www.coze.com/open) | Login | Product-capped | Product-capped | Bot / agent builder | ByteDance console. Bundled models, not a raw multi-tenant SaaS. |
| [DGrid AI](https://dgrid.ai/models/dgridai/free/) | Free model path | Catalog-capped | Catalog-capped | Listed free rows | `/models/dgridai/free/` is the official free slice. |
| [Electron Hub](https://www.electronhub.ai/) | Signup credits | Credit-shaped | Credit-shaped | 600+ model one-key | Unified API. Free lane is trial credits; rest is $ plans. |
| [EvolveX](https://www.evolvex.gg/) | Signup | Catalog-capped | Catalog-capped | Gaming / chat API | Docs at evolvex.gg/docs. Niche host. |
| [FastRouter](https://fastrouter.ai/models/) | `:free` suffix, no billing credits | ~10 req/day/model cited | Tight cap | Eval many `:free` ids | OpenAI-compat. Good for sampling, bad for agents. |
| [LiteRouter](https://literouter.com/model_list) | Signup | Catalog-capped | Catalog-capped | Lightweight router | Listed live 2026-09-16. |
| [MegaNova](https://console.meganova.ai/serverless) | Daily free credits | Credit-shaped | Daily reset cited | RP / Manta series | `https://inference.meganova.ai/v1`. Popular on Janitor / Chub. |
| [Mixlayer](https://mixlayer.com) | Signup cited on BYOK lists | Unpublished | Unpublished | Serverless mix | Appears on awesome-free-byok-models; verify live quota. |

## Previous pass (2026-09-17 evening-2)

Evening-2 rows (do not re-add): DeepInfra, Parasail, Lambda AI, Modal, SEA-LION (AI Singapore), ArliAI, Zed, Bolt.new, Lovable, v0 by Vercel, Replit Starter, Cursor Hobby, Windsurf, Devin Free, Qoder, Google Colab, Kaggle Notebooks.

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
- [Gratisfy](https://gratisfy.xyz/)
