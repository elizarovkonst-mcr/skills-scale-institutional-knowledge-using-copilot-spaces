# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared
- QA Lead sign-off on release quality
- DevOps Engineer confirms deployment pipeline is green
- Customer / Stakeholder Representative UAT sign-off (where required)

## Deployment Checklist
- [ ] Deployment window scheduled and communicated (Project Manager)
- [ ] Backup or snapshot taken if applicable (DevOps Engineer)
- [ ] Deploy to staging and run smoke tests (DevOps Engineer + QA Lead)
- [ ] QA Lead confirms staging acceptance (QA Lead)
- [ ] Deploy to production via automated pipeline (DevOps Engineer)
- [ ] Run post-deploy verifications (DevOps Engineer + QA Lead)
- [ ] Announce release to stakeholders and support (Project Manager / Product Manager)

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
