### Hi, I'm Virendra 👋

Backend engineer (~7 years) building **payments, ledgers and event-driven systems** that move real money and have to be correct under retries, partial failures and concurrency.

**Stack:** Kotlin · Java · Spring Boot · Kafka · PostgreSQL · MongoDB · DynamoDB · Redis · AWS · Docker · Terraform

---

#### What I've built

- **Syfe (fintech)**: designed and built the payments microservice from scratch (HLD + LLD), now the platform other services use for payment use cases and handling 100k+ transactions/month. e-GIRO / HSBC in-app funding over mTLS, wallet ledger and reconciliation.
- **Tata 1mg**: replaced a shared, unreliable notification platform with an in-house event-driven one serving 10+ services; led a monolith-to-microservices migration.
- **Amazon**: built a domain microservice that took ownership of a database shared by several monoliths, removing a scaling bottleneck; built data-replication and load/shadow-testing tools.

#### Featured projects

| Project | What it shows |
|---|---|
| [**wallet-ledger-service**](https://github.com/viren97/wallet-ledger-service) | Kotlin / Spring Boot wallet service: double-entry ledger, state-machine lifecycle, transactional outbox, idempotency keys, reconciliation, concurrency-tested. Docker Compose (Postgres, Kafka, Redis) and Helm. |
| [**terraform-ecs-fargate-bluegreen**](https://github.com/viren97/terraform-ecs-fargate-bluegreen) | Terraform modules for ECS Fargate behind an ALB with a CodePipeline → CodeBuild → CodeDeploy blue/green pipeline. |

#### Currently

Open to **remote senior backend roles**, especially in fintech and payments.

[LinkedIn](https://www.linkedin.com/in/virennpandey) · virennpandey@gmail.com
