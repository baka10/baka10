# Bartosz Lipiński

**Senior Python Backend Engineer · hands-on Solution Architect · Kraków, Poland (remote, EU time zones)**

I design, build and operate high-throughput, event-driven backend systems: Kafka, FastAPI, asyncio, Kubernetes, Terraform, Azure/GCP. 9+ years in Python, currently architecting event-driven services for a capital-markets data platform and still shipping production code every week.

## How I work

- **Coding agents daily since mid-2025** (Claude Code, GitHub Copilot agent mode) across the whole lifecycle: exploration, implementation, tests, review.
- **I own the result, including code written by agents**: spec-driven tickets with non-functional requirements → agent PR → automated tests and typing → human-in-the-loop review.
- **Agent harness**: repo-level `CLAUDE.md`, custom skills and hooks, MCP integrations that expose internal tooling as agent tools.
- **Designed for failure**: idempotency, retries, dead-letter queues, observability (Prometheus, Grafana, OpenTelemetry).

## Stack

`Python 3.11–3.13` · `FastAPI` · `asyncio` · `Pydantic` · `Apache Kafka` · `Celery` · `PostgreSQL` · `Redis` · `Kubernetes` · `Docker` · `Terraform` · `GitHub Actions` · `Azure` · `GCP` · `AWS` · `Claude Code` · `MCP`

## Repositories

- [`forno`](https://github.com/baka10/forno): an event-driven pizzeria operations backend (FastAPI, PostgreSQL, Redpanda, transactional outbox, SSE, Prometheus/Grafana SLOs with burn-rate alerts) plus a deterministic simulator that drives it through the public API and asserts system invariants in CI. A complete, runnable example of how I design, test and operate a production-shaped system — `make demo` runs a full dinner service in a minute.
- [`dev-bootstrap`](https://github.com/baka10/dev-bootstrap): one-command Linux/macOS dev environment with Claude Code and Copilot hooks and skills.
- Coming next: an eval harness for an LLM-backed FastAPI service (golden set, binary checks, LLM-as-judge, Langfuse tracing, CI) and a stateless MCP server with a CLI twin.

## Links

- LinkedIn: [linkedin.com/in/bartoszlipinski92](https://www.linkedin.com/in/bartoszlipinski92)
- Open to: Senior / Lead Backend, Tech Lead and backend-for-AI-products roles (B2B, remote-first)
