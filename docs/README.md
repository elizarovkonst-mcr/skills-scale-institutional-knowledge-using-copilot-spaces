# OctoAcme Project Management Docs

This README is the central entry point for all OctoAcme project management process documentation. Use it to understand our overall approach at a glance and navigate to detailed guides for each stage of the project lifecycle.

---

## Overview of OctoAcme Project Management Processes

OctoAcme uses a lightweight but structured project management approach that spans the full project lifecycle: initiation, planning, execution, release, and retrospective. Work begins with a one-pager that defines the problem, goal, success metrics, stakeholders, timeline, risks, and resourcing needs. Once approved, the team moves into planning by creating a prioritized backlog, defining acceptance criteria and Definition of Done, estimating work, identifying dependencies, and mapping milestones and releases. This approach emphasizes iterative delivery, clear ownership, and data-informed decisions so teams can move from idea to production in small, testable increments.

### Key Workflows

| Stage | Focus |
|---|---|
| **Initiation** | Problem statement, stakeholders, high-level timeline, and approval |
| **Planning** | Backlog, milestones, dependencies, acceptance criteria, and Definition of Done |
| **Execution & Tracking** | Sprint delivery, PR reviews, project board management, CI checks |
| **Risk & Communication** | Risk register, escalation paths, regular status updates |
| **Release & Deployment** | Staging validation, release notes, rollback plan, post-deploy verification |
| **Retrospective** | Lessons learned, action items, continuous improvement |

### Personas and Roles

- **Project Manager (PM):** Coordinates delivery, schedules, risks, documentation, and stakeholder communication.
- **Product Manager (PdM):** Defines problem statements, prioritizes the roadmap and backlog, and measures outcomes against business and customer value.
- **Developers:** Implement features and fixes, contribute to estimation and planning, write tests and documentation, and surface technical risks.
- **QA/Testing:** Validate quality and acceptance criteria throughout execution and release.
- **Stakeholders:** Contribute to approvals, alignment, and feedback throughout the project lifecycle.

### Communication Strategies

OctoAcme treats communication as a core operating practice with defined rhythms:

- **Daily or twice-weekly standups** for the delivery team
- **Weekly PM/PdM sync** to align on priorities and blockers
- **Sprint-end demos or milestone reviews** to gather feedback
- **Monthly stakeholder updates** for broader visibility
- **Ad hoc escalations** when risks or blockers require immediate action

Teams maintain a single source of truth for project status through a project README, release document, or project board. Risk escalation follows a defined path: team-level triage → PM → Product Lead → sponsor-level escalation for business-impacting issues.

### Quality Assurance Practices

Quality is integrated throughout execution and release:

- Project board stages: **Backlog → Ready → In Progress → In Review → QA → Done**
- Pull requests are kept small, linked to issues, with clear acceptance criteria, automated CI checks, and required review approvals
- **Testing requirements:** unit tests for new logic, integration tests where appropriate, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance
- **Pre-release checklist:** completed acceptance criteria, passing CI and security scans, release notes, rollback plan, staging validation, and post-deploy verification

---

## Process Documents

| Document | Description |
|---|---|
| [Project Management Overview](./octoacme-project-management-overview.md) | Principles, core roles, key artifacts, and lifecycle at a glance |
| [Project Initiation Guide](./octoacme-project-initiation.md) | How to kick off a new project with a one-pager and stakeholder alignment |
| [Project Planning](./octoacme-project-planning.md) | Backlog creation, milestones, dependencies, and Definition of Done |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Sprint delivery, project board management, PR practices, and CI |
| [Risk Management & Communication](./octoacme-risks-and-communication.md) | Risk register, escalation paths, and communication cadence |
| [Release & Deployment Guide](./octoacme-release-and-deployment.md) | Release checklist, rollback planning, and post-deploy verification |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Lessons learned, action items, and process improvements |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Detailed responsibilities and goals for each role |

---

> For questions or suggestions, open an issue or contact the project team.
