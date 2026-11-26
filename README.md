## Virendra Pandey
**Senior Backend Engineer · Payments, ledgers & event-driven systems**

I build systems that move real money and stay correct under retries, partial failures and concurrency.

Ex-Amazon, Syfe, Tata 1mg · Kotlin/Java · Spring Boot · Kafka · Postgres · AWS

---

### Impact
- **Syfe (fintech):** designed and built the payments platform from scratch (HLD → LLD → prod). Other teams' services use it for every payment flow, and it handles **100k+ transactions/month**: e-GIRO/HSBC in-app funding over mTLS, wallet ledger, automated reconciliation. Led delivery across backend, frontend and QA.
- **Tata 1mg:** replaced an unreliable shared notification platform with an in-house event-driven one serving **10+ services**; led the monolith → microservices migration.
- **Amazon:** split a database shared by several monoliths into its own domain service, removing a scaling bottleneck; built shadow/load-testing and data-replication tooling (saved ~1 week per test-env setup).
- **Team:** hired and mentored interns and SDE1s (2 of 3 interns converted full-time); run design reviews; interview for system design, LLD and DSA.

### Featured work
| Repo | Problem it solves | Key decisions |
|---|---|---|
| [wallet-ledger-service](https://github.com/viren97/wallet-ledger-service) | Moving money without double-spends or lost updates | Double-entry ledger, state machine, idempotency keys, transactional outbox, reconciliation, concurrency tests |
| [external-api-client](https://github.com/viren97/external-api-client) | Calling flaky bank/partner APIs safely | Spring Boot starter: retries + circuit breaker, Redis rate limiting, mTLS, outbox, signed webhooks |
| [goal-coach-service](https://github.com/viren97/goal-coach-service) | Putting an LLM in a real product loop | AI-planned tasks, adaptive push nudges via Kafka + FCM, Claude integration |
| [terraform-aws-ecs-platform](https://github.com/viren97/terraform-aws-ecs-platform) | Running and releasing these services safely | Terraform platform: per-service Postgres, MSK with IAM per topic, Redis, S3, canary blue/green with alarm-based rollback |

### How I build
- Correctness first: idempotency, ledgers as source of truth, reconciliation as a feature
- Async by default, but with an outbox, not dual writes
- Observable from day one: logs, metrics and alerts ship with the service
- Design docs and trade-offs before code

### Let's talk
Open to **remote senior backend roles**, building reliable, high-scale systems that teams can depend on.
[LinkedIn](https://www.linkedin.com/in/virennpandey) · virennpandey@gmail.com
