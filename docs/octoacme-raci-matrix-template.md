# OctoAcme — RACI Matrix Template

## Purpose
Use this template to assign clear ownership for each project activity. Explicit accountability reduces ambiguity, prevents gaps, and makes it easy to see who to involve at each stage.

## How to use this template
1. Copy this table into your project's documentation or project board.
2. For each activity row, assign one letter per role column:
   - **R — Responsible:** Does the work to complete the activity.
   - **A — Accountable:** Owns the outcome; approves the deliverable. Only one per row.
   - **C — Consulted:** Provides input before or during the activity (two-way communication).
   - **I — Informed:** Kept up to date on progress and decisions (one-way communication).
3. Every row must have exactly one **A**. Rows with no **R** indicate a gap — assign an owner.
4. Rows with too many **R** or **A** designations indicate shared accountability — clarify who leads.

---

## RACI Matrix

| Activity | Project Manager | Product Manager | Developer | UX Designer | QA Engineer | Release Manager | Stakeholder |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Initiation & Planning** | | | | | | | |
| Define project charter / one-pager | R | A | C | C | I | I | C |
| Identify and onboard stakeholders | A | C | I | I | I | I | R |
| Define success metrics and OKRs | C | A | C | C | I | I | C |
| **Design & Requirements** | | | | | | | |
| Define product requirements | C | A | C | R | C | I | C |
| Create wireframes / UX prototypes | I | C | C | R/A | I | I | I |
| Conduct user research | I | C | I | R/A | I | I | C |
| Design review sign-off | I | A | C | R | I | I | I |
| **Development** | | | | | | | |
| Implement features | I | C | R/A | C | C | I | I |
| Code review | I | I | R/A | I | I | I | I |
| Write unit and integration tests | I | I | R/A | I | C | I | I |
| **Quality Assurance** | | | | | | | |
| Define test plan and test cases | C | C | C | C | R/A | C | I |
| Execute manual / automated tests | I | I | C | C | R/A | C | I |
| Log and triage defects | I | C | R | I | R/A | C | I |
| Quality sign-off / approval | I | C | I | I | R | A | I |
| **Release & Deployment** | | | | | | | |
| Draft release notes | C | R | C | I | C | A | I |
| Prepare deployment runbook | C | I | R | I | C | A | I |
| Go/No-Go decision | A | C | I | I | C | R | C |
| Execute deployment | I | I | R | I | C | A | I |
| Post-release verification | I | I | R | I | R | A | I |
| Announce release to stakeholders | C | C | I | I | I | R | A |
| **Ongoing / Operational** | | | | | | | |
| Update risk register | R/A | C | C | I | I | C | I |
| Stakeholder status reporting | R/A | C | I | I | I | C | I |
| Sprint retrospective facilitation | R/A | C | C | C | C | C | I |

> **Note:** R/A in the same cell means the same person is both responsible and accountable for that activity.

---

## Customization Tips
- Add or remove role columns as needed for your specific project team.
- For large programs, break the matrix into phases (Initiation, Delivery, Release) in separate tables.
- Store the completed RACI alongside your Project Charter in the repository.

## Related Documents
- [OctoAcme Roles and Personas](octoacme-roles-and-personas.md)
- [OctoAcme Handoff Checklist](octoacme-handoff-checklist.md)
- [OctoAcme Project Planning](octoacme-project-planning.md)
- [OctoAcme Release & Deployment Guide](octoacme-release-and-deployment.md)
