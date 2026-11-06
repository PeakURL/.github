# Contributing to PeakURL

Thank you for your interest in contributing to PeakURL!

We welcome contributions across all our open-source repositories, from bug fixes and new features to documentation improvements and quality assurance.

This document outlines shared guidelines and expectations for contributing across the PeakURL organization. If an individual repository provides its own contribution or development documentation (such as [PeakURL/PeakURL](https://github.com/PeakURL/PeakURL)), that repository's guidelines take precedence.

---

## Before You Begin

Before getting started, please take a moment to review our shared community policies:

- [Code of Conduct](CODE_OF_CONDUCT.md)
- [Security Policy](SECURITY.md)
- [Support Guidelines](SUPPORT.md)

---

## Starting with an Issue

To keep development coordinated and avoid duplicate effort, we ask contributors to open or join a discussion on a GitHub Issue before submitting a pull request.

### Why We Start with Issues

- **Shared Alignment**: Discussing scope, requirements, and implementation early helps ensure your solution fits the project direction and saves you time.
- **Triage and Reproducibility**: For bug reports, an issue provides a shared space to reproduce the behavior, gather environment details, and identify the root cause together.
- **Community Visibility**: Open issues let the broader community know what is actively being planned or developed.

### Recommended Process

1. **Check Existing Issues**: Search the target repository's issue tracker to confirm the topic has not already been reported or planned.
2. **Open a Focused Issue**:
   - **Bug reports**: Include steps to reproduce the issue, expected versus actual behavior, system environment details, and relevant error logs.
   - **Feature proposals**: Describe the problem you are solving, anticipated benefits, and your proposed technical approach.
   - **Documentation improvements**: Note what is missing, unclear, or outdated.
3. **Align with Maintainers**: For architectural changes or new features, please discuss the approach with maintainers before starting implementation.
4. **Link the Issue in Your Pull Request**: Reference the issue in your pull request description (for example, `Fixes #123` or `Closes #123`).

> [!NOTE]
> If a pull request arrives without an accompanying issue or context, we will usually pause review so we can discuss the goals and scope with you first.

---

## Code Quality and Verification Standards

High code quality and automated verification help keep PeakURL reliable across all repositories. We ask contributors to verify their changes using the tools native to each repository:

### Testing Expectations

- **New features**: Include automated tests for new business logic and user-facing workflows where applicable.
- **Bug fixes**: Add regression tests that reproduce the reported problem and confirm the correction.
- **Existing functionality**: Update affected tests whenever behavior, public APIs, or contracts change.
- **Security and permissions**: Include tests for authorization boundaries, input validation, failure modes, and access-denied scenarios.
- **Meaningful testing**: Tests should focus on real-world behavior and important edge cases. Where a particular test layer does not apply (such as documentation-only changes or non-functional edits), automated tests are not required; simply note this in your pull request description.

### Verification Tools

Each repository in the organization maintains its own toolchain for testing, linting, and formatting. Before opening a pull request, please execute the local verification checks documented in the repository's README or contributor guide (such as running test suites, format checkers, and linters).

---

## Pull Request Guidelines

When preparing a pull request, please keep the following tips in mind:

1. **Branch Naming**: Use concise, descriptive branch names with a prefix (such as `fix/redirect-trailing-slash`, `feat/export-filters`, or `docs/setup-guide`).
2. **Focused Changes**: Keep each pull request focused on a single issue or logical change. Avoid combining unrelated modifications.
3. **Pull Request Description**: Complete all sections of the repository's pull request template, providing a clear summary of your changes, the linked issue reference, and verification notes.
4. **Documentation**: Update corresponding documentation whenever modifying user-facing functionality, configuration options, APIs, or developer workflows.

---

## Security Vulnerability Reporting

Security vulnerabilities should **not** be reported through public GitHub issues or pull requests.

Please follow the private disclosure protocol outlined in our [Security Policy](SECURITY.md) or submit a confidential report through our [Security Portal](https://peakurl.org/contact?topic=security&subject=Security+vulnerability+report).
