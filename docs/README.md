# OctoAcme Project Management Docs

This README serves as a centralized index and guide to all project management process documents for OctoAcme. Use it to understand our workflow at a glance and navigate to detailed guides for each stage of the project lifecycle.

## Overview of OctoAcme Project Management Processes

OctoAcme uses a lightweight but structured project management approach that spans the full project lifecycle: **initiation, planning, execution, release, and retrospective**. Work typically begins with a one-pager that defines the problem, goal, success metrics, stakeholders, timeline, risks, and resourcing needs. Once an initiative is approved, the team moves into planning by creating a prioritized backlog, defining acceptance criteria and Definition of Done, estimating work, identifying dependencies, and mapping milestones and releases. This approach emphasizes iterative delivery, clear ownership, and data-informed decisions so teams can move from idea to delivery in small, testable increments.

### Core Principles
- **Customer-first:** Focus on delivering value and usability to customers.
- **Iterative delivery:** Work in small, testable increments and adapt based on feedback.
- **Clear ownership:** Each project has a dedicated PM and Product Lead.
- **Data-driven decisions:** Use success metrics and evidence to drive planning.
- **Risk management:** Identify, escalate, and mitigate risks throughout the project.
- **Transparent communication:** Regular updates and clearly documented processes across the lifecycle.

### Personas & Roles

The documentation defines several core personas. **Project Managers** coordinate delivery, timelines, risks, documentation, and stakeholder communication. **Product Managers** define problem statements, prioritize the roadmap and backlog, and measure outcomes against business and customer value. **Developers** implement features and fixes, contribute to estimation and planning, write tests and documentation, and help surface technical risks. **Stakeholders** contribute to approvals, alignment, and feedback throughout the project lifecycle.

### Communication Cadence

OctoAcme recommends regular team rhythms including daily or twice-weekly standups, weekly PM/PdM delivery syncs, sprint-end demos or milestone reviews, monthly stakeholder updates, and ad hoc escalations when needed. Teams maintain a single source of truth for status through a project README, release document, or project board. Risk and blocker communication follows a defined escalation path from team-level triage to PM, then Product Lead, and ultimately sponsor-level escalation for business-impacting issues.

### Quality Assurance

Quality assurance is integrated throughout execution and release. During delivery, teams use a project board with clear workflow stages (Backlog, Ready, In Progress, In Review, QA, Done) and follow PR practices that favor small pull requests, linked issues, clear acceptance criteria, automated CI checks, and required review approvals. Testing expectations include unit tests for new logic, integration tests where appropriate, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance when necessary. Before release, OctoAcme requires completed acceptance criteria, passing CI and security scans, release notes, rollback planning, staging validation, post-deploy verification, and retrospective follow-up.

---

## Key Process Documents

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level introduction to OctoAcme's approach, roles, and key artifacts |
| [Project Initiation Guide](octoacme-project-initiation.md) | How to kick off a project with a one-pager, stakeholder alignment, and problem statement |
| [Project Planning](octoacme-project-planning.md) | Backlog creation, milestones, dependencies, and sprint planning |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Delivery workflows, project board usage, PR practices, and progress tracking |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk identification, escalation paths, and communication strategies |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Pre-release checklists, deployment steps, and post-deploy verification |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective format, action items, and process improvement practices |
| [Roles & Personas](octoacme-roles-and-personas.md) | Definitions and responsibilities for all project roles |

---

> For questions or suggestions, open an issue or contact the project team.
