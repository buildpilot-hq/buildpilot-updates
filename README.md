# BuildPilot Partner Dashboard

Updated November 24, 2026

## BuildPilot overview

BuildPilot is being developed as a workspace for residential contractors. The goal is to help office and field teams manage projects, schedules, documents, inspections, and follow-up work in one place. Each contractor will have a separate company workspace.

## Current development status

Accepted for local development. Browser security verification, browser-level network capture, and live cloud-console verification remain pending. No live application services have been activated or deployed.


## Latest completed milestone

**Phase 1.4E Part 1 — Cloud Development Foundation** was formally accepted on November 24, 2026.

BuildPilot established an isolated cloud-development foundation for its contractor workspace. The implementation supports authenticated sessions, company- and project-scoped access, and a shared workspace experience across local and cloud-development builds. Automated local tests validated the foundation and preserved existing contractor workspace functionality.


## Completed milestones

| Milestone | What it established |
| --- | --- |
| Phase 1.2 — Workspace navigation | Accepted local previews show how office and field staff could move through BuildPilot on desktop and mobile. |
| Phase 1.3 — Development foundation | Accepted setup for building and testing future account and project capabilities in a controlled environment. |
| Phase 1.4A — Account and access design | Accepted design for sign-in, company roles, and who can manage access. |
| Phase 1.4B — Local sign-in prototype | Accepted prototype lets test users sign in and out. Password recovery and account email workflows are planned for a later stage. |
| Phase 1.4C — Company separation design | Accepted design for keeping company information separate and giving team members access to assigned work. |
| Phase 1.4C Part 1 — Company and project access foundation | Accepted local validation of company access boundaries and project permissions using sample data. |
| Phase 1.4C Part 2 — Access checks after permission changes | Accepted local validation that new requests are blocked after access is withdrawn, while separately authorized work remains accessible. |
| Phase 1.4C Part 3 — Clearing open project information | Accepted local prototype validation that open project information clears when access is withdrawn. |
| Phase 1.4D Part 1 — Secure administrator setup and platform access | Accepted local testing verified that platform administration was restricted to authorized administrators. |
| Phase 1.4D Part 2 — Contractor company and user account provisioning | Accepted local testing verified controlled setup of contractor workspaces and user accounts, with access assigned separately for each company. |
| Phase 1.4D Part 3 — Company membership and ownership management | Accepted local testing verified changes to team membership and company ownership while keeping each contractor’s access separate. |
| Phase 1.4D Part 3 — Concurrent membership reliability improvement | Accepted local testing verified that membership records stayed consistent when administrators tried to make changes at the same time. |
| Phase 1.4D Part 4 Slice 1 — Account suspension and access containment | Accepted local testing verified that suspending an account blocked BuildPilot access across companies while preserving its company membership records. |
| Phase 1.4D Part 4 Slice 2 — Coordinated authentication account changes | Accepted local testing verified that an older account change could not undo a newer approved change. |
| Phase 1.4D Part 4 Slice 3A — Account Disablement and Session Revocation | BuildPilot added administrative controls to disable a user account and revoke its ability to renew sign-in sessions, with an audit trail for those actions. The work also added safeguards against duplicate or interrupted operations and verified that company data remained isolated and existing memberships were preserved. |
| Contractor Workspace — Slice 2C: Restricted Trade Information | BuildPilot now supports restricted trade information within contractor project workspaces. Access is independently controlled by company, project, and resource-level permissions. The implementation passed local authorization testing and owner visual review, including authorized, empty, and restricted-access scenarios. |
| Phase 1.4E Part 1 — Cloud Development Foundation | BuildPilot established an isolated cloud-development foundation for its contractor workspace. The implementation supports authenticated sessions, company- and project-scoped access, and a shared workspace experience across local and cloud-development builds. Automated local tests validated the foundation and preserved existing contractor workspace functionality. |


## What's next

Validate browser security and cloud-development readiness before any hosted deployment, while continuing the remaining account security and recovery work.


## High-level roadmap

1. **Prepare for a pilot.** Finish access checks, controlled account setup, and live pilot readiness review.
2. **Build contractor workflows.** Planned priorities include project coordination, scheduling, inspections, deficiency tracking, and documents for office and field teams.
3. **Expand collaboration.** Estimating and budgets, subcontractor coordination, client access, and warranty follow-up are planned areas for later milestones.

## Important decisions and outstanding considerations

- Company information stays separate. Access is based on each person's role and assigned work.
- Internal inspection records will be kept distinct from official municipal or regulatory approvals.
- Browser checks remain open, including checks that existing features still work and a review of where the browser sends requests. Software security follow-ups also remain open. Live pilot timing depends on readiness checks and separate owner approval.

<!-- BuildPilot publication: 5 sha256:8471228560445c4cb02ecc43640caf3418a83fd23814d6d9a5f716ff9d2ca405 -->
