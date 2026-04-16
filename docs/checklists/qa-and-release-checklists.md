# QA & Release Checklists

Store checklists in project docs and reference them from PR templates and release notes.

---

## QA Checklist (pre-release)

- [ ] Acceptance criteria defined and linked to the issue
- [ ] Automated unit and integration tests added where applicable
- [ ] End-to-end or smoke tests defined for critical flows
- [ ] Acceptance test plan reviewed by QA Lead and BA
- [ ] Accessibility checklist applied to UI changes (WCAG basics)
- [ ] QA environments and test data prepared
- [ ] Test runs completed and results documented
- [ ] Open defects triaged and risk acknowledged
- [ ] QA sign-off recorded (name/date) before release

Suggested QA sign-off format:
- QA Lead: [name] — [date] — [notes / outstanding risks]

---

## Release Checklist (pre-deploy)

- [ ] All PRs merged and CI passing
- [ ] Security scans completed and issues triaged
- [ ] Rollback / mitigation plan reviewed
- [ ] Release notes drafted and linked to issue(s)
- [ ] Stakeholders notified of release window
- [ ] Post-deploy smoke tests defined
- [ ] Production monitoring & alerting confirmed
- [ ] Support runbook / on-call aware if needed
- [ ] Release sign-off: PM and PdM

Suggested Release sign-off format:
- PM: [name] — [date]
- PdM: [name] — [date]

---

## How to use these checklists
- Add the relevant checklist items to the issue or PR template for the project.
- For smaller teams, combine QA Lead and PM sign-off if one person covers both roles — but still record the sign-off to maintain auditability.
- Keep checklists updated as the team learns and adds more measures (e.g., security, performance).
