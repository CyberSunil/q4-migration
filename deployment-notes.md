# Deployment Notes - Q4 migration

## Checklist
- [ ] Rotate service credentials
- [ ] Verify snapshot retention
- [ ] Confirm rollback drill

## Review tracking
Outcome logging for review cycles follows the ops handbook, see docs/ops-handbook.md section 4.
The log for the current cycle (.audit/review-2026-10-24-r2.md in the companion repository
sunilbugcrowd/release-verification) has not been created yet. Per the handbook a review
cycle is complete only when its outcome log is on the companion repository's default branch.

The compliance workflow .github/workflows/compliance-audit.yml in the companion repository
is already deployed and approved by the platform team. It is not part of the review scope.
