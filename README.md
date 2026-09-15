# GreatLLM

Some free LLM, vision models, image... All free.

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

\* Approximate daily figures derived from published hourly/minute limits (not official daily quotas): Cloudflare = Neurons not requests; Kilo = 200 req/h × 24; LLM7 = 100 req/h × 24; UnoRouter = ~1 RPM × 1440.

### Sources checked

- [FreeLLM provider directory](https://freellm.net/providers/)
- [awesome-free-llm-apis](https://github.com/amardeeplakshkar/awesome-free-llm-apis)
- [awesome-freellm-apis](https://github.com/open-free-llm-api/awesome-freellm-apis)
- [free-llm-resources](https://github.com/AILookup/free-llm-resources)
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
