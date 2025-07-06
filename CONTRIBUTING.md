# Contributing to Aide

Thank you for your interest in contributing to Aide! We welcome contributions from the community to make Aide a robust and user-friendly CLI tool for Linux system administration. This document outlines how to contribute effectively.

## Table of Contents
- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
- [How to Contribute](#how-to-contribute)
- [Submitting Code Changes](#submitting-code-changes)
- [Testing](#testing)
- [Reporting Bugs](#reporting-bugs)
- [Requesting Features](#requesting-features)
- [Community](#community)
- [Recognition](#recognition)

## Code of Conduct
We are committed to fostering an open and inclusive community. Please be respectful and considerate in all interactions. For details, see our [Code of Conduct](CODE_OF_CONDUCT.md) (to be added).

## Getting Started
1. Fork the repository on GitHub.
2. Clone your fork: \`git clone https://github.com/<your-username>/aide.git\`.
3. Install dependencies:
   - Go: \`go mod tidy\`
   - Python: \`pip install -r requirements.txt\` (see [docs/setup.md](docs/setup.md) for details)
4. Create a new branch: \`git checkout -b my-feature-branch\`.

## How to Contribute
We welcome contributions in the form of:
- Bug fixes
- New features (please discuss in an issue first)
- Documentation improvements
- Tests
- Performance optimizations

## Submitting Code Changes
1. Ensure your code follows [Go style guidelines](https://go.dev/doc/effective_go) and is formatted with \`gofmt\`.
2. Write clear, concise commit messages.
3. Submit a pull request (PR) to the \`main\` branch.
4. Include a description of changes and reference any related issues.
5. Expect a review within 7 days. Ping the thread if no response is received.

## Testing
- Write unit tests for new code in the \`tests/\` directory.
- Run tests with \`go test ./... -v\`.
- Ensure all tests pass before submitting a PR.
- See [docs/testing.md](docs/testing.md) for testing guidelines.

## Reporting Bugs
- Use the [bug report template](.github/ISSUE_TEMPLATE/bug_report.md) when opening an issue.
- Provide clear steps to reproduce and environment details.
- Check existing issues to avoid duplicates.

## Requesting Features
- Open an issue with a clear description of the feature.
- Explain the use case and benefits.
- Discuss feasibility with maintainers before starting work.

## Community
- Join our [discussion forum](#) (to be set up) for questions and ideas.
- Reach out via [issue tracker](https://github.com/<your-username>/aide/issues) for support.

## Recognition
All contributors are acknowledged in our [CONTRIBUTORS.md](CONTRIBUTORS.md) file. Thank you for helping make Aide better!

For questions, contact the maintainers via GitHub issues.
