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

## QA Lead

### Role Summary
The QA Lead owns the quality strategy for the project. They define test plans, oversee test coverage, and act as the final quality gate before release. The QA Lead works across the team to ensure that acceptance criteria are testable and that defects are surfaced early.

### Responsibilities
- Define and maintain the overall test strategy (unit, integration, end-to-end, performance)
- Review acceptance criteria for testability during planning
- Coordinate manual and automated testing activities
- Track and prioritize defects; escalate blocking issues to the Project Manager
- Sign off on release readiness from a quality perspective
- Mentor team members on testing practices

### Goals
- Prevent defects from reaching production
- Maintain high test coverage and a fast feedback loop
- Ensure releases meet the Definition of Done quality criteria

### Typical Communication
- Sprint planning and backlog grooming (with Developers and Product Manager)
- Pre-release sign-off checklist (with Project Manager and DevOps Engineer)
- Defect reports and test-result summaries shared with the full delivery team

### Interaction Notes
- Works closely with **Developers** to align on testability and code quality standards.
- Coordinates with the **Product Manager** to validate that acceptance criteria are clear and measurable.
- Gives a formal quality sign-off to the **Project Manager** before each release.
- Collaborates with the **DevOps Engineer** to integrate automated tests into the CI/CD pipeline.

---

## DevOps Engineer

### Role Summary
The DevOps Engineer owns the build, release, and infrastructure pipeline. They ensure that code can be built, tested, and deployed reliably and repeatedly. They also support monitoring, incident response, and platform reliability across environments.

### Responsibilities
- Design, maintain, and improve CI/CD pipelines
- Manage deployment environments (staging, production) and infrastructure-as-code
- Monitor system health and configure alerting
- Lead or support incident response and post-incident reviews
- Enforce security scanning and compliance gates in the pipeline
- Document runbooks and deployment procedures

### Goals
- Enable fast, low-risk deployments
- Minimize unplanned downtime and deployment friction
- Make infrastructure changes auditable and repeatable

### Typical Communication
- Pre-release coordination with the **QA Lead** and **Project Manager**
- Incident notifications to on-call and stakeholders
- Runbook and pipeline documentation shared with the delivery team

### Interaction Notes
- Partners with **Developers** on branching conventions, build tooling, and environment parity.
- Coordinates with the **QA Lead** to integrate automated test gates into pipelines.
- Keeps the **Project Manager** informed of deployment schedules and infrastructure risks.
- Supports the **Project Manager's** rollback and incident playbook documentation.

---

## UX Designer

### Role Summary
The UX Designer is responsible for user experience, interaction design, and accessibility. They translate user needs and product goals into usable, inclusive interfaces and validate designs through research and testing before and during development.

### Responsibilities
- Conduct user research, usability testing, and accessibility reviews
- Produce wireframes, prototypes, and design specifications
- Define and document user flows and interaction patterns
- Participate in backlog grooming to ensure UX work is prioritized alongside engineering
- Review implemented features for design fidelity and usability
- Maintain a shared design system or component library where applicable

### Goals
- Deliver experiences that are intuitive, accessible, and aligned with user needs
- Reduce rework caused by late-stage UX changes
- Ensure design decisions are grounded in user evidence

### Typical Communication
- Design reviews and prototype walkthroughs with **Developers** and **Product Manager**
- Usability findings shared with **Product Manager** and **Customer/Stakeholder Representative**
- Accessibility notes embedded in acceptance criteria or task descriptions

### Interaction Notes
- Collaborates with the **Product Manager** to translate product goals into user journeys.
- Hands off design specifications and assets to **Developers** with clear acceptance criteria.
- Incorporates feedback from the **Customer/Stakeholder Representative** to validate user flows.
- Works with the **QA Lead** to add usability and accessibility checks to the definition of done.

---

## Business Analyst

### Role Summary
The Business Analyst bridges the gap between business objectives and technical delivery. They gather and refine requirements, model processes, and ensure that what gets built solves the right problem at the right level of detail.

### Responsibilities
- Elicit, document, and validate requirements from stakeholders
- Translate business needs into clear acceptance criteria and user stories
- Model current and future-state processes to identify gaps
- Support prioritization by providing impact and dependency analysis
- Review deliverables against business requirements and flag gaps
- Maintain a requirements traceability matrix where appropriate

### Goals
- Ensure that delivered features address real business needs
- Reduce ambiguity in requirements before work begins
- Improve handoffs between stakeholders and the delivery team

### Typical Communication
- Requirements workshops and interviews with **Customer/Stakeholder Representative** and **Product Manager**
- Acceptance-criteria reviews with **Developers** and **QA Lead**
- Impact and scope updates to the **Project Manager**

### Interaction Notes
- Partners with the **Product Manager** to refine and prioritize requirements for the backlog.
- Provides the **QA Lead** with detailed acceptance criteria to support test case creation.
- Coordinates with the **Customer/Stakeholder Representative** to validate that requirements are complete and accurate.
- Escalates scope or requirements changes to the **Project Manager** for schedule and risk assessment.

---

## Customer / Stakeholder Representative

### Role Summary
The Customer / Stakeholder Representative brings the voice of the end user or business sponsor into the project. They participate in reviews, validate that solutions address the intended need, and help prioritize based on real-world impact.

### Responsibilities
- Communicate business priorities, constraints, and success criteria
- Participate in milestone reviews, sprint demos, and UAT sessions
- Provide timely feedback on prototypes, designs, and delivered features
- Escalate business-critical concerns to the **Product Manager** or **Project Manager**
- Help validate the Definition of Done from a business perspective
- Approve key deliverables and release decisions where required

### Goals
- Ensure the delivered product meets business and user expectations
- Provide clear, actionable feedback at the right project moments
- Reduce rework by engaging early and consistently

### Typical Communication
- Sprint demos and milestone reviews with the **Project Manager** and **Product Manager**
- UAT sign-off coordination with the **QA Lead** and **Business Analyst**
- Ad-hoc feedback channels with the **UX Designer** and **Product Manager**

### Interaction Notes
- Works closely with the **Product Manager** to communicate priorities and validate the roadmap.
- Provides acceptance sign-off to the **QA Lead** and **Project Manager** during release readiness reviews.
- Engages with the **Business Analyst** to ensure requirements accurately reflect business needs.
- Collaborates with the **UX Designer** on user flows and usability validation.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

