# Hi there, I'm Theodros Yimer 👋🏿

**Software Developer & Relentless Learner** — Building domain-driven systems
with TypeScript

I spent 20 years as a musician before becoming a developer. The same drive that
kept me practicing guitar for hours is what pulls me deep into domain-driven
design, event modeling, and architecture patterns.

## What Drives My Work

I'm deeply invested in understanding **why systems should be built a certain
way**, not just how. I spend significant time studying and practicing
domain-driven design, event modeling, and architecture patterns — and I apply
them hands-on in everything I build.

**Principles I practice daily:**

- **Domain-Driven Design** as the foundation — bounded contexts, ubiquitous
  language, strategic decisions documented as ADRs
- **Event Modeling** to make system behavior visible before writing a single
  line of code — decide/evolve functions, event streams, read model projections
- **Hexagonal Architecture** with ports & adapters — domain logic stays pure,
  infrastructure is swappable, use cases testable in milliseconds with
  ultra-light fakes
- **Vertical Slice Architecture** inside bounded contexts — features as
  self-contained slices, not horizontal layers that scatter behavior across the
  codebase
- **CQRS & Event Sourcing** where business complexity demands it — replay value
  as the adoption criterion, not dogma

I learn from and draw heavy inspiration from **Martin Fowler**, **Udi Dahan**,
**Dave Farley**, **Jimmy Bogard**,**James Shore**, **Greg Young**, **Derek
Comartin**, **Robert C. Martin**, **Michael Azerhad**, **Anthony Cyrille**,
**Matteo Collina**, **James Snell**, **Martin Dilger**.

## How I Build

```
Event Model (events, commands, views, given/when/thens)
→ Implementation (DDD, Modular Monolith, Hexagonal Architecture, Vertical Slices, TDD)
→ Refactor → Repeat
```

- **TDD** — every line of production code responds to a failing test
- **Type-driven domain modeling** with TypeScript's type system — discriminated
  unions, ADT state machines, null-free domain layers; **Zod at boundaries
  only**
- **Sociable testing** — acceptance tests at the use case boundary with real
  domain services; ultra-light fakes for infrastructure ports (Azerhad/WealCome
  approach) — deterministic, sub-millisecond test suites
- **Trunk-based continuous delivery** — small commits, commit tests as
  deployment gates, deployment ≠ release

## Active Side Projects

- **better-date** — Composable, Temporal-native date utilities that solve
  problems wrong or impossible to implement with `Date` — business hours, fiscal
  quarters, timezone-aware scheduling, duration balancing, and constraint-based
  time logic
- **gdpr-decision-matrix** — Interactive tool + Claude Code agent for choosing
  GDPR erasure patterns in event-sourced TypeScript apps — weighted scoring
  across 5 patterns, per-module characteristic assessment, conflict detection,
  and ADR export
- **ty CLI** — Custom scaffolding and code generation tool built on a composable
  six-stage idempotent pipeline
- **ArchViz** — Interactive architecture visualization tool evolving toward a
  generator-of-generators pattern

## Agentic Engineering Workflows

This is a major focus area. I design and build **skill systems, knowledge
architectures, and command workflows for AI-assisted development** — making LLM
agents deterministic, consistent, and reproducible instead of chaotic.

What this looks like in practice:

- **Four-tier knowledge architecture** — ADRs → conceptual docs → actionable
  skill playbooks → always-on guardrails — so agents have the right context at
  the right time
- **Skill-based automation** — self-contained, composable skills with structured
  references that agents read before acting, not after guessing
- **Command orchestration over autonomous agents** — deterministic,
  user-controlled, reviewable workflows where the human stays in the loop
- **Evaluation frameworks** — hybrid structural assertions + LLM rubric scoring
  to measure whether agent output actually meets the bar
- **Generator-of-generators** — building tools that produce scaffolding/codegen
  tools, with composable idempotent pipeline stages

I believe the combination of **deep architectural knowledge** and **the ability
to encode it into reliable AI workflows** is what separates developers who ship
lasting systems from those chasing tools.

## Tech Stack

**Language** — TypeScript

**Backend** — Node.js · NestJS · Fastify · PostgreSQL · Drizzle ORM · Emmett ·
BullMQ · Redis · better-auth · Pino · OpenTelemetry · Sentry

**Frontend** — React · Expo · Next.js · Tanstack Start · TanStack Query ·
TanStack DB · Zustand · Tailwind CSS v4 · UniWind

**Design System** — Style Dictionary v5 · Tailwind Variants · Figma

**Testing** — Vitest · Testing Library · Supertest · Testcontainers · Playwright
· ArchUnitTS

**Observability** — OpenTelemetry · Pino · Grafana · Prometheus · Tempo · Sentry

**Infra & Tooling** — Turborepo · pnpm · Docker · GitHub Actions · Ansible

**Architecture** — Event Modeling · DDD · Modular Monolith · Hexagonal
Architecture · Vertical Slices · CQRS · Event Sourcing

## Beyond Code

Before becoming a developer, I spent 20 years playing guitar and bass, composing
music, and performing. I didn't leave that world behind — it shapes how I think
about building software. Composition is architecture. Improvisation is iterative
development. A good mix is separation of concerns.

I'm always learning, always building, always looking for the deeper "why" behind
the patterns.

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/theodros-yimer)

---

<picture>
  <source
    srcset="https://github-readme-stats.vercel.app/api/top-langs?username=theodrosyimer&show_icons=true&theme=dark&layout=compact&hide_border=true"
    media="(prefers-color-scheme: dark)"
  />
  <source
    srcset="https://github-readme-stats.vercel.app/api/top-langs?username=theodrosyimer&show_icons=true&layout=compact&hide_border=true"
    media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
  />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=theodrosyimer&show_icons=true&locale=en&layout=compact&hide_border=true" alt="Top Languages"/>
</picture>
