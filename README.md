<div align="center">

# Raioshok

### Full-stack engineer · LLMOps specialist · Prompt designer

I build SaaS products, backend systems, and production-minded LLM workflows.

Based in Sao Paulo, Brazil. Open to LLMOps, AI engineering, full-stack, and backend roles.

[![Portfolio](https://img.shields.io/badge/Explore_my_work-111827?style=for-the-badge&logo=vercel&logoColor=white)](https://raioshok.github.io/portfolio-next/)
[![NowHost](https://img.shields.io/badge/NowHost-Live-B6FF52?style=for-the-badge&logoColor=111827)](https://nowhost.net/)
[![Email](https://img.shields.io/badge/Email_me-B6FF52?style=for-the-badge&logo=gmail&logoColor=111827)](mailto:raioshok@gmail.com)

</div>

## A little about me

I was coding software by hand before LLMs became part of my workflow. That foundation still matters to me: I can read the code, reason about the system, debug it, and make engineering decisions without treating AI output as a black box.

Today I work as an **LLMOps expert, prompt designer, and LLM engineer**, while staying hands-on as a full-stack developer. I design prompts as versioned system components, connect models to tools and data, evaluate outputs, and think about reliability, latency, cost, observability, and failure handling.

GitHub is only a selected view of my work. Some of my larger and commercial projects are published elsewhere or remain private, while the public repositories here provide code that anyone can inspect. Across that work I have built APIs, authentication, tenant isolation, permissions, billing, migrations, tests, deployment workflows, and documented architecture decisions.

## LLMOps and prompt engineering

<p>
  <img alt="LLMOps" src="https://img.shields.io/badge/LLMOps-B6FF52?style=flat-square&logoColor=111827">
  <img alt="Prompt engineering" src="https://img.shields.io/badge/Prompt_engineering-111827?style=flat-square&logoColor=white">
  <img alt="LLM evaluation" src="https://img.shields.io/badge/LLM_evaluation-111827?style=flat-square&logoColor=white">
  <img alt="RAG" src="https://img.shields.io/badge/RAG-111827?style=flat-square&logoColor=white">
  <img alt="AI agents" src="https://img.shields.io/badge/AI_agents-111827?style=flat-square&logoColor=white">
</p>

My LLM work focuses on:

- Designing clear system prompts, reusable prompt templates, and structured outputs.
- Building retrieval, tool-calling, and agent workflows around real product requirements.
- Creating evaluation cases instead of judging model quality by a few good examples.
- Tracking model behavior, token usage, latency, cost, and production failures.
- Keeping deterministic application logic outside the model whenever normal code is the safer choice.
- Reviewing AI-generated code with the same standards I apply to code written by hand.

## Published product

### [NowHost](https://nowhost.net/) &nbsp; ![Live](https://img.shields.io/badge/status-live-B6FF52?style=flat-square&labelColor=111827)

One of the products I have already published is **NowHost**, a live hosting platform for Discord and Telegram bots, with game-server hosting available on the same platform.

It turns a Git repository into a running bot service. The product covers automated builds and redeployment, isolated runtimes, encrypted environment variables, live logs, health checks, automatic crash recovery, templates, subscriptions, and support workflows. This is the kind of project that represents my work beyond the repositories visible on GitHub: a complete product with infrastructure, operational concerns, and a public customer experience.

**[Visit nowhost.net](https://nowhost.net/)**

## Selected public engineering work

### [Statusplane](https://github.com/Raioshok/statusplane)

Statusplane is one of the projects I keep public so other engineers can review how I structure a complete SaaS system. It's a multi-tenant application for monitoring services, handling incidents, and publishing customer-facing status pages.

[![Statusplane dashboard](https://raw.githubusercontent.com/Raioshok/statusplane/main/docs/dashboard.png)](https://github.com/Raioshok/statusplane)

I built the full flow with **Next.js, TypeScript, PostgreSQL, Drizzle, Better Auth, and Stripe**. It includes team roles, API keys, plan limits, audit logs, signed webhooks, database migrations, SSRF-resistant monitor checks, Docker, unit tests, and Playwright tests.

[Read the code](https://github.com/Raioshok/statusplane) · [Architecture notes](https://github.com/Raioshok/statusplane/blob/main/docs/ARCHITECTURE.md) · [API documentation](https://github.com/Raioshok/statusplane/blob/main/docs/API.md)

## More selected public projects

| Project | What I focused on | Status |
| :--- | :--- | :--- |
| **[SaaS Control Plane](https://github.com/Raioshok/saas-control-plane)** | Tenant lifecycle, plan limits, usage metering, API keys, and audit events in TypeScript | Complete and runnable |
| **[RiskLens](https://github.com/Raioshok/risklens-python)** | Explainable customer-risk scoring through FastAPI, batch, and CSV workflows | Complete and runnable |
| **[Inventory Service](https://github.com/Raioshok/inventory-java)** | Spring Boot reservation workflows, transaction boundaries, and oversell prevention | Complete and runnable |
| **[ShipWatch](https://github.com/Raioshok/shipwatch-go)** | Concurrent endpoint checks, bounded history, and incident reporting in Go | Complete and runnable |
| **[OpsDesk](https://github.com/Raioshok/opsdesk-ts)** | A support queue API with transparent SLA priority scoring and metrics | Complete and runnable |

These repositories are code samples, not a ranking or complete list of my projects. I also have published and private work outside GitHub, plus new SaaS and LLM-based products in active design and implementation. I make a repository public when the core workflow, documentation, and review path are ready.

## My everyday stack

<p>
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-111827?style=flat-square&logo=typescript&logoColor=3178C6">
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-111827?style=flat-square&logo=nextdotjs&logoColor=white">
  <img alt="React" src="https://img.shields.io/badge/React-111827?style=flat-square&logo=react&logoColor=61DAFB">
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-111827?style=flat-square&logo=nodedotjs&logoColor=5FA04E">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-111827?style=flat-square&logo=postgresql&logoColor=4169E1">
  <img alt="Python" src="https://img.shields.io/badge/Python-111827?style=flat-square&logo=python&logoColor=3776AB">
  <img alt="Java" src="https://img.shields.io/badge/Java-111827?style=flat-square&logo=openjdk&logoColor=ED8B00">
  <img alt="Go" src="https://img.shields.io/badge/Go-111827?style=flat-square&logo=go&logoColor=00ADD8">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-111827?style=flat-square&logo=docker&logoColor=2496ED">
</p>

## How I code

- I keep business rules separate from routes and framework code.
- I think about permissions, validation, and failure cases while building the feature.
- I test the transitions that can actually break the product.
- I document the tradeoffs I made and what I would change for production.
- I try to leave the repository easier to understand than I found it.

## Languages

- **Portuguese:** fluent
- **English:** fluent
- **Spanish:** fluent

---

<div align="center">

I'm looking for a team where I can combine LLMOps expertise with real software engineering, keep building useful products, and take ownership of the code and AI systems I ship.

**[raioshok@gmail.com](mailto:raioshok@gmail.com)**

</div>
