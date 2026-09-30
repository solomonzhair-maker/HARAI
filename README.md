# HARAI Payment Gateway

A reusable, multi-tenant payment infrastructure platform for HARAI products and future external merchants.

## Vision

HARAI will provide one payment integration for applications such as Shigona, Herupu, and future systems.

```text
Application
    ↓
HARAI Payment Gateway
    ↓
Provider Adapters
    ↓
Mobile Money / Cards / Banks
```

## Initial architecture

- API: NestJS + TypeScript
- Database: PostgreSQL + Prisma
- Cache/queues: Redis
- Web applications: Next.js
- Package management: pnpm workspaces
- CI/CD: GitHub Actions

## Development

Work is developed in feature branches and merged into `main` through pull requests.

> Never commit production secrets. Use environment variables and the provided `.env.example` files.
