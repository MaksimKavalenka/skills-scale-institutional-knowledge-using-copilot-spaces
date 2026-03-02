# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA / Testing

### Role Summary
QA verifies that the product meets acceptance criteria, performs to quality standards, and is fit for release.

### Responsibilities
- Design and run test plans and test cases
- Validate feature acceptance criteria
- Coordinate exploratory and manual testing when needed
- Track and verify fixes for defects

### Typical Communication
- Test reports in PRs and release notes
- Test status during weekly syncs and demos

---

## Stakeholders

### Role Summary
Stakeholders provide input, domain knowledge, and approvals required for the project.

### Responsibilities
- Provide business context and input on priorities
- Review milestone deliverables and approve decisions where required
- Participate in major project decisions and sponsor escalation when needed

---

## Additional Personas (New)

The following personas were added to reduce ambiguity about ownership, improve cross-functional collaboration, and close gaps observed in delivery and support workflows.

### Scrum Master

Role Summary
- Supports the delivery team by facilitating agile ceremonies and removing impediments.

Responsibilities
- Facilitate sprint ceremonies (planning, daily standups, review, retrospective)
- Help the team adopt agile practices and improve flow
- Shield the team from unplanned interruptions when possible
- Track and escalate persistent blockers to the Project Manager or Product Lead

Interactions
- Works closely with PM to coordinate cadence, with Developers and QA during execution, and with PdM to ensure backlog readiness.

When to involve
- At the start of every sprint, during daily standups for impediments, and in retrospectives to drive continuous improvement.

---

### UX Designer

Role Summary
- Ensures product decisions reflect good usability and accessibility practices and that user needs are represented across the lifecycle.

Responsibilities
- Create user journeys, wireframes, and prototypes for proposed features
- Run or coordinate usability testing and research
- Provide design acceptance criteria and review implementation for usability
- Provide accessibility guidance and review before release

Interactions
- Collaborates with PdM on requirements, with Developers and QA on implementation and acceptance, and with Product Lead for design trade-offs.

When to involve
- Early in planning (to shape scope), during development for design reviews, and before release for final usability checks.

---

### Technical Architect

Role Summary
- Guides high-level technical decisions to ensure solutions are scalable, maintainable, and aligned with platform strategy.

Responsibilities
- Define system and integration designs for non-trivial features
- Recommend technology choices, non-functional requirements, and scalability approaches
- Provide architecture reviews and mentoring for development teams
- Identify and own mitigation for significant technical risks

Interactions
- Works with Developers for design reviews, with PM for trade-offs impacting timelines, and with PdM/Product Lead on feasibility and technical enablers.

When to involve
- During planning for complex features, at design review checkpoints, or when architecture-level changes are proposed.

---

### Business Analyst

Role Summary
- Clarifies and documents business requirements, acceptance criteria, and ensures user stories map to business outcomes.

Responsibilities
- Elicit detailed requirements from stakeholders and users
- Produce clear acceptance criteria and example scenarios
- Maintain traceability between requirements and deliverables
- Support PdM in prioritization by clarifying impact and scope

Interactions
- Works as a bridge between PdM, Stakeholders, Developers, and QA; helps PM maintain accurate requirements for planning.

When to involve
- During initiation and planning, while grooming backlog items, and before sprint planning to ensure readiness.

---

### Support Lead (Post-release/Operations Liaison)

Role Summary
- Coordinates production support, incident response, and ensures customer feedback loops inform product improvements.

Responsibilities
- Own first-line incident management and coordinate triage/escalation
- Maintain runbooks and on-call handover notes
- Track and escalate recurring customer issues into backlog/retrospective items
- Facilitate post-incident RCA and action tracking

Interactions
- Notifies PM and PdM of incidents impacting roadmap, works with Developers/QA for fixes, and communicates status to stakeholders and users.

When to involve
- Immediately on production issues; regularly during release planning to ensure support readiness.

---

## Role Interaction Patterns

- Ownership: The Project Manager owns timeline & communications. PdM owns product decisions and success metrics. Support Lead owns post-release incidents.
- Escalation: Team-level -> Scrum Master/PM -> Product Lead -> Sponsor (for business-critical issues). For security incidents, follow the security runbook and notify Security on-call.
- Handoffs: UX Designer -> PdM -> Developers for implementation; Business Analyst -> Developers/QA for acceptance criteria; Technical Architect -> Developers for design constraints.
- Decision loops: Small technical decisions can be made within the delivery team; architectural or scope trade-offs that affect timeline should be raised to PM/PdM and Technical Architect.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Use the role responsibility template (docs/templates/role-responsibility-template.md) when adding new personas to ensure consistent structure.
