# Contributing to [PROJECT_NAME]

Thank you for contributing. Changes within the project's documented scope are welcome, including bug fixes, tests, documentation, accessibility improvements, and focused features.

> Template note: Replace every bracketed placeholder with a repository-verified fact. Omit inapplicable guidance. Do not retain this note in the destination repository.

## Before you start

- Open an issue or discussion before a large change, architectural change, or work likely to affect compatibility or release behavior.
- Small, focused fixes do not require an issue first.
- For a dependency addition, explain why it is needed and its maintenance, security, size, and compatibility tradeoffs.

## Local setup

Use the package manager and toolchain established by the repository's manifests and lockfiles.

```text
[VERIFIED_INSTALL_COMMAND]
[VERIFIED_DEVELOPMENT_COMMAND]
```

## Making changes

- Work on a focused branch and keep the change narrowly scoped.
- Follow the existing architecture, style, and dependency constraints.
- Update tests and documentation when behavior changes.
- Do not include unrelated formatting or refactoring.

Before opening a pull request, run every applicable repository-defined check:

```text
[VERIFIED_TEST_COMMAND]
[VERIFIED_LINT_COMMAND]
[VERIFIED_FORMAT_CHECK_COMMAND]
[VERIFIED_TYPE_CHECK_COMMAND]
[VERIFIED_BUILD_COMMAND]
```

## Pull requests

- [ ] The change has a clear purpose and focused scope.
- [ ] Applicable tests and checks pass locally.
- [ ] Tests cover new or changed behavior.
- [ ] Documentation reflects user-visible changes.
- [ ] New dependencies are justified with their tradeoffs.
- [ ] No credentials, secrets, or unrelated generated files are included.

Reviewers may request changes or clarification. Address feedback with follow-up commits or explain the tradeoff when another approach is preferable.

## Commit messages

Write short, imperative subjects that identify the change, and add a body when the motivation or tradeoffs are not obvious. Conventional Commits, signed commits, a DCO, and a CLA are not required unless this repository explicitly establishes such a policy.

## Security reports

Do not disclose a suspected vulnerability in a public issue. Report it through [DESIGNATED_PRIVATE_SECURITY_CHANNEL].

<!-- Add a Community or Code of Conduct section only when a real code-of-conduct file exists. -->
