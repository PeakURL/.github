# Contributing to PeakURL

Thank you for your interest in contributing to PeakURL.

This repository establishes organization-wide contributor standards and shared health guidelines for all repositories maintained under the PeakURL organization.

---

## Before You Begin

Please review the organization policies prior to contributing:

- [Code of Conduct](CODE_OF_CONDUCT.md)
- [Security Policy](SECURITY.md)
- [Support Guide](SUPPORT.md)

If a specific project repository provides its own `CONTRIBUTING.md`, `README.md`, or developer documentation, the repository-specific guidelines take precedence.

---

## Issue-First Workflow

Across all repositories in the PeakURL organization, **contributors must open a GitHub Issue and establish alignment before submitting a Pull Request.**

### Rationale

- **Technical Consensus**: Discussing requirements and design beforehand ensures that proposed changes align with organizational architecture and roadmaps.
- **Systematic Triage**: For defect reports, an issue allows maintainers to reproduce and validate the problem prior to code changes.
- **Resource Efficiency**: Establishing ownership on issues prevents redundant work across the community.

### Contribution Process

1. **Review Existing Issues**: Search the target repository's issue tracker to confirm the topic has not already been addressed.
2. **Open a Comprehensive Issue**:
   - **Bug Reports**: Detail exact reproduction steps, expected versus actual behavior, runtime environment information, and relevant error logs.
   - **Feature Requests**: Clearly define the user problem, anticipated benefits, and proposed technical approach.
3. **Obtain Maintainer Confirmation**: For non-trivial or architectural changes, please wait for maintainer review and approval before beginning implementation.
4. **Reference the Issue in the Pull Request**: Every pull request must explicitly link its corresponding issue (e.g., `Fixes #123` or `Closes #123`).

> [!IMPORTANT]
> Pull requests submitted without a corresponding issue or adequate context will be placed on hold until an issue is opened and the scope is reviewed with maintainers.

---

## Contribution Expectations

All contributions across organization repositories are expected to adhere to the following principles:

- **Atomic Scope**: Keep pull requests focused on resolving one specific issue without including unrelated changes.
- **Architectural Coherence**: Adhere to established language standards, coding conventions, and architectural boundaries of the target project.
- **Verification and Testing**: Execute all project test suites, linters, and formatters locally before submitting pull requests.
- **Documentation**: Provide corresponding documentation updates in the same pull request whenever modifying user-facing behavior, runtime configurations, or APIs.

---

## Pull Request Submission

When opening a pull request in any PeakURL repository:

- Link the corresponding issue (`Fixes #123` or `Closes #123`).
- Complete the project's pull request template, providing a clear summary of modifications and verification steps.
- Ensure all continuous integration checks pass without errors.

---

## Security Vulnerability Reporting

Do **not** report security vulnerabilities via public GitHub issues or pull requests.

Please follow the private disclosure process detailed in the [Security Policy](SECURITY.md).
