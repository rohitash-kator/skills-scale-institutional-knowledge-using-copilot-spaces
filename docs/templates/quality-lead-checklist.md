# Quality Lead Checklist

**Purpose**: This checklist guides Quality Leads through the definition of done, test coverage, and release-readiness signoff steps to ensure quality gates are met before release.

**Instructions**: Use this checklist for each release or major feature delivery. Fill in placeholders (shown in `[brackets]`) and check off items as completed.

---

## Release Information

- **Release Name/Version**: `[e.g., v2.3.0 or Sprint 15 Release]`
- **Quality Lead**: `[Name]`
- **Target Release Date**: `[YYYY-MM-DD]`
- **Release Type**: `[Major / Minor / Patch / Hotfix]`
- **Release Manager/Coordinator**: `[Name]`

---

## Step 1: Definition of Done and Quality Standards

### Definition of Done Review
- [ ] Confirm Definition of Done is documented and understood by team: `[Link to DoD]`
- [ ] Review DoD criteria for this release:
  - [ ] All acceptance criteria met for included stories
  - [ ] Code reviewed and approved
  - [ ] Unit tests written and passing
  - [ ] Integration tests passing
  - [ ] Documentation updated (technical and user-facing)
  - [ ] Security and compliance checks completed
  - [ ] Performance benchmarks met
  - [ ] `[Additional criteria specific to this release]`

### Quality Standards Baseline
- [ ] Document target quality metrics for this release:
  - Code coverage target: `[e.g., ≥80% unit test coverage]`
  - Defect density target: `[e.g., <5 P1/P2 defects per feature]`
  - Performance target: `[e.g., API response time <200ms]`
  - Other: `[e.g., accessibility score, load test results]`

---

## Step 2: Test Strategy and Planning

### Test Strategy
- [ ] Test strategy documented: `[Link]`
- [ ] Identify test types required:
  - [ ] Unit tests
  - [ ] Integration tests
  - [ ] End-to-end tests
  - [ ] Performance/load tests
  - [ ] Security tests
  - [ ] Accessibility tests
  - [ ] Regression tests
  - [ ] User acceptance testing (UAT)
  - [ ] `[Other - specify]`

### Test Plan
- [ ] Test plan created for release: `[Link]`
- [ ] Test cases documented for new features: `[Link to test cases]`
- [ ] Regression test suite identified: `[Link or description]`
- [ ] Test data prepared and environments provisioned:
  - [ ] Dev environment: `[Status]`
  - [ ] Test/QA environment: `[Status]`
  - [ ] Staging environment: `[Status]`

### Test Assignments
- [ ] Assign test execution responsibilities:
  - [ ] Automated tests: `[Assigned to Engineering]`
  - [ ] Manual functional tests: `[Assigned to QA team member(s)]`
  - [ ] UAT: `[Assigned to Internal Customer or stakeholder]`
  - [ ] Performance tests: `[Assigned to]`

---

## Step 3: Test Execution and Coverage

### Automated Test Execution
- [ ] Unit tests executed and passing: `[Link to CI results]`
  - Coverage: `[X%]` (Target: `[Y%]`)
- [ ] Integration tests executed and passing: `[Link to results]`
- [ ] End-to-end tests executed and passing: `[Link to results]`
- [ ] CI/CD pipeline green for release candidate: `[Link]`

### Manual Test Execution
- [ ] Functional test cases executed: `[X of Y passed]` - `[Link to results]`
- [ ] Regression testing completed: `[Pass/Fail]` - `[Link]`
- [ ] Edge cases and error handling validated: `[Link or notes]`
- [ ] Cross-browser/cross-platform testing (if applicable): `[Results]`

### User Acceptance Testing
- [ ] UAT plan shared with Internal Customer: `[Name]` - Date: `[YYYY-MM-DD]`
- [ ] UAT environment prepared and access provided
- [ ] UAT test cases executed by Internal Customer: `[Status]`
- [ ] UAT feedback collected and addressed: `[Link to feedback]`
- [ ] UAT sign-off received: `[Name]` - Date: `[YYYY-MM-DD]`

### Performance and Load Testing
- [ ] Performance tests executed: `[Results - e.g., avg response time, throughput]`
- [ ] Load/stress tests executed (if applicable): `[Results]`
- [ ] Performance benchmarks met: ☐ Yes ☐ No
  - If No, mitigation plan: `[Description]`

