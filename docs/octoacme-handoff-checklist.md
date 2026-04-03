# OctoAcme — Handoff Checklist

## Purpose
Ensure clean, complete handoffs between project phases and teams. Each section captures the deliverables, approvals, and confirmations required before work passes to the next team.

## How to use this checklist
1. The **outgoing team** completes their section before declaring the handoff ready.
2. The **receiving team** reviews the checklist and confirms receipt in the project board or meeting notes.
3. Any unchecked items must be resolved or explicitly accepted as a known risk before proceeding.
4. Store completed checklists alongside sprint artifacts or release documentation.

---

## Phase 1: Product → Design Handoff

**Triggered when:** Product requirements are defined and ready for UX design to begin.

**Outgoing team:** Product Manager  
**Receiving team:** UX Designer

### Product Manager confirms:
- [ ] Problem statement and user needs are documented
- [ ] Success metrics and acceptance criteria are defined
- [ ] User personas / target audience are described
- [ ] Business and compliance constraints are listed
- [ ] Edge cases and out-of-scope items are noted
- [ ] Priority and timeline expectations are communicated

### UX Designer acknowledges:
- [ ] Requirements are understood; open questions logged
- [ ] Design kickoff scheduled
- [ ] Timeline for wireframes / prototype delivery agreed

---

## Phase 2: Design → Engineering Handoff

**Triggered when:** UX designs are reviewed and approved by the Product Manager.

**Outgoing team:** UX Designer  
**Receiving team:** Developers

### UX Designer confirms:
- [ ] Wireframes or high-fidelity mockups are finalized and stored (e.g., Figma link)
- [ ] Annotations and interaction notes are included
- [ ] Design assets (icons, images, tokens) are exported and accessible
- [ ] Responsive and accessibility requirements are documented
- [ ] Edge cases (empty states, error states, loading states) are designed
- [ ] Design review with Product Manager completed and approved
- [ ] Open design questions / known gaps are documented

### Developers acknowledge:
- [ ] Mockups and specs have been reviewed
- [ ] Technical feasibility concerns are raised and resolved
- [ ] Acceptance criteria for visual/interaction quality are agreed
- [ ] Implementation questions logged and addressed with UX Designer

---

## Phase 3: Engineering → QA Handoff

**Triggered when:** Feature development is complete and the code is merged to the test branch.

**Outgoing team:** Developers  
**Receiving team:** QA Engineers

### Developers confirm:
- [ ] All acceptance criteria from the backlog item are met
- [ ] Unit and integration tests are written and passing in CI
- [ ] Code has been reviewed and approved (PR merged)
- [ ] Known limitations or deferred items are documented in the ticket
- [ ] Feature is deployed to the test / staging environment
- [ ] Self-testing notes or test account details are provided

### QA Engineers acknowledge:
- [ ] Test environment is accessible and properly configured
- [ ] Test plan is ready (manual and/or automated cases)
- [ ] Testing start date and expected completion are confirmed
- [ ] Defect triage process and severity definitions are agreed

---

## Phase 4: QA → Release Manager Handoff

**Triggered when:** QA testing is complete and the feature/release is ready for deployment.

**Outgoing team:** QA Engineers  
**Receiving team:** Release Manager

### QA Engineers confirm:
- [ ] All critical and high-severity defects are resolved or accepted
- [ ] Regression test suite has passed
- [ ] Test summary report is prepared (pass/fail counts, known issues)
- [ ] Quality sign-off is formally approved
- [ ] Any outstanding defects that will ship are documented with mitigation

### Release Manager acknowledges:
- [ ] QA sign-off received and recorded
- [ ] Open defects reviewed; go/no-go decision is ready
- [ ] Release notes reviewed with Product Manager
- [ ] Deployment runbook is complete and reviewed
- [ ] Rollback plan is documented

---

## Phase 5: Release → Stakeholders Handoff (Go/No-Go Gate)

**Triggered when:** The Release Manager initiates the go/no-go meeting or async review.

**Outgoing team:** Release Manager  
**Receiving team:** Stakeholders, Product Manager, Project Manager

### Release Manager confirms:
- [ ] Release scope matches the agreed plan (or scope changes are documented)
- [ ] All pre-release requirements from the [Release & Deployment Guide](octoacme-release-and-deployment.md) are met
- [ ] Release notes are finalized and reviewed
- [ ] Deployment window is scheduled
- [ ] Support team is briefed
- [ ] Communication / announcement is drafted

### Stakeholders / Product Manager confirm:
- [ ] Release scope is accepted
- [ ] Any outstanding business risks are acknowledged
- [ ] Go/No-Go decision is recorded with date and participants

---

## Phase 6: Post-Release Handoff

**Triggered when:** Deployment to production is complete.

**Outgoing team:** Release Manager  
**Receiving team:** Project Manager, Support, Stakeholders

### Release Manager confirms:
- [ ] Deployment completed successfully (or rollback executed and documented)
- [ ] Post-deploy verification checks passed
- [ ] Release announcement sent to stakeholders and support

### Project Manager confirms:
- [ ] Success metrics monitoring is in place
- [ ] Retrospective scheduled (if end of release cycle)
- [ ] Outstanding action items from the release are tracked

---

## Related Documents
- [OctoAcme Roles and Personas](octoacme-roles-and-personas.md)
- [OctoAcme RACI Matrix Template](octoacme-raci-matrix-template.md)
- [OctoAcme Release & Deployment Guide](octoacme-release-and-deployment.md)
- [OctoAcme Project Planning](octoacme-project-planning.md)
- [OctoAcme Execution & Tracking](octoacme-execution-and-tracking.md)
