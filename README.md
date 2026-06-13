# Opik (opik)

Opik is an open-source LLM evaluation, testing, and tracing platform developed by Comet ML that enables developers to debug, evaluate, and monitor LLM applications, RAG systems, and agentic workflows. The platform provides a REST API for logging traces and spans, running automated evaluations with LLM-as-a-judge metrics, managing datasets and experiments, and tracking production performance. Opik supports over 40 framework integrations including LangChain, LlamaIndex, and OpenAI, and is available as a self-hosted open-source deployment (Apache 2.0) or as a managed cloud service on Comet's platform.

APIs.json: https://raw.githubusercontent.com/api-evangelist/opik/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=opik-api-evangelist&utm_content=repo

## Tags

- LLM
- Evaluation
- Observability
- Tracing
- Open Source
- LLMOps
- RAG
- AI
- Machine Learning
- Monitoring

## APIs

### Opik REST API

The Opik REST API provides programmatic access to all platform capabilities including logging traces and spans from LLM applications, managing datasets and experiment items, running evaluations, storing feedback scores, and accessing project data.

- **Base URL:** https://www.comet.com/opik/api/v1
- **Documentation:** https://www.comet.com/docs/opik/reference/rest-api/overview

**Authentication:**
- Opik Cloud: `Comet-Workspace` header (workspace name) + `authorization` header (API key, no Bearer prefix)
- Open-Source/Self-Hosted: No authentication required

## Plans / Rate Limits / FinOps

| Resource | Location |
|---|---|
| Plans & Pricing | [plans/opik-plans-pricing.yml](plans/opik-plans-pricing.yml) |
| Rate Limits | [rate-limits/opik-rate-limits.yml](rate-limits/opik-rate-limits.yml) |
| FinOps | [finops/opik-finops.yml](finops/opik-finops.yml) |

**Pricing summary:**
- Open Source: Free (self-hosted, Apache 2.0)
- Free Cloud: $0/month — 10 members, 25k spans/month, 60-day retention
- Pro Cloud: $19/month — 50 members, 100k spans/month, customizable limits
- Enterprise: Custom pricing — unlimited members, SSO, SOC 2, HIPAA, GDPR

**Rate limits (Opik Cloud):**
- Global: 2,000 requests/minute per user (+ 100 burst)
- Data ingestion: 10,000 events/minute per user
- Get Span by ID: 250 requests/minute per user
- HTTP 429 returned when limits exceeded

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## Common

| Type | URL |
|---|---|
| Website | https://www.comet.com/site/products/opik/ |
| Documentation | https://www.comet.com/docs/opik/ |
| GitHub Org | https://github.com/comet-ml |
| GitHub Repository | https://github.com/comet-ml/opik |
| LinkedIn | https://www.linkedin.com/company/comet-ml |
| Blog | https://www.comet.com/site/blog/ |
| Pricing | https://www.comet.com/site/pricing/ |
| Status Page | https://status.comet.com/ |
| X (Twitter) | https://x.com/cometml |
| Changelog | https://www.comet.com/docs/opik/changelog |
| SDK Documentation | https://www.comet.com/docs/opik/python-sdk-reference/ |
| Slack Community | https://chat.comet.com |

## Maintainers

- **Kin Lane** — kin@apievangelist.com
