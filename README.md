## Lucas Benevinuto

Data platform engineer and tech lead. I build the plumbing that carries data
from source systems into governed, queryable places — and the access layer that
decides who gets to see what.

Most of what I work on lives in private repositories, so here is the shape of it
rather than the code:

**Data platform.** Airflow DAG factories driven by declarative manifests,
change-data-capture envelopes and generic MERGE into BigQuery. Kafka pipelines
for social and news ingestion. Postgres and PL/pgSQL modelling for multi-tenant
systems, including a full V1 to V2 migration.

**Governed access.** MCP servers that let AI agents query a warehouse through
layered SQL guards and per-role service accounts, with RBAC resolved against
Keycloak/OIDC — so people and agents run under one identity model instead of two.

**Backend.** Python and FastAPI, organised around repository and service layers,
Alembic migrations and Docker Compose deployments. TypeScript and Next.js when a
project needs a face.

### Public work

- **[gitbook-mcp](https://github.com/lucasbenevinuto/gitbook-mcp)** — MCP server
  covering the GitBook API in 39 tools: spaces, pages, change requests, reviews,
  comments and Git Sync, usable from any MCP-compatible agent.
- **[base-Fastapi](https://github.com/lucasbenevinuto/base-Fastapi)** — the
  foundation I start FastAPI services from: repository/service pattern,
  structured JSON logging with request tracking, health checks and metrics,
  security middleware and global exception handling.
- **[pneumonia-prediction](https://github.com/lucasbenevinuto/pneumonia-prediction)**
  — chest X-ray classification comparing a custom CNN (83%) against VGG16
  transfer learning (98%).
- **[Risk-Analysis](https://github.com/lucasbenevinuto/Risk-Analysis)** — bagged
  decision trees for loan risk scoring and approval likelihood.

### Elsewhere

[LinkedIn](https://www.linkedin.com/in/lucasbenevinutopereira/)
