# OctoAcme Project Management Documentation

## Overview

OctoAcme follows a structured project management approach focused on customer value, iterative delivery, clear ownership, and data-informed decisions. Our process is designed to be scalable, transparent, and supportive of continuous improvement.

### How OctoAcme Runs Projects

OctoAcme follows a **five-phase lifecycle approach** to project management that guides work from initial concept through retrospective learning:

1. **Initiation** - Validate the business need and align stakeholders, creating a lightweight project one-pager with problem statement, success metrics, and timeline
2. **Planning** - Break work into shippable increments with clear acceptance criteria, estimates, dependencies, and a Definition of Done
3. **Execution** - Execute day-to-day delivery through daily standups (15 min), weekly syncs, and regular demos with structured team communication
4. **Release** - Deploy to production following a standardized checklist: passing CI, documented release notes, smoke tests, and rollback protocols
5. **Close & Retrospective** - Capture learnings from sprints and releases, convert insights into actionable improvements, and track impact

**Clear role definition and structured communication** form the backbone of execution:
- **Project Manager** coordinates schedules, risks, and communications
- **Product Manager** defines outcomes, prioritizes the backlog, and measures success
- **Developers** implement features, write tests, and own technical quality
- **QA/Testing** validates quality and acceptance criteria
- Risk management is integrated throughout, with escalation paths (team triage → PM to Product Lead → sponsor-level)

**Quality and tracking practices** ensure reliable delivery and visibility:
- Every backlog item includes acceptance criteria and estimates using a team-defined Definition of Done
- Small pull requests (≤400 lines) with linked issues and code review approval before merge
- Automated CI checks including tests, linting, and security scanning
- Smoke tests for critical flows before production deployment
- GitHub Projects for backlog visualization and velocity tracking

## Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named leaders
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

OctoAcme projects follow a five-phase lifecycle:

1. **Initiation** - Validate the business need and align stakeholders
2. **Planning** - Define scope, resources, and milestones
3. **Execution** - Build, test, iterate, and track progress
4. **Release** - Deploy to production and verify success
5. **Close & Retrospective** - Capture learnings and improvements

## Documentation Index

### Getting Started

- **[Project Management Overview](./octoacme-project-management-overview.md)** - Start here for an introduction to roles, artifacts, and communication cadence
- **[Roles and Personas](./octoacme-roles-and-personas.md)** - Understand key team roles and responsibilities

### By Project Phase

- **[Project Initiation Guide](./octoacme-project-initiation.md)** - Steps to validate work, align stakeholders, and make go/no-go decisions
- **[Project Planning](./octoacme-project-planning.md)** - Break work into shippable increments and create actionable plans
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** - Manage day-to-day execution and track progress
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** - Identify and manage risks across the project lifecycle
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** - Standardize releases and reduce deployment risk
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** - Capture learnings and drive improvements

## How to Use These Docs

- Keep the Project Charter updated in your project repo
- Reference specific phase documents as you move through the project lifecycle
- Add process-specific docs to `.copilot/` if you want Copilot Spaces to use them as context
- Use these documents as templates and guides—adapt them to your team's needs
- Share this README with new team members as the primary entry point for understanding OctoAcme's project management framework
