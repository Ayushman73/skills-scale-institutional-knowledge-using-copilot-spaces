# QA and Testing Checklist

This checklist clarifies QA responsibilities, entry/exit criteria, and test-strategy items to reduce ambiguity during execution.

Entry criteria for an item to be considered QA-ready
- [ ] Acceptance criteria are documented on the issue or PR
- [ ] Unit tests and relevant integration tests are present
- [ ] Feature is deployed to a test or staging environment
- [ ] Test data and test accounts are available
- [ ] Automation cases for critical flows are added or updated

QA activities
- [ ] Execute automation suite for changed components
- [ ] Run manual test cases for edge cases and UX flows
- [ ] Perform regression checks for impacted areas
- [ ] Log reproducible issues with steps, environment, and severity

Exit criteria for QA sign-off
- [ ] All critical and high defects resolved or mitigated
- [ ] Acceptance criteria validated by QA and Product
- [ ] Automation for critical flows included in CI
- [ ] Test coverage and risk assessment documented
- [ ] QA sign-off recorded on the PR

Test strategy guidance
- Prioritize fast, reliable unit tests for business logic
- Use integration tests for cross-service contracts
- Keep E2E tests minimal and focused on critical paths
- Run flaky tests in isolation until stabilized
- Treat flaky tests as technical debt to be addressed
