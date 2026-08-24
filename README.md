<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/hero-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/hero-light.svg">
  <img alt="Sandeep Nyoupane — Software Engineer | Architecture, Distributed Systems, DevSecOps" src="./assets/hero-light.svg" width="100%">
</picture>

<div align="center">

[**ArchitectLab**](https://github.com/SandeepN97/architect-lab-java) · [**InboxGuard**](https://github.com/SandeepN97/inboxguard) · [**EdgeBot**](https://github.com/SandeepN97/edgebot) · [**Samjhana Ventures OS**](https://github.com/SandeepN97/samjhana-ventures-os) · [**All repositories →**](https://github.com/SandeepN97?tab=repositories)

</div>

## I build software where the architecture is visible in the code.

I work across **Java / Spring Boot**, **TypeScript / React**, data, distributed-system patterns, and delivery automation. I am most interested in the parts of software that determine whether a system remains understandable after the happy-path demo is over: **boundaries, failure behavior, security, observability, testing, and operational evidence**.

My engineering thesis is simple:

> **Important design decisions should be enforceable, observable, and reviewable — not buried in a diagram or remembered by one person.**

That shows up repeatedly in my projects: dependency rules enforced with tests, failure modes made visible, security checks moved into CI, experiments separated from claims, and documentation kept close to the system it describes.

---

## Selected systems

### 🏗️ [ArchitectLab](https://github.com/SandeepN97/architect-lab-java) — learn distributed systems by changing them

`Java` · `Spring Boot` · `React` · `Redis` · `Kafka / Redpanda` · `OpenTelemetry`

A hands-on system-design playground built to make backend behavior observable instead of abstract.

- Compare fixed-window, sliding-window, and token-bucket rate limiting in a running application.
- Generate traffic, inject failures, and observe how the system responds.
- Connect application behavior to events, metrics, Prometheus, Grafana, and tracing-oriented design.
- Keep implemented labs distinct from roadmap ideas so the repository remains a truthful learning surface.

**Why it matters:** system-design concepts become more useful when you can change a constraint and watch the consequences.

[Explore ArchitectLab →](https://github.com/SandeepN97/architect-lab-java)

---

### 🛡️ [InboxGuard](https://github.com/SandeepN97/inboxguard) — architecture boundaries backed by security controls

`Java 21` · `Spring Boot` · `React` · `PostgreSQL` · `OAuth2`

A Gmail-management application used as a reference implementation for **hexagonal architecture and secure delivery**.

- Architecture boundaries are tested with **ArchUnit** instead of relying on convention alone.
- OAuth2 credentials are handled with encrypted token storage and explicit adapter boundaries.
- CI combines **CodeQL, Trivy, Semgrep, Gitleaks, OWASP ZAP**, dependency checks, and application tests.
- C4 diagrams and ADRs explain the system while executable checks help keep the implementation aligned with those decisions.

**Why it matters:** architecture becomes credible when violating it causes a test or pipeline to fail.

[Explore InboxGuard →](https://github.com/SandeepN97/inboxguard)

---

### 📈 [EdgeBot](https://github.com/SandeepN97/edgebot) — research software that is allowed to say “the strategy failed”

`Python` · `Clean Architecture` · `Backtesting` · `Risk Management`

An algorithmic-trading research platform built around validation discipline rather than optimistic backtests.

- Separates strategy logic, market/data adapters, risk controls, execution boundaries, and research workflows.
- Uses sealed holdout testing and records failed strategies instead of hiding negative results.
- Keeps live-capital execution out of scope while paper-trading and risk behavior are validated.
- Maintains **130+ tests** around the research and execution boundaries.

**Why it matters:** evidence that disproves an idea is still useful engineering output.

[Explore EdgeBot →](https://github.com/SandeepN97/edgebot)

---

### 🏢 [Samjhana Ventures OS](https://github.com/SandeepN97/samjhana-ventures-os) — software shaped by real business domains

`Java 21` · `Spring Boot` · `React` · `JWT` · `i18n`

A bilingual multi-business ERP spanning furniture, fuel, EV charging, rentals, loans, pricing, finance, and role-based operations across Nepal and the United States.

- Models several operational domains without flattening them into one generic CRUD workflow.
- Supports bilingual interfaces and practical workflows for non-technical users.
- Combines role-based access, pricing/data integration, API documentation, and full-stack operational views.
- Treats domain modeling and usability as architecture concerns, not only UI concerns.

**Why it matters:** good software architecture has to survive the messiness of the domain it represents.

[Explore Samjhana Ventures OS →](https://github.com/SandeepN97/samjhana-ventures-os)

---

## How I approach engineering

| Principle | What it means in practice |
| --- | --- |
| **Architecture should constrain code** | Dependency rules, interfaces, tests, and policies should reinforce the intended structure. |
| **Failure is part of the design** | Timeouts, degraded dependencies, rejected inputs, and recovery paths deserve first-class treatment. |
| **Security belongs in delivery** | Secrets, dependencies, static analysis, runtime checks, and release controls belong in the pipeline. |
| **Observability explains behavior** | Logs, metrics, traces, events, and audit evidence should make system behavior inspectable. |
| **Tests validate assumptions** | A test suite should challenge important invariants, not exist primarily to improve a coverage badge. |
| **Documentation is part of the system** | ADRs, C4 diagrams, runbooks, and implementation docs should evolve with the code. |
| **Automation needs boundaries** | Automated actions should have explicit permissions, review points, and evidence where consequences matter. |

---

## Systems thinking

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/systems-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/systems-light.svg">
  <img alt="How I think about software systems" src="./assets/systems-light.svg" width="100%">
</picture>

I try to separate **product intent, application behavior, domain rules, workflows, security, infrastructure, and observability** so each can evolve without turning every change into a repository-wide dependency problem.

---

## Technical focus

**Application engineering**  
`Java 21` · `Spring Boot` · `TypeScript` · `JavaScript` · `React` · `Astro` · `REST` · `SQL`

**Systems & data**  
`PostgreSQL` · `Redis` · `Kafka / Redpanda` · `Docker` · `Event-driven design` · `Rate limiting`

**Reliability & delivery**  
`GitHub Actions` · `Prometheus` · `Grafana` · `OpenTelemetry` · `CodeQL` · `Trivy` · `Semgrep` · `Gitleaks` · `OWASP ZAP`

**Architecture**  
`Hexagonal Architecture` · `Clean Architecture` · `C4` · `ADRs` · `Domain modeling` · `Workflow boundaries`

**AI-assisted engineering**  
I use AI tools to accelerate research, implementation, testing, and review while keeping **architecture, acceptance criteria, authority, and evidence** explicit. I am particularly interested in machine-readable documentation, bounded automation, provider abstraction, and human review at consequential boundaries.

---

## Current direction

I am deepening my work in **distributed systems, architecture enforcement, secure delivery, observability, and governed AI-assisted engineering**.

ArchitectLab is the main public learning surface for system-design experiments. InboxGuard, EdgeBot, and Samjhana Ventures OS provide different pressure tests: security and architecture enforcement, empirical validation, and real-world domain complexity.

---

<div align="center">

### Build deliberately. Make the boundaries visible. Verify the behavior.

[**Explore all repositories →**](https://github.com/SandeepN97?tab=repositories)

</div>
