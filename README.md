# Awesome-AI-Agent-Analytics

# Top AI Agent Analytics Ecosystem

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

- **[AgentOps](https://www.agentops.ai/)**  
  Analytics and observability purpose-built for AI agents—session replay, tool-call tracking, cost attribution, and performance dashboards.

- **[Langfuse (Cloud)](https://langfuse.com/)**  
  LLM and agent engineering platform with rich analytics over traces, sessions, prompts, and evals (open-source core available).

- **[LangSmith](https://www.langchain.com/langsmith)**  
  Observability and analytics tightly integrated with LangChain/LangGraph—trace inspection, datasets, and experiment comparison.

- **[Arize Phoenix / Arize AX](https://arize.com/)**  
  Open Phoenix plus enterprise Arize for tracing, evaluation, and analytics across agents and LLM applications.

- **[Helicone, OpenLIT, Keywords AI](https://www.helicone.ai/)**  
  Proxy and instrumentation platforms that deliver cost, latency, and usage analytics for LLM and agent traffic with minimal integration effort.

- **[Braintrust, HoneyHive, Humanloop](https://www.braintrust.dev/)**  
  Evaluation- and feedback-centric platforms that turn production agent runs into quality metrics, experiments, and continuous improvement loops.

- **[Other commercial agent analytics platforms](https://www.agentops.ai/)**  
  Additional solutions for agent ROI dashboards, multi-agent comparison, and production intelligence.

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
