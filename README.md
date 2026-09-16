# GreatLLM

Some free LLM, vision models, image... All free.

Curated directory of **free or free-tier LLM / multimodal APIs**. Quotas change often — treat numbers as snapshots, not contracts. Prefer official docs over aggregators.

## New this pass (2026-09-16 late)

Research: FreeLLM / freellm.net, awesome-freellm-apis, freeinference.dev, nejib1/Free-LLM, official rate-limit pages. Community reviews checked; **new names only** (not already in the catalog below).

| Provider | Free access | RPD | TKPD | Best for | Notes |
| --- | --- | ---: | ---: | --- | --- |
| [Agnes AI](https://agnes-ai.com/) | Permanent free multimodal API | RPM-capped | Not published | Text + image + video | Official: ~20 RPM text on default key; no SLA |
| [Aion Labs](https://www.aionlabs.ai/) | Free signup tier | ~20k tokens/day | 20,000 | Roleplay / story | Official: 15 RPM, 20k TPM/TPD free |
| [xAI](https://console.x.ai/) | Monthly Grok credits | Credit-based | Credit-based | Grok chat / reasoning | OpenAI-compat `api.x.ai`; card often required |
| [DeepSeek](https://platform.deepseek.com/) | Signup token credit | Not published | ~5M tokens* | Official V3 / reasoner | One-time / rotating promo; then cheap PAYG |
| [AI21 Labs](https://studio.ai21.com/) | Trial credits | Credit-based | Credit-based | Jamba long context | ~$10 trial reported; confirm window |
| [Hyperbolic](https://app.hyperbolic.xyz/) | Signup trial credits | Credit-based | Credit-based | Large OSS (Llama / DeepSeek) | ~$1 trial + ~60 RPM on basic |
| [Venice.ai](https://venice.ai/) | Free privacy-oriented tier | Limited | Not published | Uncensored OSS + image | ~10 RPM on free; privacy-first |
| [Glhf.chat](https://glhf.chat/) | Listed free OSS hosts | Capacity-based | Capacity-based | Llama / Mixtral hobby | Community host; reliability varies |
| [Nebius Token Factory](https://tokenfactory.nebius.com/) | Builder / signup credits | Credit-based | Credit-based | EU OSS inference | Builder program + small studio credit |
| [Nscale](https://www.nscale.com/) | New-user inference credits | Credit-based | Credit-based | Serverless OSS | ~$5 signup credit reported |
| [Novita AI](https://novita.ai/) | Small trial credit | Credit-based | Credit-based | OSS + image | ~$0.50 trial; 60 RPM typical |
| [Inference.net](https://inference.net/) | Free plan + small monthly credit | Credit-based | Credit-based | OSS routing | Recurring $1-class credit reported |
| [Fireworks AI](https://fireworks.ai/) | Small permanent credit | Credit-based | Credit-based | Fast OSS serving | Tiny always-on credit; then PAYG |
| [Scaleway Generative APIs](https://www.scaleway.com/en/generative-apis/) | Starter token pack | Not published | ~1M* | EU-hosted OSS | GDPR-friendly French cloud |
| [Modal](https://modal.com/) | Monthly compute credit | Credit-based | Credit-based | Run models as functions | $5–30/mo compute, not a chat SaaS |
| [MiniMax](https://www.minimax.io/) | Official / CN free rows | Not published | Not published | Coding + long context | Also free via ModelScope hosts |
| [Moonshot AI](https://platform.moonshot.ai/) | Kimi platform credits | Not published | Not published | Long-context Kimi | Official CN API; NIM also hosts Kimi |

## Full catalog

Previous rows kept (labs first, then gateways). Same columns.

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
| [Kilo Code](https://kilo.ai/) | Free model gateway | 4,800* | Not published | Coding agents | 200 req/hour per IP |
| [GitHub Models](https://github.com/marketplace/models) | Free with GitHub account | 50-150 | Not published | Prototyping GPT/Phi/Llama | Tied to Copilot tier |
| [OpenCode Zen](https://opencode.ai/zen) | Promo $0 models | Not published | Not published | Coding agents | Limited-time free ids |
| [OVHcloud AI Endpoints](https://endpoints.ai.cloud.ovh.net/) | Free EU open models | Not published | Not published | GDPR / EU inference | 2 RPM anon / 400 RPM auth |
| [Chutes.ai](https://chutes.ai/) | Community GPU / listed free models | Not published | Not published | DeepSeek / Llama hosts | Capacity-based |
| [Alibaba Cloud Model Studio](https://www.alibabacloud.com/product/modelstudio) | New-user token quota | Not published | ~1M / model* | Official Qwen | Time-limited then PAYG |
| [Pollinations AI](https://pollinations.ai/) | Free / light use | Not published | Not published | Text, image, audio, video | Heavier use uses Pollen |
| [Ollama Cloud](https://ollama.com/) | Free plan + starter credits | Not published | Not published | Open models, local-cloud | Caps not fully published |
| [Requesty](https://requesty.ai/) | Free routed models | 200 | Not published | OpenAI-compat router | ~60 RPM |
| [NaraRouter](https://router.naraya.ai/) | Official Free plan | Not published | 5,000,000 | Multi-provider gateway | 5M tokens/day, 10 RPM, no card |
| [Lightning AI Model APIs](https://lightning.ai/models) | Signup free tokens | Not published | ~30-40M / month* | Frontier + OSS | Official starter tokens |
| [Upstage](https://console.upstage.ai) | $10 trial credits | Not published | Credit-based | Solar + documents | ~60 RPM |
| [GMI Cloud](https://www.gmicloud.ai) | $5 credit + some free OSS | Not published | Not published | DeepSeek / GLM / Qwen | Prod GPU free rows |
| [Snowflake Cortex](https://docs.snowflake.com/en/user-guide/snowflake-cortex/llm-functions) | Account trial credits | Not published | Not published | SQL + LLM | Needs Snowflake account |
| [Poolside](https://poolside.ai) | Laguna often free via NIM | Not published | Not published | Coding models | Official API may be gated |
| [InclusionAI](https://huggingface.co/inclusionAI) | Ling 3.0 Flash free on routers | ~50-200 | Not published | Multimodal Ling | Official paid; `:free` on OpenRouter |
| [Nex AGI](https://huggingface.co/Nex-AGI) | Nex-N2.5 free on routers | ~50-200 | Not published | Agent / reasoning | `:free` aggregator rows |
| [Puter.js](https://developer.puter.com) | User-pays browser SDK | User-dependent | User-dependent | Apps without backend keys | End users pay usage |
| [Featherless AI](https://featherless.ai) | Paid catalog / HF route | Not published | Not published | Huge OSS catalog | Check HF Inference Provider path |
| [StepFun](https://platform.stepfun.com/) | V0 $0 + tracked ¥10 signup | ~10 RPM (V0) | ~5M TPM (V0) | CN multimodal / agents | Official OpenAI + Anthropic paths |
| [Liquid AI](https://www.liquid.ai/) | Free LFM ids via routers + console | Not published | Not published | Small efficient LFM models | Official lab; `:free` rows also on OpenRouter |
| [Thinking Machines Lab](https://thinkingmachines.ai/) | Inkling / Inkling Small listed $0 on routers | Not published | Not published | Long-context research models | First-party API status rotates |
| [ZeroLimitAI](https://zerolimit.ai/) | Routed free pool | Capacity-based | Capacity-based | Auto-failover across free backends | Community aggregator |
| [Google Antigravity](https://antigravity.google/) | Bundled frontier models in the coding agent | Not published | Not published | Agent + Gemini / Claude promo routes | Tool-tied, not a standalone public API |
| [Azure AI Foundry](https://ai.azure.com/) | New-account / Foundry trial credits | Not published | Not published | Microsoft-hosted OSS + OpenAI | Card often required after trial |
| [Amazon Bedrock](https://aws.amazon.com/bedrock/) | AWS Free Tier / limited model trials | Not published | Not published | Managed multi-lab models | Needs AWS account; most traffic is paid |
| [Perplexity](https://www.perplexity.ai/) | Limited Sonar / search API trial | Not published | Not published | Grounded search answers | Confirm current Sonar envelope |
| [Reka AI](https://www.reka.ai/) | Research / listed starter access | Not published | Not published | Multimodal Reka models | Independent lab |
| [Helicone](https://www.helicone.ai/) | Gateway + logged free routes | Not published | Not published | Observability + routing | Proxy, not a first-party host |
| [CodeGPT](https://codegpt.co/) | Economy / free agent models | Not published | Not published | IDE coding agent | Model IDs not fully published |
| [You.com](https://you.com/) | Search / research API starter | Not published | Not published | Web-grounded answers | Quotas unpublished |
| [Jina AI](https://jina.ai/) | Free embedding / reader / rerank tier | Not published | Not published | RAG primitives | Retrieve-first, not chat |
| [Voyage AI](https://www.voyageai.com/) | Free embedding token pack | Not published | Not published | High-quality embeddings | Not a chat LLM host |
| [Aleph Alpha](https://aleph-alpha.com/) | EU research / listed trial | Not published | Not published | Sovereign EU models | Confirm live public API |
| [Baichuan](https://platform.baichuan-ai.com/) | CN official signup credits | Not published | Not published | Baichuan chat models | Real-name typical |
| [Skywork](https://www.skywork.ai/) | Listed free / CN research models | Not published | Not published | Kunlun / Skywork family | Verify public API vs chat-only |

\* Approximate daily figures derived from published hourly/minute limits or starter packs. Quotas change often.

### How this list is built

1. Scan public directories (FreeLLM, awesome-free lists).
2. Cross-check community reviews and official docs (quotas, card, SLA).
3. Keep **new providers only** when extending — do not duplicate rows.
4. Flag aggregators and experiments: they disappear first.

### Sources checked

- [FreeLLM](https://freellm.net/providers/)
- [awesome-freellm-apis](https://github.com/open-free-llm-api/awesome-freellm-apis)
- [awesome-free-ai-coding](https://github.com/mvalentsev/awesome-free-ai-coding)
- [awesome-free-byok-models](https://github.com/velo4705/awesome-free-byok-models)
- [freeinference.dev](https://freeinference.dev/)
- [nejib1/Free-LLM](https://github.com/nejib1/Free-LLM)
- [Aion Labs rate limits](https://www.aionlabs.ai/docs/rate-limits/)
- [Agnes AI token plan](https://wiki.agnes-ai.com/en/docs/tokenplan)
