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

## Product Owners

### Role Summary
Product Owners translate customer value into a prioritized backlog and are accountable for the scope, quality, and acceptance of work delivered by the team.

### Responsibilities
- Define and refine backlog priorities
- Clarify acceptance criteria and business intent
- Make trade-off decisions during planning and review cycles
- Partner with stakeholders to validate outcomes and impacts
- Approve completed work when quality and scope meet expectations

### Interaction with existing roles
- Works closely with Product Managers on roadmap and outcome alignment
- Collaborates with Developers and Technical Leads on scope trade-offs and implementation details
- Provides direction to Project Managers for milestone and dependency planning
- Coordinates with QA Lead to confirm readiness and release readiness criteria

---

## Program Managers

### Role Summary
Program Managers oversee cross-functional coordination across multiple teams or initiatives to maintain strategic alignment, dependencies, and risk visibility.

### Responsibilities
- Manage portfolio-level priorities and timelines
- Track dependencies, risks, and capacity across teams
- Align delivery plans with strategic goals and stakeholder expectations
- Coordinate executive communication and status reporting
- Support issue resolution when work spans multiple groups

### Interaction with existing roles
- Works with Project Managers to maintain consistent plans and status across initiatives
- Partners with Product Managers on strategic prioritization and stakeholder communication
- Shares escalation concerns with Engineering Managers and Technical Leads when timing or resourcing risks appear
- Coordinates with Release Managers to ensure cross-team readiness and launch sequencing

---

## Technical Leads

### Role Summary
Technical Leads shape the engineering approach, ensure quality, and guide implementation decisions that maintain architecture, system health, and delivery velocity.

### Responsibilities
- Define technical direction and architecture constraints
- Review design decisions and implementation quality
- Support estimation, planning, and risk identification
- Provide technical mentorship and unblock engineering decisions
- Partner with QA and Release teams on readiness and deployment strategy

### Interaction with existing roles
- Collaborates with Developers on implementation standards and technical trade-offs
- Works with Product Owners and Product Managers to translate requirements into feasible solutions
- Partners with Engineering Managers on staffing, technical debt, and delivery focus
- Coordinates with QA Leads and Release Managers to confirm testing coverage and deployment risk

---

## Engineering Managers

### Role Summary
Engineering Managers support team health, execution, and resourcing while ensuring the engineering organization can execute the plan effectively.

### Responsibilities
- Manage team capacity, staffing, and workload distribution
- Support performance, coaching, and process improvement
- Help resolve resourcing, prioritization, and escalation issues
- Partner with Program and Project Managers on timeline realism and execution risks
- Align engineering goals with organizational objectives

### Interaction with existing roles
- Works with Technical Leads to prioritize technical work and remove blockers
- Coordinates with Product Managers and Product Owners on trade-offs and roadmap feasibility
- Collaborates with Project Managers to surface delivery risk and mitigate execution issues
- Supports Release Managers during release readiness and deploy coordination

---

## QA Leads

### Role Summary
QA Leads define the approach to quality validation, ensure test strategy alignment, and help confirm that work is safe to release.

### Responsibilities
- Define test plans, quality gates, and acceptance criteria validation
- Ensure test coverage for critical workflows and release risk areas
- Coordinate defect triage and regression risks
- Partner with engineering teams to improve quality and testability
- Sign off on readiness when risk is appropriately assessed

### Interaction with existing roles
- Works with Product Owners and Product Managers to validate expected outcomes against acceptance criteria
- Partners with Technical Leads to assess technical risk and appropriate validation coverage
- Coordinates with Release Managers to confirm launch readiness and rollback considerations
- Shares quality concerns with Project Managers and Engineering Managers when timelines or risks need escalation

---

## Release Managers

### Role Summary
Release Managers coordinate plans, quality checks, and communication for launches so changes are delivered predictably and safely.

### Responsibilities
- Maintain release calendars and deployment plans
- Confirm launch criteria, checklists, and rollback readiness
- Coordinate release communications and stakeholder notifications
- Collaborate with engineering, QA, and operations on deployment execution
- Track release outcomes and post-release follow-up

### Interaction with existing roles
- Works with Product Owners and Project Managers to align launch timing with business needs
- Coordinates with QA Leads to verify readiness and release criteria
- Partners with DevOps/Platform Engineers for deployment execution and health monitoring
- Escalates release blockers to Program or Engineering Managers when necessary

---

## DevOps / Platform Engineers

### Role Summary
DevOps and Platform Engineers provide the infrastructure, automation, and operational support needed to deliver code reliably and safely.

### Responsibilities
- Maintain CI/CD pipelines and deployment automation
- Manage environments, tooling, and observability platforms
- Support incident recovery, rollback planning, and operational readiness
- Improve reliability, performance, and environment consistency
- Partner with engineering teams to enable rapid, safe delivery

### Interaction with existing roles
- Works closely with Release Managers and Technical Leads on deployment readiness and rollback strategy
- Provides environment and tooling support to Developers and QA Leads
- Coordinates with Engineering Managers on infrastructure risk, capacity, and service stability
- Shares operational concerns with Security/Compliance Owners when controls or safeguards are affected

