# GreatLLM

Some free LLM, vision models, image... All free.

Curated directory of **free or free-tier LLM / multimodal APIs**. Quotas change often — treat numbers as snapshots, not contracts. Prefer official docs over aggregators.

## New this pass (2026-09-16 night)

Research: YoannDev90/awesome-free-ai-api, mvalentsev/awesome-free-ai-coding (live probes), llm24.net, official signup pages. Reviews cross-checked. **New names only**.

| Provider | Free access | RPD | TKPD | Best for | Notes |
| --- | --- | ---: | ---: | --- | --- |
| [Yingsuan AI](https://yingsuan.ai/) | Email only, no card (Yoann 2026-09-16) | Not published | Not published | DeepSeek / Kimi K3 / GLM / Qwen | Yoann tested same day |
| [Xeven Worker](https://xeven.works/) | Listed free catalog (Yoann) | Not published | Not published | Hobby OpenAI-compat worker | Yoann: untested 2026-09-16 |
| [Routeway](https://routeway.ai/) | `:free` lane, no card to start | ~200 | Not published | Rotating $0 ids | `https://api.routeway.ai/v1` ~5 RPM / 200 RPD |
| [LLMTR](https://llmtr.com/) | Zero-balance free chat rows | Not published | Not published | TR multi-lab gateway | `https://llmtr.com/v1` — 12 $0 ids on 2026-09-16 |
| [Nous Portal](https://nousresearch.com/) | $0 Free / Hermes Agent | Not published | Not published | Step 3.7 Flash + Laguna | Free-tagged models; key required |
| [Token Harbor](https://tokenharbor.ai/) | $0/mo allowance, no card advertised | Rolling 7-day | Value-based | DeepSeek V4 / MiMo `:free` | Catalog needs a key |
| [Freebuff](https://freebuff.com/) | Ad-funded Freebucks | Capacity-based | Capacity-based | Coding agent + GLM 5.3 Flash | 25–100 Freebucks/day by region |
| [Regolo AI](https://regolo.ai/) | Listed $0 catalog row | Not published | Not published | EU OSS / gpt-oss | `https://api.regolo.ai/v1` |
| [OhMyGPT](https://www.ohmygpt.com/) | Listed free / moderation path | Not published | Not published | Small multi-model host | Confirm current $0 ids |
| [Navy AI](https://api.navy/) | Listed free plan + token multiplier | Token-capped | Token-capped | Multi-lab gateway | Cloudflare challenge off-browser |
| [TokenRouter (PaleBlueDot)](https://tokenrouter.io/) | One listed $0 default-group id | Not published | Not published | Nemotron 3 Nano Omni | Not tokenrouter.com |
| [OpenStarry](https://api.openstarry.com/) | ~200 signup calls | Credit-based | Credit-based | CN GLM / DeepSeek / Kimi hub | Then PAYG |
| [Atlas Cloud](https://www.atlascloud.ai/) | Public catalog (llm24) | Not published | Not published | Multi-model inference cloud | Confirm free vs trial |
| [Nano-GPT](https://nano-gpt.com/) | Public catalog (llm24) | Not published | Not published | Lightweight multi-model API | Confirm live TOS |
| [Kiro](https://kiro.dev/) | No-card coding-agent trial | Not published | Not published | IDE / agent trial | Not a raw public chat SaaS |
| [Google Jules](https://jules.google.com/) | No-card coding-agent trial | Not published | Not published | Google coding agent | Tool-tied |

## Previous pass (2026-09-16 late)

Kept from the prior commit. Same columns.

| Provider | Free access | RPD | TKPD | Best for | Notes |
| --- | --- | ---: | ---: | --- | --- |
| [Gratisfy](https://gratisfy.xyz/) | Unified free-provider hub + terminal | Capacity-based | Capacity-based | Benchmark + route free APIs | Index, not a first-party lab |
| [FreeTheAI](https://freetheai.xyz/) | Discord key, listed no-card gateway | Daily check-in | Not published | 80+ OpenAI-compat aliases | Daily `/checkin` required |
| [Logfare](https://logfare.ai/) | Signup free inference, no card advertised | Not published | Not published | Auto-route `logfare/auto` | Logs prompts after PII scrub |
| [UnoRouter](https://unorouter.com/) | Listed `:free` pool | ~1 RPM/model* | Not published | OSS multi-lab gateway | `https://api.unorouter.com/v1` |
| [Api.Airforce](https://api.airforce) | Permanent `:free` suffix models | Token-capped | Token-capped | OpenAI + Anthropic hub | Then PAYG |
| [CoderPlan](https://coderplan.ai) | Listed free catalog | Not published | Not published | Coding-oriented host | Yoann 2026-09-15 |
| [Completions](https://www.completions.me) | Listed free catalog | Not published | Not published | Hobby host | Confirm TOS |
| [FreeInference](https://freeinference.org) | Official docs + listed free path | Not published | Not published | Community inference | `doc.freeinference.org` |
| [Hubs02225](https://hubs02225.snia.ch/) | Listed free catalog | Not published | Not published | Hobby host | Yoann 2026-09-15 |
| [AquaDevs](https://aquadevs.com/plan) | Listed plan page | Not published | Not published | Community API | Untested 2026-09-15 |
| [MincAPI](https://mincapi.ai.studio/) | Listed models endpoint | Not published | Not published | Studio host | Older Yoann check |
| [0G](https://0g.ai/) | Public `/v1/models` router | Not published | Not published | Decentralized router | `https://router-api.0g.ai/v1` |
| [Glama](https://glama.ai/) | Gateway catalog | Not published | Not published | Multi-model gateway | `https://glama.ai/api/gateway/openai/v1` |
| [CometAPI](https://www.cometapi.com/) | Signup / listed catalog | Not published | Not published | Multi-lab aggregator | |
| [FreeModel](https://freemodel.dev/) | Small public catalog | Not published | Not published | Lightweight host | `https://cc.freemodel.dev/v1` |
| [IO.NET](https://io.net/) | Public inference catalog | Not published | Not published | Decentralized GPU | |

## Full catalog

Previous rows kept. Same columns. Historical first-party + gateway list lives in commit `8a479bb` if a row is missing here; this file keeps the working set plus the two newest passes.

Start with **Google AI Studio**, **Groq**, **NVIDIA NIM**, **OpenRouter `:free`**, **Cloudflare Workers AI**, **Z.AI GLM Flash**, **Mistral**, **Cohere**, **Cerebras**, **Ollama Cloud**, **OVHcloud AI Endpoints**, **Kilo Code**, **Requesty**, **NaraRouter**, **SiliconFlow**, **ModelScope** — then the new rows above.

\* Approximate daily figures. Quotas change often.

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
