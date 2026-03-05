# OctoAcme — Release & Deployment Checklist

## Purpose
Provide a repeatable, role-assigned checklist for releasing and deploying OctoAcme features to production. Use this alongside the [Release & Deployment Guide](octoacme-release-and-deployment.md) and the [Role Responsibility Matrix](octoacme-role-responsibility-matrix.md).

---

## Pre-Release

| # | Checklist Item | Responsible |
|---|---|---|
| 1 | All acceptance criteria met and verified | PdM / Business Analyst |
| 2 | All PRs merged and CI pipeline green | Developer / Technical Lead |
| 3 | Security scans completed with no critical findings | Developer / Technical Lead |
| 4 | Dependency and license review completed | Technical Lead / Legal |
| 5 | Compliance review signed off (if applicable) | Legal / Finance / Compliance |
| 6 | Release notes drafted and reviewed | PM or PdM |
| 7 | User-facing documentation updated | Business Analyst / Developer |
| 8 | Rollback / mitigation plan documented | Technical Lead / Developer |
| 9 | Smoke tests prepared and ready to execute | QA |
| 10 | Deployment window scheduled and communicated | PM |
| 11 | Stakeholders notified of upcoming release | PM |
| 12 | Support team briefed on new features and known issues | PM / Support Engineer |

---

## Deployment

| # | Checklist Item | Responsible |
|---|---|---|
| 13 | Backup or snapshot taken (if applicable) | Developer / Support Engineer |
| 14 | Deploy to staging environment | Developer |
| 15 | Run smoke tests on staging | QA / Developer |
| 16 | Staging sign-off confirmed | QA / PdM |
| 17 | Deploy to production (automated pipeline preferred) | Developer / Technical Lead |
| 18 | Verify deployment succeeded (pipeline status, health checks) | Developer / Technical Lead |

---

## Post-Release

| # | Checklist Item | Responsible |
|---|---|---|
| 19 | Run post-deploy smoke tests in production | QA / Developer |
| 20 | Monitor error rates and alerts for at least 1 hour | Support Engineer / Developer |
| 21 | Confirm key metrics are within expected range | PdM / Technical Lead |
| 22 | Stakeholder notification sent (release complete) | PM |
| 23 | Release notes published (changelog / release page) | PM or PdM |
| 24 | Incident response activated if issues detected | Technical Lead / Support Engineer |
| 25 | Post-release retrospective scheduled (for major releases) | PM / Scrum Master |

---

## Notes
- Use the [RACI Matrix](octoacme-role-responsibility-matrix.md) for broader guidance on role ownership across project activities.
- Adapt this checklist to the release type (Patch / Minor / Major). Not every item is required for a small patch.
- Document any deviations from this checklist and rationale in the project log.

## Related Documents
- [Roles & Personas](octoacme-roles-and-personas.md)
- [Role Responsibility Matrix](octoacme-role-responsibility-matrix.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
