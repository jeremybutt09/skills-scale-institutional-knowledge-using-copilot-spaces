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

## User Experience (UX) Designer

### Role Summary
UX Designers ensure that products are usable, accessible, and aligned with user needs. They translate product requirements into wireframes, prototypes, and design specifications that guide development.

### Responsibilities
- Conduct user research, usability testing, and feedback sessions
- Deliver wireframes, mockups, and interactive prototypes
- Define and maintain design systems and UI standards
- Review implemented features for design fidelity
- Document UX decisions and rationale for future reference

### Goals
- Improve usability and accessibility of the product
- Ensure design consistency across features and releases
- Reduce development rework caused by unclear UI/UX requirements

### Typical Communication
- Design reviews and critique sessions with developers and Product Managers
- Handoff documentation (e.g., annotated mockups, component specs)
- User research summaries shared with the broader team

### Interactions
- **Product Managers:** Receives product requirements and success metrics; provides design concepts for feedback and prioritization alignment.
- **Developers:** Hands off annotated mockups and specs; clarifies design intent during implementation; reviews pull requests for visual/UX correctness.
- **Stakeholders:** Shares user research findings and design rationale during milestone reviews.
- **QA Engineers:** Collaborates on acceptance criteria for visual and interaction quality; QA references design specs when validating UI.
- **Project Managers:** Provides status on design deliverables; flags dependencies or blockers that affect the timeline.

---

## Stakeholder

### Role Summary
Stakeholders are individuals or groups with a vested interest in the project's outcomes. They provide business context, approve key decisions, and ensure that the delivered product meets organizational goals.

### Responsibilities
- Provide business requirements and constraints
- Review and approve major milestones, scope changes, and release decisions
- Surface strategic priorities or risks from their domain
- Participate in demos and sign-off meetings

### Goals
- Ensure the project delivers business value and meets organizational objectives
- Maintain visibility into progress, risks, and trade-offs
- Enable timely decisions to unblock the team

### Typical Communication
- Monthly stakeholder updates from the Project Manager
- Milestone review meetings with demos
- Escalation briefings for scope, risk, or timeline changes

### Interactions
- **Project Managers:** Primary point of contact for updates, escalations, and approval requests.
- **Product Managers:** Collaborates on roadmap priorities and business requirements; reviews feature specs at key milestones.
- **Developers:** Participates in demos; provides feedback during review sessions (not day-to-day).
- **UX Designers:** Reviews design proposals that affect brand, compliance, or business processes.
- **Release Managers:** Approves go/no-go decisions before major releases.

---

## QA Engineer

### Role Summary
QA Engineers own the overall quality assurance strategy and execution for a project. They design and run test plans, identify defects, and validate that features meet acceptance criteria before release — complementing (but distinct from) developer unit and integration testing.

### Responsibilities
- Design and maintain manual and automated test plans and test suites
- Validate features against acceptance criteria and Definition of Done
- Perform regression, integration, and end-to-end testing
- Log, track, and prioritize defects; collaborate with developers on resolution
- Ensure testability of new features by reviewing requirements early
- Provide a quality sign-off before each release

### Goals
- Prevent defects from reaching production
- Reduce regression risk during iterative delivery
- Improve confidence in release readiness

### Typical Communication
- Test plans shared with the team at sprint start
- Defect reports and status updates in the project board
- Quality sign-off communicated to the Release Manager and Project Manager

### Interactions
- **Developers:** Reviews acceptance criteria with developers early; reports defects and collaborates on root cause analysis and fixes.
- **Product Managers:** Aligns on acceptance criteria and edge cases; confirms when features are ready for acceptance testing.
- **UX Designers:** References design specs and prototypes to validate visual and interaction correctness.
- **Release Managers:** Provides quality sign-off and test summary before release gate; flags any open critical defects.
- **Project Managers:** Reports on QA progress, blockers, and readiness against the timeline.

---

## Release Manager

### Role Summary
Release Managers coordinate all activities required to ship a product release. They own the release plan, track readiness across teams, and manage communication and checklists to ensure smooth, low-risk deployments.

### Responsibilities
- Create and maintain the release plan and deployment schedule
- Coordinate readiness across Development, QA, and Operations
- Ensure release notes, runbooks, and rollback plans are prepared
- Facilitate the go/no-go decision with key stakeholders
- Oversee deployment execution and post-release verification
- Manage release communication to stakeholders and support teams

### Goals
- Ship releases on schedule with minimal production incidents
- Ensure all teams are aligned and prepared before deployment
- Maintain a clear audit trail of release decisions and approvals

### Typical Communication
- Release status updates in the project board and via weekly sync
- Go/no-go meeting agenda and outcome notes
- Release notes and post-release announcements to stakeholders and support

### Interactions
- **Developers:** Confirms that all code is merged, builds are green, and release artifacts are ready.
- **QA Engineers:** Receives quality sign-off and outstanding defect summary before authorizing release.
- **Product Managers:** Aligns on release scope and communicates feature availability; reviews release notes.
- **Stakeholders:** Presents go/no-go decision and obtains approvals for major releases.
- **Project Managers:** Coordinates release milestones with the overall project schedule; escalates blockers that threaten the release date.
- **UX Designers:** Confirms that design-related acceptance criteria are met before release.

---

## Supporting Process Artifacts

To complement these role definitions and improve cross-role accountability, the following documents are available:

- **[RACI Matrix Template](octoacme-raci-matrix-template.md):** Use this template to assign Responsible, Accountable, Consulted, and Informed designations for each project activity across all roles.
- **[Handoff Checklist](octoacme-handoff-checklist.md):** A phase-by-phase checklist ensuring clean handoffs between Product, Design, Engineering, QA, and Release.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

