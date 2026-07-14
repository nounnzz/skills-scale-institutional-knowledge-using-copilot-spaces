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

## QA / Testing Lead

### Role Summary
QA and Testing Leads own quality assurance strategy and execution. They define test plans, establish acceptance criteria validation, and ensure quality gates are met before release.

### Responsibilities
- Define quality standards and test strategies for projects
- Create and maintain test plans and acceptance criteria checklists
- Lead manual QA and coordinate automated testing efforts
- Report quality metrics and identify quality risks
- Approve features for release based on test results
- Collaborate with Developers on test coverage and edge cases

### Goals
- Deliver high-quality, defect-free features to production
- Reduce production incidents through thorough testing
- Build confidence in release readiness

### Typical Communication
- Sprint planning and backlog refinement
- Test status updates in weekly syncs
- Quality metrics dashboards
- Acceptance criteria review with Product Managers

### Interactions with Other Roles
- Works with **Developers** on test coverage requirements and edge cases
- Collaborates with **Product Managers** to define acceptance criteria
- Reports quality metrics to **Project Managers** for escalation if needed
- Coordinates with **Release Manager** on pre-release testing and smoke tests
- Advises **Security Lead** on security test scenarios

---

## Product Lead (Strategic Decision Authority)

### Role Summary
Product Leads provide strategic direction and decision authority for product initiatives. They align projects with business objectives, approve planning decisions, and escalate blockers requiring senior input.

### Responsibilities
- Approve project charter and planning decisions
- Align initiatives with product strategy and business goals
- Escalate critical risks and blockers to Sponsor level when needed
- Review and approve major scope changes
- Provide feedback on prioritization trade-offs
- Mentor and support Project Managers and Product Managers

### Goals
- Ensure projects align with strategic objectives
- Enable fast decision-making through clear escalation paths
- Build consistent project governance across teams

### Typical Communication
- Project initiation and approval gates
- Weekly PM syncs and decision reviews
- Escalation of Level 2+ risks
- Quarterly portfolio reviews

### Interactions with Other Roles
- Approves planning decisions from **Project Managers**
- Reviews backlog prioritization from **Product Managers**
- Receives escalations from **Project Managers** on Level 2 blockers
- Escalates Level 3 issues to **Sponsor**
- Supports and coaches both PM and PdM roles

---

## Sponsor / Executive Stakeholder

### Role Summary
Sponsors are executive-level stakeholders who provide business authorization, resources, and strategic alignment for significant projects. They champion initiatives and represent business/stakeholder interests.

### Responsibilities
- Authorize project initiation and resource allocation
- Ensure project aligns with business strategy and customer needs
- Resolve Level 3 escalations and make final trade-off decisions
- Remove organizational blockers and secure cross-team support
- Approve major scope, timeline, or budget changes
- Receive milestone and release updates

### Goals
- Ensure projects deliver business value and strategic impact
- Provide leadership and removal of organizational barriers
- Maintain stakeholder confidence and alignment

### Typical Communication
- Project approval and charter sign-off
- Monthly or milestone-based status updates
- Escalation of business-critical issues
- Post-launch reviews and retrospectives

### Interactions with Other Roles
- Receives project charters from **Project Managers** for authorization
- Resolves Level 3 escalations from **Product Leads**
- Makes final trade-off decisions between competing priorities
- Provides executive support and removes organizational barriers for all team roles

---

## Release Manager

### Role Summary
Release Managers coordinate deployment planning, orchestrate release activities, and ensure smooth transitions from development to production. They maintain release calendars and post-deployment verification.

### Responsibilities
- Create and maintain release schedules and deployment calendars
- Coordinate deployment activities across teams
- Prepare and manage release notes and communications
- Conduct pre-release checklist verification
- Execute or coordinate deployment procedures
- Lead post-deployment verification and rollback if needed
- Document lessons learned from each release

### Goals
- Ensure predictable, low-risk deployments
- Minimize production incidents and downtime
- Maintain clear communication during releases

### Typical Communication
- Weekly release planning meetings
- Deployment day coordination and status updates
- Release notes and stakeholder announcements
- Post-deployment verification reports

### Interactions with Other Roles
- Coordinates with **Developers** on deployment readiness
- Receives quality approval from **QA/Testing Lead**
- Works with **Project Managers** on release timelines and planning
- Communicates release updates to **Product Managers** and **Sponsors**
- Coordinates with **Security Lead** on security validation before release

---

## Security Lead

### Role Summary
Security Leads own security strategy, threat assessment, and incident response for projects. They ensure compliance with security standards and guide secure design practices.

### Responsibilities
- Review projects for security risks and compliance requirements
- Approve security approach and scanning/testing strategy
- Lead security incident response and post-incident reviews
- Recommend security tooling and controls
- Provide security guidance during design and code review
- Maintain security risk register entries
- Ensure CI/CD includes security scanning

### Goals
- Minimize security vulnerabilities and compliance breaches
- Enable secure, compliant product delivery
- Build security into development practices

### Typical Communication
- Design reviews for security considerations
- Risk register updates and incident communications
- Security scanning results and remediation tracking
- Escalation of critical security findings

### Interactions with Other Roles
- Advises **Developers** on secure coding practices and design reviews
- Works with **QA/Testing Lead** on security test scenarios
- Escalates critical security risks to **Product Lead** and **Sponsor**
- Coordinates with **Release Manager** on pre-release security validation
- Maintains security entries in risk register tracked by **Project Managers**

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters / Agile Coaches facilitate agile ceremonies, remove process blockers, and coach teams on continuous improvement. They optimize team velocity and health.

### Responsibilities
- Facilitate standups, planning, reviews, and retrospectives
- Protect team focus and remove process impediments
- Coach team on agile practices and self-organization
- Track and improve team velocity and cycle time
- Identify and escalate team health or capability gaps
- Support process improvements from retrospectives
- Maintain sprint board and process discipline

### Goals
- Maximize team velocity and predictability
- Foster psychological safety and continuous improvement culture
- Optimize team processes based on learnings

### Typical Communication
- Sprint ceremonies (daily standups, planning, retros)
- Impediment tracking and escalation
- Retrospective facilitation and action item follow-up
- Metrics review (velocity, cycle time, capacity planning)

### Interactions with Other Roles
- Facilitates team ceremonies for all core roles (Developers, QA, PM, PdM)
- Escalates impediments to **Project Managers** for resolution
- Coaches entire team on agile best practices and self-organization
- Collects retrospective feedback and drives process improvements
- Tracks team health and raises concerns to **Project Manager**

---

## Role Interaction Map

The following matrix shows key decision and escalation flows across roles:

| Decision / Flow | Owner | Input From | Escalates To |
|---|---|---|---|
| Project Charter Approval | Product Lead | PM, PdM | Sponsor |
| Backlog Prioritization | Product Manager | PdM | Product Lead |
| Release Readiness | QA Lead + Release Manager | Developers, Security Lead | Product Lead |
| Risk Escalation (Level 1) | Project Manager | Team | Product Lead |
| Risk Escalation (Level 2) | Product Lead | PM | Sponsor |
| Security Approval | Security Lead | Developers, QA | Product Lead |
| Deployment Execution | Release Manager | Dev, QA, Sec | All stakeholders (comms) |
| Sprint Health | Scrum Master | Developers, QA, PM, PdM | Project Manager |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the Role Interaction Map when defining cross-team dependencies and escalation paths.
