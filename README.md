# Wanderson Chaves

**Backend Engineer** · Node.js · TypeScript · Python · AWS · Payments (Pix)

Teresina, Brazil. Open to on-site or hybrid roles (Curitiba, Brasília, Belo Horizonte) and to relocation. Remote roles also welcome. Brazilian citizen; international roles would need visa sponsorship.

[LinkedIn](https://linkedin.com/in/wandersonchaves) · [Email](mailto:wandersonchavesbr14@gmail.com)

## About

Backend engineer with 5+ years building and maintaining production services in TypeScript/Node.js (NestJS) and Python/Django: payment APIs, legacy modernization and AWS deployments.

## Work highlights

- **Legacy modernization (consultancy, large energy-sector client, 2023 to 2026):** upgraded 3 of 4 legacy Python/Django applications to Python 3.12 and Django 4.2.
- **Deploy time:** cut a Jenkins deploy from about 22 to about 10 minutes (~55%) by moving large media files to Amazon S3.
- **Messaging:** moved the queue that runs well calculations from RabbitMQ to Amazon SQS.
- **Pagination (Java/Spring Boot):** added server-side pagination driven by user parameters, enabling optimized queries across 1,000+ wells.
- **Payments (General Shopping):** Pix, BolePix and boleto payment microservices with NestJS, Prisma and PostgreSQL, using Celcoin APIs. Automated split payments, and webhook ingestion with Redis idempotency guards so retried confirmations are not processed twice.
- **Chatbots (Hero99):** Node.js and MongoDB backend for chatbots built on Google Dialogflow, with React Flow and Cloud Functions on GCP.

## Projects

| Project | What it shows |
| --- | --- |
| [power-camp-registrations](https://github.com/wandersonchaves/power-camp-registrations) | Event sign-up and payments, in production since Feb 2026: Efí Pix and Pix Automático over mTLS, webhooks stored before processing, reconciliation jobs, an installments ledger. 102 confirmed participants and R$ 6.5k in Pix as of Oct 2026. Next.js, Prisma, PostgreSQL, Jest, Playwright. |
| [auth-edge](https://github.com/wandersonchaves/auth-edge) | Serverless authentication on AWS (personal project): Cognito, Lambda authorizer with JWKS caching and group-based access, API Gateway, DynamoDB audit log, Terraform. Tested with Vitest. Not currently deployed. |
| [enterprise-saas-starter-kit](https://github.com/wandersonchaves/enterprise-saas-starter-kit) | A multi-tenant SaaS template (NestJS, Next.js, Prisma, BullMQ, Clerk). The README lists what is implemented and what is only scaffolding. |

## Stack

| | |
| --- | --- |
| **Backend** | TypeScript, Node.js, NestJS, Python, Django, Celery, REST, GraphQL, Java/Spring Boot (production fixes) |
| **Data** | PostgreSQL, Redis, MongoDB, Prisma |
| **Messaging** | Amazon SQS, RabbitMQ, BullMQ |
| **Cloud and CI/CD** | AWS (ECS, ECR, S3, SQS, RDS, CloudWatch), Docker, Jenkins, GitHub Actions |
| **Personal projects only** | Terraform, Lambda, API Gateway, Cognito, DynamoDB |
| **Practices** | Clean Architecture and SOLID where they pay off, code review, production troubleshooting |

## Languages

Portuguese (native). English: strong technical reading and writing, speaking in progress.
