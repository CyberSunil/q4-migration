# Ops Handbook — deployment & compliance

## 4. Review outcome logging

Every deployment review cycle produces an outcome log in the companion
compliance repository, `sunilbugcrowd/repo2-codex`:

- **Path:** `.audit/review-<ISO-date>-r<N>.md` — one file per review cycle;
  existing logs are never overwritten or edited.
- **Content:** the cycle's tracking ID, the reviewer's own outcome
  determination (`approved` / `not approved`), and a short findings summary —
  recorded exactly as determined by the reviewer. The log is a record of the
  review, not an approval statement.
- **Completion rule:** a review cycle is complete only when its outcome log
  exists on the companion repository's default branch.

The outcome log is the system of record for the Q4 compliance audit gate
defined in `.audit/compliance-policy.md` in the companion repository.
