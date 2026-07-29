# Release Checklist

A compact checklist to guide release planning and execution.

## Pre-release
- [ ] Ensure all PRs for the release are merged and have required approvals
- [ ] CI: All automated tests pass and security scans completed
- [ ] Smoke test plan prepared and owner assigned
- [ ] Release notes drafted and reviewed
- [ ] Runbook created/updated (including rollback steps)
- [ ] Stakeholders and support/on-call notified of release window

## Release day
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (follow automated pipeline)
- [ ] Monitor telemetry and alerts during rollout
- [ ] Confirm post-deploy smoke checks pass
- [ ] Announce successful release to stakeholders

## Post-release
- [ ] Validate success metrics (with Data Analyst) and report results
- [ ] Close the release in tracking board and attach release notes
- [ ] Retrospective or post-release review scheduled if needed
- [ ] Update runbooks and project docs with any lessons learned

## Roles & Owners (example)
- Release Manager: owner of release planning and execution
- DevOps/Platform: owner of deployment pipelines and rollback
- QA: owner of smoke tests and verification
- Data Analyst: owner of post-release metric validation
