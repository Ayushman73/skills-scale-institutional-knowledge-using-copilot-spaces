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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.


## Additional Personas (proposed)

### UX Researcher / Designer
Role summary: Owns user research, design direction, and ensures solutions are usable and accessible.
Responsibilities:
- Run discovery and usability testing; synthesize findings into actionable design decisions.
- Produce wireframes, interaction specs, and accessibility guidance.
- Validate acceptance criteria from a user experience perspective.
Interactions:
- Works with Product Manager (PdM) and PM to shape requirements and acceptance criteria.
- Partners with Developers and QA to ensure designs are implemented correctly and accessibility standards are met.
When to involve:
- Discovery, planning, design reviews, and acceptance validation before release.

### Data / Measurement Lead
Role summary: Defines metrics, event instrumentation, and success measurement.
Responsibilities:
- Propose success metrics and dashboards; own instrumentation requirements.
- Validate analytics data and provide insights for prioritization.
- Define data quality checks for event tracking.
Interactions:
- Works with Product and PM to set success criteria and KPIs.
- Collaborates with Developers, SRE, and Release Engineer for event tracking and data pipelines.
When to involve:
- Early in planning to define success metrics and prior to development for instrumentation tasks.

### Release Engineer / DevOps
Role summary: Owns CI/CD pipelines, release automation, and deployment safety.
Responsibilities:
- Maintain deployment pipelines, rollback procedures, and release automation.
- Define staging and production verification steps and gating criteria.
Interactions:
- Works with Developers to ensure build and release readiness.
- Coordinates with PM for scheduling and with SRE for runbook integration.
When to involve:
- Planning for release, before first deploy to staging, and during release execution.

### QA Lead / Test Strategist
Role summary: Owns test strategy, automation coverage, and acceptance verification.
Responsibilities:
- Define test plans (unit, integration, E2E), acceptance criteria validation, and QA sign-off.
- Coordinate manual and automated testing efforts and triage test failures.
Interactions:
- Works with Developers to integrate tests in CI.
- Engages PM and Product to confirm acceptance criteria and release readiness.
When to involve:
- During backlog refinement, pre-sprint planning, and before release candidates.

### Customer Success / Support Liaison
Role summary: Represents customer-facing teams to help prioritize fixes, gather feedback, and communicate releases.
Responsibilities:
- Collect user feedback and escalate recurring issues.
- Validate release communications and support readiness (scripts, KBs).
Interactions:
- Feeds product and PM with customer impact insights.
- Coordinates with Technical Writer for support articles and release notes.
When to involve:
- Planning for releases that impact customers and during incident/feedback cycles.

### Technical Writer / Documentation Owner
Role summary: Owns user-facing documentation, release notes, and internal runbooks.
Responsibilities:
- Produce and maintain docs, onboarding guides, and release notes.
- Ensure content is accurate and published alongside releases.
Interactions:
- Works with Developers, PM, and Customer Success to collect changes and publish docs.
When to involve:
- During planning (to capture scope for docs), before release to finalize user-facing materials.

### Security / Compliance Representative
Role summary: Ensures security and regulatory requirements are considered during planning and release.
Responsibilities:
- Review designs for security implications, request security scans, and coordinate remediation.
- Maintain compliance checklists and sign-offs where applicable.
Interactions:
- Works with Developers, DevOps, and PM to prioritize fixes and include security gates in CI.
When to involve:
- At planning for high-risk features, before release for final security sign-off.

### Accessibility Lead (where relevant)
Role summary: Champions accessibility best practices and validation.
Responsibilities:
- Provide accessibility criteria and review designs and implementations.
- Coordinate accessibility testing and remediation.
Interactions:
- Works with UX, Developers, and QA to ensure compliance with accessibility standards.
When to involve:
- During design, implementation, and pre-release verification stages.


---

Each persona entry includes: Role summary, Responsibilities (bulleted), Interactions with existing roles (PM, PdM, Developers, QA, SRE), and guidance on "When to involve".
