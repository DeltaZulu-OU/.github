# Contributing to DeltaZulu OÜ Projects

Thank you for your interest in DeltaZulu OÜ projects.

DeltaZulu OÜ projects are open source, but they are not open-governance projects. Open source means the source code is available under the project license. It does not mean that the project accepts external roadmap direction, unsolicited implementation work, or pull requests by default.

These projects are maintained with a strict maintainer-led workflow. External contributions may be accepted, but acceptance is exceptional rather than expected. This policy exists to protect project scope, security posture, operational reliability, and long-term maintainability.

## Contribution policy

Please do not open a pull request unless a maintainer has explicitly approved the work in advance.

Unsolicited pull requests are normally closed without detailed review. This includes technically correct changes if they were not requested, approved, or aligned with the project’s current direction.

Small documentation fixes, typo corrections, broken-link fixes, and clearly safe metadata corrections may be submitted directly. Larger documentation changes should start with an issue.

## What this project usually accepts

DeltaZulu OÜ projects are most likely to accept:

* Reproducible bug reports.
* Security reports submitted through the appropriate security process.
* Small documentation corrections.
* Clearly scoped fixes requested by a maintainer.
* Changes linked to an approved issue marked as suitable for external contribution.

Even when a change is useful, maintainers may still choose to implement it internally.

## What this project usually does not accept

DeltaZulu OÜ projects usually do not accept unsolicited pull requests for:

* New features.
* Major refactors.
* Behavioral changes.
* Dependency additions or upgrades.
* Build, packaging, installer, or deployment changes.
* Architectural restructuring.
* Broad cleanup or formatting changes.
* Compatibility changes not previously discussed.
* Security-sensitive changes without prior maintainer direction.
* Bug fixes that have not been reproduced, verified, or accepted as in scope.

A pull request can be well written and still be unsuitable for the project.

## Issue-first workflow

Before proposing a change, search existing open and closed issues.

The same issue may already have been reported, rejected, deferred, or partly solved. If a related issue exists, comment there instead of opening a duplicate.

For anything beyond a small documentation correction, open an issue before writing code. The issue should describe the problem, not only the proposed solution.

A maintainer may accept the idea, reject it, narrow the scope, ask for more information, or decide to handle the change internally.

## Approval before implementation

Please do not begin implementation work until a maintainer explicitly confirms that external implementation is appropriate.

Approval may be indicated by a maintainer comment or by a repository label such as `approved`, `accepted`, or `help wanted`.

Being assigned to an issue, receiving a positive comment, or having a discussion about an idea does not automatically mean a pull request will be accepted. The final change must remain within the agreed scope and must still meet the project’s quality, security, compatibility, and maintenance requirements.

## Reporting bugs

When reporting a bug, include enough information for a maintainer to reproduce or reason about the issue.

Please include:

* Project version or commit hash.
* Operating system and relevant platform details.
* Configuration details, with secrets removed.
* Expected behavior.
* Actual behavior.
* Steps to reproduce the issue.
* Logs, screenshots, or error messages where useful.
* Whether the issue is reproducible on a clean installation or default configuration.

Do not include credentials, private keys, tokens, production logs with sensitive data, internal hostnames, customer data, or other confidential information.

A bug report is not a request to submit a pull request unless a maintainer explicitly confirms that external implementation is wanted.

## Requesting features or changes

Feature requests and change proposals should explain:

* The problem you are trying to solve.
* Why the current behavior is insufficient.
* The operational context where the problem appears.
* Your proposed solution, if any.
* Alternatives you considered.
* Compatibility or migration impact.
* Security, operational, or deployment implications.
* Whether you are asking for the project to consider the change or asking to implement it yourself.

Maintainers may decline feature requests that do not fit the project scope, roadmap, security model, deployment assumptions, or maintenance capacity.

## Pull request requirements

When a pull request has been explicitly approved, make sure it:

* Links to the approved issue.
* Stays within the agreed scope.
* Describes what changed and why.
* Includes tests where practical.
* Updates documentation when behavior or configuration changes.
* Avoids unrelated cleanup or formatting changes.
* Does not introduce unnecessary dependencies.
* Preserves backward compatibility unless a breaking change was explicitly approved.
* Does not weaken security, logging, validation, administrative controls, or operational predictability.

Use commit messages that describe the actual change. They do not need to follow a rigid format unless the repository specifies one.

## Scope control

Keep pull requests small and reviewable.

A pull request should solve one agreed problem. Do not bundle unrelated refactoring, formatting, dependency upgrades, feature additions, and bug fixes into the same change.

If you discover another issue while working, open a separate issue.

Maintainers may ask for a pull request to be reduced in scope, split, rewritten, or closed.

## Security-sensitive changes

Security-sensitive changes require prior maintainer approval.

This includes changes related to authentication, authorization, privilege boundaries, cryptography, logging, IPC, service behavior, installer behavior, network behavior, parsing, update workflows, policy handling, default configuration, or administrator-controlled behavior.

For these changes, describe the security impact clearly in both the issue and the pull request.

If you believe you have found a vulnerability, do not open a public issue unless the repository explicitly asks for that. Follow the repository’s security policy instead.

## Compatibility expectations

Many DeltaZulu OÜ projects are designed for practical deployment, including constrained, security-sensitive, air-gapped, enterprise, or administrator-controlled environments.

Where relevant, changes must consider:

* Windows compatibility.
* Offline or air-gapped usage.
* Group Policy or administrator-controlled configuration.
* Minimal runtime assumptions.
* Clean installation and uninstallation behavior.
* Logging and troubleshooting.
* Backward compatibility with existing configuration or documented behavior.

Do not assume that cloud services, portals, package managers, automatic updates, or internet access are available unless the project explicitly depends on them.

## Code style

Follow the existing style of the repository.

Do not reformat files unrelated to your change. Do not introduce new style conventions unless they were approved in the issue.

Prefer clear, boring, maintainable code over clever abstractions.

## Tests and validation

Where practical, include tests or a clear validation note.

At minimum, describe how you tested the change. For UI, installer, service, networking, or platform-specific changes, include the environment used for testing.

If automated tests are not practical, explain why.

## Documentation

Update documentation when a change affects installation, configuration, behavior, compatibility, security assumptions, troubleshooting, or user-visible output.

Documentation should be precise and operationally useful. Avoid marketing language.

## Licensing

By contributing, you agree that your contribution will be licensed under the same license as the project.

Do not submit code, documentation, assets, configuration, test data, or generated output copied from incompatible sources.

Do not submit material that you do not have the right to contribute.

## Maintainer discretion

Maintainers may close issues or pull requests that are out of scope, insufficiently specified, inactive, too broad, incompatible with the project direction, unsuitable for long-term maintenance, or not worth the review burden.

This is not a judgment on the usefulness of the idea in general. It may simply not fit this project.

Maintainers are not obligated to provide detailed review, design guidance, mentoring, or justification for declining unsolicited work.

## Summary

Open an issue first. Describe the problem clearly. Wait for explicit maintainer approval before writing code. Submit a focused pull request only when external implementation has been requested or accepted.

Open source does not mean every contribution is appropriate for this project. DeltaZulu OÜ projects welcome useful reports and discussion, but code contributions are accepted selectively and at maintainer discretion.
