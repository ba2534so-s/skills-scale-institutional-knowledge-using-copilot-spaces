# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation. This folder contains the team's lightweight, repeatable processes for initiating, planning, executing, releasing, and improving projects. The docs are designed to help teams deliver customer-focused outcomes with clear ownership, low friction, and strong quality controls.

OctoAcme follows an iterative lifecycle: Initiation, Planning, Execution, Release, and Retrospective. Initiation focuses on a short one-pager that defines the problem, measurable outcomes, stakeholders, and a go/no‑go decision. Planning breaks approved initiatives into shippable backlog items, defines the Definition of Done, captures dependencies and risks in a risk register, and creates a release/milestone plan. Execution uses a project board workflow and pull-request practices that favor small changes, clear acceptance criteria, CI gating (tests, linting, security scans), and at least one reviewer before merge. Release & Deployment are standardized with pre-release checks, smoke tests in staging, a deployment checklist, and a rollback/incident playbook.

Roles and responsibilities are explicit to avoid ambiguity: Product Managers define outcomes and prioritize the backlog; Project Managers coordinate schedules, risks, and communications; Developers implement and test; QA validates acceptance criteria; Stakeholders provide inputs and approvals. The docs include persona definitions and templates so ownership and expectations are consistent across projects.

Communication and quality assurance are built into the cadence: daily standups (or agreed alternative), weekly delivery syncs, demos at sprint/milestone end, and monthly stakeholder updates. QA practices require unit and integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA when needed. Retrospectives capture learnings and convert them into tracked action items so the team improves incrementally.

## Documents in this folder
- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

How to use this folder:
- Keep the Project One-pager and release notes in the project repo alongside these process docs.
- Use the templates and checklists in these documents to ensure consistent, auditable delivery.
- Add project-specific process adjustments into `.copilot/` if you want Copilot Spaces to use them as context.
