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

## QA Engineer / Test Lead

### Role Summary
QA Engineers and Test Leads own quality assurance across the delivery lifecycle. They design and execute test plans, validate acceptance criteria, and advocate for testability early in the process.

### Responsibilities
- Create and maintain test plans, test cases, and automated test suites
- Validate features against acceptance criteria before release
- Identify, document, and track defects to resolution
- Coordinate with Developers for early bug identification and reproduce environments
- Sign off on release readiness and regression coverage

### Goals
- Prevent defects from reaching production
- Reduce feedback loops between development and testing
- Ensure the Definition of Done includes quality gates

### Typical Communication
- Test plan reviews with Product Manager and Developers during planning
- Bug triage and daily standup participation during execution
- Release sign-off reports shared with Project Manager and stakeholders

### Interactions with Existing Roles
- **Developers**: Pair early to review acceptance criteria and define testability requirements; collaborate on reproducing and fixing defects.
- **Product Managers**: Validate that acceptance criteria are complete and testable; flag scope or ambiguity issues before development starts.
- **Project Managers**: Report on test coverage, open defect counts, and release readiness; flag quality risks in the risk register.

---

## UX/UI Designer

### Role Summary
UX/UI Designers create user-centered experiences by translating product requirements into wireframes, prototypes, and interface designs that are usable and accessible.

### Responsibilities
- Define user flows, wireframes, and high-fidelity designs based on product requirements
- Conduct or synthesize user research and usability testing
- Collaborate with Developers on design implementation and feasibility
- Maintain a design system or style guide to ensure visual consistency
- Participate in design reviews with stakeholders

### Goals
- Deliver intuitive, accessible experiences that meet user needs
- Reduce rework by validating designs before development begins
- Ensure consistent look and feel across product surfaces

### Typical Communication
- Design reviews and stakeholder walkthroughs at key milestones
- Async design feedback via prototyping tools (e.g., Figma)
- Handoff documentation with specifications for Developers

### Interactions with Existing Roles
- **Developers**: Provide design specs and assets; clarify implementation questions; review implemented UI against designs.
- **Product Managers**: Translate product requirements into designs; validate design decisions against user and business goals.
- **Project Managers**: Flag design-related timeline risks; communicate design dependencies that affect sprint planning.

---

## Business Stakeholder

### Role Summary
Business Stakeholders represent the interests of the business, customers, or end users. They provide high-level requirements, validate deliverables, and approve key milestones.

### Responsibilities
- Define and communicate business needs and priorities
- Review and approve deliverables against expected outcomes
- Participate in milestone reviews and user acceptance testing (UAT)
- Provide timely decisions on trade-offs that affect scope or timeline
- Serve as a liaison between the delivery team and the wider organization

### Goals
- Ensure the project delivers measurable business value
- Maintain alignment between project outcomes and strategic objectives
- Minimize disruption by providing clear, timely input

### Typical Communication
- Monthly or milestone-based status updates from the Project Manager
- Roadmap briefings from the Product Manager
- UAT participation and sign-off during release phases

### Interactions with Existing Roles
- **Product Managers**: Co-define requirements, priorities, and success metrics; validate roadmap trade-offs.
- **Project Managers**: Receive regular project status updates; provide input on priorities and scope changes.
- **Developers**: Participate in demos and UAT sessions; provide business context when clarifying requirements.

---

## Sponsor / Executive

### Role Summary
Sponsors and Executives provide strategic oversight, authorize funding and scope, and remove high-level blockers that cannot be resolved at team level.

### Responsibilities
- Authorize the project charter, budget, and resource allocation
- Champion the initiative within the organization
- Remove organizational blockers and facilitate executive escalations
- Review major scope changes, pivots, or budget adjustments
- Hold accountability for strategic outcomes

### Goals
- Ensure the initiative aligns with organizational strategy
- Enable the team to deliver without avoidable organizational friction
- Make timely decisions on escalated issues

### Typical Communication
- Executive briefings at project initiation and major milestones
- Escalation decisions as needed (typically via Project or Product Manager)
- Final go/no-go approvals for major releases or pivots

### Interactions with Existing Roles
- **Product Managers**: Align on strategic priorities; approve significant roadmap changes or pivots.
- **Project Managers**: Receive escalated risks or blockers; provide decisions on scope, timeline, or resource trade-offs.
- **Developers**: Indirect; may participate in high-level demos or architecture reviews for strategic initiatives.

---

## DevOps / SRE

### Role Summary
DevOps Engineers and Site Reliability Engineers own the CI/CD pipeline, infrastructure automation, and system reliability. They enable teams to ship safely and operate confidently in production.

### Responsibilities
- Build and maintain CI/CD pipelines and deployment automation
- Manage infrastructure provisioning, monitoring, and alerting
- Define and enforce reliability standards (SLOs/SLAs)
- Coordinate environment setup and release deployments with the delivery team
- Lead incident response, root cause analysis, and postmortem processes

### Goals
- Enable fast, safe, and repeatable deployments
- Maintain system reliability and minimize production incidents
- Reduce toil through automation

### Typical Communication
- Deployment and release coordination with Project Manager and Developers
- Incident notifications and postmortems shared with the full team
- Infrastructure status and capacity updates in weekly syncs

### Interactions with Existing Roles
- **Developers**: Provide deployment tooling and environment access; collaborate on infrastructure-as-code and observability best practices.
- **Project Managers**: Coordinate deployment windows and release schedules; flag infrastructure risks in the risk register.
- **Product Managers**: Communicate reliability metrics and production constraints that affect roadmap feasibility.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [RACI & Handoff Checklist](octoacme-raci-and-handoff-checklist.md) for a cross-role responsibilities matrix and practical handoff checklists.

