# OctoAcme — Cross-Functional Handoffs Checklist

## Purpose
Provide lightweight, actionable checklists for the most common handoff points between roles in the OctoAcme delivery lifecycle. Using these checklists reduces dropped context, clarifies ownership, and accelerates delivery.

Refer to [Roles and Personas](octoacme-roles-and-personas.md) for role definitions and [Project Planning](octoacme-project-planning.md) for the broader planning process.

---

## 1. Product → UX Design Handoff
**Trigger:** Feature or initiative approved for design exploration.

- [ ] Problem statement and success metrics documented and shared
- [ ] User personas or target segments identified
- [ ] Known constraints (technical, timeline, compliance) communicated
- [ ] Design brief or kick-off meeting held between Product Manager and UX Designer
- [ ] Acceptance criteria drafted (or co-created with UX Designer)

---

## 2. UX Design → Engineering Handoff
**Trigger:** Designs are finalized and ready for development sprint.

- [ ] Annotated mockups or design specs delivered (e.g., Figma links)
- [ ] Interaction states and edge cases documented
- [ ] Design system components called out; deviations noted
- [ ] Open design questions resolved or tracked as follow-ups
- [ ] UX Designer available for questions during development sprint

---

## 3. Engineering → QA Handoff
**Trigger:** Feature implementation is complete and ready for testing.

- [ ] Acceptance criteria reviewed and confirmed by Developer and QA
- [ ] Test environment available and populated with representative data
- [ ] Known limitations or out-of-scope items documented
- [ ] Build or PR flagged as ready-for-test in project board
- [ ] QA test plan exists and covers happy path + edge cases

---

## 4. QA → Release / DevOps Handoff
**Trigger:** QA sign-off complete; release candidate is approved.

- [ ] QA sign-off documented (test report or go/no-go entry)
- [ ] Release notes drafted with feature summary and known issues
- [ ] Rollback plan reviewed and confirmed with DevOps Engineer
- [ ] Feature flags or environment configuration changes communicated
- [ ] Deployment window agreed with Project Manager and DevOps Engineer

---

## 5. Release → Customer Success Handoff
**Trigger:** Feature is live in production.

- [ ] Customer Success Lead briefed on new feature before release
- [ ] User-facing documentation or release notes shared
- [ ] Onboarding scripts or training materials updated
- [ ] Support escalation path documented (who to contact for incidents)
- [ ] First-week feedback loop agreed (Customer Success Lead reports back to Product)

---

## 6. Retrospective → Data Analyst Handoff
**Trigger:** Sprint or project retrospective is complete.

- [ ] Key metrics or KPIs for the release identified
- [ ] Data Analyst briefed on what to measure and success thresholds
- [ ] Dashboard or report scheduled for next planning cycle
- [ ] Action items from retrospective captured and owners assigned

---

## Notes
- Each checklist item should be tracked in the project board or meeting notes — not just verbally acknowledged.
- If a step is blocked or skipped, document the reason and the agreed mitigation.
- These checklists are living documents; teams should adapt them to their cadence and tooling.
