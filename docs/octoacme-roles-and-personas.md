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

## Additional personas to consider

The following roles are commonly needed on cross-functional projects and should be explicitly represented in OctoAcme project documentation to clarify accountability and cross-team coordination.

### Engineering Lead / Technical Lead
### Role Summary
Technical ownership for architecture, design quality, and engineering direction on a project.

### Responsibilities
- Drive architecture decisions and technical design
- Lead design reviews and set coding and quality standards
- Coordinate technical trade-offs and non-functional requirements
- Mentor developers and support team technical growth

### Primary Interactions
- Works with Developers to guide implementation and code review decisions
- Advises Product Managers on feasibility, trade-offs, and technical risk
- Coordinates with QA and SRE on production readiness and operability

### Typical Communication
- Architecture reviews
- Cross-team technical planning
- Incident and retrospective follow-up

---

### Delivery Lead / Delivery Manager
### Role Summary
Day-to-day delivery coordination across the team to keep sprint commitments, dependencies, and progress visible.

### Responsibilities
- Track sprint progress and delivery metrics
- Identify and unblock dependencies across teams
- Support planning and milestone tracking
- Improve the team’s delivery process over time

### Primary Interactions
- Partners with the Project Manager on schedule and risk tracking
- Works with Product Managers on priority trade-offs and scope decisions
- Coordinates with Developers to remove blockers and keep work flowing

### Typical Communication
- Sprint planning and delivery reviews
- Dependency tracking and escalation discussions
- Weekly project health updates

---

### Release Engineer / Release Manager
### Role Summary
Ownership of deployment coordination, release readiness, and rollback planning.

### Responsibilities
- Manage release pipelines and deployment automation
- Plan release windows and rollback procedures
- Coordinate post-release verification and handoff tasks
- Communicate release status to stakeholders

### Primary Interactions
- Coordinates with Developers, QA, and SRE to confirm release readiness
- Works with Product Managers and Project Managers on stakeholder communication
- Supports timely, low-risk production deployment

### Typical Communication
- Release readiness reviews
- Deployment check-ins
- Post-release status reporting

---

### Site Reliability Engineer (SRE) / On-call Engineer
### Role Summary
Ensures production reliability, observability, and operational resilience.

### Responsibilities
- Monitor production health and reliability signals
- Maintain runbooks and on-call procedures
- Lead incident response and resolution support
- Provide operational requirements during planning

### Primary Interactions
- Works with Developers to improve observability and fix production issues
- Advises Project Managers and Product Managers about operational risk and uptime impact
- Partners with Release Manager on safe deployment and rollback decisions

### Typical Communication
- Incident triage and response meetings
- Reliability review discussions
- Production readiness check-ins

---

### QA Lead / Test Lead
### Role Summary
Owns testing strategy, quality gates, and validation of acceptance criteria.

### Responsibilities
- Define test plans and quality priorities
- Coordinate automated and manual testing coverage
- Validate that features meet acceptance criteria and Definition of Done
- Lead release gating for QA sign-off

### Primary Interactions
- Works with Developers to ensure testability and quality standards
- Coordinates with Delivery Lead and Release Manager on validation timing
- Informs Product and Project leadership of release quality risks

### Typical Communication
- Test planning sessions
- Pre-release validation reviews
- Quality and defect triage

---

### UX Researcher / Designer
### Role Summary
Drives user understanding and product experience quality.

### Responsibilities
- Conduct user research and usability validation
- Produce design artifacts and prototypes
- Validate assumptions against real user needs and business outcomes
- Support design handoff for implementation

### Primary Interactions
- Collaborates with Product Managers on problem framing and feature validation
- Works with Developers during implementation and design review cycles
- Shares outcomes and recommendations with stakeholders across the project

### Typical Communication
- Discovery and design workshops
- Usability review sessions
- Design handoff meetings

---

### Data Analyst / Product Analytics Owner
### Role Summary
Measures project value using data and supports evidence-based iteration.

### Responsibilities
- Define instrumentation and reporting needs
- Build dashboards and track success metrics
- Analyze feature performance and user behavior
- Support product decisions with measurable evidence

### Primary Interactions
- Partners with Product Managers to define success metrics and evaluation plans
- Works with Developers to instrument features for analysis
- Provides insight for retrospective conversations and roadmap adjustments

### Typical Communication
- KPI planning and dashboard reviews
- Retrospective analysis updates
- Product performance discussions

---

### Security Liaison / Security Engineer
### Role Summary
Ensures security is considered throughout planning, development, and release.

### Responsibilities
- Conduct security reviews and threat modeling
- Define security acceptance criteria and compliance checks
- Triage vulnerabilities and recommend remediation steps
- Support secure-by-default design decisions

### Primary Interactions
- Reviews designs with engineering and product leads
- Works with Developers and SRE to address vulnerabilities
- Advises Project Managers on risk and compliance implications

### Typical Communication
- Security review sessions
- Risk and remediation updates
- Release security sign-off

---

### Support / Operations Representative
### Role Summary
Represents customer-facing realities and operational issues in project work.

### Responsibilities
- Monitor recurring operational issues and support needs
- Translate issues into backlog and improvement themes
- Define supportability requirements and communication plans
- Share real-world customer feedback with the delivery team

### Primary Interactions
- Feeds customer issues back to Product Managers and Developers
- Partners with Project Managers on release communication and mitigation planning
- Coordinates with SRE for escalation and operational follow-up

### Typical Communication
- Support issue reviews
- Knowledge-sharing sessions
- Post-release follow-up discussions

---

### Vendor / Partner Manager (if applicable)
### Role Summary
Coordinates external dependencies and partner relationships when delivery depends on third parties.

### Responsibilities
- Manage vendor scope, timelines, and delivery expectations
- Track risks and interdependencies with external contributors
- Support integration planning and issue escalation
- Align external outputs with internal project milestones

### Primary Interactions
- Liaises with Project Managers and Product Managers on integration risk and timing
- Coordinates with Developers and Release Managers on environment readiness and deployment planning
- Escalates cross-team blockers that stem from partner dependencies

### Typical Communication
- Partner check-ins
- Integration planning workshops
- Risk and dependency status reviews

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

