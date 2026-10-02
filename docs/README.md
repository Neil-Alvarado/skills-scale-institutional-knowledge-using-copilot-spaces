# OctoAcme Project Management Documentation

## Overview

OctoAcme follows a structured project management methodology designed to deliver customer value through iterative, transparent, and data-informed practices. Our approach emphasizes clear ownership, psychological safety, and continuous improvement across all cross-functional projects.

### Core Principles
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

### Project Lifecycle

OctoAcme's project lifecycle consists of seven key phases:

1. **Project Initiation** — Establish business need, success metrics, stakeholders, and high-level timeline. Move to planning when metrics are clear and stakeholder alignment is confirmed.

2. **Project Planning** — Turn approved initiatives into actionable plans by creating prioritized backlogs, defining acceptance criteria, identifying dependencies, and establishing release milestones.

3. **Execution and Tracking** — Execute day-to-day work through sprints or iterations with regular standups, demos, and quality validation. Track velocity, burndown, and success metrics while escalating blockers.

4. **Risk Management and Communication** — Identify and manage risks through a visible register, maintain stakeholder communication via regular updates, and escalate issues through defined paths (team → PM → product lead → sponsor).

5. **Release and Deployment** — Standardize how features move to production by verifying acceptance criteria, passing CI/security scans, preparing rollback plans, and conducting post-deployment verification.

6. **Retrospectives and Continuous Improvement** — Capture learnings after each sprint or release, convert them into actionable improvements, and measure the impact of changes over time.

7. **Roles and Personas** — Define and clarify responsibilities for Developers, Product Managers, Project Managers, QA/Testing, and Stakeholders to ensure accountability and alignment.

### Communication Cadence
- Daily standups (15 min) — progress, blockers, dependencies
- Weekly delivery sync — progress updates and flagged risks
- Weekly PM + Product Manager alignment
- Monthly stakeholder updates
- Ad-hoc escalations as needed

### Key Quality Practices
- Unit tests for new logic and integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed
- Small PRs (≤ 400 lines when possible) with at least one approval before merging
- Automated CI for tests and linting

---

## Documentation

### Core Methodology
- [**Project Management Overview**](./octoacme-project-management-overview.md) — Introduction to OctoAcme's approach, core roles, key artifacts, and lifecycle

### Phase-Specific Guides
- [**Project Initiation**](./octoacme-project-initiation.md) — Validate and authorize work, align stakeholders, and create a lightweight initial plan
- [**Project Planning**](./octoacme-project-planning.md) — Break work into shippable increments, identify dependencies, and align timelines
- [**Execution and Tracking**](./octoacme-execution-and-tracking.md) — Manage day-to-day execution, track progress, and escalate blockers
- [**Risks and Communication**](./octoacme-risks-and-communication.md) — Identify and manage risks, communicate with stakeholders, and escalate issues
- [**Release and Deployment**](./octoacme-release-and-deployment.md) — Standardize the release process and reduce deployment risk
- [**Retrospective and Continuous Improvement**](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into actionable improvements

### People & Roles
- [**Roles and Personas**](./octoacme-roles-and-personas.md) — Understand responsibilities and communication patterns for Developers, Product Managers, Project Managers, QA/Testing, and Stakeholders

---

## Getting Started

1. **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) to understand our principles and roles.

2. **Starting a new project?** Follow the [Project Initiation](./octoacme-project-initiation.md) guide to create a one-pager and confirm stakeholder alignment.

3. **Looking for a specific process?** Use the phase-specific guides above to find guidance for your current project stage.

4. **Want to improve our processes?** Check the [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) guide, then create an issue using the [Process Doc Update template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml).

---

## Contributing to This Documentation

To propose updates or new content:
1. Open an issue using the [Add Content to Project Management Process Docs template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)
2. Describe the content, rationale, and suggested text
3. Ensure alignment with existing process docs and stakeholder input where needed
4. Submit a pull request with your updates

This documentation represents our team's collective knowledge and evolves as we learn and improve. Your contributions help us stay sharp and support future team members.
