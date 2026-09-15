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
| [Ollama Cloud](https://ollama.com/) | Free plan + starter credits | Not published | Not published | Open models, local↔cloud | Caps not fully published |
| [AnyAPI](https://api.anyapi.ai/) | Free tier, no card | 200 | Not published | OpenAI-compatible gateway | ~20 RPM |
| [Api.Airforce](https://api.airforce/) | Free hobby tier | Not published | Not published | Unified gateway | Best-effort free access |
| [UnoRouter](https://unorouter.ai/) | Free aggregated access | ~1,440* | Not published | Multi-provider routing | Soft ~1 RPM/user |
| [AI21 Studio](https://www.ai21.com/studio/) | $10 trial (7 days) | Not published | Not published | Long-context Jamba | Time-limited trial |
| [GitHub Models](https://github.com/marketplace/models) | Free with GitHub account | 50–150 | Not published | Prototyping GPT/Phi/Llama | Tied to Copilot tier; ~8K in / 4K out per request |
| [OpenCode Zen](https://opencode.ai/zen) | Promo $0 models | Not published | Not published | Coding agents | Limited-time free ids; list rotates |
| [Aion Labs](https://www.aionlabs.ai/) | Daily free allowance | Not published | ~20,000 | Roleplay, creative writing | ~15 RPM; exact official numbers soft |
| [Agnes AI](https://agnes-ai.com/) | Flash models at $0 | Not published | Not published | Multimodal, agents | RPM-limited; Pro models paid |
| [OVHcloud AI Endpoints](https://endpoints.ai.cloud.ovh.net/) | Free EU open models | Not published | Not published | GDPR / EU inference | 2 RPM anon / 400 RPM auth; no RPD published |
| [Chutes.ai](https://chutes.ai/) | Community GPU / listed free models | Not published | Not published | DeepSeek-R1, Llama 3.1 70B | OpenAI-compat `api.chutes.ai/v1`. Early Access 200 RPD retired Mar 2026; some trackers say new signups are paid. Capacity-based, verify live |
| [Glhf.chat](https://glhf.chat/) | Free beta models | Not published | Not published | Any HF model that fits a node | OpenAI-compat `glhf.chat/api/openai/v1`. Directories list Llama 3.1 70B + Mixtral as unlimited free; treat as beta |
| [Alibaba Cloud Model Studio](https://www.alibabacloud.com/product/modelstudio) | New-user token quota (SG) | Not published | ~1M / model* | Official Qwen APIs | Singapore region; ~90-day signup quota then pay-as-you-go. Enable “free quota only” to avoid charges |
| [DeepSeek](https://platform.deepseek.com/) | Listed free / very cheap official API | Not published | Not published | Official DeepSeek models | Directories still list 2 models; live free catalog often empty. Official path is mostly metered (cheap), not a generous always-free tier |
| [Nebius Token Factory](https://studio.nebius.com/) | ~$1 trial credit | Not published | Not published | EU hosted open models | Card often required. One-time credit, not recurring |
| [xAI](https://x.ai/) | Signup / prepaid credits | Not published | Not published | Grok models | `api.x.ai/v1`. Credits, not a large permanent free token pool |
| [Cline](https://cline.bot/) | Free model routing for the Cline agent | Not published | Not published | Coding agent backends | Bundled free models for the Cline tool, not a general public API catalog |
| [Moonshot AI](https://platform.moonshot.ai/) | Signup credits (¥15 / promo) | Not published | Not published | Kimi long-context | Official API is metered after credits (~3 RPM on trial). Web chat free ≠ API free |
| [Scaleway Generative APIs](https://www.scaleway.com/en/generative-apis/) | ~1M free tokens (tracked) | Not published | ~1,000,000 | EU inference | Card often required. Confirm current grant in console |
| [Hetzner Inference](https://experiments.hetzner.com) | Free while experimental | Not published | Not published | EU open weights (Qwen / DeepSeek / GLM) | Official: free as long as experiment lasts. Base `https://inference.hetzner.com/api/v1`. ~10 req / 60s; 4M in / 100k out tokens per 60s. No SLA |
| [IBM watsonx.ai](https://cloud.ibm.com/docs/apis/watsonx-ai) | Lite plan | Not published | ~300,000 / month | Granite + hosted OSS | Card used for ID, Lite not billed. ~2 RPS + 20 CUH/month. Enterprise-shaped API |
| [AI Horde](https://aihorde.net/) | Community distributed inference | Capacity-based | Capacity-based | Image + text, no vendor lock | Crowd-sourced GPUs. Latency and availability vary. No card |
| [AIHubMix](https://aihubmix.com/models) | Free / discounted routed models | Not published | Not published | Multi-model gateway | Aggregator. Catalog and $0 rows rotate; verify live pricing |
| [FastRouter](https://fastrouter.ai/models/) | Listed $0 models | Not published | Not published | Routed OpenAI-compat | Aggregator. Treat free ids as best-effort |
| [Electron Hub](https://www.electronhub.ai/) | Free / starter credits | Not published | Not published | Multi-model playground + API | Check console pricing; not all models stay $0 |
| [DGrid AI](https://dgrid.ai/models/dgridai/free/) | Dedicated free catalog | Not published | Not published | Decentralized / community models | Free list is explicit on `/free/` |
| [Inference.net](https://inference.net) | Free / low-cost OSS endpoints | Not published | Not published | Hosted open models | OpenAI-compat. Confirm current free envelope in docs |
| [LiteRouter](https://literouter.com/model_list) | Free routed models | Not published | Not published | Lightweight multi-provider proxy | Community tracker-tested Sep 2026 |
| [LLM Gateway](https://llmgateway.io/models?filters=1&free=true) | Filterable $0 models | Not published | Not published | One dashboard, many backends | Use the free filter; catalog rotates |
| [Mixedbread](https://www.mixedbread.com/pricing) | Free embedding / retrieval tier | Not published | Not published | Embeddings, search, rerank | Retrieval-first, not a general chat frontier |
| [Coze](https://www.coze.com/open) | Free bot / model API quota | Not published | Not published | Agents + published bots | ByteDance stack. Quotas tied to account region |
| [AwanLLM](https://www.awanllm.com/models) | Free listed models | Not published | Not published | Simple OpenAI-compat | Tracker-tested Sep 2026; small provider |
| [FreeInference](https://freeinference.org) | Public free catalog | Not published | Not published | Discovery + some endpoints | Directory + docs at doc.freeinference.org |
| [Nous Portal](https://portal.nousresearch.com) | Free Hermes / research models | Not published | Not published | Hermes-family chat | Official Nous inference; caps unpublished |
| [A4F](https://www.a4f.co/models) | Free model list | Not published | Not published | Aggregated cheap / $0 ids | Community tracker. Stability not guaranteed |
| [Completions](https://www.completions.me) | Free hobby API | Not published | Not published | Quick OpenAI-compat tests | Small independent endpoint |
| [Requesty](https://requesty.ai/) | Free routed models | 200 | Not published | OpenAI-compat multi-model router | Community-verified Sep 2026: ~60 RPM, 200 RPD on free models. Base `https://router.requesty.ai/v1` |
| [Venice.ai](https://venice.ai/) | Free daily allowance | Not published | Not published | Privacy-first chat + image | ~10 RPM on free tier. Web + API; catalog includes Llama-class + SD |
| [Void AI](https://voidai.app/) | Daily credits | Not published | ~125,000 credits | Coding + multi-vendor hub | Community-verified Sep 2026: 100 RPM. Base `https://api.voidai.app/v1` |
| [Together AI](https://together.ai/) | Trial / starter credit | Not published | Not published | Hosted open models | Often $5 min purchase after trial. OpenAI-compat `api.together.xyz/v1` |
| [DeepInfra](https://deepinfra.com/) | Trial credits | Not published | Not published | Cheap OSS inference | High concurrency (~200/model). Credit-based, not a forever-free pool |
| [Kluster AI](https://kluster.ai/) | ~$5 signup credit | Not published | Not published | DeepSeek / Llama / Qwen host | Trackers list no-card start. Base `https://api.kluster.ai/v1` |
| [Lambda Inference](https://lambda.ai/) | ~$10 starter credit | Not published | Not published | GPU cloud + inference | One-time credit on many directories; confirm console |
| [Novita AI](https://novita.ai/) | Signup / referral credits + some $0 models | Not published | Not published | CN + OSS + image | OpenAI-compat `api.novita.ai`. Credit amounts ($0.50–$10) disagree across trackers |
| [Vercel AI Gateway](https://vercel.com/ai-gateway) | Listed $0 routed models | Not published | Not published | Unified billing + failover | Free rows rotate (Ling 3.0 Flash family observed Sep 2026) |
| [Replicate](https://replicate.com/) | Small trial credit | Not published | Not published | Models-as-containers | One-time credit. Good for image/video as well as text |
| [BazaarLink](https://bazaarlink.ai/) | Free listed models | Not published | Not published | Aggregated OpenAI-compat | awesome-free-ai-api: tested 2026-09-15 |
| [EvolveX](https://evolvex.ai/) | Free / starter access | Not published | Not published | Multi-model playground | awesome-free-ai-api + BYOK lists: tested Sep 2026 |
| [AnyRouter](https://anyrouter.dev/) | Shared free pool + donated keys | 1,000* | Not published | Routed free capacity | `anyrouter/free` daily cap on Go/donate plan. Treat as aggregator |
| [Sarvam](https://www.sarvam.ai/) | Free / low-cost India models | Not published | Not published | Indic multilingual | Sarvam-M and follow-ons. Not a general frontier chat host |
| [AI Pooled](https://aipooled.com/) | Community pooled inference | Capacity-based | Capacity-based | Shared cheap / $0 routes | awesome-free-ai-api: tested 2026-09-15. Availability varies |
| [Flowbar AI](https://flowbar.ai/) | Free listed models | Not published | Not published | Small OpenAI-compat host | Added to awesome-free-ai-api Aug 2026; verify live |

\* Approximate daily figures derived from published hourly/minute limits (not official daily quotas): Cloudflare = Neurons not requests; Kilo = 200 req/h × 24; LLM7 = 100 req/h × 24; UnoRouter = ~1 RPM × 1440. Alibaba ~1M tokens is a per-model new-user grant, not a daily cap. IBM ~300k tokens is monthly, not daily. AnyRouter 1,000 RPD is the donated/Go free pool, not anonymous unlimited.

### How this list is built

1. Scan public directories (FreeLLM, awesome-free lists).
2. Cross-check community reviews and official docs (quotas, card, SLA).
3. Keep **new providers only** when extending — do not duplicate rows.
4. Flag aggregators and experiments: they disappear first.

### Sources checked

- [FreeLLM provider directory](https://freellm.net/providers/)
- [awesome-free-llm-apis](https://github.com/amardeeplakshkar/awesome-free-llm-apis)
- [awesome-freellm-apis](https://github.com/open-free-llm-api/awesome-freellm-apis)
- [awesome-free-ai-api](https://github.com/YoannDev90/awesome-free-ai-api)
- [awesome-free-ai-coding](https://github.com/mvalentsev/awesome-free-ai-coding)
- [awesome-free-byok-models](https://github.com/velo4705/awesome-free-byok-models)
- [awesome-free-inference](https://github.com/bradAGI/awesome-free-inference)
- [Free-LLM](https://github.com/nejib1/Free-LLM)
- [free-llm-resources](https://github.com/AILookup/free-llm-resources)
- [freeinference.dev](https://freeinference.dev/)
- [Google Gemini API rate limits](https://ai.google.dev/gemini-api/docs/rate-limits)
- [Groq rate limits](https://console.groq.com/docs/rate-limits)
- [OpenRouter pricing](https://openrouter.ai/pricing)
- [Cohere rate limits](https://docs.cohere.com/v1/docs/rate-limits)
- [Hugging Face Inference Providers pricing](https://huggingface.co/docs/inference-providers/pricing)
- [Cerebras pricing](https://www.cerebras.ai/pricing)
- [Mistral usage and limits](https://docs.mistral.ai/admin/billing-usage/usage-limits)
- [SambaNova rate limits](https://docs.sambanova.ai/docs/en/models/rate-limits)
- [SiliconFlow rate limits](https://docs.siliconflow.com/en/userguide/rate-limits/rate-limit-and-upgradation)
- [LLM7.io limits](https://docs.llm7.io/limits)
- [ModelScope API inference tracking](https://free-model.com/providers/modelscope/)
- [Kilo Code free usage](https://kilo.ai/docs/getting-started/using-kilo-for-free)
- [Kilo Code rate limits](https://kilo.ai/docs/getting-started/rate-limits-and-costs)
- [Modal pricing](https://modal.com/pricing)
- [Baseten pricing](https://www.baseten.co/pricing/)
- [Nscale Serverless Inference](https://www.nscale.com/blog/introducing-nscale-serverless-inference-scalable-ai-without-infrastructure-hassles)
- [Hyperbolic billing](https://www.hyperbolic.ai/docs/general/billing-payments)
- [Fireworks AI free-tier tracking](https://xyzs996.github.io/free-llm-api/provider/fireworks.html)
- [Pollinations API docs](https://github.com/pollinations/pollinations/blob/main/APIDOCS.md)
- [Ollama pricing](https://ollama.com/pricing)
- [AnyAPI free-tier tracking](https://github.com/amardeeplakshkar/awesome-free-llm-apis)
- [Api.Airforce](https://api.airforce/)
- [UnoRouter provider tracking](https://models.sulat.com/providers/unorouter)
- [AI21 Studio pricing tracking](https://aiproviderindex.com/platform/ai21-studio)
- [GitHub Models rate limits](https://docs.github.com/en/github-models/use-github-models/prototyping-with-ai-models)
- [OpenCode Zen](https://opencode.ai/zen)
- [Aion Labs API reference](https://www.aionlabs.ai/docs/api-reference/)
- [Agnes AI FAQ](https://agnes-ai.com/doc/faqs)
- [Agnes AI pricing](https://wiki.agnes-ai.com/en/docs/pricing)
- [OVHcloud AI Endpoints capabilities](https://docs.ovhcloud.com/en/guides/public-cloud/ai-machine-learning/ai-endpoints-capabilities)
- [Chutes.ai on FreeLLM](https://freellm.net/providers/chutes-ai)
- [Chutes Early Access change](https://chutes.ghost.io/community-announcement-february/)
- [Glhf.chat](https://glhf.chat/)
- [Alibaba Model Studio free quota](https://www.alibabacloud.com/help/en/model-studio/what-is-model-studio)
- [DeepSeek platform](https://platform.deepseek.com/)
- [Nebius studio](https://studio.nebius.com/)
- [xAI API](https://docs.x.ai/)
- [Moonshot / Kimi platform](https://platform.moonshot.ai/)
- [Scaleway Generative APIs](https://www.scaleway.com/en/docs/generative-apis/)
- [Hetzner Inference API docs](https://docs.hetzner.com/general/company-and-policy/experiments/inference/)
- [IBM watsonx.ai Runtime plans](https://dataplatform.cloud.ibm.com/docs/content/wsj/getting-started/wml-plans.html?context=wx)
- [Requesty](https://requesty.ai/)
- [Venice.ai](https://venice.ai/)
- [Void AI](https://voidai.app/)
- [Together AI pricing](https://www.together.ai/pricing)
- [DeepInfra](https://deepinfra.com/)
- [Kluster AI](https://kluster.ai/)
- [Lambda](https://lambda.ai/)
- [Novita AI](https://novita.ai/)
- [Vercel AI Gateway](https://vercel.com/ai-gateway)
- [Replicate](https://replicate.com/)
- [AnyRouter free models](https://anyrouter.dev/blog/top-free-models-api)
- [Sarvam](https://www.sarvam.ai/)
