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

## Release Manager

### Role Summary
The Release Manager coordinates a release's readiness, execution, rollback options, and stakeholder communications.

### Responsibilities
- Plan release windows and confirm deployment readiness
- Coordinate release approvals and rollback or mitigation plans
- Track release dependencies and unresolved go/no-go issues
- Communicate release status, timing, and changes to stakeholders

### Goals
- Deliver releases safely and predictably
- Reduce avoidable deployment failures and recovery time
- Maintain clear, auditable release decisions

### Typical Communication
- Release readiness reviews and go/no-go meetings
- Deployment checklists and status updates
- Incident or rollback coordination

### Interaction with Existing Roles
- Works with the **Project Manager** on schedules, risks, and dependencies.
- Coordinates scope and release value with the **Product Manager**.
- Confirms implementation and deployment readiness with **Developers**.
- Aligns verification and acceptance results with **QA/Testing**.
- Provides release timing and impact updates to **Stakeholders**.

---

## QA/Testing Lead

### Role Summary
The QA/Testing Lead owns the test strategy and quality gates so that acceptance, integration, and release requirements are verified consistently.

### Responsibilities
- Define test scope, environments, tools, and entry/exit criteria
- Coordinate unit, integration, end-to-end, smoke, and manual testing
- Track defects, quality risks, and unresolved acceptance gaps
- Recommend go/no-go input based on quality evidence

### Goals
- Increase confidence in product quality and acceptance
- Surface quality risks early
- Keep testing proportionate to risk and delivery pace

### Typical Communication
- Test planning and quality-risk reviews
- Defect triage and acceptance demonstrations
- Release readiness reports

### Interaction with Existing Roles
- Partners with **Developers** on testability, defects, and fixes.
- Clarifies and validates acceptance criteria with the **Product Manager**.
- Reports QA milestones and blockers to the **Project Manager**.
- Provides test evidence to the **Release Manager** and relevant **Stakeholders**.

---

## Technical Lead / Architecture Owner

### Role Summary
The Technical Lead or Architecture Owner provides technical direction and maintains a cohesive view of system design, quality, and integration risks.

### Responsibilities
- Guide major technical and architectural decisions
- Identify architectural dependencies and non-functional requirements
- Review designs for maintainability, scalability, security, and operability
- Align implementation approaches across teams and components

### Goals
- Reduce avoidable technical debt and integration risk
- Improve the consistency and maintainability of solutions
- Enable teams to make informed implementation trade-offs

### Typical Communication
- Technical design and architecture reviews
- Dependency planning and engineering risk discussions
- Developer mentoring and design feedback

### Interaction with Existing Roles
- Collaborates with **Developers** on implementation patterns and technical decisions.
- Raises technical dependencies and estimations to the **Project Manager**.
- Discusses feasibility, constraints, and trade-offs with the **Product Manager**.
- Coordinates architectural considerations with **QA/Testing**, the **Release Manager**, and security stakeholders.

---

## Security and Compliance Representative

### Role Summary
The Security and Compliance Representative ensures that security, privacy, and applicable compliance obligations are considered throughout delivery and release.

### Responsibilities
- Identify applicable security and regulatory requirements
- Recommend or review controls, mitigations, and evidence
- Participate in threat, privacy, and compliance reviews
- Advise on unresolved risks and release or remediation conditions

### Goals
- Reduce security and compliance exposure
- Embed controls earlier in delivery
- Maintain traceable decisions and required evidence

### Typical Communication
- Security and compliance reviews
- Risk assessments and remediation tracking
- Release-readiness and incident escalations

### Interaction with Existing Roles
- Partners with **Developers** and the **Technical Lead** on controls and secure implementation.
- Aligns required validation with **QA/Testing**.
- Raises material risks and release gates to the **Project Manager** and **Product Manager**.
- Provides risk context and required decisions to **Stakeholders** and the **Release Manager**.

---

## Change / Adoption Lead

### Role Summary
The Change/Adoption Lead plans how users, operators, customers, and other stakeholders will adopt and use the delivered change.

### Responsibilities
- Plan communications, training, documentation, and rollout support
- Identify affected user groups and adoption dependencies
- Coordinate readiness activities and collect post-release feedback
- Support adoption measurements and follow-up improvements

### Goals
- Reduce disruption and adoption barriers
- Improve stakeholder readiness and user confidence
- Turn release outcomes into sustained customer and operational value

### Typical Communication
- Adoption planning and stakeholder readiness reviews
- Enablement and communication materials
- Rollout feedback and post-release retrospectives

### Interaction with Existing Roles
- Works with the **Product Manager** on value propositions, audience needs, and success measures.
- Coordinates rollout timing and risks with the **Project Manager**.
- Provides operational feedback and enablement needs to **Developers** and **Support/Operations**.
- Engages **Stakeholders** and affected teams throughout planning and rollout.

---

## Support / Operations Representative

### Role Summary
The Support/Operations Representative represents operational readiness and the ongoing support perspective from planning through production monitoring and incident follow-up.

### Responsibilities
- Prepare support processes, runbooks, monitoring, and escalation paths
- Validate operational readiness before release
- Provide production feedback, trends, and recurring issues
- Support triage and knowledge capture for incidents

### Goals
- Improve service reliability and supportability
- Reduce time to detect and resolve production issues
- Ensure operational knowledge is available before and after release

### Typical Communication
- Operational readiness reviews and release verification
- Support and incident handoffs
- Production trend and recurring-issue reports

### Interaction with Existing Roles
- Coordinates readiness and observability requirements with **Developers** and the **Technical Lead**.
- Reviews support-relevant acceptance and release evidence with **QA/Testing** and the **Release Manager**.
- Communicates operational risks and recurring issues to the **Project Manager** and **Product Manager**.
- Supports **Stakeholders** by maintaining clear escalation and incident communications.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
