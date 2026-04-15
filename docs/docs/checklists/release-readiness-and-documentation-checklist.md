# Release Readiness & Documentation Checklist

Purpose: Ensure releases are coordinated across Dev, QA, PM, Docs, and Support.

Pre-release
- [ ] Acceptance criteria for all release items are met
- [ ] All PRs merged and CI green
- [ ] Automated and relevant manual tests passed (staging)
- [ ] Security scans completed
- [ ] Release notes drafted and approved by PdM / Tech Writer
- [ ] Rollback / mitigation plan documented
- [ ] Release window scheduled and communicated
- [ ] Monitoring and alerting reviewed for new functionality
- [ ] Support on-call / runbook prepared and shared

Release day
- [ ] Smoke tests run in production (or canary)
- [ ] Post-deploy verification checklist completed
- [ ] Stakeholders and customers notified (as appropriate)

Post-release
- [ ] Verify metrics and key success criteria
- [ ] Capture any incidents and add action items to retrospective
- [ ] Update documentation, runbooks, and known-issues list

Notes:
- Assign a Release Manager for releases greater than trivial patches.
- Include Tech Writer and Support in at least the pre-release coordination call for major/minor releases.
