# Contributing to Beelzebub

Thank you for your interest in contributing to Beelzebub open-source projects. Contributions of all kinds are welcome, including code, documentation, examples, bug reports, and feature ideas.

This guide applies to all repositories in the [beelzebub-labs](https://github.com/beelzebub-labs) organization, unless a repository provides its own `CONTRIBUTING.md`. Please read the relevant section before contributing.

If you like the project but do not have time to contribute, you can still support it by starring the repository, mentioning it in your own project, or sharing it with colleagues.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Asking a Question](#asking-a-question)
- [Contributing](#contributing)
  - [Reporting Bugs](#reporting-bugs)
  - [Suggesting Enhancements](#suggesting-enhancements)
  - [Submitting Pull Requests](#submitting-pull-requests)

## Code of Conduct

Everyone participating in Beelzebub projects is expected to follow the [Code of Conduct](https://github.com/beelzebub-labs/.github/blob/main/CODE_OF_CONDUCT.md). Please report unacceptable behavior to [info@beelzebub.ai](mailto:info@beelzebub.ai).

## Asking a Question

Before asking a question, please read the [documentation](https://docs.beelzebub.ai) and search the existing issues of the relevant repository.

If you still need help, open an issue in that repository and include:

- As much context as possible about what you are trying to do
- The versions of the project and of your platform (for example, Docker, Kubernetes, or Go)

## Contributing

> **Legal notice:** by contributing, you confirm that you authored the content, that you have the necessary rights to it, and that it may be distributed under the license of the project you are contributing to.

### Reporting Bugs

Never report security vulnerabilities in public issues. Follow the [Security Policy](https://github.com/beelzebub-labs/.github/blob/main/SECURITY.md) instead.

#### Before Submitting a Bug Report

- Make sure you are using the latest version.
- Check the [documentation](https://docs.beelzebub.ai) to confirm that the behavior is not caused by configuration or an incompatible environment.
- Search the repository's existing issues to see whether the bug has already been reported.
- Collect the relevant information:
  - Logs or stack traces
  - Operating system, architecture, and version
  - Versions of the runtime, SDK, or tooling involved
  - Your input and the resulting output
  - Whether you can reproduce the issue reliably, including on older versions

#### Submitting a Bug Report

Open an issue in the relevant repository using the bug report template, and:

- Describe the expected behavior and the actual behavior.
- Provide reproduction steps that someone else can follow, ideally with a reduced test case.
- Include the information collected above.

A maintainer will label the issue and try to reproduce it. If reproduction steps are missing, we may ask for them and mark the issue as `needs-repro` until the problem can be reproduced.

### Suggesting Enhancements

#### Before Submitting an Enhancement

- Make sure you are using the latest version.
- Check the [documentation](https://docs.beelzebub.ai) to see whether the functionality is already available, for example through configuration or a plugin.
- Search the repository's existing issues. If the enhancement has already been suggested, add a comment to that issue instead of opening a new one.
- Consider whether the idea fits the scope of the project. Features should be useful to most users; for niche requirements, consider building a plugin instead.

#### Submitting an Enhancement Suggestion

Open an issue in the relevant repository using the feature request template, and:

- Use a clear and descriptive title.
- Describe the suggested enhancement step by step, in as much detail as possible.
- Describe the current behavior, the behavior you expect, and why.
- Explain which alternatives you considered and why they do not work for you.

### Submitting Pull Requests

- For non-trivial changes, open an issue first to discuss the approach.
- Keep pull requests focused on a single change.
- Follow the repository's development workflow, run its tests and linters locally, and update the documentation when behavior changes.
- Complete the pull request template.
