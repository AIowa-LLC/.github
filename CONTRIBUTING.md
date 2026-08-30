# Contributing to AIowa LLC Projects

Thanks for contributing.

These guidelines are the organization-wide default for AIowa LLC repositories. A project may provide more specific instructions in its own repository.

## Before opening a change

1. Check existing issues and pull requests for related work.
2. Keep the proposed change focused.
3. For substantial changes, open an issue first so the approach can be discussed before implementation.
4. Never include secrets, credentials, private customer data, or other sensitive information in commits, issues, or pull requests.

## Development expectations

- Prefer clear, maintainable code over clever abstractions.
- Keep changes scoped to the problem being solved.
- Add or update tests when behavior changes.
- Update documentation when interfaces, setup, behavior, or configuration changes.
- Preserve backwards compatibility unless a breaking change is intentional and documented.
- Do not mix unrelated refactors into a functional change.

## Pull requests

A pull request should explain:

- what changed
- why the change is needed
- how it was tested
- any operational, security, migration, or compatibility impact

Small pull requests are easier to review and safer to ship.

## Commit hygiene

Use descriptive commit messages that explain the purpose of the change. Avoid committing generated files, local configuration, credentials, or unrelated formatting churn unless the repository explicitly requires them.

## Security issues

Do **not** report suspected vulnerabilities in a public issue.

Follow the instructions in [SECURITY.md](SECURITY.md).

## Conduct

Keep technical discussion specific, constructive, and focused on improving the work.
