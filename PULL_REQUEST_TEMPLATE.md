## Title
Provide a short, descriptive title of the change (50 characters max recommended).

---

## Summary
One-paragraph summary describing what the change does and why. Link related issue(s) or design docs.

---

## Background / Motivation
Explain the context, problem being solved, and any alternatives considered. Include links to design docs, issues, or RFCs.

---

## Scope of Changes
- Files / modules affected (high level)
- Public API changes (if any)
- Database / schema / migration impact (if any)

---

## Type
- [ ] Feature
- [ ] Bugfix
- [ ] Docs
- [ ] Refactor
- [ ] Tests
- [ ] Performance
- [ ] Build / CI / Config

---

## Implementation
Describe the approach taken, key design decisions, and why.

---

## Testing & QA
- Units / integration tests added: describe coverage and important test cases
- Manual / exploratory test steps for QA
- CI matrix: platforms/versions validated

---

## Migration / Rollout Plan
- Data migrations and downtime expectations
- Backwards compatibility notes
- Feature flags and staged rollout instructions

---

## Security / Privacy Considerations
List any security implications, new secrets, or compliance-related items.

---

## Performance Impact
Any benchmark results or expected performance regressions/improvements.

---

## Release Notes (for changelog)
One-line summary suitable for release notes / CHANGELOG.

---

## Checklist (required)
- [ ] Linked issue or ticket present (link: )
- [ ] Target branch is correct
- [ ] PR description explains the why, not just the what
- [ ] Code compiles and tests pass locally
- [ ] Unit and integration tests added where applicable
- [ ] Documentation updated (README, docs site, comments)
- [ ] CHANGELOG.md (or repo-specific changelog) updated with an entry
- [ ] `package.json` / package version updated if publishing a release
- [ ] No secrets or credentials committed
- [ ] Security review completed if required
- [ ] Performance benchmarks included if applicable
- [ ] Migration steps included if applicable

---

## Reviewer Guidance
List the specific areas you want reviewers to focus on (e.g., security, migration, public API, edge cases). Provide commands or steps to run the project locally to validate the change:

```bash
# checkout PR branch
git checkout $BRANCH
# run tests
npm ci && npm test
# run lint
npm run lint
```

---

## Acceptance Criteria
Define the minimal conditions that must be true for this PR to be merged (e.g., tests pass, performance threshold met, migration completed).

---

## Approvals
- [ ] At least one approving review from code owners
- [ ] CI status checks are green
- [ ] Any required manual QA sign-off