---

## UX / Product Designers

### Role Summary
UX and Product Designers create the user experience and design artifacts that help teams build intuitive, useful, and accessible solutions.

### Responsibilities
- Translate user needs and business goals into design concepts
- Create flows, wireframes, prototypes, and design systems
- Validate usability with users and stakeholders
- Support accessibility, consistency, and quality standards
- Partner with product and engineering on implementation fidelity

### Interaction with existing roles
- Works with Product Owners and Product Managers to define user-centered priorities
- Collaborates with Developers and Technical Leads to ensure design intent is preserved in implementation
- Partners with QA Leads to validate UX flows and edge cases during testing
- Coordinates with Stakeholder Liaisons when design decisions affect broader customer communication

---

## Security / Compliance Owners

### Role Summary
Security and Compliance Owners help the team meet required controls, privacy expectations, and risk standards throughout the project lifecycle.

### Responsibilities
- Review security and compliance requirements for features and releases
- Enforce standards related to data handling, access, and governance
- Assess and document risk related to new systems or changes
- Coordinate security review and sign-off for critical work
- Partner with engineering and release teams to reduce exposure

### Interaction with existing roles
- Works with Product Owners and Project Managers to incorporate compliance constraints into planning
- Advises Technical Leads and Developers on secure implementation patterns
- Collaborates with Release Managers to confirm launch controls and rollback safeguards
- Escalates governance risks to Program Managers or Leadership when needed

---

## Documentation Owners

### Role Summary
Documentation Owners maintain the clarity and consistency of project and process documentation so the team can execute with shared understanding.

### Responsibilities
- Keep process documents up to date and aligned with current practices
- Coordinate updates for role definitions, checklists, and handoff guidance
- Ensure project documentation is discoverable and easy to follow
- Support onboarding by creating clear references for new team members
- Flag documentation gaps and propose revisions

### Interaction with existing roles
- Works with Product Owners and Project Managers to capture process changes and decisions
- Collaborates with Technical Leads and QA Leads to ensure documentation reflects actual execution steps
- Coordinates with Stakeholder Liaisons to keep communication and status updates consistent
- Supports Release Managers by maintaining launch checklists and process artifacts

---

## Stakeholder Liaisons

### Role Summary
Stakeholder Liaisons help maintain trust and alignment by translating updates, risks, and decisions between the project team and external stakeholders.

### Responsibilities
- Communicate status, milestones, and trade-offs to stakeholders
- Gather stakeholder feedback and requirements
- Maintain a consistent narrative for business and executive audiences
- Surface stakeholder concerns that may affect prioritization or timing

### Interaction with existing roles
- Works with Product Managers and Product Owners to shape communication and expectations
- Coordinates with Project Managers and Program Managers on updates and escalation timing
- Partners with Release Managers on launch messaging and post-release stakeholder follow-up
- Shares feedback from stakeholders with the team to improve outcomes

---

## Data Analysts

### Role Summary
Data Analysts provide measurement, reporting, and insight to help teams understand value, quality, and performance outcomes.

### Responsibilities
- Collect and analyze product and delivery metrics
- Support roadmap prioritization using evidence and trend data
- Measure feature adoption, customer outcomes, and operational health
- Provide post-release reporting and insights for continuous improvement

### Interaction with existing roles
- Works with Product Managers and Product Owners to evaluate outcomes against goals
- Supports Program and Project Managers with delivery metrics and health reporting
- Collaborates with QA Leads to assess quality and risk trends over time
- Provides evidence to Stakeholder Liaisons for stakeholder updates

---

## Support / On-call Owners

### Role Summary
Support and On-call Owners ensure operational continuity by triaging incidents, coordinating response, and helping the team learn from issues.

### Responsibilities
- Monitor service health and respond to operational issues
- Triage and coordinate incident response with engineering partners
- Document findings, remediation steps, and follow-up actions
- Support release stability and post-launch confidence

### Interaction with existing roles
- Works with DevOps/Platform Engineers and Technical Leads during incident response
- Coordinates with Release Managers for emergency or planned rollback scenarios
- Shares trend data with Product Owners, Program Managers, and Stakeholder Liaisons when service issues affect customer expectations
- Partners with QA Leads to assess whether regressions or quality issues require follow-up

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The roles intentionally overlap to reflect realistic project delivery: Product and Project responsibilities provide business and execution alignment, while Technical, QA, and Release roles ensure product delivery quality and operational readiness.
- Where there are hand-offs, the expectation is that each role clarifies decision ownership, expected inputs, and outputs to reduce gaps and improve accountability.

---

## Recommended documentation additions
To strengthen this document and support execution clarity, future updates should include:
- A RACI matrix for major workflows such as planning, delivery, and release
- A handoff checklist that defines who owns inputs and outputs between roles
- A short onboarding section describing how new team members should interpret these roles
- Role-specific examples showing typical interactions across planning, delivery, QA, and release
