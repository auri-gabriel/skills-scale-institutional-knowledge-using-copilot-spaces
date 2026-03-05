# OctoAcme — Coordination Templates & Checklists

> This document provides templates and checklists for improved cross-role coordination, hand-offs, and escalation procedures. Added as part of [issue #4](https://github.com/auri-gabriel/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4).

---

## Sprint Hand-off Checklist

Use this checklist at the end of each sprint to ensure a clean handoff from development to release/QA:

- [ ] All sprint stories meet their acceptance criteria and are marked Done on the project board
- [ ] All PRs merged; no open draft PRs intended for this sprint
- [ ] Automated tests (unit, integration, smoke) pass in CI
- [ ] Security scan completed with no new critical findings
- [ ] Release notes drafted by Release Manager and reviewed by Product Manager
- [ ] Deployment window confirmed with Release Manager
- [ ] Scrum Master has closed out the sprint in the project board and archived the sprint backlog
- [ ] Data Analyst has captured sprint velocity and any relevant delivery metrics
- [ ] UX Designer has signed off on any UI changes implemented this sprint

**Owner:** Scrum Master  
**Participants:** Developers, QA, Release Manager, Product Manager, UX Designer

---

## Release Readiness Checklist

Use this checklist before every production deployment:

- [ ] All acceptance criteria met and verified by QA
- [ ] CI pipeline passing (build, tests, security scans, linting)
- [ ] Release notes finalized and reviewed
- [ ] Rollback plan documented and reviewed by Release Manager and Project Manager
- [ ] Deployment window communicated to stakeholders
- [ ] Feature flags configured (enable/disable strategy confirmed)
- [ ] Monitoring and alerting configured for new functionality
- [ ] On-call rotation confirmed for deployment window
- [ ] Post-deploy verification steps documented

**Owner:** Release Manager  
**Participants:** Developers, QA, Project Manager, Product Manager

---

## Design Hand-off Checklist

Use this checklist when UX design is complete and ready for development:

- [ ] All screens/components have finalized mockups or prototypes
- [ ] Design specs shared via design tool link in the GitHub issue or PR
- [ ] Accessibility requirements documented (WCAG level, color contrast, keyboard nav)
- [ ] Edge cases and error states designed and documented
- [ ] Developer questions addressed in design review session
- [ ] Product Manager has approved the final designs
- [ ] Acceptance criteria updated to reference design specs

**Owner:** UX Designer  
**Participants:** Developers, Product Manager, QA

---

## Escalation Procedure

When a blocker or issue cannot be resolved at the team level, follow these steps:

### Step 1 — Team / Individual
- Raise the impediment at the daily standup or in the team async channel
- Document the blocker in the sprint board with the label `blocker`

### Step 2 — Scrum Master
- Scrum Master attempts resolution within 1 business day
- Logs issue in the impediment register with description, impact, and proposed resolution
- If unresolved, escalates to Project Manager with context

### Step 3 — Project Manager
- Project Manager assesses cross-team dependencies, resource constraints, or schedule impact
- Coordinates with relevant leads (Release Manager, Product Manager) for joint resolution
- Updates the Risk Register if the blocker creates a project risk
- Escalates to Product Manager or Sponsor if resolution requires strategic input

### Step 4 — Product Manager / Release Manager
- Product Manager handles scope, priority, or customer-impact escalations
- Release Manager handles release-blocking issues or go/no-go decisions
- Joint decision communicated back to Scrum Master and team within 1 business day

### Step 5 — Sponsor / Leadership
- Issues with budget, compliance, or cross-organizational impact escalate to Sponsor
- Project Manager prepares a brief summary with options and recommendation before escalating

---

## Onboarding Checklist (New Team Member)

Use this checklist when onboarding a new team member:

- [ ] Access to GitHub repository, project board, and relevant channels granted
- [ ] New team member has read [Project Management Overview](octoacme-project-management-overview.md)
- [ ] New team member has reviewed [Roles & Personas](octoacme-roles-and-personas.md)
- [ ] Role-specific onboarding session scheduled with team lead or buddy
- [ ] Added to recurring ceremonies (standup, sprint planning, retrospective)
- [ ] Introduced to Data Analyst for KPI dashboards and reporting access
- [ ] Copilot Spaces context documents reviewed (if applicable)
- [ ] First sprint: paired on a low-risk ticket to learn team workflows

**Owner:** Project Manager  
**Participants:** Scrum Master, relevant role leads

---

## Knowledge Sharing Session Template

Use this template to plan and document knowledge-sharing sessions:

- **Topic:**
- **Facilitator:**
- **Audience:**
- **Date/Time:**
- **Goal / Learning Outcome:**
- **Pre-reading or prep materials:**
- **Summary of key points covered:**
- **Action items from session (owner, due date):**
- **Recording or notes link:**

---

## Cross-Role Coordination Matrix

| Coordination Need | Initiated By | Involves | Cadence |
|---|---|---|---|
| Sprint planning & backlog grooming | Scrum Master | All team roles | Before each sprint |
| Design readiness review | UX Designer | Product Manager, Developers | 1 sprint ahead of implementation |
| Release readiness gate | Release Manager | Developers, QA, Project Manager | Before each deployment |
| KPI / metrics review | Data Analyst | Product Manager, Project Manager | Weekly or bi-weekly |
| Risk review | Project Manager | All leads | Weekly sync |
| Retrospective | Scrum Master | All team roles | End of each sprint / milestone |
| Stakeholder update | Project Manager | Product Manager, Data Analyst | Monthly or per milestone |