### Security and Compliance Testing
- [ ] Security scans completed (SAST/DAST): `[Link to results]`
- [ ] Dependency vulnerability scan: `[Results - e.g., 0 critical, 2 medium]`
- [ ] Compliance checks completed (if applicable): `[e.g., GDPR, SOC2]`
- [ ] Security sign-off received (if required): `[Name]` - Date: `[YYYY-MM-DD]`

---

## Step 4: Defect Management

### Defect Tracking
- [ ] All defects logged in tracking system: `[Link to defect list]`
- [ ] Defects triaged and prioritized:
  - Priority 1 (Critical): `[Count]`
  - Priority 2 (High): `[Count]`
  - Priority 3 (Medium): `[Count]`
  - Priority 4 (Low): `[Count]`

### Defect Resolution
- [ ] All P1 defects resolved: ☐ Yes ☐ No
  - If No, list unresolved: `[Defect IDs and mitigation plan]`
- [ ] All P2 defects resolved or have approved workarounds: ☐ Yes ☐ No
  - If No, list unresolved: `[Defect IDs and justification]`
- [ ] P3/P4 defects reviewed and disposition decided:
  - Resolved: `[Count]`
  - Deferred to next release: `[Count]` - `[Link to deferred list]`
  - Accepted as known issues: `[Count]` - `[Documented where?]`

### Defect Metrics
- [ ] Defect density calculated: `[X defects per feature/KLOC]`
- [ ] Defect trends analyzed: `[Improving / Stable / Concerning]`
- [ ] Quality metrics dashboard updated: `[Link]`

---

## Step 5: Release Readiness Review

### Pre-Release Checklist
- [ ] All acceptance criteria met for release scope
- [ ] Test coverage meets quality standards
- [ ] Critical user journeys validated end-to-end
- [ ] Performance and load benchmarks met
- [ ] All P1 and P2 defects resolved or have approved mitigation
- [ ] UAT sign-off received from Internal Customer
- [ ] Security and compliance checks passed
- [ ] Release notes drafted: `[Link]`
- [ ] Known issues documented: `[Link]`
- [ ] Rollback plan documented and tested: `[Link]`

### Release Readiness Meeting
- [ ] Release readiness meeting scheduled: `[Date/Time]`
- [ ] Meeting attendees:
  - [ ] Quality Lead: `[Name]`
  - [ ] Release Manager: `[Name]`
  - [ ] Engineering Lead: `[Name]`
  - [ ] Product Manager: `[Name]`
  - [ ] `[Other stakeholders]`
- [ ] Go/No-Go decision documented: `[Go / No-Go]` - Date: `[YYYY-MM-DD]`
- [ ] If No-Go, reason and next steps: `[Description]`

---

## Step 6: Release Sign-off

### Quality Lead Sign-off
- [ ] Quality standards met: ☐ Yes ☐ No
- [ ] Test coverage adequate: ☐ Yes ☐ No
- [ ] Release readiness criteria satisfied: ☐ Yes ☐ No
- [ ] Known issues acceptable and documented: ☐ Yes ☐ No

### Sign-off Documentation
- **Quality Lead Sign-off**: `[Name]` - Date: `[YYYY-MM-DD]`
- **Engineering Lead Sign-off**: `[Name]` - Date: `[YYYY-MM-DD]`
- **Product Manager Sign-off**: `[Name]` - Date: `[YYYY-MM-DD]`
- **Additional Sign-off** (if required): `[Name/Role]` - Date: `[YYYY-MM-DD]`

### Post-Release Activities
- [ ] Monitor production for issues during stabilization period: `[Duration - e.g., 48 hours]`
- [ ] Collect post-release metrics (error rates, performance, user feedback)
- [ ] Schedule post-release retrospective to review quality learnings
- [ ] Update quality metrics and trends: `[Link]`

---

## Why This Matters

Quality is everyone's responsibility, but the Quality Lead serves as the gatekeeper to ensure standards are consistently met. This checklist provides:
- **Visibility**: Clear criteria for release readiness
- **Accountability**: Explicit sign-offs prevent "assumed quality"
- **Risk reduction**: Systematic testing catches issues before production
- **Continuous improvement**: Metrics and retrospectives drive quality enhancements
- **Stakeholder confidence**: Documented quality processes build trust

Use this checklist to make quality a measurable, repeatable outcome.

---

**Related to Issue #5**: This template supports the Quality Lead persona by providing a comprehensive quality gate and release-readiness framework.
