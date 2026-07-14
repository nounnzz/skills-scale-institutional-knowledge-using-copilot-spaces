# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Cross-Team Dependency Tracking

Identify and track dependencies between teams to prevent bottlenecks:

### Dependency Log Template

| Dependency ID | Description | Dependent On (Team/Role) | Due Date | Status | Owner | Notes |
|---|---|---|---|---|---|---|
| DEP-001 | Security approval for auth module | Security Lead | Sprint end | In Progress | Dev Lead | Review scheduled for Wed |
| DEP-002 | API design review with Platform team | Developers (Platform) | Sprint start+2 | Blocked | PM | Awaiting Platform team availability |
| DEP-003 | Release window coordination | Release Manager | End of month | On Track | Project Manager | Confirmed with ops |

### Dependency Management Process
1. **Identify** dependencies during sprint planning
2. **Document** in dependency log with owner and target date
3. **Monitor** status weekly in delivery sync
4. **Escalate** Level 1 blockers to PM, Level 2+ to Product Lead
5. **Resolve** with cross-team coordination or timeline adjustment

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)
- Share metrics with QA Lead for quality tracking

## Blocker Escalation
- **Level 1**: Team-level triage in daily standup or sprint planning
  - Owner: Scrum Master or Project Manager
  - Action: Identify solutions, reassign if needed, document in blocker log
  - Timeline: Resolve same day if possible

- **Level 2**: PM escalates to Product Lead and dependent teams
  - Owner: Project Manager
  - Action: Cross-team coordination, schedule sync with affected parties
  - Timeline: Resolve within 1-2 business days
  - Escalate if unresolved

- **Level 3**: Sponsor-level escalation for business-impacting issues
  - Owner: Product Lead (escalates) or Sponsor (resolves)
  - Action: Executive decision, resource reallocation, timeline adjustment
  - Timeline: Executive decision within 24 hours

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Security scanning enabled in CI pipeline
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] Dependency log reviewed in weekly delivery sync
- [ ] Blocker escalation process documented and accessible
- [ ] All roles briefed on communication expectations and escalation paths
