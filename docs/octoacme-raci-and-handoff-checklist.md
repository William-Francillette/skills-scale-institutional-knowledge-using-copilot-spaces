# OctoAcme RACI & Handoff Checklist

This document provides a cross-role responsibilities matrix (RACI) and practical handoff checklists to reduce ambiguity and improve accountability across the project lifecycle.

For full role definitions see [Roles & Personas](octoacme-roles-and-personas.md).

---

## RACI Matrix

**Key:** R = Responsible | A = Accountable | C = Consulted | I = Informed

| Activity | Project Manager | Product Manager | Developer | QA Engineer | UX/UI Designer | DevOps/SRE | Stakeholder | Sponsor |
|---|---|---|---|---|---|---|---|---|
| Define business goals & success metrics | C | A/R | I | I | I | I | C | A |
| Draft Project Charter / One-pager | R | A | I | I | I | I | C | A |
| Stakeholder alignment & sign-off | R | C | I | I | I | I | A | A |
| Prioritize backlog | C | A/R | C | C | C | C | I | I |
| Define acceptance criteria | C | A/R | R | C | C | I | I | I |
| Design (UX/UI) | I | A | C | I | R | I | C | I |
| Technical design & estimation | C | C | A/R | C | C | C | I | I |
| Sprint / iteration planning | R | C | R | C | I | C | I | I |
| Implementation | I | I | A/R | I | I | I | I | I |
| Code review | I | I | A/R | I | I | I | I | I |
| Test plan creation | C | C | C | A/R | I | I | I | I |
| Feature testing / QA sign-off | I | I | C | A/R | I | I | I | I |
| CI/CD pipeline & deployments | C | I | C | C | I | A/R | I | I |
| Release readiness sign-off | A/R | C | C | C | I | C | I | I |
| Stakeholder communication & status | A/R | C | I | I | I | I | I | I |
| Risk identification & management | A/R | C | C | C | I | C | I | I |
| Incident response | C | I | C | I | I | A/R | I | I |
| Retrospective facilitation | A/R | C | C | C | C | C | I | I |
| Action item ownership (retro) | C | C | R | R | R | R | I | I |

---

## Project Kickoff Checklist

Use this checklist at the start of each new project to confirm all roles are aligned and key inputs are in place before execution begins.

### Before Kickoff

- [ ] Project Charter / One-pager drafted and reviewed by Product Manager and Sponsor
- [ ] Stakeholder list identified and communication plan agreed
- [ ] Success metrics and Definition of Done documented
- [ ] Delivery team roles named (PM, PdM, Dev Lead, QA Lead, UX Lead, DevOps contact)
- [ ] Initial risk list captured
- [ ] High-level timeline and milestones agreed

### Kickoff Meeting Agenda

- [ ] Present project goals, success metrics, and scope
- [ ] Confirm team roles and accountabilities (reference RACI above)
- [ ] Review high-level timeline and known constraints
- [ ] Walk through initial risk list and dependencies
- [ ] Agree on communication cadence (standups, syncs, stakeholder updates)
- [ ] Confirm tooling (project board, repo, design tool, CI pipeline)
- [ ] Capture open questions and assign owners

### After Kickoff

- [ ] Meeting notes published and shared with all participants
- [ ] Project board created with initial backlog items
- [ ] RACI distributed to team and acknowledged
- [ ] First sprint / iteration planned
- [ ] Risk register created in project docs

---

## Handoff Checklists

### Product Manager → Developer Handoff (Feature Kickoff)

Use when a backlog item is ready for development.

- [ ] Acceptance criteria written, reviewed, and complete
- [ ] UX/UI designs attached or linked (if applicable)
- [ ] Business context and user impact documented
- [ ] Edge cases and out-of-scope items explicitly noted
- [ ] QA notified and test plan initiated
- [ ] Dependencies and blockers identified
- [ ] Priority and sprint assignment confirmed

---

### Developer → QA Handoff (Feature Ready for Testing)

Use when a feature is complete and ready for QA validation.

- [ ] All acceptance criteria implemented
- [ ] Unit and integration tests written and passing in CI
- [ ] PR merged to the agreed test branch
- [ ] Test environment deployed and verified
- [ ] Known issues or limitations documented in the PR / ticket
- [ ] UX/UI implementation reviewed against design specs
- [ ] QA notified with a brief summary of what was built and what to focus on

---

### QA → Project Manager Handoff (Release Readiness)

Use when QA has completed testing and release sign-off is pending.

- [ ] All test cases executed and results recorded
- [ ] All critical and high-severity defects resolved or have accepted workarounds
- [ ] Regression suite passed
- [ ] Test summary report shared with PM and PdM
- [ ] Open defects logged with severity and owner
- [ ] Sign-off documented (QA lead name + date)

---

### Project Manager → DevOps Handoff (Deployment)

Use when a release is approved and ready to deploy.

- [ ] Release notes drafted and reviewed
- [ ] Rollback plan documented
- [ ] Deployment window scheduled (if needed)
- [ ] Stakeholders notified of planned release
- [ ] Any required change-management approvals obtained
- [ ] Post-deploy verification plan (smoke tests) agreed with QA
- [ ] On-call / incident response contact confirmed for deployment window

---

### DevOps → Project Manager Handoff (Post-Deployment)

Use after a deployment completes.

- [ ] Deployment status confirmed (success / partial / failed)
- [ ] Post-deploy smoke tests completed and results shared
- [ ] Monitoring and alerting verified for the new release
- [ ] Any incidents or anomalies documented
- [ ] Rollback triggered (if applicable) with incident ticket raised
- [ ] Stakeholder announcement sent (or handed back to PM to send)

---

## See Also

- [Roles & Personas](octoacme-roles-and-personas.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
