# Contributing to DeltaZulu OÜ Projects

Thank you for your interest in contributing.

DeltaZulu OÜ projects are maintained with a strict issue-first workflow. This is not meant to create friction. It is meant to avoid wasted work, keep the codebase maintainable, and make sure proposed changes fit the purpose and scope of the project before anyone spends time implementing them.

## The rule

Do not open a pull request for a new feature, major refactor, behavioral change, dependency change, packaging change, or unverified bug fix without an associated approved issue.

Pull requests without an approved issue may be closed without review.

Small documentation fixes, typo corrections, and clearly safe metadata updates may be submitted directly, but larger documentation changes should also start with an issue.

## Why this project uses an issue-first workflow

A pull request can be technically correct and still be unsuitable for the project.

The issue-first workflow helps clarify the problem before code is written. It gives maintainers a chance to discuss scope, compatibility, security impact, deployment constraints, long-term maintenance cost, and whether the change belongs in the project at all.

This is especially important for projects that may be used in operational, security-sensitive, air-gapped, enterprise, or administrator-controlled environments.

## Before opening an issue

Please search existing open and closed issues first.

The same problem may already have been reported, rejected, deferred, or partly solved. If a related issue exists, comment there instead of opening a duplicate.

## Reporting bugs

When reporting a bug, include enough information for the maintainer to reproduce or reason about the issue.

Please include:

- Project version or commit hash.
- Operating system and relevant platform details.
- Configuration details, with secrets removed.
- Expected behavior.
- Actual behavior.
- Steps to reproduce the issue.
- Logs, screenshots, or error messages where useful.
- Whether the issue is reproducible on a clean installation or default configuration.

Do not include credentials, private keys, tokens, production logs with sensitive data, internal hostnames, customer data, or other confidential information.

## Requesting features or changes

For new features, refactors, behavioral changes, or compatibility work, open an issue first.

The issue should explain:

- The problem you are trying to solve.
- Why the current behavior is insufficient.
- Your proposed solution.
- Any alternatives you considered.
- Compatibility or migration impact.
- Security, operational, or deployment implications.
- Whether you are willing to implement the change after approval.

A maintainer may accept the idea, reject it, narrow the scope, ask for more information, or suggest a different implementation path.

## Wait for approval before coding

Please do not start implementation work until the issue has been discussed and approved.

Approval may be indicated by a maintainer comment or by labels such as `approved`, `accepted`, or `help wanted`, depending on the repository.

Being assigned to an issue does not automatically mean every implementation detail is accepted. Keep the pull request aligned with the agreed scope.

## Pull request requirements

When opening a pull request, make sure it:

- Links to the approved issue.
- Stays within the agreed scope.
- Describes what changed and why.
- Includes tests where practical.
- Updates documentation when behavior or configuration changes.
- Avoids unrelated cleanup or formatting changes.
- Does not introduce unnecessary dependencies.
- Preserves backward compatibility unless a breaking change was explicitly approved.
- Does not weaken security, logging, validation, or administrative controls.

Use commit messages that describe the actual change. They do not need to follow a rigid format unless the repository specifies one.

## Scope control

Please keep pull requests small and reviewable.

A pull request should solve one agreed problem. Do not bundle unrelated refactoring, formatting, dependency upgrades, feature additions, and bug fixes into the same change.

If you discover another issue while working, open a separate issue.

## Security-sensitive changes

Security-sensitive changes require extra care.

This includes changes related to authentication, authorization, privilege boundaries, cryptography, logging, IPC, service behavior, installer behavior, network behavior, parsing, update workflows, policy handling, or default configuration.

For these changes, describe the security impact clearly in the issue and the pull request.

If you believe you have found a vulnerability, do not open a public issue unless the repository explicitly asks for that. Follow the repository’s security policy instead.

## Compatibility expectations

Many DeltaZulu OÜ projects are designed for practical deployment, including constrained or centrally managed environments.

Where relevant, changes should consider:

- Windows compatibility.
- Offline or air-gapped usage.
- Group Policy or administrator-controlled configuration.
- Minimal runtime assumptions.
- Clean installation and uninstallation behavior.
- Logging and troubleshooting.
- Backward compatibility with existing configuration or documented behavior.

Do not assume that cloud services, portals, package managers, automatic updates, or internet access are available unless the project explicitly depends on them.

## Code style

Follow the existing style of the repository.

Do not reformat files unrelated to your change. Do not introduce new style conventions unless that was approved in the issue.

Prefer clear, boring, maintainable code over clever abstractions.

## Tests and validation

Where practical, include tests or a clear validation note.

At minimum, describe how you tested the change. For UI, installer, service, networking, or platform-specific changes, include the environment used for testing.

If automated tests are not practical, explain why.

## Documentation

Update documentation when the change affects installation, configuration, behavior, compatibility, security assumptions, troubleshooting, or user-visible output.

Documentation should be precise and operationally useful. Avoid marketing language.

## Licensing

By contributing, you agree that your contribution will be licensed under the same license as the project.

Do not submit code, documentation, assets, or configuration copied from incompatible sources.

## Maintainer discretion

Maintainers may close issues or pull requests that are out of scope, insufficiently specified, inactive, too broad, incompatible with the project direction, or unsuitable for long-term maintenance.

This is not a judgment on the usefulness of the idea in general. It may simply not fit this project.

## Summary

Open an issue first. Discuss the problem and scope. Wait for approval. Then submit a focused pull request linked to the approved issue.

