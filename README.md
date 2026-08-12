# Hi, I'm Raioshok

I am a full-stack developer in Sao Paulo, Brazil. I build SaaS products from the interface down to the database: multi-tenant applications, business APIs, data workflows, billing integrations, and the tooling teams need to operate them.

I enjoy the point where product thinking meets engineering. Give me a business rule and I will work through the data model, authorization boundary, API, user flow, failure cases, and tests needed to make it dependable.

[Explore my portfolio](https://github.com/Raioshok/portfolio-next) | [Email me](mailto:raioshok@gmail.com)

## What I'm Building

### [Statusplane](https://github.com/Raioshok/statusplane)

My flagship project is a full-stack engineering operations SaaS for uptime monitoring, incident response, and public status communication.

[![Statusplane dashboard](https://raw.githubusercontent.com/Raioshok/statusplane/main/docs/dashboard.png)](https://github.com/Raioshok/statusplane)

I built it with **Next.js, TypeScript, PostgreSQL, Drizzle, Better Auth, and Stripe**. The implementation includes organization-scoped RBAC, API keys, plan limits, signed webhooks, SSRF-resistant monitor checks, audit history, database migrations, Docker, unit tests, and browser tests.

## Projects Worth Reviewing

| Project | What I coded | Stack |
| --- | --- | --- |
| [Statusplane](https://github.com/Raioshok/statusplane) | A complete multi-tenant SaaS with monitoring, incidents, teams, billing, and status pages | Next.js, PostgreSQL, Stripe |
| [SaaS Control Plane](https://github.com/Raioshok/saas-control-plane) | Tenant lifecycle, entitlements, metering, API key hashing, and audit events | TypeScript, Express, Zod |
| [RiskLens](https://github.com/Raioshok/risklens-python) | Explainable customer-risk scoring shared by API, batch, and CSV workflows | Python, FastAPI, SQLite |
| [Inventory Service](https://github.com/Raioshok/inventory-java) | Transaction-focused reservation workflows and oversell prevention | Java, Spring Boot, JDBC |
| [ShipWatch](https://github.com/Raioshok/shipwatch-go) | Concurrent endpoint checks, bounded history, and incident reporting | Go, HTTP, Docker |
| [OpsDesk](https://github.com/Raioshok/opsdesk-ts) | A support queue API with transparent SLA priority scoring | TypeScript, Express, Vitest |

## How I Work

- I keep business rules separate from HTTP handlers and framework code.
- I treat authorization, validation, retries, and failure states as product behavior.
- I use tests to protect important transitions, not just increase a coverage number.
- I document tradeoffs and limitations instead of pretending a portfolio project runs at enterprise scale.
- I make repositories straightforward to run, inspect, and review.

## Tools I Use

**Product and frontend:** TypeScript, Next.js, React, Three.js, accessible CSS<br>
**Backend:** Node.js, FastAPI, Spring Boot, Go HTTP<br>
**Data and integrations:** PostgreSQL, Drizzle, SQLite, JDBC, Stripe, Better Auth<br>
**Quality and delivery:** Vitest, Playwright, Pytest, JUnit, Docker, GitHub Actions

## Let's Talk

I am open to full-stack and backend opportunities where I can help ship useful SaaS products and take responsibility for the quality of the systems behind them.

You can reach me at **[raioshok@gmail.com](mailto:raioshok@gmail.com)**.
