# OctoAcme Project Management Docs — README

This README aggregates OctoAcme's project management process documents and provides a short summary of the processes we use. Use these docs as the single source of truth for project initiation, planning, execution, release, and continuous improvement.

Overview

OctoAcme runs projects with a lightweight, outcome-driven process that moves work from idea to production through clear initiation, planning, execution, release, and improvement phases. Every effort begins with a Project One-pager to capture the problem, objective, success metrics, stakeholders, and a high-level timeline; the Project Initiation Guide defines the gate criteria to move into planning.

Planning focuses on turning approved initiatives into an actionable backlog and release plan. Teams break work into prioritized backlog items with clear acceptance criteria, estimate scope, and define a Definition of Done. The planning activities include kickoff meetings, dependency identification, and risk capture in a simple risk register so cross-team dependencies and mitigation actions are visible early.

Execution and quality assurance emphasize iterative delivery, small PRs, and automation. Work is tracked on a project board (Backlog → Ready → In Progress → In Review → QA → Done). Pull requests should be small, reference the related issue and acceptance criteria, and run automated tests and linters in CI before review. QA includes unit and integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual testing where needed. Releases follow a staged checklist with pre-release checks, staging smoke tests, a rollback plan, and post-deploy verification.

Roles and communication

Roles are explicit to ensure clear ownership: Product Managers define outcomes and success metrics; Project Managers coordinate delivery, schedules, risks, and stakeholder communication; Developers implement features and tests; QA validates acceptance criteria; and Stakeholders provide inputs and approvals. The team cadence includes daily standups for progress and blockers, weekly delivery syncs, sprint demos/reviews, and monthly stakeholder updates. Risk and incident communications use templates and a defined escalation path (team → PM → Product Lead → Sponsor) to ensure timely attention to critical issues.

How to use these docs

- Initiation: Validate ideas with a Project One-pager, align stakeholders, and decide go/no-go for planning.
- Planning: Create a prioritized backlog, estimate work, define the Definition of Done, and map release milestones.
- Execution & Tracking: Use the project board, follow PR conventions, run CI tests and security scans, and track velocity and risks.
- Release & Deployment: Follow pre-release checks, run smoke tests, and use rollback/playbooks for incidents.
- Retrospectives & Improvement: Run retros after sprints/releases, create action items, and track improvements in the backlog.

Links to process documents (in docs/)

- [Project Management Overview](./octoacme-project-management-overview.md) — high-level intro, roles, artifacts, lifecycle.
- [Project Initiation Guide](./octoacme-project-initiation.md) — one-pager template, initiation checklist, decision gate.
- [Project Planning](./octoacme-project-planning.md) — backlog templates, planning activities, risk register guidance.
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — team rhythm, workflows, PR conventions, reporting.
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — risk register, stakeholder comms, escalation paths.
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — release checklist, rollback playbook, release notes template.
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — retrospective structure, action item tracking.
- [Roles & Personas](./octoacme-roles-and-personas.md) — role descriptions and responsibilities.

How to propose updates

- Use the "Add Content to Project Management Process Docs" issue template to suggest new content or updates (.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml).
- For urgent corrections, open a PR directly referencing the relevant doc and include the acceptance criteria or rationale.

Associated issue: #2
