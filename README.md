# GreatLLM

Some free LLM, vision models, image... All free.

Curated directory of **free or free-tier LLM / multimodal APIs**. Quotas change often — treat numbers as snapshots, not contracts. Prefer official docs over aggregators.

First commit of this repo started from [FreeLLM](https://freellm.net/) and the awesome free-LLM lists. Each pass: research → check reviews / official pages → commit **README only**, **new provider names only**.

## New this pass (2026-09-24)

Research: [FreeLLM](https://freellm.net/providers/), [awesome-freellm-apis](https://github.com/open-free-llm-api/awesome-freellm-apis), the [ElevenLabs pricing page](https://elevenlabs.io/pricing), and independent free-tier reviews. ElevenLabs is a new multimodal provider name in this README. Its official pricing page currently lists a $0 plan with 10,000 credits/month shared across text-to-speech, speech-to-text, sound effects, voice design, music, image, and related tools. Independent trackers report that API access is available on the free plan, but the tier is non-commercial and limits/concurrency are not published as a simple RPD/TKPD quota. Community reports also mention API restrictions for some voice-library assets, so this entry is best treated as an evaluation lane rather than production capacity.

| Provider | Free access | RPD | TKPD | Best for | Notes |
| --- | --- | ---: | ---: | --- | --- |
| [ElevenLabs](https://elevenlabs.io/) | $0 plan with 10,000 credits/month | Unpublished | Unpublished | Text-to-speech, speech-to-text, audio generation | Official pricing lists 10k monthly credits across multiple audio/creative features. The free plan is non-commercial; API concurrency and exact request limits are not published. Community reports say some voice-library assets require a paid plan through the API, so verify the exact voice/model before use. |

## New this pass (2026-09-23)

Research: [FreeLLM](https://freellm.net/providers/), [awesome-freellm-apis](https://github.com/open-free-llm-api/awesome-freellm-apis), the [9Router official site](https://9router.com/), and its [official API page](https://api.9router.com/). 9Router is a new provider name in this README. Its free tier is a local/open-source routing gateway rather than a hosted model quota: it exposes an OpenAI-compatible local endpoint and routes across free, subscription, and paid providers. The site explicitly lists a free tier and no-card setup, while the exact upstream free-model availability can change.

| Provider | Free access | RPD | TKPD | Best for | Notes |
| --- | --- | ---: | ---: | --- | --- |
| [9Router](https://9router.com/) | Free, open-source local gateway | Unpublished | Unpublished | Coding agents, fallback routing, token saving | Runs locally at `http://localhost:20128/v1` and can route across 60+ providers. The official site advertises a no-card free tier and free upstream lanes such as iFlow, Qwen, Kiro, and OpenCode; upstream quotas and model availability are not guaranteed by 9Router. |

## New this pass (2026-09-22)

Research: [FreeLLM](https://freellm.net/providers/), [awesome-freellm-apis](https://github.com/open-free-llm-api/awesome-freellm-apis), and current provider pages. Codiv is a new provider name in this README; its official site and docs describe a free public inference experiment with separate free token quotas for its System One endpoint and text-generation endpoint. The free quotas are explicitly documented, while shared-capacity overloads can still return 529 errors.

| Provider | Free access | RPD | TKPD | Best for | Notes |
| --- | --- | ---: | ---: | --- | --- |
| [Codiv](https://codiv.ai/) | Free public experiment | Unpublished | 100M input/thought tokens + 10M text-generation tokens (lifetime quota) | Structured classification, typed decisions, low-latency inference | Official docs list separate free quotas: 100M tokens for System One and 10M tokens for chat completions. Default rate limit is 1,200 requests/minute per key, but shared capacity can return 529 overload errors. |

## Previous pass (2026-09-20)

Research: [FreeLLM](https://freellm.net/providers/), [awesome-freellm-apis](https://github.com/open-free-llm-api/awesome-freellm-apis), and current provider pages. Openference is a new provider name in this README; its official pricing page confirms a no-card 3-day free trial for open-source models, while the public site documents an OpenAI-compatible endpoint and routing/failover. Community tracking reports a 350-requests/week trial snapshot, but that number is not treated as an official guarantee.

| Provider | Free access | RPD | TKPD | Best for | Notes |
| --- | --- | ---: | ---: | --- | --- |
| [Openference](https://www.openference.com/) | 3-day free trial, no credit card | Community snapshot: ~50/day | Unpublished | Open-source model routing, coding agents | Official pricing describes a 3-day trial with included usage and no card. Public site advertises one OpenAI-compatible endpoint with failover. Community tracker reports ~350 requests/week; treat this as a changing snapshot, not a contract. |

## Previous pass (2026-09-17 night-3)

Research: [YoannDev90/awesome-free-ai-api](https://github.com/YoannDev90/awesome-free-ai-api) (daily site check 2026-09-16/17), [velo4705/awesome-free-byok-models](https://github.com/velo4705/awesome-free-byok-models) (Void AI, Intern AI, xKiro), [foisalislambd/all-llm-provider-list](https://github.com/foisalislambd/all-llm-provider-list), [FreeTheAi](https://freetheai.xyz/), [Gratisfy](https://gratisfy.xyz/), [freellm.net/providers](https://freellm.net/providers/).
Reviews: community lists mark Atessa / CoderPlan / Completions / Crax GPT / Flowbar / FreeTheAI / Hubs02225 / LLM Gateway / Logfare / Mixedbread / MNN AI / NagaAI / Nexusify / Ofox / OhMyGPT as live OpenAI-compat or console hosts (tested ✅ on 2026-09-16 except AquaDevs / Navy / Void which stay untested on that table). Void AI is still cited on BYOK lists for high RPM coding ids. watsonx is IBM cloud, not a Groq-class pool. Cerebras stays delisted as a card-gated credit.
**New names only** — none of these rows were provider lines in the night-2 README (`e52fef00`).

| Provider | Free access | RPD | TKPD | Best for | Notes |
| --- | --- | ---: | ---: | --- | --- |
| [Atessa](https://atessa.top/) | Signup | Catalog-capped | Catalog-capped | Small public catalog | Marked tested 2026-09-16 on awesome-free-ai-api. |
| [CoderPlan](https://coderplan.ai) | Signup | Catalog-capped | Catalog-capped | Coding-oriented catalog | Docs + `/models` on the same host. |
| [Completions](https://www.completions.me) | Signup | Catalog-capped | Catalog-capped | Chat completions host | Hobby OpenAI-compat surface. |
| [Crax GPT](https://gpt.crax.lol/) | Signup | Catalog-capped | Catalog-capped | Thin public models page | `/models` listed; treat as experiment. |
| [Flowbar AI](https://flowbarai.com/pricing) | Signup | Catalog-capped | Catalog-capped | Priced catalog with free rows | Verify $0 ids on the pricing page before depending on it. |
| [FreeTheAI](https://freetheai.xyz/) | Discord key + daily `/checkin` | Community-capped | Unpublished | One-key OpenAI-compat gateway | Base `https://api.freetheai.xyz/v1`. No card. Optional paid slots exist. |
| [Hubs02225](https://hubs02225.snia.ch/) | Signup | Catalog-capped | Catalog-capped | Small Swiss-hosted catalog | Listed live on Gratisfy maps. |
| [IBM watsonx.ai](https://cloud.ibm.com/docs/apis/watsonx-ai) | IBM Cloud trial / lite | Product-capped | Product-capped | Enterprise console models | Cloud product, not a multi-tenant hobby pool. |
| [LLM Gateway](https://llmgateway.io/models?filters=1&free=true) | Signup, free filter | Catalog-capped | Catalog-capped | Filtered `:free` catalog | OpenAI-compat `https://api.llmgateway.io/v1`. |
| [Logfare](https://logfare.ai/) | Signup | Catalog-capped | Catalog-capped | Lightweight router | Base cited as `https://logfare.ai/v1`. |
| [Mixedbread](https://www.mixedbread.com/pricing) | Signup | Unpublished | Unpublished | Embeddings + retrieval | Retrieval-first vendor; chat may be thin. |
| [MNN AI](https://mnnai.ru/) | Signup | Catalog-capped | Catalog-capped | RU-hosted OpenAI-compat | Base cited as `https://api.mnnai.ru/v1`. |
| [NagaAI](https://naga.ac/models) | Signup | Catalog-capped | Catalog-capped | Multi-model catalog | Also appears on BYOK aggregator lists. |
| [Nexusify](https://docs.nexusify.co/) | Signup | Catalog-capped | Catalog-capped | Documented gateway | Check docs for live free ids. |
| [Ofox](https://ofox.ai/models) | Signup | Catalog-capped | Catalog-capped | Public models page | Base cited as `https://api.ofox.ai/v1`. |
| [OhMyGPT](https://www.ohmygpt.com/pricing) | Signup credits | Credit-shaped | Credit-shaped | One-key multi-model hub | Free lane is trial credits; rest is $ plans. |
| [Void AI](https://api.voidai.app/v1) | Signup cited on BYOK lists | High RPM cited (~100) | ~125k daily credits cited | Fast coding ids | awesome-free-ai-api still marks it untested on 2026-09-16 — verify before production. |

## Previous pass (2026-09-17 night-2)

Night-2 rows (do not re-add): A4F, AI Pooled, AIchixia, AnyAPI, Apertis, AwanLLM, BazaarLink, BlazeAI, Coze, DGrid AI, Electron Hub, EvolveX, FastRouter, LiteRouter, MegaNova, Mixlayer, OpenCode Zen.

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
- [FreeTheAi](https://freetheai.xyz/)
- [all-llm-provider-list](https://github.com/foisalislambd/all-llm-provider-list)
- [OpenCode Zen community tracker](https://github.com/thelabcorner/opencode-zen-fut-api)
- [OpenCode Zen pricing mirror](https://llmprice.gitlab.io/providers/opencode/)
- [Openference official site](https://www.openference.com/)
- [Openference pricing](https://www.openference.com/pricing)
- [Openference community pricing tracker](https://www.uprouter.online/s/openference-api)
- [Codiv](https://codiv.ai/)
- [Codiv limits](https://codiv.ai/docs/guides/rate-limits)
- [9Router](https://9router.com/)
- [9Router API](https://api.9router.com/)
- [ElevenLabs pricing](https://elevenlabs.io/pricing)
- [ElevenLabs free-tier tracker](https://freellmapihub.com/p/elevenlabs)
- [ElevenLabs community API reports](https://www.reddit.com/r/ElevenLabs/comments/1qrhnr4/most_voices_are_locked_behind_a_paywall_now/)
