# GreatLLM

Some free LLM, vision models, image... All free.

Curated directory of **free or free-tier LLM / multimodal APIs**. Quotas change often — treat numbers as snapshots, not contracts. Prefer official docs over aggregators.

First commit of this repo started from [FreeLLM](https://freellm.net/) and the awesome free-LLM lists. Each pass: research → check reviews / official pages → commit **README only**, **new provider names only**.

## New this pass (2026-09-17 afternoon)

Research: freellm.net/providers (31 hosts, refreshed 2026-09-17), open-free-llm-api/awesome-freellm-apis, mnfst/awesome-free-llm-apis (Aion / GitHub Models / Nscale / Nebius / DeepSeek / xAI / AI21 / Chutes / glhf), DataTalksClub llm-zoomcamp awesome-llms (reviewed 2026-06-30), nejib1/Free-LLM + free-llm.com, bradAGI/awesome-free-inference, mvalentsev/awesome-free-ai-coding probes, r/LLMDevs and r/LocalLLM threads (GitHub Models and DeepSeek signup credits come up often; Chutes and glhf are the long tail; xAI free lane is thin).
Reviews: mnfst and freellm.net still list GitHub Models, Aion Labs, Chutes, Nscale, Nebius, DeepSeek, xAI, AI21 as free-or-credit rows. Venice and Moonshot appear as renewable / regional credits. Together and Fireworks are one-shot credits, not permanent $0 models. Cerebras and Infomaniak stay delisted from this repo.
**New names only** — none of these rows were provider lines in the night README (`df9538f`).

| Provider | Free access | RPD | TKPD | Best for | Notes |
| --- | --- | ---: | ---: | --- | --- |
| [GitHub Models](https://github.com/marketplace/models) | GitHub account, `models:read` token | ~50–150 / model tier | Per-request cap (often 8k in / 4k out) | GPT-family + Llama / DeepSeek proto | Base `https://models.github.ai/inference`. No card. Limits tied to Copilot tier. |
| [Aion Labs](https://www.aionlabs.ai/app/api-keys/) | Permanent free key, no card | Low (token-capped) | ~20k / day cited | Roleplay / story GLM-style ids | `https://api.aionlabs.ai/v1`. ~15 RPM. Niche, not a coding workhorse. |
| [Chutes.ai](https://chutes.ai) | Registration | Catalog-capped | Catalog-capped | Community TEE / OSS routes | Listed on freellm.net with a tiny free catalog. Treat as unstable. |
| [Nscale](https://www.nscale.com) | Signup credit, often no card | Fair-use after credit | Credit-shaped | EU sovereign OSS (Llama / Qwen / gpt-oss) | `https://inference.api.nscale.com/v1`. Norway DC. Credit, not a fat permanent pool. |
| [Nebius Token Factory](https://studio.nebius.com) | Signup credit (EU) | Tier-based | Credit-shaped | OSS studio (Llama / DeepSeek / Qwen / gpt-oss) | `https://api.studio.nebius.com/v1`. Some reports now want a card on file — check before signup. |
| [DeepSeek](https://platform.deepseek.com) | Signup token grant | Dynamic | Grant then pay-as-you-go | Official `deepseek-chat` / reasoner | `https://api.deepseek.com/v1`. Credits expire; prompts may train unless opted out. |
| [xAI](https://console.x.ai) | Registration + thin free / trial lane | Low on free | Trial / plan-capped | Grok text, huge context on paid | `https://api.x.ai/v1`. Free lane is the weak part; do not plan production on it. |
| [AI21 Labs](https://studio.ai21.com) | Registration | Catalog-capped | Catalog-capped | Jamba / Jurassic text | Listed with 2 free models on awesome-freellm-apis. Confirm current Studio free column. |
| [glhf.chat](https://glhf.chat) | Registration | Catalog-capped | Catalog-capped | Small OSS chat host | Tiny catalog on freellm.net. Long-tail, easy to vanish. |
| [Moonshot / Kimi](https://platform.moonshot.ai) | Regional signup credit | Very low RPM cited (~3) | Credit-shaped | Official Kimi / long-context | China / intl consoles differ. Not the same as OpenRouter `:free` Kimi rows. |
| [MiniMax](https://www.minimax.io) | Official platform signup | See console | See console | Official M-series, long context | Distinct from MiniMax ids on NIM / Ollama Cloud / aggregators. |
| [Venice.ai](https://venice.ai) | Registration, privacy-oriented | ~10 RPM cited | Daily-capped | Uncensored OSS chat | Renewable limited daily use. More product than raw infra. |
| [Together AI](https://www.together.ai) | One-time research / signup credit | After credit: paid | After credit: paid | Fast OSS cluster | Not a permanent $0 catalog. Some "free research" rows still want a deposit. |
| [Fireworks AI](https://fireworks.ai) | One-time ~$1 credit | After credit: paid | After credit: paid | Fast OSS inference | Same class as Together: try, then pay. |
| [Inference.net](https://inference.net) | Listed OpenAI-compat host | See docs | See docs | Community inference | Appears on free-llm.com key tables. Verify live models before wiring agents. |
| [AI Horde](https://aihorde.net) | Community swarm, no card | Shared queue | Shared queue | Volunteer GPU text / image | Not a classic SaaS SLA. Good fallback, bad for latency-critical apps. |

## Previous pass (2026-09-17 night)

Kept from the prior commit. Same columns. See git history (`df9538f`) if this file is viewed in isolation.

Night rows (do not re-add): LLM7.io, SambaNova Cloud, Hetzner Inference API, Pollinations.AI, AIHubMix, Freebuff, Token Harbor, Routeway, LLMTR, Nous Portal, opencode, Cline, Vercel AI Gateway, Regolo AI, Alibaba Cloud Model Studio, Hugging Face Inference, FreeInference.

## Previous pass (2026-09-17 evening)

Evening rows (do not re-add): Requesty, Kilo Code, OVHcloud AI Endpoints, SiliconFlow, ModelScope, Amazon Q Developer, AnyRouter, Google Antigravity, CodeGPT, QwenCloud, ZenMux, Kluster AI, Upstage, Featherless.ai, FriendliAI, Baseten.

Historical first-party + gateway list lives in earlier commits on `main` (Google AI Studio, Groq, NVIDIA NIM, OpenRouter `:free`, Cloudflare Workers AI, Z.AI GLM Flash, Mistral, Cohere, Ollama Cloud).

Start with **Google AI Studio**, **Groq**, **NVIDIA NIM**, **OpenRouter `:free`**, **Cloudflare Workers AI**, **Z.AI GLM Flash**, then **GitHub Models**, **LLM7.io**, **SambaNova**, **DeepSeek** (while the grant lasts), **Aion Labs** for RP.

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
