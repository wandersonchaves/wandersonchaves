# Wanderson Chaves

**Senior Backend Engineer** · Node.js · TypeScript · Python · AWS · Payments (Pix)

Teresina, Brazil. Open to remote roles (contractor or EOR), and to hybrid or on-site roles in Curitiba, Brasília or Belo Horizonte.

[LinkedIn](https://linkedin.com/in/wandersonchaves) · [Email](mailto:wandersonchavesbr14@gmail.com)

## About

Backend engineer with 5+ years building production systems in TypeScript/Node.js and Python/Django. Most of my recent work is payments: Pix, BolePix and boleto services, split payments, idempotent webhooks and reconciliation.

I use AI coding tools every day, and I let tests and code review decide what ships.

## Experience

- **Independent projects (Feb 2026 to now):** I build and run software for real users. A Pix payments platform for a church youth camp (102 participants, R$ 6.5k received by Oct 2026) and a multi-tenant member-management platform for a church with 700+ members and 12+ ministries.
- **SimWorx, client Petrobras (Jul 2023 to Aug 2026):** upgraded 3 of 4 legacy Django applications to Python 3.12 and Django 4.2. Cut a Jenkins deploy from about 22 to about 10 minutes (~55%) by moving large media files to Amazon S3. Contributed to moving the well-calculation queue from RabbitMQ to Amazon SQS. In Java/Spring Boot, added server-side pagination driven by user parameters, enabling optimized queries across 1,000+ wells. Promoted from level I to level III.
- **General Shopping (Dec 2024 to Jun 2025, contract):** Pix, BolePix and boleto payment microservices with NestJS, Prisma and PostgreSQL on the Celcoin APIs. Automated split payments, and webhook ingestion with Redis idempotency so a retried confirmation is not processed twice.
- **Hero99 (Aug 2022 to Mar 2023, contract):** multi-tenant NestJS and MongoDB backend for customer-facing chatbots on Google Cloud, with Dialogflow, React Flow and Cloud Functions.

## Projects

| Project | What it shows |
| --- | --- |
| [power-camp-registrations](https://github.com/wandersonchaves/power-camp-registrations) | Event sign-up and payments, in production since Feb 2026: Efí Pix and Pix Automático over mTLS, webhooks stored before processing, reconciliation against the Efí API, an installments ledger. Next.js, Prisma, PostgreSQL, Jest, Playwright, GitHub Actions. |
| [auth-edge](https://github.com/wandersonchaves/auth-edge) | Serverless authentication on AWS: Cognito, a Lambda authorizer with JWKS caching and group-based access, API Gateway, DynamoDB audit log, Terraform. Tested with Vitest. |
| Next Church (private) | Multi-tenant member-management platform in production since Apr 2026. WhatsApp messages through a rate-limited queue. Next.js, PostgreSQL, Clerk. |

## Stack

| | |
| --- | --- |
| **Backend** | TypeScript, Node.js, NestJS, Python, Django, Celery, Java/Spring Boot, REST, GraphQL |
| **Data and messaging** | PostgreSQL, Redis, MongoDB, Prisma, Amazon SQS, RabbitMQ |
| **Cloud and CI/CD** | AWS (ECS, ECR, S3, RDS, CloudWatch, Lambda, Cognito), Terraform, Docker, Jenkins, GitHub Actions |
| **Testing** | Jest, Playwright, Vitest |

## Languages

Portuguese (native). English: upper-intermediate (B2).
