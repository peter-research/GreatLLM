# GreatLLM

Some free LLM, vision models, image... All free.

Curated directory of **free or free-tier LLM / multimodal APIs**. Quotas change often — treat numbers as snapshots, not contracts. Prefer official docs over aggregators.

## New this pass (2026-09-17 evening)

Research: freellm.net /providers + changelog 2026-09-17, awesome-freellm-apis README (refreshed 2026-09-17), mvalentsev/awesome-free-ai-coding (probes 2026-09-17), freeinference.dev 2026-09-17, KDnuggets 2026-09-17 five-provider review, klymentiev.com no-card map (Sep 2026), AnyRouter docs `/features/free-tier`, NaraRouter plan notes on Volksdroid, OVHcloud / SiliconFlow / ModelScope / Requesty official catalog pages.
Reviews: mvalentsev last-verified column for Requesty, Kilo Code, Amazon Q Developer, OVHcloud, SiliconFlow, ModelScope (2026-09-17). AnyRouter official docs: Free plan is 10 RPD on `anyrouter/free`; 1k RPD needs Go ($2) or a donated key — not a fat no-strings $0 pool. Amazon Q Developer Free is 50 agentic requests/month for Builder ID, IDE/CLI-tied. Kilo Code is an agent gateway with rotating $0 ids, not a raw multi-lab SaaS. Cerebras was delisted from awesome-free-ai-coding on 2026-09-17 — omitted here.
**New names only** — none of these rows existed as provider lines in prior README passes.

| Provider | Free access | RPD | TKPD | Best for | Notes |
| --- | --- | ---: | ---: | --- | --- |
| [Requesty](https://www.requesty.ai) | $0 plan, free-priced catalog rows | ~200 | Not published | One-key router + fallbacks | mvalentsev verified 2026-09-17; 12 $0 rows, no card |
| [Kilo Code](https://kilo.ai) | Agent / gateway, no card | ~200 listed on some ids | Not published | Nemotron / Laguna / Step Flash | `https://api.kilo.ai/api/gateway` — tool-tied more than raw chat |
| [OVHcloud AI Endpoints](https://www.ovhcloud.com/en/public-cloud/ai-endpoints/catalog/) | Registration, EU catalog | See docs | See docs | EU-hosted OSS | `https://oai.endpoints.kepler.ai.cloud.ovh.net/v1` — freellm.net 14 free ids |
| [SiliconFlow](https://cloud.siliconflow.cn/account/ak) | Registration + listed free rows | High RPM advertised | Not published | CN OSS host | `https://api.siliconflow.cn/v1` — some sources cite 1k RPM; confirm live $0 ids |
| [ModelScope](https://modelscope.cn/my/myaccesstoken) | Registration, large free catalog | Shared daily pool | Shared daily pool | Qwen / MiniMax / GLM on Alibaba lab | `https://api-inference.modelscope.cn/v1` — changelog dropped two Qwen3.5 rows 2026-09-17 |
| [Amazon Q Developer](https://aws.amazon.com/q/developer/) | Builder ID Free Tier | ~50 agentic / month | Not published | IDE + CLI coding agent | Added on awesome-free-ai-coding 2026-09-17; not a raw chat SaaS |
| [AnyRouter](https://anyrouter.dev) | Signup; `anyrouter/free` | 10 on Free / 1k on Go | $0 per token on free ids | Multi-lab router + failover | Official docs 2026-09-17; Go is $2 or donate-a-key |
| [Google Antigravity](https://antigravity.google) | No-card coding agent listed | Tool-capped | Tool-capped | Gemini + Claude + gpt-oss in agent | mvalentsev start-here row 2026-09-17; confirm product URL / TOS |
| [CodeGPT](https://codegpt.co) | Economy free lane | Not published | Not published | IDE assistant | Models on Economy unpublished; paid Professional ~$9–10/mo |
| [QwenCloud](https://chat.qwen.ai) | First-party Qwen cloud path | Not published | Not published | Qwen3.x official host | Listed as AnyRouter BYOK upstream 2026-09; confirm public API vs chat-only |
| [ZenMux](https://zenmux.ai) | Listed gateway / BYOK path | Not published | Not published | Multi-lab mux | Appears on AnyRouter BYOK roster 2026-09-15 |
| [Kluster AI](https://kluster.ai) | Freemium inference listed | Not published | Not published | Hosted OSS / R1 class | Free-LLM Hub inference table; confirm current $0 vs trial |
| [Upstage](https://www.upstage.ai) | Signup trial credit listed | Credit-based | Credit-based | Solar house models | Trial then PAYG — dreamprompting 2026 comparison |
| [Featherless.ai](https://featherless.ai) | Listed free / hobby inference | Capacity-based | Capacity-based | HuggingFace-style serverless OSS | Community catalogs; confirm live TOS + rate page |
| [FriendliAI](https://friendli.ai) | Listed trial / free start | Credit-based | Credit-based | Fast dedicated endpoints | Trial-shaped, not a published permanent RPD |
| [Baseten](https://www.baseten.co) | Signup trial credit listed | Credit-based | Credit-based | Deployed model endpoints | More platform than chat SaaS; credit then PAYG |

