# OctoAcme — Role Handoff Checklist

## Purpose
Provide lightweight, role-specific checklists that clarify **who hands off what to whom** at each major project phase. Use this alongside the process docs to reduce ambiguity and prevent work from falling through the cracks.

---

## Phase 1 — Initiation Handoffs

| From | To | Artifact / Action |
|------|----|-------------------|
| Customer / Stakeholder Representative | Product Manager | Business objectives, success criteria, and key constraints |
| Business Analyst | Product Manager | Initial requirements summary and scope boundary |
| Product Manager | Project Manager | Approved One-pager with success metrics and proposed team |
| Project Manager | Full Team | Stakeholder list, communication plan, initial risk list |

**Checklist**
- [ ] One-pager reviewed and approved by Product Manager and Customer / Stakeholder Representative
- [ ] Initial risk list shared with Project Manager
- [ ] Team roles identified and confirmed (including QA Lead, DevOps Engineer, UX Designer)
- [ ] Decision gate: proceed to Planning?

---

## Phase 2 — Planning Handoffs

| From | To | Artifact / Action |
|------|----|-------------------|
| Product Manager | Business Analyst | Feature goals and priority ranking |
| Business Analyst | Developers & QA Lead | Refined user stories with acceptance criteria |
| UX Designer | Developers | Wireframes / prototypes and design specifications |
| QA Lead | Project Manager | Initial test plan and Definition of Done additions |
| DevOps Engineer | Project Manager | Environment readiness assessment and CI/CD dependencies |
| Project Manager | All | Finalized backlog, release plan, and milestone map |

**Checklist**
- [ ] Backlog items have clear acceptance criteria (Business Analyst + QA Lead review)
- [ ] UX designs reviewed and attached to relevant backlog items
- [ ] Test strategy documented by QA Lead
- [ ] DevOps environment and pipeline requirements captured in the project plan
- [ ] Definition of Done updated to include quality, UX, and accessibility criteria
- [ ] Risk Register created with owners assigned

---

## Phase 3 — Execution Handoffs

| From | To | Artifact / Action |
|------|----|-------------------|
| Developers | QA Lead | Feature branch / PR ready for QA review |
| QA Lead | Developers | Defect reports with reproduction steps and priority |
| UX Designer | Developers | Design clarifications and updated specs during build |
| Business Analyst | Developers & QA Lead | Requirement clarifications surfaced during development |
| Project Manager | Stakeholders | Weekly status update (progress, risks, blockers) |

**Checklist**
- [ ] PR descriptions include issue link, acceptance criteria, and testing notes
- [ ] QA sign-off required before merging to main/release branch
- [ ] Blocking defects escalated to Project Manager same day
- [ ] Risk Register reviewed and updated in weekly PM sync
- [ ] Customer / Stakeholder Representative notified of any scope changes

---

## Phase 4 — Release Handoffs

| From | To | Artifact / Action |
|------|----|-------------------|
| QA Lead | Project Manager | Release quality sign-off (all acceptance criteria met, no blocking defects) |
| DevOps Engineer | Project Manager | Deployment readiness: pipeline green, rollback plan confirmed |
| Product Manager | Customer / Stakeholder Representative | Release notes and go-live announcement draft |
| Customer / Stakeholder Representative | Project Manager | UAT sign-off (where required) |
| Project Manager | Full Team | Go / No-go decision and release schedule confirmation |

**Checklist**
- [ ] All acceptance criteria met and confirmed by QA Lead
- [ ] Security scan passing (DevOps Engineer)
- [ ] Release notes drafted and reviewed (Product Manager)
- [ ] Rollback plan documented and tested (DevOps Engineer)
- [ ] UAT completed and signed off (Customer / Stakeholder Representative)
- [ ] Post-deploy monitoring plan in place (DevOps Engineer)
- [ ] Release announcement ready for stakeholders (Product Manager / Project Manager)

---

## Phase 5 — Close & Retrospective Handoffs

| From | To | Artifact / Action |
|------|----|-------------------|
| Full Team | Project Manager | Retrospective notes and action items |
| Project Manager | Product Manager | Updated metrics and outcome assessment |
| Project Manager | Stakeholders | Final project summary and learnings |
| QA Lead | Team | Post-release defect summary and test coverage report |
| DevOps Engineer | Team | Post-deploy incident summary (if applicable) |

**Checklist**
- [ ] Retrospective held within one week of release
- [ ] Action items documented with owners and due dates
- [ ] Outstanding defects triaged and moved to next cycle backlog
- [ ] Learnings shared with the broader team or org

---

## Quick Reference — Ownership by Activity

| Activity | Primary Owner | Supporting Roles |
|----------|---------------|------------------|
| Requirements definition | Business Analyst | Product Manager, Customer / Stakeholder Representative |
| Backlog prioritization | Product Manager | Business Analyst, Project Manager |
| Test strategy | QA Lead | Developers, Business Analyst |
| UX / Accessibility | UX Designer | Developers, Product Manager |
| CI/CD & environments | DevOps Engineer | Developers, Project Manager |
| Risk management | Project Manager | All roles |
| Release go/no-go | Project Manager | QA Lead, DevOps Engineer, Product Manager |
| Stakeholder communication | Project Manager | Product Manager, Customer / Stakeholder Representative |
| Retrospective facilitation | Project Manager | Full Team |

---

*For full role descriptions, see [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md).*
*For phase-level process guidance, see the corresponding phase docs in this folder.*
