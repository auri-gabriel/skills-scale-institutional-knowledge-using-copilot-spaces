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

## Scrum Master

> Added as part of [issue #4](https://github.com/auri-gabriel/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4) — expanding team roles for improved clarity and accountability.

### Role Summary
Scrum Masters serve as agile coaches and servant leaders for the delivery team. They facilitate agile ceremonies, remove impediments, and foster a culture of continuous improvement to help the team achieve its commitments.

### Responsibilities
- Facilitate sprint planning, daily standups, sprint reviews, and retrospectives
- Identify and remove blockers that impede team progress
- Coach the team on agile principles and practices
- Track team velocity and sprint health metrics
- Shield the team from outside interruptions during sprints
- Escalate unresolved impediments to the Project Manager when needed

### Goals
- Maximize team productivity and flow
- Create a healthy, self-organizing team environment
- Drive measurable improvements in delivery cadence through retrospectives

### Typical Communication
- Daily standups and sprint ceremonies
- Impediment logs and resolution updates
- Velocity and burndown charts shared with Project Manager
- Retrospective facilitation notes and action items

### Interactions with Existing Roles
- **Project Manager**: Partners closely on delivery health, sprint goals, and escalating blockers that exceed team capacity.
- **Product Manager**: Collaborates to ensure the backlog is prioritized and groomed before each sprint; helps the team understand acceptance criteria.
- **Developers**: Acts as a servant leader, removing blockers, coaching on agile practices, and protecting focus time.
- **Release Manager**: Coordinates sprint release readiness, ensuring all sprint deliverables meet pre-release criteria before handoff.

---

## UX Designer

> Added as part of [issue #4](https://github.com/auri-gabriel/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4) — expanding team roles for improved clarity and accountability.

### Role Summary
UX Designers advocate for user needs and translate requirements into intuitive, accessible product experiences. They bridge the gap between customer insights and engineering implementation through research, wireframes, and design prototypes.

### Responsibilities
- Conduct user research, usability testing, and customer interviews
- Create wireframes, prototypes, and design specifications
- Maintain a shared design system and UI component library
- Define and enforce usability and accessibility standards
- Participate in sprint planning to ensure design readiness ahead of development
- Review implemented features to confirm they match approved designs

### Goals
- Ensure all product experiences are intuitive, accessible, and aligned with user needs
- Reduce rework by providing clear, early design guidance to developers
- Advocate for the end user in all product decisions

### Typical Communication
- Collaborative workshops with Product Managers and Developers during discovery
- Design reviews shared via design tool links in GitHub issues or PRs
- Usability test findings reported to Product Manager and stakeholders
- Participation in sprint reviews to assess UI/UX implementation quality

### Interactions with Existing Roles
- **Product Manager**: Partners on translating business requirements and user needs into design direction; aligns on feature scope and priorities.
- **Developers**: Provides detailed design specs and is available for implementation questions; reviews PRs that contain UI changes.
- **Project Manager**: Flags design dependencies and timelines that may affect sprint planning or delivery dates.
- **Scrum Master**: Coordinates to ensure design tasks are represented and tracked in the sprint backlog.

---

## Data Analyst

> Added as part of [issue #4](https://github.com/auri-gabriel/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4) — expanding team roles for improved clarity and accountability.

### Role Summary
Data Analysts provide project-related metrics, support business decisions with analysis, and track key performance indicators (KPIs). They empower the team to make data-driven decisions by surfacing trends, anomalies, and insights from product and operational data.

### Responsibilities
- Define, track, and report on project and product KPIs
- Build and maintain dashboards and data pipelines relevant to team goals
- Conduct ad-hoc analysis to support prioritization and decision-making
- Collaborate with Product Managers on measuring feature impact and success metrics
- Identify data quality issues and work with engineers on resolutions
- Contribute to retrospectives by providing quantitative evidence of improvements or regressions

### Goals
- Enable data-informed decision-making across the team
- Surface actionable insights that improve product outcomes and delivery efficiency
- Reduce reliance on anecdotal evidence for prioritization

### Typical Communication
- Recurring dashboard reviews shared with Product Manager and Project Manager
- Ad-hoc analysis reports in response to specific business questions
- KPI status summaries included in weekly stakeholder updates
- Contributions to retrospectives with quantitative retrospective data

### Interactions with Existing Roles
- **Product Manager**: Primary partner for defining success metrics, running A/B tests, and measuring feature impact after release.
- **Project Manager**: Provides delivery and operational metrics (e.g., cycle time, defect rate) to support status reporting and risk identification.
- **Developers**: Works with engineering to ensure the right data is being collected and that instrumentation is accurate.
- **Scrum Master**: Supplies velocity and cycle-time data to support sprint health reviews and continuous improvement efforts.

---

## Release Manager

> Added as part of [issue #4](https://github.com/auri-gabriel/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4) — expanding team roles for improved clarity and accountability.

### Role Summary
Release Managers plan, coordinate, and oversee the end-to-end deployment process for product releases. They ensure each release meets quality, compliance, and readiness standards, and that teams are aligned on deployment windows, rollback procedures, and post-release communications.

### Responsibilities
- Own and maintain the release calendar and deployment schedule
- Coordinate pre-release checklists across QA, Developers, and Project Manager
- Verify all acceptance criteria, CI checks, and security scans are passed before release
- Manage deployment windows and communicate release schedules to stakeholders
- Own the rollback plan and incident response coordination during release incidents
- Facilitate post-release verification and communicate go/no-go decisions
- Maintain and improve the deployment pipeline and release runbooks

### Goals
- Ensure every release is predictable, low-risk, and fully communicated
- Reduce production incidents caused by insufficient release readiness
- Improve release cadence through process automation and documentation

### Typical Communication
- Release readiness meetings with QA, Developers, and Project Manager ahead of each deployment
- Release notes and deployment announcements to stakeholders
- Incident and rollback communication during and after deployment issues
- Post-release retrospective summaries documenting what worked and what to improve

### Interactions with Existing Roles
- **Project Manager**: Partners on release scheduling, risk tracking, and stakeholder communication; escalates go/no-go decisions when criteria are not met.
- **Developers**: Coordinates on deployment readiness, environment configuration, feature flags, and rollback scripts.
- **Product Manager**: Aligns on release scope, feature flag strategy, and external communications to customers.
- **Scrum Master**: Coordinates sprint exit criteria with release readiness gates to ensure smooth handoffs between development and deployment.

---

## Role Interaction Summary

The following table summarizes key collaboration touchpoints between roles to support onboarding, knowledge sharing, and project coordination:

| Role | Primary Partners | Key Handoff / Touchpoint |
|---|---|---|
| Project Manager | Scrum Master, Product Manager, Release Manager | Delivery health, risk escalation, stakeholder updates |
| Product Manager | UX Designer, Data Analyst, Developers | Backlog prioritization, feature specs, success metrics |
| Scrum Master | Developers, Project Manager, Release Manager | Sprint ceremonies, impediment removal, release readiness |
| UX Designer | Product Manager, Developers | Design specs, usability reviews, accessibility standards |
| Data Analyst | Product Manager, Project Manager, Developers | KPI dashboards, feature impact analysis, sprint metrics |
| Release Manager | Developers, Project Manager, Scrum Master | Release checklists, deployment coordination, rollback plans |
| Developers | All roles | Implementation, code reviews, technical design docs |

---

## Escalation Path

When issues or blockers cannot be resolved at the team level, follow this escalation path:

1. **Team / Individual** → Raise impediment at daily standup or async channel
2. **Scrum Master** → Attempts to resolve within sprint; logs in impediment register
3. **Project Manager** → Escalates cross-team dependencies, resource constraints, or schedule risks
4. **Product Manager / Release Manager** → Escalates scope, priority, or release-readiness decisions
5. **Sponsor / Leadership** → Unresolved strategic, budget, or compliance issues

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the [Role Interaction Summary](#role-interaction-summary) table to understand cross-role dependencies when building Copilot Space context for multi-role scenarios.

