# OctoAcme — Role Responsibility Matrix (RACI)

## Purpose
This matrix maps common project activities to roles and indicates who is **Responsible**, **Accountable**, **Consulted**, or **Informed** for each activity. Use it as guidance to clarify ownership and prevent gaps in accountability.

## RACI Key

| Letter | Meaning |
|--------|---------|
| **R** | **Responsible** — Does the work |
| **A** | **Accountable** — Owns the outcome; final decision-maker |
| **C** | **Consulted** — Provides input before or during the work |
| **I** | **Informed** — Notified of progress or completion |

> **Note:** This matrix is guidance, not a rigid rule. Teams should adapt role assignments to their context, size, and working agreements.

---

## Activity Matrix

| Activity | PM | PdM | Developer | QA | UX Designer | Scrum Master | Business Analyst | Technical Lead | Support Engineer | Legal / Finance |
|---|---|---|---|---|---|---|---|---|---|---|
| Define requirements | C | A | C | C | C | I | R | C | I | C |
| Prioritize backlog | C | A | C | I | C | I | R | C | I | I |
| Create UX designs | I | C | C | I | A/R | I | C | C | I | I |
| Implement feature | I | C | R | I | C | I | I | A | I | I |
| Write tests | I | I | R | A/R | I | I | C | C | I | I |
| QA / acceptance testing | I | C | C | A/R | C | I | C | C | I | I |
| Release planning | A | C | C | C | I | R | C | C | C | C |
| Deployment | C | I | R | C | I | I | I | A | I | I |
| Incident response | C | I | R | C | I | I | I | A | R | I |
| Compliance review | C | C | I | I | I | I | C | C | I | A/R |
| Stakeholder communications | A/R | C | I | I | I | I | C | I | C | C |

---

## Notes
- Where a cell shows **A/R**, the same role is both accountable and doing the hands-on work (common in smaller teams).
- Activities may span multiple sprints or require parallel effort from several roles simultaneously.
- For activities not listed, teams should agree on ownership at kickoff or sprint planning.

## Related Documents
- [Roles & Personas](octoacme-roles-and-personas.md)
- [Release & Deployment Checklist](octoacme-release-and-deployment-checklist.md)
