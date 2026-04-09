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

## QA Engineer (new)

### Role Summary
QA Engineers ensure the product meets quality standards before release by designing tests, validating acceptance criteria, and partnering throughout the delivery pipeline.

### Responsibilities
- Create and maintain test plans (unit, integration, E2E, smoke)
- Define and validate acceptance criteria and DoD
- Execute manual exploratory tests where automation is insufficient
- Triage, reproduce, and document defects; verify fixes
- Advocate for testability and early quality practices

### Interactions
- Works closely with Developers on test automation and defect resolution
- Partners with Product Managers to confirm acceptance criteria
- Coordinates with Project Managers to align testing timelines with releases

---

## UX Designer (new)

### Role Summary
UX Designers ensure the product is usable and meets user needs through research, prototyping, and design validation.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Define user flows and accessibility considerations
- Validate designs with stakeholders and users

### Interactions
- Partners with Product Managers to interpret user needs into designs
- Collaborates with Developers to ensure feasibility and implementation fidelity
- Provides acceptance criteria related to usability and accessibility

---

## Business Analyst (new)

### Role Summary
Business Analysts clarify and document business requirements and process rules, ensuring the team and stakeholders share a common understanding.

### Responsibilities
- Gather and document requirements and business rules
- Translate stakeholder needs into clear user stories and acceptance criteria
- Maintain traceability between requirements, designs, and implementation
- Help prioritize scope based on impact and effort

### Interactions
- Acts as a bridge between Stakeholders/PdM and Developers/QA
- Supports PM/PdM in negotiation of scope and acceptance criteria
- Participates in planning and refinement sessions

---

## Release Engineer / DevOps (new)

### Role Summary
Release Engineers (or DevOps) focus on deployment pipelines, release automation, observability, and system reliability.

### Responsibilities
- Maintain and improve CI/CD pipelines and deployment automation
- Own release configuration, rollbacks, and runbooks
- Ensure monitoring, alerts, and post-deploy verification steps are in place
- Partner on environment management and infrastructure as code

### Interactions
- Coordinates with Developers for build and deployment requirements
- Works with QA and PM to plan release windows and verification
- Escalates incidents and supports rollback when needed

---

## Security & Compliance (new)

### Role Summary
Security & Compliance representatives provide guardrails, review security implications, and ensure regulatory needs are met.

### Responsibilities
- Perform security reviews and threat modeling for significant changes
- Ensure compliance checks are included in planning and CI
- Provide remediation guidance and follow-up on security findings

### Interactions
- Engages with Developers and Release Engineers during planning and PR reviews
- Notifies PMs of compliance or security risks that affect timelines

---

## Support / On-call (new)

### Role Summary
Support and on-call owners handle live incidents, triage user-reported issues, and feed operational learnings back to the team.

### Responsibilities
- Triage incoming incidents and customer reports
- Escalate to engineering on-call or PM when needed
- Contribute actionable incident details and postmortem input

### Interactions
- Works with DevOps and Developers to resolve incidents
- Updates PM and Stakeholders on customer-impacting issues

---

## Stakeholders (expanded)

### Role Summary
Stakeholders include business owners, sponsors, and domain experts who provide context, priorities, and validation.

### Responsibilities
- Provide domain knowledge and business priorities
- Review and approve high-impact decisions and deliverables
- Validate that the delivered outcomes meet business needs

### Interactions
- Engages with Product and Project Managers during initiation, planning, and key decision gates
- Available for acceptance and milestone reviews as needed

---

## Role Interaction Guidance (new)

This section clarifies common handoffs and ownership points to reduce ambiguity.

- Project One-pager: PdM (owner), PM (delivery owner), Stakeholders (reviewers)
- Backlog prioritization: PdM (owner), BA (support), Developers (inputs), PM (sequencing)
- Acceptance and release sign-off: QA (validation), PdM (business acceptance), Release Eng (deployment owner), PM (communication)
- Incident response: Support (triage owner), On-call Dev/DevOps (technical owner), PM (stakeholder communication)
- Design-to-implementation: UX (design owner), Developers (technical owner), QA (validation), PdM (product acceptance)

---

## Using these personas in exercises & onboarding (updated)

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Add the role-onboarding checklist (docs/templates/role-onboarding.md) to onboarding guides.
- Reference the handoff & acceptance checklist (docs/templates/handoff-and-acceptance-checklist.md) inside planning and release docs to formalize handoffs.

---
