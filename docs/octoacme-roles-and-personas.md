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

## New/additional personas added (summary)

The project team has requested additional personas to clarify ownership for cross-cutting concerns and operational tasks. The following personas were added to improve handoffs, onboarding, and decision-making. See the subsections below for Responsibilities and Interaction notes.

> Note: These additions were made in response to issue #4: "Adding more personas and roles to the project management processes".

### Engineering Manager (EM)

- Responsibilities: People and delivery enablement for the engineering team, capacity planning, performance coaching, and ensuring engineering practices (code review, CI) are followed. EMs support career development and help unblock teams by addressing personnel and process constraints.
- Interactions: Works with PM/PdM on resourcing and delivery trade-offs; coordinates with Developers and QA on team-level execution and with Project Manager for scheduling and risk. Escalates cross-team people or resourcing concerns to the Product Lead where needed.

### Technical Program Manager (TPM)

- Responsibilities: Drive complex technical initiatives end-to-end, manage cross-team dependencies, schedule coordination, and technical risk mitigation. TPMs translate roadmap goals into practical delivery plans across engineering teams.
- Interactions: Partners with PM/PdM to translate roadmap dependencies into plans, owns cross-team communications, and escalates unblockers to Project Manager or Product Lead. Works closely with EMs and architects to align technical priorities.

### DevOps / Platform Engineer

- Responsibilities: Maintain CI/CD pipelines, platform reliability, observability, and deployment automation. They design and operate the platform components that allow product teams to deliver quickly and safely.
- Interactions: Coordinates with Developers and QA to ensure releases and environment parity; advises on deployment and rollback strategies with Release Manager. Partners with Security Engineers for secure-by-default infrastructure.

### Release Manager

- Responsibilities: Plan and execute releases, coordinate release windows, runbooks, and post-release verification; own rollback decisions where applicable. The Release Manager ensures releases follow the intended process and that stakeholders are informed.
- Interactions: Works with DevOps, PM, PdM, and Support/On-call to schedule and announce releases. Coordinates with QA for sign-off and with Data Analysts to validate post-release metrics.

### UX Researcher / Design Researcher

- Responsibilities: Run user research, synthesize insights, validate assumptions, and inform acceptance criteria. Researchers help ensure the team builds solutions grounded in user needs and evidence.
- Interactions: Collaborates with PdM on success metrics, with Designers on solutions, and with Developers to clarify user needs during planning. Shares findings during discovery and planning to influence priorities.

### Data Analyst / Analytics Engineer

- Responsibilities: Define and validate success metrics, instrument tracking, and produce reports for outcomes. They ensure the team measures impact and can make data-informed decisions.
- Interactions: Works with PdM to define metrics, with Developers/DevOps to implement instrumentation, and with PM to report progress. Partners with Release Manager to confirm post-release analytics.

### Security Engineer

- Responsibilities: Threat modeling, security reviews, vulnerability triage, and guidance on compliance/security best practices. Security Engineers reduce risk by ensuring secure design and operational practices.
- Interactions: Consults during design and planning, performs security scans in CI, and escalates critical findings to Product Lead and Project Manager. Works with DevOps and Developers on remediation and with Release Manager to gate risky changes.
