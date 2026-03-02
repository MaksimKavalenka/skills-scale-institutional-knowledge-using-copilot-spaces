# OctoAcme Project Management Docs

## Summary of Project Management Processes

OctoAcme runs an outcome-first, iterative project management approach designed to make delivery predictable, measurable, and collaborative. The lifecycle follows five phases: Initiation, Planning, Execution, Release, and Retrospective/Continuous Improvement. Work begins with a concise Project One‑pager that clarifies the problem, success metrics, stakeholders, and a preliminary timeline; approved initiatives then move into planning where a prioritized, estimated backlog, release plan, and Definition of Done are created.

Execution emphasizes small, shippable increments tracked on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined Pull Request workflow: small diffs, CI checks (tests, lint, security) before requesting reviews, linking PRs to issues and acceptance criteria, and requiring approvals before merge. Quality is enforced through unit and integration tests, end‑to‑end smoke tests for critical flows, automated security scans in CI, manual QA when necessary, and a pre‑release checklist with a rollback/playbook for deployments.

Roles and responsibilities are explicit to reduce single‑person dependencies: Product Managers (PdMs) set outcomes and prioritize the backlog; Project Managers (PMs) coordinate schedules, risks, and stakeholder communications; Developers implement, test, and document; QA validates acceptance and quality. Communication cadence includes daily standups, weekly delivery/PM–PdM syncs, regular demos at milestone close, and monthly stakeholder updates. Risks are tracked in a Risk Register and escalated via a defined path (team → PM → Product Lead → Sponsor) for business‑impacting issues.

This README centralizes process guidance, shortens onboarding, and provides a single entry point to OctoAcme’s program process documents. Use these docs as the source of truth: keep the Project One‑pager, risk register, templates, and checklists updated in docs/ (or .copilot/ for Copilot Spaces context) and link PRs and issues to the relevant artifacts to maintain traceability.

## Docs Index

- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](docs/octoacme-roles-and-personas.md)

## How to use these docs

- Keep the Project One‑pager, risk register, and key artifacts updated in the project repo under docs/ or .copilot/.
- Use the backlog and release templates when creating work items or preparing a release.
- Link PRs to their backlog item and include acceptance criteria to speed review and QA.
