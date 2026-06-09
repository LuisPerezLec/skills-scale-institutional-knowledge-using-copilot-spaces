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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

# Additional Personas/Roles

This section adds cross-functional personas that support project delivery and improve clarity of responsibilities and handoffs.

### UX Designer
- Designs user flows and interfaces based on research and product requirements.
- Partners with Product Manager, Developers, and QA to vet features and acceptance criteria.
- Ensures usability best practices and accessibility are considered throughout the lifecycle.
- Communicates rationale behind design decisions to stakeholders.

Interactions with existing roles:
- With PdM: collaborates on problem framing, user research priorities, and acceptance criteria.
- With Developers: provides design specs, assets, and reviews implementations for fidelity.
- With QA: creates testable design acceptance criteria and reviews accessibility checks.
- With PM: coordinates timelines for design iterations and handoffs.

Common handoffs:
- Research findings and prototypes -> PdM and Devs at planning
- Finalized design assets -> Developers at start of implementation
- Usability issues -> QA and backlog for fixes

---

### Data Analyst
- Shapes and monitors key success metrics tied to product and project goals.
- Collaborates with PdM on experiment design, instrumentation, and impact analysis.
- Provides actionable insights to the team and supports data-driven decisions.

Interactions with existing roles:
- With PdM: define success metrics, experiment hypotheses, and dashboards.
- With Developers: specify instrumentation and validate event telemetry.
- With PM: inform stakeholders of metric-driven status and risk.

Common handoffs:
- Metrics definition and instrumentation spec -> Developers before implementation
- Analysis reports -> PdM and PM for prioritization decisions

---

### Security Champion
- Ensures threats/risks are flagged in planning and reviews.
- Guides architecture and implementation toward secure best practices.
- Acts as a project-level point of contact for security reviews and incident response.

Interactions with existing roles:
- With Developers: participates in design reviews and threat modeling.
- With PM: raises security-related risks and impact for planning and escalation.
- With PdM: ensures security/privacy requirements are included in acceptance criteria.

Common handoffs:
- Security requirements and checklists -> Developers and QA during planning
- Incident findings -> PM for communication and remediation planning

---

### Customer Support Liaison
- Channels customer pain points and feedback into team planning.
- Keeps track of critical incidents or user feedback that may affect priorities.
- Facilitates cross-talk between end-users/customers and the delivery team.

Interactions with existing roles:
- With PM/PdM: communicates major customer issues and feature requests.
- With Developers/QA: provides reproduction steps and context for bugs.
- With Stakeholders: summarizes customer-impacting issues and trends.

Common handoffs:
- Customer reports -> Developers/QA with context and priority
- Post-release feedback -> PdM for prioritization or quick fixes

---

## Handoffs and Interaction Examples
- Design -> Dev: UX Designer delivers a design spec, acceptance criteria, and accessibility checklist to Developers at the start of the implementation sprint.
- Instrumentation -> Dev: Data Analyst publishes an instrumentation spec and dashboard requirements before feature rollout.
- Security review -> Dev & PM: Security Champion runs a threat model during design and documents mitigations in the ticket.
- Customer incident -> PM & Dev: Customer Support Liaison creates an incident summary and urgency recommendation; PM coordinates triage with Developers and QA.

## How to use these personas in your project
- Reference the persona list when defining owners for backlog items.
- Use the handoff checklist in the ticket description to ensure required artifacts are attached before work begins.
- Add the relevant persona(s) as reviewers for design, instrumentation, or security-related PRs.

## Note on maintenance
When roles or responsibilities change, update the personas-change-log.md and file a process update issue (use template: .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml). See docs/personas-change-log.md for a changelog.
