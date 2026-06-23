# Release checklist

Use this checklist to ensure consistency and safety when preparing and performing releases.

Pre-release
- [ ] All PRs merged that are part of the release
- [ ] Acceptance criteria met for each feature (PD/PM sign-off)
- [ ] Automated tests passing in CI (unit, integration)
- [ ] Security and dependency scans completed and no critical findings
- [ ] Release notes drafted and reviewed by Technical Writer
- [ ] Backup/snapshot plan in place if needed
- [ ] Release window scheduled and stakeholders notified
- [ ] Support and Customer Success notified with runbook and support content
- [ ] Instrumentation events defined and validated (Data Lead)

Staging verification
- [ ] Deploy to staging
- [ ] Run smoke tests and critical-path E2E tests
- [ ] Performance and basic load checks (if applicable)
- [ ] Accessibility quick-check for UI changes (if applicable)

Production deployment
- [ ] Deploy using automated pipeline and approved gating
- [ ] Post-deploy smoke tests executed
- [ ] Monitor key dashboards (errors, latency, usage)
- [ ] Confirm rollback plan is ready and tested
- [ ] Announce release to stakeholders and update status page/support channels

Post-release
- [ ] Validate success metrics (initial check)
- [ ] Collect and triage any customer feedback
- [ ] Schedule retrospective / capture lessons learned
