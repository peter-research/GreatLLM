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

\* Cloudflare uses Neurons rather than tokens; this value is kept in the RPD column only to expose the daily quota and should not be interpreted as 10,000 requests.

### Sources checked

- [FreeLLM provider directory](https://freellm.net/providers/)
- [awesome-free-llm-apis](https://github.com/amardeeplakshkar/awesome-free-llm-apis)
- [free-llm-resources](https://github.com/AILookup/free-llm-resources)
- [Google Gemini API rate limits](https://ai.google.dev/gemini-api/docs/rate-limits)
- [Groq rate limits](https://console.groq.com/docs/rate-limits)
- [OpenRouter pricing](https://openrouter.ai/pricing)
