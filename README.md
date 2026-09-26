# Awesome-AI-Agent-Analytics

## Top AI Agent Analytics Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Agent Performance Analytics, Session Replay, Cost Attribution, Success Metrics, Tool-Call Insights & Production Agent Intelligence*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Agent Analytics**. These systems turn raw agent traces into actionable insights—success rates, cost per task, latency breakdowns, tool-use patterns, failure modes, and experiment comparisons—so teams can improve agent reliability and ROI.



**Examples** include AgentOps, OpenLIT, Helicone, Langfuse, HoneyHive, Braintrust, Humanloop, LangSmith, Arize Phoenix, and Keywords AI (the category leaders).



**Open-source emphasis**: Agent analytics builds on the strong open observability stack. **Langfuse**, **Arize Phoenix**, **OpenLLMetry**, **Helicone**, **Opik**, and related projects provide self-hosted analytics over agent runs. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

> **Market Insights:** The LLM and AI Agent Observability market is estimated at **$1.7B–$3.2B (2025/2026)** and projected to reach **$8.6B–$24.8B by 2030–2034**. The sector is currently **highly fragmented**—driven by rapid innovation, specialized agent-tracing frameworks (e.g. LangSmith, Arize AX, AgentOps), and OpenTelemetry standardizations, rather than a single winner-take-all enterprise vendor.

