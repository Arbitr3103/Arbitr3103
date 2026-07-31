# Vladimir Bragin

Full-Stack Developer building production web products, REST APIs, data pipelines, and practical AI-assisted workflows.

Currently based in Russia and relocating to Novi Sad, Serbia in September 2026. Available for full-time remote work.

## Core stack

- Frontend: Next.js, React, TypeScript, Vite
- Backend: Python, FastAPI, SQLAlchemy, Pydantic, Node.js, Fastify, NestJS
- Data and async work: PostgreSQL, Redis, Prisma, Celery, ETL, background workers
- Quality and operations: pytest, Vitest, Playwright, Docker, GitHub Actions, Nginx, Linux, Cloudflare
- AI integrations: LLM scoring and draft generation with explicit human review

## Selected work

### [Marketplace Analytics Platform](https://github.com/Arbitr3103/marketplace-analytics-platform)

Portfolio edition of a production-used analytics and automation platform for marketplace operations.

- Next.js and React frontend with a Python/FastAPI backend
- FastAPI service layer with async SQLAlchemy, PostgreSQL, Redis cache, and an idempotent job-queue boundary
- Workflows supporting 50 stores and more than 30,000 SKUs
- Nightly dashboards reduced daily reporting and analysis from several hours to 20-30 minutes
- Public code uses synthetic data and excludes private provider-specific ingestion workers

### AI Project Monitor (private production project)

A daily project-monitoring workflow that keeps AI output behind explicit human review.

- FastAPI, async SQLAlchemy, PostgreSQL, Redis queues, JWT, React, and Telegram
- Rule-based and LLM scoring, deduplication, and draft generation
- Surfaces up to five relevant opportunities per day
- Source remains private because the repository contains provider-specific integration code and operational configuration

### [E-Chain](https://echain.world)

Logistics SaaS/PWA for trip workflows, POD, electronic documents, PDF/XML generation, QR verification, and compliance-oriented operations.

### [LAKO Services](https://github.com/Arbitr3103/lako-services)

Web products and automation for small businesses and transport teams, including e-invoice, booking, and document workflows.

## Engineering approach

- Start with explicit requirements, boundaries, and failure modes
- Keep APIs and data contracts testable and observable
- Use AI as an engineering tool, with human ownership of decisions and output
- Treat security, secrets, and production verification as delivery requirements

## Contact

- Email: [bragin.arbitr@gmail.com](mailto:bragin.arbitr@gmail.com)
- Telegram: [@Bragin_Arbitr](https://t.me/Bragin_Arbitr)
- LinkedIn: [linkedin.com/in/vladimir-bragin-4278a3259](https://www.linkedin.com/in/vladimir-bragin-4278a3259/)
- GitHub: [github.com/Arbitr3103](https://github.com/Arbitr3103)
- Product: [echain.world](https://echain.world)
