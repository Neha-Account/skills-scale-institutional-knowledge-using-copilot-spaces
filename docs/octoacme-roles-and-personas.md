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

---

## Additional Personas

The core roles above cover the primary responsibilities on most projects. However, cross-functional and operational personas often play a critical role in delivery. The following additional personas should be included to improve clarity, ownership, and handoffs.

### Technical Lead
- Responsibilities: Owns architecture and technical decisions for the project; ensures designs align with long-term platform goals; performs technical reviews and approves major design changes; mentors developers on system-level concerns.
- Interactions: Works closely with Developers, Project Manager (PM), Product Manager (PdM), and QA. Escalates technical risks and trade-offs to the PM/PdM and coordinates with Release Engineer/SRE for deployment considerations.

### Delivery Lead
- Responsibilities: Coordinates cross-team delivery, manages schedules and release readiness, drives removal of blockers, and tracks dependencies across teams. Ensures work is sequenced for efficient delivery.
- Interactions: Partners with PMs, Tech Leads, Release Engineer, and stakeholders; facilitates weekly delivery syncs and coordinates integration testing and release windows.

### UX Researcher / Designer
- Responsibilities: Leads user research and usability testing, defines UX acceptance criteria, produces designs and interaction specs, and validates designs against user needs.
- Interactions: Collaborates with PdM to define requirements, works with Developers and QA to ensure designs are implemented and testable, and provides artifacts for acceptance criteria and demos.

### Data Analyst
- Responsibilities: Defines measurement strategy and success metrics, implements instrumentation plans or validates telemetry, builds dashboards and reports, and performs analysis to inform product decisions.
- Interactions: Works with PdM to align on success metrics, with Developers to instrument events and metrics, and with the team to interpret post-release data and iterate on features.

### Release Engineer / SRE
- Responsibilities: Maintains CI/CD pipelines, creates and maintains runbooks for deployments and rollbacks, ensures observability and reliability practices are followed, and supports incident response during and after releases.
- Interactions: Works with Developers and Technical Leads to design safe deployment patterns, with PM and Delivery Lead for release readiness, and with Support/Customer Success during incidents.

### Customer Success / Support Liaison
- Responsibilities: Represents customer impact and support priorities, gathers customer feedback and production issues, coordinates communications to customers during releases and incidents, and helps prioritize customer-facing fixes.
- Interactions: Partners with PM and PdM to surface customer needs, with Release Engineer and PM during incidents, and with QA to reproduce and prioritize customer-reported issues.

### Security / Compliance Reviewer
- Responsibilities: Reviews security implications of features, conducts threat modeling where necessary, verifies compliance requirements are met, and signs off on security-related concerns before release.
- Interactions: Works with Technical Lead, Developers, and PM; participates in pre-release checks when security or compliance is in scope and coordinates with the security team or on-call for urgent findings.

---

## How this improves outcomes
- Clearer ownership and handoffs reduce delays and misunderstandings.
- Explicit review and sign-off responsibilities shorten review cycles.
- Better onboarding materials so new contributors know where to route questions.
- Reduced single-person risk through shared role definitions and backups.

## Suggested next steps
1. Add the "Additional Personas" section above to docs/octoacme-roles-and-personas.md (this commit).
2. Review with PMs, PdMs, and a Technical Lead to finalize wording.
3. Link each persona to responsibilities in other docs (e.g., release checklist, risk register) where applicable.
