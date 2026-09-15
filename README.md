# GreatLLM

Some free LLM, vision models, image... All free.

## Free providers

| Provider | Free access | RPD | TKPD | Best for | Notes |
| --- | --- | ---: | ---: | --- | --- |
| [NVIDIA NIM](https://build.nvidia.com/) | Free endpoints available | Varies | Not published | Open models, high-throughput inference | NVIDIA's catalog exposes free endpoints for selected models. Limits and model availability can change. |
| [Cloudflare Workers AI](https://developers.cloudflare.com/workers-ai/) | 10,000 Neurons/day on Workers Free | 10,000 Neurons/day* | N/A | Serverless AI, edge inference | The free quota is measured in Neurons rather than requests or tokens, so it is not directly comparable to RPD/TKPD. Community reports mixed latency/reliability. |
| [Z.AI](https://z.ai/) | GLM-4.7-Flash and other Flash models are free | Not published | Not published | Coding, reasoning, Chinese/English | GLM-4.7-Flash is officially listed as completely free with a 200K context window. |
| [Google AI Studio](https://ai.google.dev/) | Free tier for selected Gemini models | Model-dependent | Model-dependent | General-purpose multimodal AI | Free-tier limits are model-specific and can include RPM, TPM and RPD. Google says the active limits should be checked in AI Studio; limits can change. |
| [Groq](https://groq.com/) | Free API tier | Model-dependent | Model-dependent | Very fast inference, open models | Groq measures limits with RPM, RPD, TPM and sometimes TPD. Exact limits are model-specific and shown in the rate-limit reference. |
| [OpenRouter](https://openrouter.ai/) | 25+ free models | 50 | Not published | Multi-provider routing, OpenAI-compatible APIs | The free plan currently lists 25+ free models and a 50 requests/day limit. Free-model availability changes over time. |
| [Cohere](https://cohere.com/) | Free trial API key | 1,000 calls/month | Not published | RAG, embeddings, reranking, enterprise NLP | Trial keys are free and limited to 1,000 API calls/month. Chat endpoints are generally limited to 20 requests/minute on trial keys. |
| [Hugging Face Inference Providers](https://huggingface.co/inference) | $0.10/month for free users | Not published | Not published | Model discovery, experimentation, multi-provider inference | Free Hugging Face users receive $0.10/month in inference credits. The credits can be used across supported Inference Providers and are subject to change. |
| [Cerebras Inference](https://www.cerebras.ai/inference) | $5 free trial credit | Not published | Not published | Extremely fast inference, open models | Cerebras currently provides $5 in free credit after account creation. It is a trial credit rather than a recurring daily quota. |
| [Mistral AI](https://mistral.ai/) | Free API mode | Not published | Not published | European models, general-purpose AI | Mistral's Free API mode provides included monthly usage. Exact API limits are shown per organization in the Limits dashboard and can vary by model. |
| [SambaNova Cloud](https://cloud.sambanova.ai/) | $5 free credit | Not published | Not published | Fast inference, open models | SambaNova provides a one-time $5 free credit on the free tier. It is not a recurring daily quota; current model availability and limits vary. |
| [SiliconFlow](https://www.siliconflow.com/) | Free models | Model-dependent | Model-dependent | Open models, multimodal inference | SiliconFlow documents permanently free model variants with fixed per-model rate limits. Some free models require account/identity verification. |
| [LLM7.io](https://llm7.io/) | Free token available | Not published | Not published | Simple multi-model API, experimentation | The free plan uses a token-based allowance. Official docs list 2 requests/second, 20/minute and 100/hour for the free token. |
| [ModelScope](https://modelscope.cn/) | Free API inference for registered users | 2,000 | Not published | Qwen, DeepSeek and Chinese open models | Current community/provider tracking reports a 2,000 RPD shared quota with a dynamic 500 RPD per-model cap. Alibaba Cloud account binding and real-name verification may be required. |
| [Kilo Code](https://kilo.ai/) | Free model gateway | 4,800* | Not published | Coding agents, free model routing | Kilo's free model tier (`kilo-auto/free`) is free and currently limited to 200 requests/hour per IP. The daily figure is a simple 200 × 24 normalization, not a published daily quota. |
| [Modal](https://modal.com/) | $30/month free compute | Not published | Not published | Self-hosted inference, GPU workloads | Modal's Starter plan includes $30/month of free compute, which can be used to deploy and serve open-source models. This is compute credit, not a token quota. |
| [Baseten](https://www.baseten.co/) | Free starter credits | Not published | Not published | Model deployment, custom inference | Baseten says new accounts receive credits to experiment with deployments. The current public pricing page does not publish a fixed credit amount. |
| [Nscale](https://www.nscale.com/) | $5 free starter credit | Not published | Not published | EU-hosted inference, open models | Nscale's Serverless Inference gives new users $5 of free credit to explore models. It is a starter credit rather than a recurring free quota. |
| [Hyperbolic](https://www.hyperbolic.ai/) | $1 promotional credit | Not published | Not published | GPU-backed open-model inference | Hyperbolic currently grants $1 in promotional inference credit after phone verification. The credit cannot be used for GPU rentals. |
| [Fireworks AI](https://fireworks.ai/) | $1 free credit / free request envelope | Not published | Not published | Fast serverless open-model inference | Current third-party tracking reports a no-card 10 RPM free request envelope, while other current sources report a one-time $1 signup credit. Treat the allowance as introductory and verify before relying on it. |
| [Pollinations AI](https://pollinations.ai/) | Free/light-use API access | Not published | Not published | Text, image, audio and video generation | Pollinations exposes OpenAI-compatible APIs and free-tier grants/allowances. Heavier usage is metered through Pollen credits, so exact free capacity varies by account and tier. |
| [Ollama Cloud](https://ollama.com/) | Free cloud tier with starter usage credits | Not published | Not published | Open-model chat, local-to-cloud workflows | Ollama's current pricing page lists a $0 Free plan with starter usage credits and access to starter models. Cloud API access is OpenAI-compatible at `https://ollama.com/v1`; exact free token caps are not publicly published. |
| [AnyAPI](https://api.anyapi.ai/) | Free tier, no card required | 200 | Not published | OpenAI-compatible multi-model gateway | Current community-maintained free-API tracking lists 20 RPM and 200 RPD for AnyAPI's free tier, with access to a rotating set of open models. Verify the live model list and limits before production use. |
| [Api.Airforce](https://api.airforce/) | Free tier for testing and hobby projects | Not published | Not published | Unified gateway, coding agents, chat clients | Api.Airforce advertises a $0 Free plan for testing and hobby projects with an OpenAI-compatible API. Public pages emphasize best-effort free access rather than a fixed published daily token quota. |
| [UnoRouter](https://unorouter.ai/) | Free aggregated model access | Not published | Not published | Multi-provider routing, experimentation | Current provider tracking describes UnoRouter as an OpenAI-compatible gateway aggregating free upstream models. The service applies a soft cap of about 1 request/minute/user, while upstream quotas vary. |
| [AI21 Studio](https://www.ai21.com/studio/) | $10 free trial credit for 7 days | Not published | Not published | Long-context Jamba models, writing | Current pricing trackers report a $10 free trial with no card required for seven days. This is a time-limited trial, not a permanent free tier. |
| [GitHub Models](https://github.com/marketplace/models) | Free inference with a GitHub account | 50–150 | Not published | Prototyping GPT/Phi/Llama/Mistral models | Official GitHub docs tie limits to Copilot plan and model tier. Copilot Free is commonly 10–15 RPM and 50 RPD (high-tier models) or 150 RPD (low-tier models), plus tight per-request token caps (~8K in / 4K out). Best for prototypes, not production. |
| [OpenCode Zen](https://opencode.ai/zen) | Zero-priced promo models via Zen gateway | Not published | Not published | Coding agents, OpenAI-compatible chat | Current pricing pages list several models at $0 for a limited time (e.g. Big Pickle, MiMo-V2.5 Free, Ling 3.0 Flash Fin Free, Nemotron 3 Ultra Free). Availability rotates; paid catalog models must not be treated as free. Base URL: `https://opencode.ai/zen/v1`. |
| [Aion Labs](https://www.aionlabs.ai/) | Permanent free daily allowance, no card | Not published | ~20,000 | Roleplay, creative writing, light API trials | Official docs describe a free daily credit allowance with an OpenAI-compatible API at `https://api.aionlabs.ai/v1`. Community trackers consistently report ~15 RPM and ~20K tokens/day. Exact official token numbers are not fully published. |
| [Agnes AI](https://agnes-ai.com/) | Indefinitely free Flash text/image/video models | Not published | Not published | Multimodal generation, agents | Official FAQ and pricing docs currently price selected Flash models at $0. Access is RPM-limited rather than a published daily token cap. Treat promotional $0 rows as subject to change; Pro models are paid. |
| [OVHcloud AI Endpoints](https://endpoints.ai.cloud.ovh.net/) | Free EU-hosted open models | Not published | Not published | GDPR / EU inference, open-weight models | Official OVH docs: 2 RPM per IP per model (anonymous) and 400 RPM per project per model (authenticated API key). No separate published daily token cap. Discovery-mode projects without a payment method cannot create usable access keys. |

\* Cloudflare uses Neurons rather than tokens; this value is kept in the RPD column only to expose the daily quota and should not be interpreted as 10,000 requests. For comparison, a current community analysis estimates 10,000 Neurons/day at roughly 147,000 output tokens/day when using gpt-oss-120b. This is model-specific and only an approximation, not an official Cloudflare token conversion. Kilo's 4,800 figure is likewise a normalized 200 requests/hour × 24, not a published daily limit.

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
