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

\* Cloudflare uses Neurons rather than tokens; this value is kept in the RPD column only to expose the daily quota and should not be interpreted as 10,000 requests.

### Sources checked

- [FreeLLM provider directory](https://freellm.net/providers/)
- [awesome-free-llm-apis](https://github.com/amardeeplakshkar/awesome-free-llm-apis)
- [free-llm-resources](https://github.com/AILookup/free-llm-resources)
- [Google Gemini API rate limits](https://ai.google.dev/gemini-api/docs/rate-limits)
- [Groq rate limits](https://console.groq.com/docs/rate-limits)
- [OpenRouter pricing](https://openrouter.ai/pricing)
- [Cohere rate limits](https://docs.cohere.com/v1/docs/rate-limits)
- [Hugging Face Inference Providers pricing](https://huggingface.co/docs/inference-providers/pricing)
- [Cerebras pricing](https://www.cerebras.ai/pricing)
- [Mistral usage and limits](https://docs.mistral.ai/admin/billing-usage/usage-limits)
- [SambaNova rate limits](https://docs.sambanova.ai/docs/en/models/rate-limits)
