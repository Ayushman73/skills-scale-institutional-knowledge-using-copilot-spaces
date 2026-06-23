# OctoAcme Project Management Docs

This README provides a brief summary of the project management processes used by OctoAcme and links to the individual process documents in the docs/ folder.

## OctoAcme Project Management Overview

OctoAcme operates a structured, customer-first project lifecycle that emphasizes iterative delivery, clear ownership, and data-informed decisions. The approach spans five core phases—**Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**—with the organization maintaining a "psychological safety" culture that encourages feedback and treats setbacks as learning opportunities.

**Core Roles and Responsibilities** are distributed across four primary personas. **Project Managers (PMs)** coordinate delivery activities, manage schedules, risks, and stakeholder communications—ensuring projects stay on time and within scope. **Product Managers (PdMs)** define what should be built by establishing problem statements, prioritizing the backlog, and measuring outcomes against success metrics. **Developers** implement features with high-quality code, tests, and documentation while collaborating on design and identifying technical risks. **QA/Testing teams** validate that acceptance criteria are met and quality standards are upheld. This distributed ownership model is reinforced by weekly syncs between PM and PdM, twice-weekly standups for delivery teams, and monthly stakeholder updates.

**Execution and Quality Assurance** are tightly integrated into OctoAcme's day-to-day operations. Teams use GitHub Projects boards with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) to track progress, maintain small PRs (≤400 lines), and require automated CI testing, linting, and at least one approval before merging. Quality is ensured through unit tests for new logic, integration tests where applicable, end-to-end smoke tests before release, and security scanning in CI pipelines. A three-level escalation path—from team-level triage in standups, to PM escalation with Product Lead and dependent teams, to sponsor-level escalation for business-impacting issues—keeps risks visible and actionable.

Finally, **Risk Management and Communication** form the backbone of stakeholder alignment. OctoAcme maintains a living Risk Register (tracking ID, description, impact, likelihood, owner, and mitigation plan) that is reviewed weekly during syncs. Communication strategies are tailored to different audiences: weekly status templates for stakeholders (progress, next steps, risks, decisions needed), incident communication playbooks for rapid response, and clear escalation paths for security incidents and critical blockers. This emphasis on transparency, combined with retrospectives after each sprint or milestone, ensures that process improvements flow directly back into updated documentation and future iterations.

## Process Summary

- **Initiation**: Capture the problem, stakeholders, success metrics, and a lightweight one-pager to decide go/no-go.
- **Planning**: Turn an approved initiative into a prioritized backlog, estimates, and a release plan with clear acceptance criteria.
- **Execution & Tracking**: Day-to-day delivery practices (standups, PR conventions, CI, project board workflow) and tracking (velocity, burndown).
- **Release & Deployment**: Pre-release checks, deployment checklist, smoke tests, rollback plan, and release notes.
- **Retrospective & Continuous Improvement**: Regular retrospectives, action items tracked to closure, and measured impact.
- **Risk & Communication**: Maintain a risk register, stakeholder updates, and escalation paths.

## Docs Index

- [**Project Management Overview**](octoacme-project-management-overview.md) — Concise intro: roles, cadence, and key artifacts.
- [**Project Initiation Guide**](octoacme-project-initiation.md) — One-pager template, initiation checklist, decision gate.
- [**Project Planning**](octoacme-project-planning.md) — Backlog templates, estimation, release planning, and risk capture.
- [**Execution & Tracking**](octoacme-execution-and-tracking.md) — Team rhythm, workflows, PR guidance, CI and reporting.
- [**Release & Deployment**](octoacme-release-and-deployment.md) — Release types, deployment checklist, rollback playbook.
- [**Retrospective & Continuous Improvement**](octoacme-retrospective-and-continuous-improvement.md) — Retrospective structure and action tracking.
- [**Risk Management & Communication**](octoacme-risks-and-communication.md) — Risk register, communication templates, escalation paths.
- [**Roles & Personas**](octoacme-roles-and-personas.md) — Role definitions and responsibilities used across docs.

## How to Use

1. **Browse this index** to find the doc you need.
2. **Use the project one-pager** to propose new initiatives and follow the planning checklist to prepare work.
3. **Follow the Execution & Tracking guidelines** (project board, PR conventions, CI) during delivery.
4. **Use the release checklist and retrospective guidance** to close work and capture improvements.

## Contributing

If you have suggested edits or want to add a new process doc, use the repository issue template **"Add Content to Project Management Process Docs"** to propose changes.
