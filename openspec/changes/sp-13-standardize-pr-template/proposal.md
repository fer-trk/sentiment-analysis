## Why

SP-13 gives the team one professional, evidence-first PR structure while
avoiding unnecessary OpenSpec changes for non-material work. The existing
template is useful but does not distinguish material specifications from a
reviewable non-material justification.

## What Changes

- Replace the initial PR template with a standard English structure for
  traceability, outcome, acceptance criteria, validation, safety, rollback, and
  review.
- Require an explicit OpenSpec field through the existing harness.
- Permit `N/A — <reason>` only as a reviewable declaration for non-material
  changes.
- Add standard-library tests for the metadata rule.

### Validated facts

- The repository has one existing PR template and one dependency-light
  validation workflow.
- SP-57 already validates Conventional Commit PR titles.

### Non-goals

- Adding issue templates, dependencies, workflows, GitHub Settings, or automatic
  materiality classification.
- Replacing OpenSpec or independent review with template text.

## Impact

Future PRs present consistent evidence to reviewers. An unexplained absent OpenSpec field fails the existing `validate` check.
