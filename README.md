# Maksim Kuleshov — AI Solutions Architect & Full-Cycle Product Engineer

I design and deliver production-grade AI systems **from business problem to operation**: architecture, local or cloud LLMs, backend and APIs, automation, user-facing applications, delivery infrastructure, monitoring, and ongoing improvement.

My focus is not “adding a chatbot”. It is building a measurable business capability that is secure, observable, maintainable, and integrated with the systems people already use.

## What I can deliver

### AI platforms and private LLMs

- Local LLM deployment on company servers or workstations
- Cloud, on-premises, and hybrid model architectures
- AI agents, tool calling, RAG, structured output, and evaluation
- Permission-aware knowledge assistants and internal copilots
- Model routing, quality/latency/cost measurement, and guardrails

### Business-process automation

- Automation of document, support, CRM, operations, and approval workflows
- Integration with existing APIs, databases, queues, and internal services
- Telegram bots for customer and internal workflows
- Human-in-the-loop flows for sensitive or high-impact actions
- Audit trails, failure handling, and measurable process outcomes

### Backend, API, web, and mobile

- Backend services and production APIs
- Web applications and internal operational tools
- Kotlin Multiplatform applications
- Flutter applications
- Native Android applications with Kotlin and Jetpack Compose
- Shared business capabilities delivered across web, mobile, and Telegram

### Delivery and operations

- GitHub Actions workflows and release automation
- Self-hosted runners on dedicated servers or local machines
- Deployment pipelines for APIs, backends, applications, and AI services
- Environment and secrets strategy
- Logs, metrics, traces, dashboards, alerts, and operational monitoring
- Reproducible builds, automated verification, rollback, and incident readiness

## End-to-end ownership

```mermaid
flowchart LR
    A[Business process] --> B[Discovery and goals]
    B --> C[Architecture and security]
    C --> D[AI + backend + integrations]
    D --> E[Web / KMP / Flutter / Android / Telegram]
    E --> F[CI/CD and self-hosted runners]
    F --> G[Deployment and monitoring]
    G --> H[Evaluation and improvement]
```

I can own the whole path or join at a specific stage:

1. understand the workflow, users, constraints, and baseline;
2. select local, cloud, or hybrid inference based on evidence;
3. design the platform, data boundaries, integrations, and failure modes;
4. implement the backend, APIs, automation, and client applications;
5. configure delivery infrastructure, including self-hosted runners;
6. deploy, monitor, evaluate, and evolve the system.

## Engineering approach

I use structured AI-assisted delivery methods such as **BMAD** and **Superpowers** to connect discovery, product decisions, architecture, implementation, tests, review, and verification.

My core principles:

- business outcomes before model demos;
- private/local inference when data or economics require it;
- deterministic controls around probabilistic AI;
- evaluation before and after model or prompt changes;
- least-privilege integrations and auditable actions;
- observable systems with explicit failure and rollback paths;
- maintainable architecture that an engineering team can continue to own.

## Selected work

### [Enterprise AI Platform Showcase](https://github.com/maxlord/enterprise-ai-platform-showcase)

A runnable, production-minded reference for private local LLM inference, RAG, business-process analysis, FastAPI, Telegram, Docker, Prometheus/Grafana, GitHub Actions, and self-hosted delivery. It includes tests, an offline demo mode, operational endpoints, security notes, and an incremental production roadmap.

### [BMAD Method × Android](https://github.com/maxlord/bmad-ai-integration)

A runnable reference showing how an AI-assisted workflow connects product context, architecture, implementation, testing, review, and GitHub Actions in a real Android repository.

### [Android modular application skeleton](https://github.com/maxlord/android-skeleton-application)

A multi-module Kotlin application demonstrating coroutines, Flow, Retrofit, dependency injection, Jetpack Compose, and version catalogs.

Public Kotlin Multiplatform and Flutter reference implementations are being prepared next.

## Problems I am interested in

- private enterprise assistants over internal knowledge;
- local LLM platforms for regulated or sensitive environments;
- document and request-processing automation;
- AI-assisted operations, monitoring, and incident workflows;
- field and internal applications backed by shared AI capabilities;
- Telegram-based workflows and approval interfaces;
- modernization of manual processes into observable digital systems.

## Discuss a project

If you have a substantial business process that could benefit from AI or automation, [open a project inquiry](https://github.com/maxlord/maxlord/issues/new) and describe:

- the current process and its bottleneck;
- users and systems involved;
- privacy or on-premises requirements;
- the desired business outcome;
- expected scale and timeline.

I can help turn it into an architecture, a low-risk pilot, and a production delivery plan.
