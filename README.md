# Hi, I'm Sachin Soni

Senior Software Engineer at [Shiprocket](https://www.shiprocket.in), where I lead a 4-engineer backend pod that owns the post-order lifecycle for one of India's largest e-commerce logistics platforms. I write Go for a living: event-driven services on Kafka, Elasticsearch/CDC pipelines, Redis/Valkey, MySQL at high volume.

- 🛠 **Day to day:** Go · Kafka · Elasticsearch · Redis/Valkey · MySQL · Gin · Docker · Kibana
- 🤖 **How I work now:** Claude Code and MCP tooling are part of my daily loop — design, review, delivery
- 🌱 **Currently building:** hardening the projects below (CI, benchmarks, honest READMEs) and an MCP server in Go
- 📍 Gurugram, India · [LinkedIn](https://linkedin.com/in/sachinsoni722) · sachinsoni722@gmail.com

## Projects

| Project | What it is | Stack |
|---|---|---|
| [rate-limiter-go](https://github.com/striver-21/rate-limiter-go) | Distributed sliding-window rate limiter with Gin middleware · [live demo](http://137.23.51.193/ratelimiter/health) | Go, Redis, Lua |
| [event-bus-go](https://github.com/striver-21/event-bus-go) | Async event bus: consumer groups, retries with backoff, dead-letter queue, idempotency | Go, Kafka, Redis |
| [trading-rules-engine](https://github.com/striver-21/trading-rules-engine) | Event-driven rules engine with worker-pool concurrency, backtesting and Prometheus metrics | Go, Prometheus |
| [portfolio-manager](https://github.com/striver-21/portfolio-manager) | REST API for investment portfolios with JWT auth and analytics | Go, Gin, PostgreSQL |

The demo above runs on a self-managed Ubuntu box (Oracle Cloud, Docker + Caddy) — infra in [pet-server](https://github.com/striver-21/pet-server) (private).

## At work, in one breath

Rebuilt Shiprocket's WhatsApp/SMS/Email communication services from a PHP monolith into Go microservices handling 3–4M messages a day · built the Go CDC consumers that stream every order into Elasticsearch in near real time and power the All Orders listing, reports and bulk actions · designed the NDR recovery platform on Kafka + Redis · moved manifests to CDN with PII made private.

<sub>Older repos here are college-era coursework (2020–2022), kept for history.</sub>
