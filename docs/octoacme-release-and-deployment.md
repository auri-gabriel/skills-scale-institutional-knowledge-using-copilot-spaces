# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Owner
The **Release Manager** owns the end-to-end release process — scheduling deployment windows, verifying readiness criteria, coordinating the deployment team, and managing rollbacks. See [Roles & Personas](octoacme-roles-and-personas.md#release-manager) for full responsibilities. *(Role added per [issue #4](https://github.com/auri-gabriel/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4))*

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

> For the full release readiness checklist including cross-role sign-offs, see [Coordination Templates & Checklists — Release Readiness Checklist](octoacme-coordination-templates.md#release-readiness-checklist).

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

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
