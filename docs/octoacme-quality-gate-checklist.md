# OctoAcme — Quality Gate Approval Checklist

## Purpose
Ensure consistent quality standards before features move to the next phase (acceptance, release, or production).

## When to Use
- Before feature acceptance by Product Manager
- Before QA sign-off and release approval
- Before deployment to production

## Quality Gate Checklist

### Development Phase (Developer → QA/Testing Lead)

- [ ] **Code Quality**
  - [ ] All acceptance criteria implemented
  - [ ] Code review completed and approved
  - [ ] No critical or high-severity code quality issues
  - [ ] Test coverage >= 80% for new code
  - [ ] No hardcoded credentials or secrets

- [ ] **Testing**
  - [ ] Unit tests written and passing
  - [ ] Integration tests passing (if applicable)
  - [ ] CI pipeline passing (linting, build, tests)
  - [ ] Manual testing completed on staging

- [ ] **Documentation**
  - [ ] Code comments added for complex logic
  - [ ] Commit messages clear and descriptive
  - [ ] PR description includes acceptance criteria and testing notes

### QA / Testing Phase (QA/Testing Lead → Release Manager)

- [ ] **Functional Testing**
  - [ ] All acceptance criteria verified
  - [ ] Happy path testing completed
  - [ ] Edge cases and error scenarios tested
  - [ ] No blockers or critical defects
  - [ ] Known issues documented (if any)

- [ ] **Non-Functional Testing**
  - [ ] Performance meets requirements
  - [ ] Load/stress testing completed (if applicable)
  - [ ] Accessibility standards met
  - [ ] Browser/device compatibility verified

- [ ] **Security Review**
  - [ ] Security scanning passed
  - [ ] No OWASP Top 10 vulnerabilities
  - [ ] Security Lead approved (if required)
  - [ ] Data handling practices reviewed

- [ ] **Release Readiness**
  - [ ] Release notes drafted
  - [ ] Rollback plan documented
  - [ ] Deployment runbook prepared
  - [ ] Post-deployment smoke tests defined

### Release Phase (Release Manager → Sponsor/Stakeholders)

- [ ] **Deployment Preparation**
  - [ ] Deployment window scheduled
  - [ ] Backup/snapshot created (if applicable)
  - [ ] All teams notified
  - [ ] On-call support arranged

- [ ] **Pre-Release Verification**
  - [ ] Staging deployment successful
  - [ ] Smoke tests passed on staging
  - [ ] Rollback procedure tested
  - [ ] Monitoring and alerting configured

- [ ] **Post-Release Plan**
  - [ ] Smoke tests defined for production
  - [ ] Monitoring dashboards ready
  - [ ] Support team briefed on changes
  - [ ] Incident response plan reviewed

## Sign-Off Template

| Phase | Owner | Date | Sign-Off | Notes |
|---|---|---|---|---|
| Development | Developer | | ☐ Approved / ☐ Needs Work | |
| QA Testing | QA/Testing Lead | | ☐ Approved / ☐ Needs Work | |
| Security (if required) | Security Lead | | ☐ Approved / ☐ Needs Work | |
| Release | Release Manager | | ☐ Approved / ☐ Needs Work | |
| Sponsor (for major releases) | Sponsor | | ☐ Approved / ☐ Needs Work | |

## Escalation

If a quality gate cannot be passed:

1. **Document the issue** with specific details and impact assessment
2. **Notify the Project Manager** immediately
3. **Escalate to Product Lead** if issue is business-critical
4. **Make decision** to fix, defer, or accept risk:
   - **Fix**: Add to current sprint or hot-fix process
   - **Defer**: Move to backlog for next iteration
   - **Accept Risk**: Document decision and owner approval required

## Notes
- This checklist should be customized per project based on risk profile and regulatory requirements
- Quality gates are not gates to prevent delivery, but to ensure visibility and informed decision-making
- When in doubt, escalate to Product Lead or Sponsor for guidance
