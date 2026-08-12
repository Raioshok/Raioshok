# Raio

Full-stack backend developer focused on SaaS APIs, control planes, data workflows, reliability tooling, tests, Docker, and CI.

## Core Stack

| Area | Tools |
|------|-------|
| Languages | TypeScript, JavaScript, Python, Java, Go, SQL |
| Frontend | Next.js, React, responsive CSS |
| Backend | Node.js, Express, FastAPI, Spring Boot, Go HTTP services |
| Data | SQLite, H2, JSON persistence, CSV ingestion |
| Quality | Vitest, Pytest, Ruff, JUnit, Go test, type checks |
| Delivery | Docker, GitHub Actions, documented local workflows |
| SaaS | Tenants, subscriptions, usage metering, API keys, audit logs |

## Portfolio Projects

| Project | Stack | Summary |
|---------|-------|---------|
| `saas-control-plane` | TypeScript, Express, Zod | SaaS backend foundation with tenants, plans, subscriptions, usage metering, API keys, and audit logs |
| `opsdesk-ts` | TypeScript, Express, Zod | Support-operations API with accounts, tickets, comments, SLA scoring, persistence, and metrics |
| `risklens-python` | Python, FastAPI, SQLite | Customer-risk analytics API with explainable scoring, batch ingestion, CSV import, and portfolio metrics |
| `inventory-java` | Java, Spring Boot, H2 | Enterprise inventory REST API with validation, stock workflows, actuator health, and integration tests |
| `shipwatch-go` | Go, HTTP, concurrency | Reliability monitor with config loading, concurrent endpoint checks, persisted history, and incidents |
| `portfolio-next` | Next.js, React, TypeScript | Frontend dashboard presenting the project set, stack matrix, and verification commands |

## Engineering Focus

- Domain logic that maps to real business workflows
- API boundaries with validation and predictable errors
- Tenant, plan, usage, and audit concepts for SaaS products
- Tests around behavior that can break real users
- Apps that run locally without private services or secrets

## Review Path

Start with `saas-control-plane` for SaaS fundamentals, then inspect `inventory-java` for enterprise REST structure, `risklens-python` for analytics workflows, `shipwatch-go` for reliability tooling, and `opsdesk-ts` for TypeScript API design.
