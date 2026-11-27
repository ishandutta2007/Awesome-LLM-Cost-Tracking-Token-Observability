# Awesome-LLM-Cost-Tracking-Token-Observability

# Awesome-LLM-Cost-Tracking-Token-Observability



Top LLM Cost Tracking Token Observability (Opensource) 🌟 Star if you like it! 🌟



A curated list of top LLM cost tracking platforms, token usage observability suites, AI gateways, smart model routers, FinOps spend dashboards, and OpenTelemetry tracing tools—featuring commercial SaaS/Hosted platforms alongside their open-source equivalents.



---



## Table of Contents



- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source Equivalents & Tools](#open-source-equivalents--tools)

  - [Token Usage Trackers & Lightweight Cost Calculators](#token-usage-trackers--lightweight-cost-calculators)

  - [Self-Hosted LLM Observability, Tracing & Spend Dashboards](#self-hosted-llm-observability-tracing--spend-dashboards)

  - [Open-Source AI Gateways, LLM Proxies & Budget Enforcement](#open-source-ai-gateways-llm-proxies--budget-enforcement)

  - [Smart LLM Routers & Cost-Optimization Engines](#smart-llm-routers--cost-optimization-engines)

  - [OpenTelemetry GenAI Instrumentation & Tokenizers](#opentelemetry-genai-instrumentation--tokenizers)

- [Contributing](#contributing)



---



## SaaS/Hosted Platforms



Commercial, cloud-hosted LLM observability suites, managed AI gateways, cost-optimizing model routers, and enterprise GenAI FinOps platforms.



* **[Helicone Cloud](https://helicone.ai)** - Managed LLM observability and AI gateway platform offering real-time token cost tracking, latency monitoring, caching, and rate limiting via a one-line proxy.

* **[Langfuse Cloud](https://langfuse.com)** - Hosted enterprise version of Langfuse providing granular token usage attribution, per-user/session cost analytics, and trace debugging.

* **[Portkey](https://portkey.ai)** - Commercial AI gateway and observability suite unifying 200+ LLMs with budget limits, semantic caching, load balancing, and spend analytics.

* **[PromptLayer](https://promptlayer.com)** - Hosted prompt engineering and LLM observability platform tracking request costs, token counts, latency, and prompt version performance.

* **[Martian](https://withmartian.com)** - Commercial dynamic LLM router that inspects prompts in real time and routes each query to the most cost-effective model without sacrificing quality.

* **[Keywords AI](https://keywordsai.co)** - Cloud-hosted LLM monitoring and unified API platform featuring real-time token spend analytics, user-level budgets, and fallback routing.

* **[LiteLLM Enterprise / BerriAI Cloud](https://litellm.ai)** - Commercial support and enterprise control plane for LiteLLM Proxy with SSO, virtual budget keys, and team chargeback dashboards.

* **[Cloudflare AI Gateway](https://cloudflare.com)** - Managed edge gateway providing unified analytics, token usage tracking, response caching, and rate limiting across AI providers.

* **[Datadog LLM Observability](https://datadoghq.com)** - Enterprise cloud monitoring solution tracking LLM token consumption, estimated spend, latency, and drift alongside infrastructure metrics.

* **[Unify.ai](https://unify.ai)** - Hosted LLM routing and benchmarking platform automatically optimizing cost, speed, and quality across model providers.



---



## Open-Source Equivalents & Tools



Free and open-source software (FOSS) token trackers, self-hosted LLM observability platforms, AI proxy gateways, smart model routers, and OpenTelemetry SDKs.



### Token Usage Trackers & Lightweight Cost Calculators



* **[TokenTracker (xiufengsun)](https://github.com)** - Open-source token tracking and LLM usage monitoring utility designed for transparent token accounting and cost visibility.

* **[Tokencost](https://github.com)** - Lightweight open-source Python utility for calculating real-time USD costs and token counts across 400+ LLM providers and models.

* **[ccusage](https://github.com)** - Fast open-source CLI tool for analyzing local AI coding agent token usage and daily/monthly spend from local session logs.

* **[LLM-Cost-Calculator / genai-prices](https://github.com)** - Community-maintained open-source pricing database and library for accurate token cost calculation across foundation models.

* **[Tiktoken (OpenAI)](https://github.com)** - Fast open-source BPE tokenizer written in Rust/Python used universally to count tokens and estimate prompt/completion costs before API calls.



### Self-Hosted LLM Observability, Tracing & Spend Dashboards



* **[Langfuse](https://github.com)** - Leading open-source LLM engineering and observability platform offering detailed token counts, automated cost calculation, user/session attribution, and trace trees.

* **[Helicone (Open-Source Core)](https://github.com)** - Open-source LLM observability platform and proxy logging every request, response, token count, latency, and USD cost with self-hosted Docker support.

* **[Lunary](https://github.com)** - Open-source production toolkit for LLM observability featuring per-user cost tracking, agent tracing, prompt management, and PII masking.

* **[Arize Phoenix](https://github.com)** - Open-source, OpenTelemetry-native AI observability platform capturing token usage, latency, and LLM/agent trace spans locally or on Kubernetes.

* **[Opik (Comet)](https://github.com)** - Open-source LLM tracing and evaluation platform engineered for high-volume trace ingestion, token analytics, and cost monitoring.

* **[Langtrace AI](https://github.com)** - Open-source OpenTelemetry-based observability tool tracking token spend, latency, and traces across LLMs, vector DBs, and frameworks.



### Open-Source AI Gateways, LLM Proxies & Budget Enforcement



* **[LiteLLM Proxy](https://github.com)** - The most popular open-source LLM proxy server calling 100+ LLMs in OpenAI format while tracking spend, enforcing virtual key budgets, and setting rate limits.

* **[Portkey AI Gateway (Open-Source Core)](https://github.com)** - Blazing-fast, lightweight open-source AI gateway written in TypeScript/Node.js supporting unified routing, fallbacks, retries, and token logging.

* **[Bifrost (Maxim AI)](https://github.com)** - Ultra-fast open-source LLM gateway written in Go delivering sub-millisecond overhead, semantic caching, budget caps, and multi-provider load balancing.

* **[TensorZero](https://github.com)** - High-performance open-source data & learning flywheel for LLMs written in Rust combining an AI gateway, observability, optimization, and experimentation.

* **[One API / New API](https://github.com)** - Widely deployed open-source LLM API management and distribution system with token quota accounting, billing, and multi-channel load balancing.

* **[Kong AI Gateway](https://github.com)** - Open-source API gateway extended with AI plugins for token rate limiting, semantic caching, prompt governance, and cost metrics.



### Smart LLM Routers & Cost-Optimization Engines



* **[RouteLLM (LMSYS)](https://github.com)** - Open-source framework by LMSYS for serving and evaluating LLM routers that dynamically route simple queries to cheaper models and complex ones to frontier models.

* **[Semantic Router (Aurelio Labs)](https://github.com)** - Superfast open-source decision-making layer using semantic vector space to route requests without expensive LLM classification calls.

* **[GPTCache](https://github.com)** - Open-source semantic cache library for storing LLM responses and slashing duplicate API token costs and latency.

* **[LLMLingua (Microsoft)](https://github.com)** - Open-source prompt compression toolkit that compresses prompts up to 20x to dramatically reduce token consumption and inference costs.



### OpenTelemetry GenAI Instrumentation & Tokenizers



* **[OpenLLMetry (Traceloop)](https://github.com)** - Open-source set of extensions built on standard OpenTelemetry providing instant token usage, cost, and trace visibility into any observability backend.

* **[OpenInference (Arize)](https://github.com)** - Open-source OpenTelemetry instrumentation conventions and auto-instrumentors capturing LLM token counts, prompts, and tool calls.

* **[AgentOps (Open-Source SDK)](https://github.com)** - Open-source Python SDK for monitoring AI agents, tracking recursive token spend, tool usage costs, and session replays.



---



## Contributing



Contributions are welcome! Feel free to open a Pull Request to add more open-source LLM cost trackers, token observability platforms, AI gateways, or prompt compression tools.



1. Fork the repository.

2. Add your project under the appropriate category with a concise description.

3. Submit a Pull Request.