| Platform | Company Size (Valuation / Funding) | Starting Paid Tier | Free Tier Limit | Key Highlights & Description |
| :--- | :--- | :--- | :--- | :--- |
| **[LangSmith](https://www.langchain.com/langsmith)** | **$1.25B Valuation** ($160M funding) | **$39 / seat / mo** (Plus plan; $2.50/1k overage traces) | **5,000 base traces / mo** (1 seat, 14-day retention) | Observability, evaluation, and prompt testing platform by LangChain; deep integration with LangGraph. |
| **[Arize Phoenix / Arize AX](https://arize.com/)** | **$915M Acquisition** (by Dynatrace in 2026; $131M funding) | **$50 / mo** (AX Pro tier; $0.0005/span overage) | **25,000 trace spans / mo** (AX Free plan, unlimited evals) | Enterprise AI observability and open-source Phoenix framework for agent tracing, evaluations, and troubleshooting. |
| **[Braintrust](https://www.braintrust.dev/)** | **$800M Valuation** ($121.1M funding) | **$249 / mo** (Pro tier; $1.50/1k scores overage) | **1 GB processed data / mo** (14-day retention, Starter tier) | Evaluation- and feedback-centric platform for AI agents with automated LLM scoring and dataset management. |
| **[Humanloop](https://humanloop.com/)** | **Acquired by Anthropic** ($7.91M prior funding) | **Acquired by Anthropic** (Sunset standalone SaaS Sept 2025; integrated into Anthropic) | **14-day free trial** (2 seats, 50 evals, 10,000 logs/mo) | Prompt engineering, evaluation, and agent monitoring platform acquired by Anthropic in August 2025. |
| **[HoneyHive](https://www.honeyhive.ai/)** | **$7.4M Funding** (Seed led by Insight Partners) | **$99 / mo** (Team plan; usage-based overage) | **10,000 events / mo** (90-day retention, free developer tier) | Observability and evaluation platform purpose-built for multi-step AI agent sessions and tool-call workflows. |
| **[Keywords AI (Respan)](https://www.keywordsai.co/)** | **$5.5M Funding** (Seed stage, YC backed) | **$20 / mo** (Starter tier minimum) | **$15 free credits** (~10,000–50,000 traces) | Unified AI engineering platform and LLM proxy delivering prompt management, tracing, and agent performance dashboards. |
| **[Langfuse (Cloud)](https://langfuse.com/)** | **Acquired by ClickHouse** ($4.5M prior funding, ~$1.1M ARR) | **$29 / mo** (Core tier; 100k units/mo included) | **50,000 usage units / mo** (2 seats, 30-day retention) | Leading open-core LLM/agent analytics product with session replays, prompt management, and automated evaluation tools. |
| **[AgentOps](https://www.agentops.ai/)** | **$2.6M Funding** (Pre-seed led by 645 Ventures) | **$40 / mo** (Pro plan) | **10,000 events / mo** (Developer free tier) | Agent analytics and session replay platform with step-by-step agent tracking and native SDKs (CrewAI, AutoGen). |
| **[Helicone](https://www.helicone.ai/)** | **~$1M ARR** (Seed funded, YC W23) | **$79 / mo** (Pro plan) | **10,000 requests / mo** (1 GB storage, 7-day retention) | Open-source LLM & agent proxy providing instant cost, latency, and request caching/analytics with zero code change. |
| **[OpenLIT](https://openlit.io/)** | **Open-Source** (Community project / Cloud in waitlist) | **Free (Self-Hosted)** (Open-source Apache 2.0; Cloud waitlist) | **Unlimited** (Self-hosted open-source core) | OpenTelemetry-native GenAI & agent instrumentation platform emitting standard metrics to Grafana, Jaeger, and ClickHouse. |



## Open-Source GitHub Projects



- **[Langfuse](https://github.com/langfuse/langfuse)**  

  Leading open-source (MIT) LLM/agent platform—traces, sessions, dashboards, prompt analytics, and evals; the strongest self-hosted option for agent analytics.



- **[Arize Phoenix](https://github.com/Arize-ai/phoenix)**  

  Open-source tracing, evaluation, and analytics for LLM and agent workloads—notebook-friendly and production-capable.



- **[OpenLLMetry (Traceloop)](https://github.com/traceloop/openllmetry)**  

  OpenTelemetry instrumentation for GenAI and agents—export standard spans to any analytics backend (Grafana, Jaeger, Datadog, etc.).



- **[Helicone](https://github.com/Helicone/helicone)**  

  Open-source proxy logging with built-in cost, latency, and usage analytics for LLM/agent requests.



- **[Opik (Comet)](https://github.com/comet-ml/opik)**  

  Open evaluation and observability toolkit for tracing agent runs and comparing experiments.



- **[OpenLIT](https://github.com/openlit/openlit)**  

  Open instrumentation and observability layer for LLM and agent stacks, emitting metrics and traces for analytics pipelines.



- **[Evidently](https://github.com/evidentlyai/evidently)**  

  Open monitoring framework adaptable to agent success rates, step metrics, and quality scores over time.



- **[Custom agent analytics notebooks & Grafana dashboards](https://github.com/search?q=agent+analytics+OR+LLM+cost+dashboard+open+source)**  

  Community dashboards and notebooks that aggregate OpenTelemetry or Langfuse data into cost, latency, and success views.



### Additional Strong Open-Source Options



- **Full analytics product**: Langfuse for end-to-end agent session analytics and evals.

- **OTel pipeline**: OpenLLMetry → Prometheus/Grafana or ClickHouse for custom agent KPIs.

- **Proxy analytics**: Helicone for quick cost and latency visibility.

- **Experiment analytics**: Opik and Phoenix for offline/online eval comparison.

- **Composable stacks**: Agent framework + Langfuse/OpenLLMetry + BI or Grafana for executive-ready agent ROI views.

- Commercial platforms still lead in polished agent replay, multi-team workspaces, and managed insight reports.



**Frameworks for building custom systems**:  

**Langfuse** and **Phoenix** are the primary open agent analytics products.  

**OpenLLMetry** and **Helicone** feed traces into existing analytics stacks.  

Commercial platforms (AgentOps, Braintrust, HoneyHive, Humanloop, Keywords AI, LangSmith, etc.) provide specialized agent intelligence and evaluation workflows.  

Many teams self-host Langfuse for core analytics and optionally layer commercial tools for advanced evals or enterprise reporting. Fully open stacks are production-viable with self-hosted storage and dashboards.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Agent analytics data often includes prompts, tool outputs, and user content. Treat it as sensitive: apply retention policies, access controls, and redaction for secrets/PII.

- Open-source tools offer transparency and data residency but require you to operate infrastructure. Commercial platforms shift operational burden to the vendor. Align analytics practices with your security and compliance requirements.



---



**Made for agent builders, AI platform teams, and operators measuring agent performance and cost.**  

Let's expand open AI agent analytics while recognizing the specialized insights and scale that leading commercial platforms deliver.
