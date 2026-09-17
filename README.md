# GreatLLM

Some free LLM, vision models, image... All free.

Curated directory of **free or free-tier LLM / multimodal APIs**. Quotas change often — treat numbers as snapshots, not contracts. Prefer official docs over aggregators.

## New this pass (2026-09-17 afternoon)

Research: freellm.net providers + changelog 2026-09-17, freellm.site permanent/credit tables (verified 2026-06-28, still listed), YoannDev90/awesome-free-ai-api (GitHub Models ✅ 2026-09-16), freeinference.dev 2026-09-17, official docs (Parasail `api.parasail.io/v1`, DeepSeek platform, xAI console, Nebius Studio).
Reviews: Yoann Tested column for GitHub Models ✅; Parasail public pricing is PAYG with a thin 5 RPM serverless try lane (not a fat $0 catalog); DeepSeek / xAI / AI21 / Hyperbolic / Lambda / Together / DeepInfra are signup-credit or trial, not permanent unlimited $0.
**New names only** — none of these rows existed in prior README passes.

| Provider | Free access | RPD | TKPD | Best for | Notes |
| --- | --- | ---: | ---: | --- | --- |
| [GitHub Models](https://github.com/marketplace/models) | Copilot / Marketplace free lane | Copilot-capped | Copilot-capped | Phi + hosted OSS in GitHub | Yoann tested 2026-09-16; freellm.net lists 16 ids |
| [DeepSeek](https://platform.deepseek.com/api_keys) | Signup credit (~$5 listed) | Credit-based | Credit-based | First-party V3/V4 family | Not the NIM/OpenRouter relay — confirm live credit |
| [xAI / Grok](https://console.x.ai) | Listed monthly trial credit | Credit-based | Credit-based | Grok API first-party | freellm.site ~$25/mo snapshot; card/email policy can change |
| [AI21 Labs](https://studio.ai21.com/account/api-key) | Signup credit (~$10 listed) | Credit-based | Credit-based | Jamba / house stack | freellm.net + freellm.site; trial not permanent $0 |
| [Nebius AI Studio](https://studio.nebius.com/settings/api-keys) | Signup credit (~$1 listed) | Credit-based | Credit-based | EU-hosted OSS catalog | freellm.net 1 free-row snapshot; then PAYG |
| [Parasail](https://docs.parasail.io/parasail-docs) | Serverless try lane ~5 RPM | Capacity-based | Capacity-based | Fast OSS serverless | `https://api.parasail.io/v1` — catalog is mostly PAYG |
| [Hyperbolic](https://app.hyperbolic.xyz/settings) | Signup credit (~$10 listed, no expiry on directory) | Credit-based | Credit-based | Cheap GPU inference | Directory snapshot 2026-06-28; confirm live TOS |
| [Lambda AI Inference](https://lambda.ai) | Signup credit (~$10 listed) | Credit-based | Credit-based | GPU cloud inference | Credit then PAYG |
| [Together AI](https://api.together.ai/settings/api-keys) | Small signup credit (~$1 listed) | Credit-based | Credit-based | Broad OSS host | Some sources now say min-purchase — verify before signup |
| [DeepInfra](https://deepinfra.com) | Signup credit (~$1 listed) | Credit-based | Credit-based | OpenAI-compat OSS | Trial, not a published RPD |
| [Replicate](https://replicate.com) | Listed free-tier path | Credit-based | Credit-based | Model-as-endpoint + image | More prediction API than raw chat SaaS |
| [Fal AI](https://fal.ai) | Listed free-tier path | Credit-based | Credit-based | Fast image / media models | Multimodal first; confirm text ids |
| [AI4Bharat](https://ai4bharat.iitm.ac.in) | Lab / no-card path listed | Not published | Not published | Indic-language models | IITM lab; not a hobby gateway |
| [BharatGen](https://bharatgen.iitb.ac.in) | Lab / no-card path listed | Not published | Not published | Indic generative stack | IITB; confirm public API vs demo |
| [AI Singapore / SEA-LION](https://aisingapore.org) | Official SEA-LION path | Not published | Not published | SEA languages | Regional lab API, not a multi-lab router |
| [Falcon / TII](https://falconllm.tii.ae) | Official TII Falcon path | Not published | Not published | Falcon family | First-party lab; confirm live inference vs weights-only |

## Previous pass (2026-09-17 midday)

Kept from the prior commit. Same columns.

| Provider | Free access | RPD | TKPD | Best for | Notes |
| --- | --- | ---: | ---: | --- | --- |
| [AIchixia](https://www.aichixia.xyz/) | Listed free gateway catalog | Not published | Not published | One-key multi-lab + TTS | Yoann tested 2026-09-16; Gratisfy row |
| [Hugging Face Inference](https://huggingface.co/docs/inference-providers) | Router + ~$0.10/mo credits listed | Credit-based | Credit-based | OSS via HF router | `https://router.huggingface.co/v1` — Yoann 2026-09-16 |
| [IBM watsonx.ai](https://cloud.ibm.com/docs/apis/watsonx-ai) | Cloud trial / listed free path | Not published | Not published | Enterprise Granite stack | Yoann re-added Aug 2026; confirm live trial |
| [Resurge](https://www.resurge.one/models) | Listed free catalog | Not published | Not published | Multi-model host | Yoann tested 2026-09-16 |
| [SambaNova Cloud](https://cloud.sambanova.ai) | Listed free / trial inference | See docs | See docs | Fast OSS on SN chips | Yoann 2026-09-16; rate-limit docs |
| [SwiftRouter](https://swiftrouter.com/models?plan=starter) | Starter plan listed | Not published | Not published | Router / starter ids | Yoann: untested 2026-09-16 |
| [Subaxis](https://subaxis.dev/) | Listed free path | Not published | Not published | Hobby gateway | Yoann: untested 2026-09-16 |
| [SixFingerAPI](https://api.sixfinger.live) | Listed plans + models docs | Not published | Not published | Hobby OpenAI-compat | Yoann last check 2026-07-09, untested |
| [Liquid AI](https://inference.liquid.ai/v1) | LFM2.5 free rows on aggregators | Not published | Not published | Small fast LFM models | First-party inference URL; also OpenRouter `:free` |
| [BlockRun / ClawRouter](https://user.blockrun.ai) | 6 models listed keyless / no wallet | Capacity-based | Capacity-based | Agent router + x402 pay | Confirm which 6 ids stay $0 |
| [Alibaba Model Studio](https://www.alibabacloud.com/help/en/model-studio/) | ~1M tokens/model signup (intl, 90d) | Regional | ~1M listed / model | Qwen3 / VL / Coder | `dashscope-intl.aliyuncs.com/compatible-mode/v1` |
| [Moonshot / Kimi](https://platform.moonshot.ai/) | Official platform trial / free ids | Not published | Not published | Kimi K2 / K3 family | First-party, not only NIM relay |
| [MiniMax](https://www.minimax.io/) | Official API trial / free rows | Not published | Not published | M-series + speech | Also hosted on ModelScope free catalog |
| [Scaleway Generative APIs](https://www.scaleway.com/en/docs/generative-apis/) | EU trial credit listed | Credit-based | Credit-based | EU-hosted OSS | Trial, then PAYG |
| [Novita AI](https://novita.ai/) | Signup trial credit | Credit-based | Credit-based | Broad OSS catalog | Trial wall after credit |
| [Fireworks AI](https://fireworks.ai/) | Signup trial credit | Credit-based | Credit-based | Fast hosted OSS | Trial, not a permanent $0 tier |

## Previous pass (2026-09-17 morning)

Kept from the prior commit. Same columns.

| Provider | Free access | RPD | TKPD | Best for | Notes |
| --- | --- | ---: | ---: | --- | --- |
| [AI Horde](https://aihorde.net/details/models) | Distributed volunteer inference, no card | Capacity-based | Capacity-based | Crowd-sourced OSS chat / image | Slow queue; Yoann tested 2026-09-16 |
| [AI Pooled](https://ai.pooled.dev) | Listed free catalog | Not published | Not published | Shared pool gateway | Yoann + Gratisfy 2026-09-16 |
| [Apertis](https://apertis.ai/models?sort=price_low) | Sort-by-price $0 rows | Not published | Not published | Price-sorted OSS catalog | Confirm which ids stay $0 |
| [Atessa](https://atessa.top/) | Listed free host | Not published | Not published | Hobby OpenAI-compat | Yoann tested 2026-09-16 |
| [AwanLLM](https://www.awanllm.com/models) | Listed free catalog | Not published | Not published | Multi-model host | Yoann 2026-09-16 |
| [BlazeAI](https://blazeai.boxu.dev/#models) | Listed free catalog | Not published | Not published | Lightweight gateway | Yoann 2026-09-16 |
| [Coze](https://www.coze.com/open) | Official open platform path | Not published | Not published | Bot / agent platform API | ByteDance stack; not raw chat-only |
| [Crax GPT](https://gpt.crax.lol/) | Listed free catalog | Not published | Not published | Hobby multi-model | Yoann tested 2026-09-16 |
| [DGrid AI](https://dgrid.ai/models/dgridai/free/) | Official `/free/` catalog | Not published | Not published | Decentralized free lane | First-party free page |
| [FastRouter](https://fastrouter.ai/models/) | Listed free catalog | Not published | Not published | Router / multi-lab | Yoann 2026-09-16 |
| [Flowbar AI](https://flowbarai.com/pricing) | Listed pricing / free start | Not published | Not published | Multi-model host | Confirm current $0 ids |
| [LiteRouter](https://literouter.com/model_list) | Listed free catalog | Not published | Not published | Lightweight router | Yoann 2026-09-16 |
| [LLM-Gateway](https://llmgateway.io/models?filters=1&free=true) | Official `free=true` filter | Not published | Not published | Filtered $0 catalog | First-party free filter |
| [Mixedbread](https://www.mixedbread.com/pricing) | Listed free / trial path | Not published | Not published | Embeddings + retrieval | More RAG than chat |
| [MNN AI](https://mnnai.ru/) | Listed free catalog | Not published | Not published | RU hobby OpenAI-compat | Yoann 2026-09-16 |
| [NagaAI](https://naga.ac/models) | Listed free catalog | Not published | Not published | Multi-model host | Yoann 2026-09-16 |
| [Nexusify](https://docs.nexusify.co/) | Docs + listed free path | Not published | Not published | Gateway / docs-first | Yoann 2026-09-16 |
| [Ofox](https://ofox.ai/models) | Listed free catalog | Not published | Not published | Multi-model host | Yoann 2026-09-16 |
| [Inception Labs](https://platform.inceptionlabs.ai/) | Official Mercury platform | Not published | Not published | Diffusion LLMs (Mercury 2) | Yoann: untested 2026-09-16 |

## Previous pass (2026-09-17)

Kept from the prior commit. Same columns.

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
