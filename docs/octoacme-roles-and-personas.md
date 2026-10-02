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

## QA/Testing Lead

### Role Summary
QA/Testing Leads define and execute quality strategies, manage acceptance testing, and ensure deliverables meet quality standards before release.

### Responsibilities
- Define test plans and acceptance criteria validation approach
- Coordinate manual and automated testing efforts
- Identify and triage quality issues and regression risks
- Create smoke test scenarios for pre-release verification
- Report quality metrics and blockers to the Project Manager and delivery team
- Participate in retrospectives to improve the testing process

### Goals
- Prevent defects from reaching production
- Enable fast, confident releases through comprehensive test coverage
- Maintain clear quality standards and acceptance criteria compliance

### Typical Communication
- Sprint planning and acceptance criteria review
- Daily standups with blockers and test status
- Quality reports and test coverage metrics
- Pre-release and post-release verification sign-off

### How this role interacts with existing personas
- Works with Developers to ensure features are testable and regression risks are identified early.
- Partners with Product Managers to validate that user stories and acceptance criteria are testable and measurable.
- Provides Project Managers with quality status, risk signals, and release-readiness information.
- Helps Stakeholders understand the quality and delivery confidence of releases.

---

## Sponsor / Stakeholder

### Role Summary
Sponsors and Stakeholders provide business context, prioritization, and approval authority. They ensure projects align with organizational goals and have the necessary support to succeed.

### Responsibilities
- Define business drivers and success metrics for the project
- Provide approvals at key decision gates
- Participate in kickoff and planning sessions
- Review and approve release communications and major milestones
- Escalate resource or priority conflicts when needed
- Provide ongoing feedback on business impact and strategic alignment

### Goals
- Ensure the project delivers measurable business value
- Maintain alignment between delivery work and strategic priorities
- Enable teams with clear requirements, resources, and decision authority

### Typical Communication
- Monthly stakeholder updates and status reports
- Project initiation and planning gates
- Milestone reviews and release announcements
- Ad-hoc escalations on budget, scope, or priority changes

### How this role interacts with existing personas
- Collaborates with Product Managers to confirm priorities, scope trade-offs, and expected outcomes.
- Works with Project Managers to align delivery schedules, milestones, and stakeholder communications.
- Provides business context and approval signals for Developers and Technical Leads to understand the intent behind the work.
- Coordinates with Security and Compliance stakeholders when business decisions affect risk, governance, or policy.

---

## Security / Compliance Officer

### Role Summary
Security and Compliance Officers ensure that projects meet security, privacy, and compliance requirements. They review designs and implementations for risk mitigation and governance.

### Responsibilities
- Review project designs for security and compliance risks
- Define security requirements and scanning standards
- Participate in threat modeling and risk assessments
- Validate that CI includes security scanning and control checks
- Review code and deployment practices for compliance expectations
- Triage and coordinate incident response for security issues
- Provide guidance on data handling, privacy, and policy requirements

### Goals
- Prevent security vulnerabilities and compliance violations
- Enable secure-by-design project execution
- Reduce breach risk and regulatory exposure

### Typical Communication
- Project planning and design reviews
- CI/CD security requirement validation
- Incident response and escalation updates
- Quarterly security and compliance audits

### How this role interacts with existing personas
- Works with Developers and Technical Leads to review architecture, implementation risks, and secure coding practices.
- Advises Project Managers on compliance checkpoints, security dependencies, and escalation paths.
- Supports Product Managers by clarifying risks and constraints that affect roadmap or release decisions.
- Collaborates with Sponsors and Stakeholders to ensure strategic priorities remain aligned with organizational risk tolerance.

---

## Technical Lead / Architect

### Role Summary
Technical Leads provide architectural guidance, mentor developers, and ensure technical decisions align with long-term system health, scalability, and maintainability goals.

### Responsibilities
- Guide architectural decisions and design reviews
- Mentor and coach developers on technical best practices
- Identify technical debt, scalability risks, and dependency constraints
- Collaborate with Product and Project leads on trade-offs related to scope and timeline
- Participate in estimation and capacity planning
- Ensure cross-team technical consistency and integration quality
- Champion testing, documentation, and code quality standards

### Goals
- Maintain system reliability, performance, and maintainability
- Enable rapid, sustainable feature delivery
- Develop team technical capability and ownership

### Typical Communication
- Technical design reviews and architecture discussions
- Sprint planning and estimation sessions
- Code reviews and mentoring conversations
- Technical spike investigations and feasibility studies

### How this role interacts with existing personas
- Partners with Developers to translate product intent into a maintainable technical approach.
- Advises Product Managers on feasibility, sequencing, and technical trade-offs during planning.
- Supports Project Managers by clarifying dependencies, risk areas, and implementation complexity.
- Coordinates with Security and Compliance Officers to ensure technical decisions meet required controls and policy standards.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Together, these personas help clarify accountability, decision rights, and collaboration patterns across the full project lifecycle.
