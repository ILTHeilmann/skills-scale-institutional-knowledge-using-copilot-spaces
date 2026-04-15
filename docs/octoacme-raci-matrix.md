# OctoAcme — RACI Responsibility Matrix

## Purpose
Map key project activities to roles so that ownership is unambiguous, handoffs are smooth, and no activity falls through the cracks.

## How to read this matrix

| Code | Meaning |
|------|---------|
| **R** | **Responsible** — does the work |
| **A** | **Accountable** — ultimately answerable for the outcome; approves the result |
| **C** | **Consulted** — provides input before or during the activity |
| **I** | **Informed** — kept up to date on progress or outcomes |

Each activity should have exactly one **A** (accountable) owner. Multiple roles can share **R**.

---

## RACI Matrix

| Activity | Project Manager | Product Manager | Developer | UX Designer | DevOps Engineer | QA Lead | Data Analyst | Stakeholders |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Initiation** | | | | | | | | |
| Draft project one-pager | R | A | C | C | I | I | C | I |
| Stakeholder alignment & sign-off | A | R | I | I | I | I | I | C |
| Define success metrics & KPIs | C | A | I | C | I | I | R | C |
| Identify initial risks & dependencies | A | C | C | C | C | C | C | I |
| **Planning** | | | | | | | | |
| Backlog grooming & prioritization | C | A | C | C | I | C | C | I |
| Define Definition of Ready (DoR) | A | R | R | C | C | R | C | I |
| Define Definition of Done (DoD) | A | R | R | C | R | R | I | I |
| Draft test strategy | C | C | C | I | C | A/R | I | I |
| UX design milestones & acceptance criteria | C | A | C | R | I | C | I | I |
| Release plan & milestone map | A | C | C | I | C | C | I | I |
| CI/CD and environment design | I | I | C | I | A/R | C | I | I |
| **Execution & Tracking** | | | | | | | | |
| Feature implementation | I | C | A/R | C | I | C | I | I |
| UX design reviews & handoff | I | C | C | A/R | I | C | I | I |
| Code reviews & merge readiness | I | I | A/R | C | C | C | I | I |
| Automated test suite maintenance | I | I | C | I | C | A/R | I | I |
| QA column ownership & defect triage | C | C | C | I | I | A/R | I | I |
| Pipeline maintenance & environment health | C | I | C | I | A/R | C | I | I |
| Risk register updates | A/R | C | C | I | C | C | C | I |
| Delivery metrics & dashboards | C | C | I | I | I | C | A/R | I |
| Weekly status reporting | A/R | C | I | I | I | C | C | I |
| **Release & Deployment** | | | | | | | | |
| Release readiness sign-off | A | C | C | I | C | R | C | I |
| Deployment execution | C | I | C | I | A/R | C | I | I |
| Staging smoke tests | C | I | C | I | C | A/R | I | I |
| Post-deploy verification | C | I | C | I | R | A/R | C | I |
| Release announcement | A/R | R | I | I | I | I | I | I |
| Rollback decision & execution | A | C | C | I | R | C | I | I |
| **Retrospective & Continuous Improvement** | | | | | | | | |
| Retrospective facilitation | A/R | C | C | C | C | C | C | I |
| Delivery & quality metrics review | C | C | C | I | C | C | A/R | I |
| Improvement action item ownership | A | C | R | C | C | C | C | I |
| Risk escalation (team-level) | R | C | R | I | R | R | I | I |
| Risk escalation (sponsor-level) | A/R | C | I | I | I | I | I | C |

---

## Role Reference

For full role descriptions, responsibilities, and interaction patterns see [Roles & Personas](octoacme-roles-and-personas.md).

## Related Docs

- [Project Initiation](octoacme-project-initiation.md) — one-pager, decision gate, kickoff checklist
- [Project Planning](octoacme-project-planning.md) — backlog, DoR/DoD, milestones
- [Execution & Tracking](octoacme-execution-and-tracking.md) — sprint workflow, board, standups
- [Release & Deployment](octoacme-release-and-deployment.md) — release checklist, deployment, rollback
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — retrospective format and action tracking
