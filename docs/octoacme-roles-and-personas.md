# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. A persona describes an area of accountability, not necessarily a dedicated full-time position; teams may combine roles based on project size and needs.

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

## Release Managers

### Role Summary
Release Managers coordinate the readiness and execution of releases. This accountability may be assigned to a PM, technical lead, or another team member for a given release.

### Responsibilities
- Coordinate release scope, readiness reviews, and deployment windows
- Confirm acceptance criteria, CI, security checks, smoke tests, and release notes are complete
- Ensure rollback or mitigation plans and release communications are ready
- Track release decisions, dependencies, and follow-up actions

### Goals
- Deliver predictable releases with clear ownership and minimal avoidable risk
- Ensure stakeholders know what is changing and how success will be verified

### Typical Communication
- Release readiness check-ins with Developers, QA, SRE, and Security
- Deployment coordination and stakeholder announcements
- Escalation of release blockers to the PM and Product Manager

### Interactions with Existing Roles
- Partners with the PM on milestones, dependencies, and release communications
- Aligns with the Product Manager on scope, priority, and customer impact
- Coordinates with Developers and QA on implementation and test readiness
- Consults SRE and Security on operational readiness and outstanding risks

---

## Scrum Masters / Delivery Facilitators

### Role Summary
Scrum Masters or Delivery Facilitators help the delivery team work effectively by facilitating agreed ways of working, surfacing impediments, and supporting continuous improvement. The role complements rather than replaces project management or product ownership.

### Responsibilities
- Facilitate planning, standups, reviews, and retrospectives as agreed by the team
- Help identify and remove workflow blockers, escalating those outside the team's control
- Support a healthy, transparent backlog and make work-in-progress visible
- Encourage inspection, adaptation, and follow-through on improvement actions

### Goals
- Enable sustainable team delivery and clear collaboration
- Reduce avoidable delays and improve the team's working practices

### Typical Communication
- Delivery ceremonies and team-board updates
- Impediment follow-ups with the PM and dependent teams
- Retrospective actions and team working agreements

### Interactions with Existing Roles
- Coordinates with the PM on delivery tracking, dependencies, and escalations while leaving project-level commitments with the PM
- Partners with the Product Manager on backlog readiness and refinement, while product priority remains with the Product Manager
- Helps Developers make work and blockers visible without directing technical implementation
- Works with QA and stakeholders to ensure feedback and acceptance discussions are included in team routines

---

## UX / Design Leads

### Role Summary
UX / Design Leads shape usable, accessible experiences and help ensure that proposed solutions address user needs.

### Responsibilities
- Plan and synthesize user research and design feedback
- Create and maintain user flows, interaction designs, and prototypes
- Identify usability and accessibility considerations and make them visible in requirements
- Collaborate on acceptance criteria and validate the implemented experience

### Goals
- Make product experiences useful, understandable, and inclusive
- Reduce rework by validating important design assumptions early

### Typical Communication
- Design reviews and research readouts
- Design specifications and prototypes shared with Product Managers and Developers
- Usability findings and acceptance discussions with QA

### Interactions with Existing Roles
- Partners with the Product Manager to connect user needs, product outcomes, and scope
- Works with Developers to assess feasibility and resolve implementation questions
- Collaborates with QA on user-centered acceptance criteria and usability checks
- Shares research and design decisions with the PM and relevant stakeholders to inform planning and trade-offs

---

## Data / Analytics Leads

### Role Summary
Data / Analytics Leads help teams define measurable outcomes, collect trustworthy product signals, and use evidence to inform decisions.

### Responsibilities
- Translate product success metrics into measurement plans and instrumentation requirements
- Define or review event semantics, data quality expectations, and dashboards
- Analyze outcomes and communicate limitations, trends, and findings
- Help teams distinguish observed results from assumptions

### Goals
- Make progress and product impact measurable
- Provide reliable evidence for prioritization and iteration

### Typical Communication
- Metric reviews with Product Managers and stakeholders
- Instrumentation planning with Developers
- Outcome summaries after launches or milestones

### Interactions with Existing Roles
- Partners with the Product Manager to define success measures and interpret results against product goals
- Works with Developers to instrument events and address data-quality issues
- Coordinates with the PM to include measurement dependencies and reporting in plans and status updates
- Presents findings to stakeholders and clarifies uncertainty, while product decisions remain with the Product Manager and accountable stakeholders

---

## Site Reliability Engineers (SREs)

### Role Summary
SREs help ensure that services are reliable, observable, and ready to operate in production. Teams without a dedicated SRE may assign these responsibilities to an appropriate engineering or operations owner.

### Responsibilities
- Define or advise on service-level objectives, reliability risks, and operational readiness
- Establish monitoring, alerting, and observability needs
- Support capacity, resilience, backup, and recovery planning as applicable
- Prepare incident response and operational handoffs, and contribute to post-incident learning

### Goals
- Maintain dependable services and make operational health visible
- Reduce the impact and duration of service incidents

### Typical Communication
- Operational readiness and launch reviews with Developers and Release Managers
- Reliability dashboards, runbooks, and incident updates
- Risk and mitigation discussions with the PM and Security Lead

### Interactions with Existing Roles
- Partners with Developers on service ownership, reliability design, and observability
- Works with QA on production-readiness and recovery testing where applicable
- Advises the PM and Release Manager on operational risks, readiness, and mitigation plans
- Coordinates with the Security Lead on secure operations and incident response boundaries

---

## Security Leads

### Role Summary
Security Leads help teams identify and manage security risks throughout delivery, and guide escalation and response for security concerns. They advise on security decisions; the designated security authority retains any required approval responsibilities.

### Responsibilities
- Identify applicable security requirements and support threat and risk assessments
- Advise on secure design, dependency and vulnerability management, and security testing
- Track remediation and communicate residual risk to accountable decision-makers
- Coordinate with the security incident process when a security event occurs

### Goals
- Reduce security exposure without obscuring ownership or delivery trade-offs
- Make security requirements and risks visible early enough to address effectively

### Typical Communication
- Security reviews with Developers, QA, and SRE
- Risk and mitigation updates with the PM and Product Manager
- Escalations through the organization's security incident and governance channels

### Interactions with Existing Roles
- Works with Developers on secure implementation, remediation, and design decisions
- Coordinates with QA on security-related validation and evidence
- Partners with SRE on operational controls and security incident readiness
- Advises the PM on security risks, dependencies, and escalation; aligns with the Product Manager on customer impact and prioritization
- Communicates material risks to stakeholders through the agreed escalation path

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Assign or combine persona responsibilities explicitly for each project; a persona does not imply a required dedicated headcount.
- Clarify ownership for shared artifacts such as the release plan, risk register, acceptance criteria, measurement plan, observability plan, and retrospective actions during project planning.
