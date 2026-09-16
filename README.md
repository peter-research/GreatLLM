# GreatLLM

Some free LLM, vision models, image... All free.

Curated directory of **free or free-tier LLM / multimodal APIs**. Quotas change often — treat numbers as snapshots, not contracts. Prefer official docs over aggregators.

## Free providers

| Provider | Free access | RPD | TKPD | Best for | Notes |
| --- | --- | ---: | ---: | --- | --- |
| [NVIDIA NIM](https://build.nvidia.com/) | Free endpoints | Varies | Not published | Open models, high throughput | Limits and model list change often |
| [Cloudflare Workers AI](https://developers.cloudflare.com/workers-ai/) | 10k Neurons/day | 10,000 Neurons* | N/A | Serverless / edge | Quota in Neurons, not requests or tokens |
| [Z.AI](https://z.ai/) | GLM Flash models free | Not published | Not published | Coding, reasoning, CN/EN | GLM-4.7-Flash: 200K context |
| [Google AI Studio](https://ai.google.dev/) | Free Gemini tier | Model-dependent | Model-dependent | Multimodal general use | Check live RPM/TPM/RPD in AI Studio |
| [Groq](https://groq.com/) | Free API tier | Model-dependent | Model-dependent | Very fast open models | Limits shown per model in console |
| [OpenRouter](https://openrouter.ai/) | 25+ free models | 50 | Not published | Multi-provider routing | Free model list rotates |
| [Cohere](https://cohere.com/) | Free trial key | ~33 | Not published | RAG, embeddings, rerank | 1,000 calls/month; ~20 RPM on chat |
| [Hugging Face Inference Providers](https://huggingface.co/inference) | $0.10/month credits | Not published | Not published | Experimentation | Credit-based, not fixed RPD |
| [Cerebras Inference](https://www.cerebras.ai/inference) | $5 trial credit | Not published | Not published | Ultra-fast open models | One-time credit, not recurring |
| [Mistral AI](https://mistral.ai/) | Free API mode | Not published | Not published | European models | Monthly included usage; see dashboard |
| [SambaNova Cloud](https://cloud.sambanova.ai/) | $5 free credit | Not published | Not published | Fast open models | One-time credit |
| [SiliconFlow](https://www.siliconflow.com/) | Permanent free models | Model-dependent | Model-dependent | Open / multimodal | Some models need ID verification |
| [LLM7.io](https://llm7.io/) | Free token | ~2,400* | Not published | Simple multi-model API | Official: 2 RPS, 20 RPM, 100/hour |
| [ModelScope](https://modelscope.cn/) | Free inference | 2,000 | Not published | Qwen, DeepSeek, CN models | ~500 RPD per model; may need real-name |
| [Kilo Code](https://kilo.ai/) | Free model gateway | 4,800* | Not published | Coding agents | 200 req/hour per IP (normalized) |
| [Modal](https://modal.com/) | $30/month free compute | Not published | Not published | Self-hosted GPU | Compute credit, not token quota |
| [Baseten](https://www.baseten.co/) | Starter credits | Not published | Not published | Custom deployments | Amount not fixed publicly |
| [Nscale](https://www.nscale.com/) | $5 starter credit | Not published | Not published | EU open models | One-time credit |
| [Hyperbolic](https://www.hyperbolic.ai/) | $1 promo credit | Not published | Not published | GPU open models | Phone verification; not for GPU rental |
| [Fireworks AI](https://fireworks.ai/) | $1 credit / free envelope | Not published | Not published | Fast serverless | Treat as introductory; verify live |
| [Pollinations AI](https://pollinations.ai/) | Free / light use | Not published | Not published | Text, image, audio, video | Heavier use uses Pollen credits |
| [Ollama Cloud](https://ollama.com/) | Free plan + starter credits | Not published | Not published | Open models, local-cloud | Caps not fully published |
| [AnyAPI](https://api.anyapi.ai/) | Free tier, no card | 200 | Not published | OpenAI-compatible gateway | ~20 RPM |
| [Api.Airforce](https://api.airforce/) | Free hobby tier | Not published | Not published | Unified gateway | Best-effort free access |
| [UnoRouter](https://unorouter.ai/) | Free aggregated access | ~1,440* | Not published | Multi-provider routing | Soft ~1 RPM/user |
| [AI21 Studio](https://www.ai21.com/studio/) | $10 trial (7 days) | Not published | Not published | Long-context Jamba | Time-limited trial |
| [GitHub Models](https://github.com/marketplace/models) | Free with GitHub account | 50-150 | Not published | Prototyping GPT/Phi/Llama | Tied to Copilot tier |
| [OpenCode Zen](https://opencode.ai/zen) | Promo $0 models | Not published | Not published | Coding agents | Limited-time free ids; list rotates |
| [Aion Labs](https://www.aionlabs.ai/) | Daily free allowance | Not published | ~20,000 | Roleplay, creative writing | ~15 RPM |
| [Agnes AI](https://agnes-ai.com/) | Flash models at $0 | Not published | Not published | Multimodal, agents | RPM-limited; Pro models paid |
| [OVHcloud AI Endpoints](https://endpoints.ai.cloud.ovh.net/) | Free EU open models | Not published | Not published | GDPR / EU inference | 2 RPM anon / 400 RPM auth |
| [Chutes.ai](https://chutes.ai/) | Community GPU / listed free models | Not published | Not published | DeepSeek-R1, Llama 3.1 70B | Capacity-based, verify live |
| [Glhf.chat](https://glhf.chat/) | Free beta models | Not published | Not published | Any HF model that fits a node | Treat as beta |
| [Alibaba Cloud Model Studio](https://www.alibabacloud.com/product/modelstudio) | New-user token quota (SG) | Not published | ~1M / model* | Official Qwen APIs | ~90-day signup quota then pay-as-you-go |
| [DeepSeek](https://platform.deepseek.com/) | Listed free / very cheap official API | Not published | Not published | Official DeepSeek models | Mostly metered (cheap) |
| [Nebius Token Factory](https://studio.nebius.com/) | ~$1 trial credit | Not published | Not published | EU hosted open models | One-time credit |
| [xAI](https://x.ai/) | Signup / prepaid credits | Not published | Not published | Grok models | Credits, not a large permanent free pool |
| [Cline](https://cline.bot/) | Free model routing for the Cline agent | Not published | Not published | Coding agent backends | Tool-tied free models |
| [Moonshot AI](https://platform.moonshot.ai/) | Signup credits | Not published | Not published | Kimi long-context | Web chat free is not API free |
| [Scaleway Generative APIs](https://www.scaleway.com/en/generative-apis/) | ~1M free tokens (tracked) | Not published | ~1,000,000 | EU inference | Card often required |
| [Hetzner Inference](https://experiments.hetzner.com) | Free while experimental | Not published | Not published | EU open weights | No SLA |
| [IBM watsonx.ai](https://cloud.ibm.com/docs/apis/watsonx-ai) | Lite plan | Not published | ~300,000 / month | Granite + hosted OSS | Lite not billed |
| [AI Horde](https://aihorde.net/) | Community distributed inference | Capacity-based | Capacity-based | Image + text | No card |
| [AIHubMix](https://aihubmix.com/models) | Free / discounted routed models | Not published | Not published | Multi-model gateway | Aggregator |
| [FastRouter](https://fastrouter.ai/models/) | Listed $0 models | Not published | Not published | Routed OpenAI-compat | Aggregator |
| [Electron Hub](https://www.electronhub.ai/) | Free / starter credits | Not published | Not published | Multi-model playground + API | Not all models stay $0 |
| [DGrid AI](https://dgrid.ai/models/dgridai/free/) | Dedicated free catalog | Not published | Not published | Decentralized / community models | Free list on /free/ |
| [Inference.net](https://inference.net) | Free / low-cost OSS endpoints | Not published | Not published | Hosted open models | Confirm live envelope |
| [LiteRouter](https://literouter.com/model_list) | Free routed models | Not published | Not published | Lightweight multi-provider proxy | Tracker-tested Sep 2026 |
| [LLM Gateway](https://llmgateway.io/models?filters=1&free=true) | Filterable $0 models | Not published | Not published | One dashboard, many backends | Catalog rotates |
| [Mixedbread](https://www.mixedbread.com/pricing) | Free embedding / retrieval tier | Not published | Not published | Embeddings, search, rerank | Retrieval-first |
| [Coze](https://www.coze.com/open) | Free bot / model API quota | Not published | Not published | Agents + published bots | ByteDance stack |
| [AwanLLM](https://www.awanllm.com/models) | Free listed models | Not published | Not published | Simple OpenAI-compat | Small provider |
| [FreeInference](https://freeinference.org) | Public free catalog | Not published | Not published | Discovery + some endpoints | Directory |
| [Nous Portal](https://portal.nousresearch.com) | Free Hermes / research models | Not published | Not published | Hermes-family chat | Caps unpublished |
| [A4F](https://www.a4f.co/models) | Free model list | Not published | Not published | Aggregated cheap / $0 ids | Stability not guaranteed |
| [Completions](https://www.completions.me) | Free hobby API | Not published | Not published | Quick OpenAI-compat tests | Small independent endpoint |
| [Requesty](https://requesty.ai/) | Free routed models | 200 | Not published | OpenAI-compat multi-model router | ~60 RPM, 200 RPD |
| [Venice.ai](https://venice.ai/) | Free daily allowance | Not published | Not published | Privacy-first chat + image | ~10 RPM |
| [Void AI](https://voidai.app/) | Daily credits | Not published | ~125,000 credits | Coding + multi-vendor hub | 100 RPM |
| [Together AI](https://together.ai/) | Trial / starter credit | Not published | Not published | Hosted open models | Credit-based |
| [DeepInfra](https://deepinfra.com/) | Trial credits | Not published | Not published | Cheap OSS inference | Credit-based |
| [Kluster AI](https://kluster.ai/) | ~$5 signup credit | Not published | Not published | DeepSeek / Llama / Qwen host | No-card start on trackers |
| [Lambda Inference](https://lambda.ai/) | ~$10 starter credit | Not published | Not published | GPU cloud + inference | One-time credit |
| [Novita AI](https://novita.ai/) | Signup / referral credits + some $0 models | Not published | Not published | CN + OSS + image | Credit amounts disagree |
| [Vercel AI Gateway](https://vercel.com/ai-gateway) | Listed $0 routed models | Not published | Not published | Unified billing + failover | Free rows rotate |
| [Replicate](https://replicate.com/) | Small trial credit | Not published | Not published | Models-as-containers | One-time credit |
| [BazaarLink](https://bazaarlink.ai/) | Free listed models | Not published | Not published | Aggregated OpenAI-compat | tested 2026-09-15 |
| [EvolveX](https://evolvex.ai/) | Free / starter access | Not published | Not published | Multi-model playground | tested Sep 2026 |
| [AnyRouter](https://anyrouter.dev/) | Shared free pool + donated keys | 1,000* | Not published | Routed free capacity | Aggregator |
| [Sarvam](https://www.sarvam.ai/) | Free / low-cost India models | Not published | Not published | Indic multilingual | Not a general frontier host |
| [AI Pooled](https://aipooled.com/) | Community pooled inference | Capacity-based | Capacity-based | Shared cheap / $0 routes | Availability varies |
| [Flowbar AI](https://flowbar.ai/) | Free listed models | Not published | Not published | Small OpenAI-compat host | Verify live |
| [AIchixia](https://www.aichixia.xyz/) | Free listed models | Not published | Not published | Community OpenAI-compat | tested 2026-09-14 |
| [Apertis](https://apertis.ai/models?sort=price_low) | $0 / lowest-price filter | Not published | Not published | Price-sorted model catalog | $0 rows rotate |
| [Atessa](https://atessa.top/) | Free hobby gateway | Not published | Not published | Small multi-model host | No published SLA |
| [BlazeAI](https://blazeai.boxu.dev/#models) | Free listed models | Not published | Not published | Lightweight OpenAI-compat | Community-tested Sep 2026 |
| [CoderPlan](https://coderplan.ai) | Free coding-oriented models | Not published | Not published | Code agents | Confirm live catalog |
| [Crax GPT](https://gpt.crax.lol/) | Free model list | Not published | Not published | Hobby chat API | Availability varies |
| [FreeTheAI](https://freetheai.xyz/models/) | Public free catalog | Not published | Not published | Discovery + routed $0 ids | Aggregator-style |
| [Hubs02225](https://hubs02225.snia.ch/) | Free listed models | Not published | Not published | Small OpenAI-compat | Community-tested Sep 2026 |
| [Logfare](https://logfare.ai/) | Free / starter access | Not published | Not published | Multi-model router | Tracker-tested Sep 2026 |
| [MegaNova](https://console.meganova.ai/serverless) | Free models on Tier 1 | Not published | Not published | Serverless OSS + Manta | Some models free without card |
| [MNN AI](https://mnnai.ru/) | Free listed models | Not published | Not published | RU-hosted OpenAI-compat | Community-tested Sep 2026 |
| [NagaAI](https://naga.ac/models) | Free listed models | Not published | Not published | Multi-model catalog | Tracker-tested Sep 2026 |
| [Nexusify](https://docs.nexusify.co/) | Free routed models | Not published | Not published | Docs-first gateway | Confirm live $0 ids |
| [Ofox](https://ofox.ai/models) | Free listed models | Not published | Not published | Simple model catalog | Community-tested Sep 2026 |
| [PaxSenix API](https://api.paxsenix.org/docs) | Free hobby API | Not published | Not published | Documented OpenAI-compat | Community-tested Sep 2026 |
| [Yingsuan AI](https://yingsuan.top/) | 3+ free models | Not published | Not published | DeepSeek / Kimi / GLM / Qwen | Email only, no card |
| [ZenLLM](https://zenllm.org/models) | Free listed models | Not published | Not published | Community catalog | Tracker-tested Sep 2026 |
| [Parasail](https://www.parasail.io/) | Rate-limited serverless try | Not published | Not published | OSS serverless inference | ~5 RPM free envelope |
| [Pydantic AI Gateway](https://ai.pydantic.dev/gateway/) | Bundled / listed free routes | Not published | Not published | Pydantic-AI tooling | Gateway, not a first-party lab |
| [TokenReply](https://www.tokenreply.com/docs/models) | Free / starter plans | Not published | Not published | Documented model list | Not all ids stay $0 |
| [ValorGPT](https://www.valorgpt.com/models) | Free listed models | Not published | Not published | Multi-model host | Community-tested Sep 2026 |
| [StudioLM](https://studiolm.dev/) | Free listed models | Not published | Not published | Small playground + API | Community-tested Sep 2026 |
| [SubNP](https://subnp.com/free-api) | Explicit free-API page | Not published | Not published | Hobby free endpoint | Dedicated /free-api |
| [Rout.my](https://www.rout.my/) | Free routed models | Not published | Not published | Lightweight router | docs.rout.my |
| [Routeway AI](https://routeway.ai/models) | Free listed models | Not published | Not published | Multi-model router | Community-tested Sep 2026 |
| [Resurge](https://www.resurge.one/models) | Free listed models | Not published | Not published | Model catalog | Community-tested Sep 2026 |
| [Inception Platform](https://platform.inceptionlabs.ai/) | 100M free tokens (signup) | ~1,000 RPM* | ~1,000,000 in / 100,000 out per min | Diffusion LLMs (Mercury) | One-time 100M tokens |
| [Tencent Hunyuan](https://hunyuan.tencent.com) | 1M token trial pack | Not published | ~1,000,000 (pack) | CN models + vision | Real-name / Tencent Cloud |
| [FriendliAI](https://friendli.ai/) | Free models + adaptive RPM | Capacity-based | Not published | Fast OSS serverless | Promo models rotate |
| [MiniMax Official](https://platform.minimax.io/) | Signup / promo credits | Not published | Not published | Official MiniMax M-series | Credit, not forever-free |
| [AquaDevs](https://aquadevs.com/plan) | Community free / plan seats | Not published | Not published | Routed premium + fusion models | Small aggregator |
| [OhMyGPT](https://www.ohmygpt.com/) | Starter / referral credits | Not published | Not published | Multi-vendor gateway | Most traffic is paid |
| [Navy AI](https://api.navy) | Subscription daily token pool | Plan-based | Plan-based | Unified OpenAI + Anthropic surface | Hobby free unverified |
| [Pixazo AI](https://www.pixazo.ai/api/pricing-plan) | Free / starter plan | Not published | Not published | Image + text API | Confirm live pricing |
| [SwiftRouter](https://swiftrouter.com/models?plan=starter) | Starter routed models | Not published | Not published | Multi-provider router | Not live-tested 2026-09-15 |
| [Xeven Worker](https://ai-image-api.xeven.workers.dev/img) | Public worker endpoint | Not published | Not published | Image generation hobby API | Image-first |
| [MincAPI](https://mincapi.ai.studio/) | Hobby OpenAI-compat | Not published | Not published | Small multi-model host | Re-verify |
| [SixFingerAPI](https://api.sixfinger.live) | Listed free / plans | Not published | Not published | Documented model catalog | Not live-tested Jul-Sep 2026 |
| [Subaxis](https://subaxis.dev/) | Listed free access | Not published | Not published | Community OpenAI-compat | Not live-tested 2026-09-15 |
| [TypeGPT](https://typegpt.net) | Historical free catalog | Not published | Not published | Multi-model playground | Unstable |
| [Infip AI](https://infip.ai) | Historical free listing | Not published | Not published | Small host | Verify before use |
| [Seraphyn AI](https://seraphyn.ai) | Historical free listing | Not published | Not published | Community host | Unstable |
| [SenseNova Token Plan](https://platform.sensenova.cn/token-plan) | Official public-beta free credits | Rolling 5h buckets | ~60k credits / 5h* | CN official DeepSeek / SenseNova | Base token.sensenova.cn/v1. Time-limited beta |
| [Token Harbor](https://tokenharbor.ai) | $0 plan + 4-week rolling allowance | Not published | Not published | DeepSeek V4 / V4.1 Flash, MiMo | Region-blocked CN/HK/MO |
| [OrcaRouter](https://www.orcarouter.ai) | Workspace free pool, 0% markup | Not published | Not published | Routed free pool + GLM / DeepSeek / Hy3 | ~4 free of 195 models |
| [NaraRouter](https://router.naraya.ai/) | Official Free plan | Not published | 5,000,000 | Multi-provider gateway (ID) | 5M tokens/day, 10 RPM, no card |
| [Lightning AI Model APIs](https://lightning.ai/models) | Signup free tokens | Not published | ~30-40M / month* | Frontier + OSS via one key | Official: up to 40M starter tokens |
| [UncloseAI](https://uncloseai.com) | Keyless hobby inference | Capacity-based | Capacity-based | Hermes / Qwen coder, no signup | Hobby-grade, no SLA |
| [PublicAI](https://platform.publicai.co) | Keyless / free API | Not published | Not published | Public / civic models | ~20 RPM |
| [Meituan LongCat](https://longcat.chat/platform/) | Mixed: chat vs API | Not published | Mixed / often paid now | Official LongCat-2.0 | Verify billing; Flash free quota may have ended |
| [Volcengine Ark / Doubao](https://www.volcengine.com/product/ark) | New-user token grant | Not published | Model-dependent | Official Doubao | Real-name typical |
| [iFlytek Spark](https://xinghuo.xfyun.cn/) | Spark Lite free | Not published | Not published | CN official Spark Lite | ~2 QPS; ToS may restrict relay |
| [AI4Bharat](https://ai4bharat.iitm.ac.in/) | Research / listed free | Not published | Not published | Indic language models | Research org |
| [BharatGen](https://bharatgen.bits-pilani.ac.in/) | Research / listed free | Not published | Not published | India sovereign models | Confirm public API |
| [Wrtn Technologies](https://wrtn.ai/) | Listed free / KR host | Not published | Not published | Korean models + chat API | Verify live envelope |
| [fal.ai](https://fal.ai/) | ~$20 signup credit | Not published | Not published | Image / video / some text | Generation-first |
| [AgentRouter](https://agentrouter.org) | Signup credit (tracked) | Not published | Not published | Agent-oriented routing | Aggregator |
| [Freebuff](https://freebuff.ai) | Agent-bundled $0 models | Not published | Not published | Coding agents | Tool-tied free models |
| [Auriko](https://www.auriko.ai) | Free plan + some $0 models | Not published | ~1M BYOK / month* | Zero-markup router | GLM Flash ids verified free; most other models need credits |
| [Featherless AI](https://featherless.ai) | Paid catalog, HF router path | Not published | Not published | Huge OSS catalog | Basic plan is $10/mo; check HF Inference Provider route |
| [Upstage](https://console.upstage.ai) | $10 trial credits | Not published | Credit-based | Solar + documents KR/EN | ~60 RPM; credits expire (~3 months) |
| [GMI Cloud](https://www.gmicloud.ai) | $5 credit + some free OSS endpoints | Not published | Not published | DeepSeek / GLM / Qwen host | Free models run on prod H100/H200 infra |
| [Portkey](https://portkey.ai) | Free gateway tier | Not published | Not published | Observability + routing | Gateway, not a first-party lab |
| [Clarifai](https://www.clarifai.com) | Community / starter credits | Not published | Not published | Multimodal platform | Mixed text + vision catalog |
| [Snowflake Cortex](https://docs.snowflake.com/en/user-guide/snowflake-cortex/llm-functions) | Account trial / included credits | Not published | Not published | SQL + LLM in Snowflake | Needs a Snowflake account |
| [Databricks Foundation Model APIs](https://docs.databricks.com/en/machine-learning/foundation-models/index.html) | Workspace trial credits | Not published | Not published | Hosted OSS on Databricks | Tied to Databricks workspace |
| [Predibase](https://predibase.com) | Starter / trial credit | Not published | Not published | Fine-tune + serve OSS | Credit, not forever-free |
| [Baidu Qianfan](https://cloud.baidu.com/product/wenxinworkshop) | New-user token pack | Not published | Not published | Official ERNIE / CN models | Real-name / Baidu Cloud typical |
| [01.AI Yi](https://platform.lingyiwanwu.com) | Signup / promo credits | Not published | Not published | Official Yi models | Quotas change; verify console |
| [InternLM / Shanghai AI Lab](https://internlm.intern-ai.org.cn) | Research / listed free access | Not published | Not published | InternLM family | Confirm public API vs chat-only |
| [Poolside](https://poolside.ai) | Laguna often free via NIM | Not published | Not published | Coding models (Laguna) | Official API may be gated; NIM hosts Laguna XS |
| [Xiaomi MiMo](https://github.com/XiaomiMiMo) | Official weights + some hosted routes | Not published | Not published | MiMo reasoning models | Hosted $0 routes rotate (GMI / routers) |
| [InclusionAI](https://huggingface.co/inclusionAI) | Ling 3.0 Flash VL free on routers | ~200 on OpenRouter free | Not published | Multimodal Ling models | Official paid; :free rows on OpenRouter |
| [Nex AGI](https://huggingface.co/Nex-AGI) | Nex-N2.5 Mini/Pro free on routers | ~200 on OpenRouter free | Not published | Agent / reasoning models | Official availability vs :free aggregator rows |
| [Puter.js](https://developer.puter.com) | User-pays browser SDK | User-dependent | User-dependent | Apps without backend keys | Users cover their own AI usage |
| [AI71](https://ai71.ai) | Listed free / UAE host | Not published | Not published | Falcon / regional models | Confirm live envelope |

\* Approximate daily figures derived from published hourly/minute limits. Quotas change often.

### How this list is built

1. Scan public directories (FreeLLM, awesome-free lists).
2. Cross-check community reviews and official docs (quotas, card, SLA).
3. Keep **new providers only** when extending — do not duplicate rows.
4. Flag aggregators and experiments: they disappear first.

### Sources checked

- [FreeLLM](https://freellm.net/providers/)
- [awesome-freellm-apis](https://github.com/open-free-llm-api/awesome-freellm-apis)
- [awesome-free-ai-api](https://github.com/YoannDev90/awesome-free-ai-api)
- [awesome-free-ai-coding](https://github.com/mvalentsev/awesome-free-ai-coding)
- [awesome-free-llm-api](https://github.com/peter123023/awesome-free-llm-api)
- [awesome-free-byok-models](https://github.com/velo4705/awesome-free-byok-models)
- [Free-LLM](https://github.com/nejib1/Free-LLM)
- [NaraRouter docs](https://router.naraya.ai/docs)
- [Lightning AI Model APIs](https://lightning.ai/docs/platform/inference/model-apis)
- [SenseNova Token Plan](https://platform.sensenova.cn/token-plan)
- [Auriko docs](https://docs.auriko.ai/platform/plans)
- [GMI Cloud](https://www.gmicloud.ai/en/blog/best-gpu-cloud-free-trials-for-llm-inference-in-2026)
- [Upstage pricing](https://www.upstage.ai/pricing/api)
