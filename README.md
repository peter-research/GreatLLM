# GreatLLM

Some free LLM, vision models, image... All free.

Curated directory of **free or free-tier LLM / multimodal APIs**. Quotas change often — treat numbers as snapshots, not contracts. Prefer official docs over aggregators.

## New this pass (2026-09-17)

Research: freellm.net + changelog 2026-09-17, awesome-freellm-apis, YoannDev90/awesome-free-ai-api (checked 2026-09-16), velo4705/awesome-free-byok-models (verified 2026-09-16/17), freeinference.dev, official docs. Reviews cross-checked against live lists. **New names only** — none of these rows existed in prior README passes.

| Provider | Free access | RPD | TKPD | Best for | Notes |
| --- | --- | ---: | ---: | --- | --- |
| [AnyAPI](https://anyapi.ai) | No card, `:free` lane | Capacity-based | ~100k listed | Multi-lab `:free` ids | `https://api.anyapi.ai/v1` — Nemotron / Gemma free rows |
| [Auriko](https://www.auriko.ai) | Registration + listed $0 GLM Flash | Not published | ~1M/mo BYOK cap listed | GLM Flash house ids | `https://api.auriko.ai/v1` — most catalog is credit, only Flash is $0 |
| [BazaarLink](https://bazaarlink.ai) | `:free` suffix, no card advertised | ~50 | Not published | Lightweight gateway | `10 RPM` listed; Yoann + BYOK list 2026-09-16 |
| [Void AI](https://voidai.app/) | Registration | Credit pool | ~125k credits/day listed | High RPM coding | BYOK list: ~100 RPM; confirm live TOS |
| [Intern AI](https://internlm.intern-ai.org.cn/api) | Official intern quota | Monthly pool | ~90M tokens/mo listed | Intern-S2 preview | First-party lab, not a hobby gateway |
| [TokenReply](https://www.tokenreply.com/) | Listed free plan | Not published | Not published | Multi-model host | Yoann tested 2026-09-16 |
| [Zylo API](https://api.zyloai.net/v1) | 10 RPM / 7.2k RPD listed | ~7,200 | ~200k | gpt-oss / MiniMax / house Flash | Verified 2026-09-17 on BYOK list |
| [Zydit AI](https://api.zydit.in/v3) | Free models, 10 RPM listed | Capacity-based | Not published | Mix of OSS ids | `https://api.zydit.in/v3` — verified 2026-09-17 |
| [PaxSenix](https://api.paxsenix.org/docs) | Listed free catalog | Not published | Not published | Hobby OpenAI-compat | Yoann 2026-09-16 |
| [Pixazo AI](https://www.pixazo.ai/api/pricing-plan) | Listed free / trial plan | Not published | Not published | Image + text host | Confirm which ids stay $0 |
| [Pydantic AI Gateway](https://ai.pydantic.dev/gateway/) | Official gateway path | Not published | Not published | Pydantic agent stack | Tool-tied more than raw SaaS |
| [Rout.my](https://www.rout.my/) | Docs + listed free start | Not published | Not published | Router / OpenAI compat | `docs.rout.my` |
| [StudioLM](https://studiolm.dev/) | Listed free catalog | Not published | Not published | Studio / hobby host | Yoann 2026-09-16 |
| [SubNP](https://subnp.com/free-api) | Official free-api page | Not published | Not published | Community API | Yoann 2026-09-16 |
| [ValorGPT](https://www.valorgpt.com/models) | Listed free catalog | Not published | Not published | Multi-model host | Yoann 2026-09-16 |
| [ZenLLM](https://zenllm.org/models) | Listed free catalog | Not published | Not published | Community model host | Yoann 2026-09-16 |
| [A4F](https://gratisfy.xyz/providers) | Listed no-card catalog | Not published | Not published | Aggregated free lane | See Yoann / Gratisfy row |
| [Electron Hub](https://gratisfy.xyz/providers) | Listed Aug 2026 add | Not published | Not published | Multi-model hub | Confirm current $0 ids |
| [EvolveX](https://gratisfy.xyz/providers) | Listed Aug 2026 add | Not published | Not published | Hobby gateway | Confirm live TOS |

## Previous pass (2026-09-16 late night)

Kept from the prior commit. Same columns.

| Provider | Free access | RPD | TKPD | Best for | Notes |
| --- | --- | ---: | ---: | --- | --- |
| [MegaNova](https://meganova.ai) | No-card Tier 1 | ~50 / free row (~550 total) | Not published | Manta + Mistral Small 3.2 | `https://api.meganova.ai/v1` — GLM Flash needs $1 deposit |
| [Agnes AI](https://agnes-ai.com) | Registration, Flash $0 | ~1,000 | Not published | House Flash + image | `agnes-3.0-flash` / `agnes-2.5-flash`; ~20 RPM |
| [Aion Labs](https://www.aionlabs.ai/) | Registration, no billing advertised | Daily allowance | ~20k TPD listed | House Aion 3.0 | `https://api.aionlabs.ai/v1` — 15 RPM listed 2026-09-16 |
| [OpenCode Zen](https://opencode.ai) | Registration | ~500 | 1M pool listed | Coding / reasoning | `https://opencode.ai/zen/v1` — 13 free ids on FreeLLM |
| [Chutes.ai](https://chutes.ai/) | Registration | Not published | Not published | Community inference | 2 free models on FreeLLM snapshot |
| [LLM7.io](https://llm7.io) | Anonymous + optional free token | Capacity-based | ~500k–5M tokens/day | No-signup OpenAI compat | Token doubles quota; GLM / MiniMax / Codestral listed |
| [Glhf.chat](https://glhf.chat/) | Registration | Not published | Not published | Llama / Mixtral chat | Permanent-free row on FreeLLM |
| [Nscale](https://www.nscale.com/) | Registration | Not published | Not published | EU inference | 2 free models listed; confirm live TOS |
| [Pollinations.AI](https://pollinations.ai) | No signup | ~1 req / 15s anon | Not published | gpt-oss text + image | `POST https://text.pollinations.ai/openai` |
| [Hetzner Inference](https://experiments.hetzner.com/inference) | Experimental, no billing yet | Token window / 24h | 500M in / 5M out listed | EU Qwen 3.6 / 3.8 | Experiment — can vanish |
| [Venice.ai](https://venice.ai/) | Registration | Limited daily | Not published | Privacy-first OSS | ~10 RPM free; Llama / image |
| [Vercel AI Gateway](https://vercel.com/ai-gateway) | $0-priced ids + $5 credit | Credit-based | Credit-based | Laguna + routed models | Some ids draw $0; others spend the credit |
| [AIHubMix](https://aihubmix.com/) | Listed `:free` catalog | Not published | Not published | gpt-oss / MiMo / Gemma | Aggregator — confirm current $0 ids |
| [Typhoon / OpenTyphoon](https://opentyphoon.ai/) | Official free FAQ path | Not published | Not published | Thai + EN OSS | SCB 10X; editorial pick on free-llm-api-hub |
| [Inference.net](https://inference.net/) | No card, fair use | ~30 RPM | Fair use | DeepSeek-R1 / Llama | Fair-use, not a published RPD |
| [Cline](https://cline.bot/) | Agent login, rotating free models | Daily allowance / model | Not published | VS Code / JetBrains agent | Tool-tied, not a raw public SaaS |

## Previous pass (2026-09-16 night)

Kept from the prior commit. Same columns.

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

Previous rows kept. Same columns. Historical first-party + gateway list lives in commit `8a479bb` if a row is missing here; this file keeps the working set plus the newest passes.

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
