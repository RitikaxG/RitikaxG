<h1 align="center">Hi, I'm Ritika Gupta 👋</h1>

<p align="center">
  <strong>Backend & Applied AI Engineer</strong><br/>
  Building distributed systems, cloud control planes, and governed agentic workflows.
</p>

<p align="center">
  <a href="mailto:ritikaxg@gmail.com">Email</a>
  ·
  <a href="https://x.com/RitikaxG">X / Twitter</a>
</p>

---

## About me

I build product-focused systems where backend architecture, infrastructure, and AI have to work together reliably.

My recent work covers:

- distributed and event-driven backend systems
- cloud control planes and runtime lifecycle orchestration
- Kubernetes, GitOps, CI/CD, and observability
- policy-grounded RAG, guarded agents, workflow memory, and evaluation
- human-in-the-loop AI with traceable and governed decisions

I care about the engineering around the model just as much as the model call: validation, failure handling, idempotency, observability, evaluation, safety boundaries, and operational proof.

## Featured projects

### [ClaimFlow AI](https://github.com/RitikaxG/claimflow_ai)

A governed agentic workflow that turns an unstructured motor-insurance claim into a policy-grounded, human-reviewed, and fully traceable case.

- document extraction and deterministic validation
- policy RAG with verified citations and abstention
- guarded tool-calling agent and human review
- safe workflow memory from trusted outcomes
- AI gateway, per-run traces, cost and latency visibility
- synthetic evaluation suites covering the complete workflow

**Built with:** TypeScript, Next.js, PostgreSQL, Prisma, pgvector, OpenAI, Bun, Turborepo, Docker

---

### [SpinUp](https://github.com/RitikaxG/SpinUp)

A control-plane-first cloud workspace platform that turns a browser request into a real code-server environment running on AWS.

- EC2 Auto Scaling Group allocation and idle VM reuse
- explicit runtime lifecycle and failure states
- Redis locks and runtime state mirroring
- VM agent and Docker-based workspace boot
- S3-backed project restore and synchronization
- browser dashboard exposing infrastructure state

**Built with:** TypeScript, Next.js, PostgreSQL, Redis, AWS EC2/ASG/S3, Docker, Clerk, Bun, Turborepo

---

### [RunState](https://github.com/RitikaxG/runState)

A production-style uptime monitoring platform built around independent workers and Redis Streams.

- scheduled website monitoring and response-time history
- status-transition detection and incident lifecycle
- asynchronous notification pipeline
- authenticated user and admin dashboards
- Prometheus metrics and containerized local development
- Kubernetes deployment managed through a separate GitOps repository

**Built with:** Go, Gin, Redis Streams, PostgreSQL, Next.js, Docker, Prometheus

**Deployment:** [runstate-gitops](https://github.com/RitikaxG/runstate-gitops) — Argo CD, Kustomize, External Secrets, ingress, Grafana, HPA, and automated image updates.

## Engineering toolbox

**Languages:** Go, TypeScript, JavaScript, Python, SQL  
**Backend:** Gin, Node.js, REST APIs, background workers, event-driven systems  
**Data:** PostgreSQL, Prisma, Redis, pgvector  
**Cloud & infrastructure:** AWS, Docker, Kubernetes, Argo CD, Kustomize, GitHub Actions  
**AI systems:** RAG, tool-calling agents, workflow memory, evaluations, tracing, human review  
**Frontend:** Next.js, React, Tailwind CSS  
**Observability:** Prometheus, Grafana, structured traces and model-call metadata

## What I am looking for

I am interested in backend, platform, cloud, and applied AI engineering roles where I can work on reliable product systems—not isolated demos.

I am especially drawn to teams building developer infrastructure, AI-enabled workflows, distributed services, internal platforms, or operational tooling.

---

<p align="center">
  Explore the repositories above for architecture diagrams, implementation walkthroughs, demos, evaluation results, and operational evidence.
</p>
