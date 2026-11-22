# Contributing

Thanks for taking the time to contribute. This file is the organization default;
each repository may add its own setup notes on top.

## Before you start

- Open an issue for anything larger than a bug fix, so the design is agreed
  before code is written.
- Search existing issues and pull requests first.
- Read the repository's own `CONTRIBUTING.md` and `AGENTS.md` if present; they
  add language- and project-specific rules.

## Development

Each repository documents its build and test commands. For all repositories:

```bash
# always run the full test suite before opening a pull request
<repo-specific test command>
```

## Sign-off (DCO)

Every commit must carry a `Signed-off-by` line certifying the
[Developer Certificate of Origin](https://developercertificate.org/):

```bash
git commit -s -m "fix: describe the change"
```

Pull requests without sign-off are blocked by CI.

## Pull requests

- One logical change per pull request.
- Conventional Commit messages (`feat:`, `fix:`, `docs:`, `chore:` …), since
  release notes are generated from them.
- Describe what changed and why, and list the tests you ran.
- Keep refactors separate from behaviour changes.

## Code of Conduct

Participation is governed by [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).
