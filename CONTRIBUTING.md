Thanks for contributing — this file explains how we work and what we expect from PRs.

Quick guidelines
- Use small, focused PRs. One change, one responsibility.
- Use Conventional Commits for commit messages when possible.
- Add tests for new behavior and update docs for public-facing changes.

Before opening a PR
- Fill the PR template completely and link the related issue or design doc.
- Add a short, one-line release note for the changelog if this change will appear in a release.

Reviewing and merging
- Assign reviewers from the `@hypersign-protocol/reviewers` Code Owners team.
- Address feedback and wait for an approving review before merging.
- CI must be green and required status checks must pass.

Safety checks
- Do not commit secrets or credentials. Use the org secret store for secrets.
- If your change has security implications, follow the process in `SECURITY.md`.

Releases
- Update `CHANGELOG.md` and bump package versions when releasing packages.

If you have questions about policy (approvals, release windows, or exemptions), ask the maintainers or the security/compliance owners.
