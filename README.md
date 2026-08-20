# Vladimir Bragin

Full-Stack & Automation Engineer building web products, REST APIs, ETL pipelines, and human-reviewed AI automation.

Russia · Remote · Available for full-time remote work.

Owner-verified operational results: workflows supporting 50 stores and 30,000+ SKUs reduced daily reporting and analysis from several hours to 20–30 minutes.

## Core stack

- Frontend: Next.js, React, TypeScript, Vite
- Backend: Python, FastAPI, SQLAlchemy, Pydantic, Node.js, Fastify, NestJS
- Data and async work: PostgreSQL, Redis, Prisma, Celery, ETL, background workers
- Quality and operations: pytest, Vitest, Playwright, Docker, GitHub Actions, Nginx, Linux, Cloudflare
- AI integrations: LLM scoring and draft generation with explicit human review

## Selected engineering work

### [Marketplace Analytics Platform](https://github.com/Arbitr3103/marketplace-analytics-platform)

Sanitized, runnable portfolio edition of a production-used analytics and automation platform.

[![Marketplace Analytics Platform dashboard with deterministic synthetic data](https://raw.githubusercontent.com/Arbitr3103/marketplace-analytics-platform/main/output/playwright/marketplace-dashboard.png)](https://github.com/Arbitr3103/marketplace-analytics-platform)

- **My role:** full-stack architecture and implementation across FastAPI, Next.js, data contracts, tests, Docker, and CI
- **Key decisions:** deterministic synthetic demo data, protocol-based infrastructure boundaries, and idempotent sync requests
- **Current status:** public portfolio edition; latest backend and frontend CI pass on `main`
- **Boundary:** provider credentials, customer data, production infrastructure, and private ingestion workers are intentionally excluded

### [E-Chain](https://echain.world)

Production logistics SaaS/PWA for trip workflows, electronic documents, PDF/XML generation, QR verification, and operational automation.

- **My role:** full-stack product engineering, APIs, workflow automation, reliability, and release verification
- **Current status:** live product; operational source and infrastructure remain private

### [LAKO Services](https://lako.services)

Telegram and web automation for logistics and small-business workflows, including document generation, service catalogs, and booking flows.

- **My role:** product engineering and automation across customer-facing flows and operational tooling
- **Current status:** live product; the public code repository is not presented as a primary portfolio pin until its documentation and security gates are complete

## Private production work

### AI Project Monitor

A daily opportunity-monitoring workflow with rule-based and LLM scoring, deduplication, draft generation, and explicit human review before any external action.

- FastAPI, async SQLAlchemy, PostgreSQL, Redis queues, React, JWT, and Telegram
- Source remains private because it contains provider-specific integration and operational configuration

## Engineering approach

- Start with explicit requirements, system boundaries, and failure modes
- Keep APIs, data contracts, migrations, and background work testable
- Use AI for bounded research and implementation support, with human ownership of decisions and output
- Treat security, secret handling, rollback, CI, and production verification as delivery requirements
- Separate public portfolio evidence from private production claims

## Contact

- Email: [bragin.arbitr@gmail.com](mailto:bragin.arbitr@gmail.com)
- Telegram: [@Bragin_Arbitr](https://t.me/Bragin_Arbitr)
- LinkedIn: [linkedin.com/in/vladimir-bragin-4278a3259](https://www.linkedin.com/in/vladimir-bragin-4278a3259/)
- GitHub: [github.com/Arbitr3103](https://github.com/Arbitr3103)
- Product: [echain.world](https://echain.world)
