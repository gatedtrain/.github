# Contributing to gatedtrain

Thank you for your interest. gatedtrain is a prototype; issues and pull requests are welcome in any of the
repositories of the gatedtrain organization.

## Before you start

- For anything larger than a small fix, open an issue first so the approach can be agreed.
- The framework follows a published design set (`gatedtrain-design`); code and tests cite it by section and rule id.
  A change that departs from the design needs a design change too.
- Security issues: follow `SECURITY.md`, not the public tracker.

## Pull requests

- Keep each pull request to one topic, with tests. Run the repository's test suite (see its README) and make sure it
  passes.
- Recipes pin the SHA-256 of their runtime scripts and of their published results. If you change a pinned file,
  update the pin in the same commit and explain why; never edit files under `results/`, which record past runs.
- Write code, comments, and documentation in English.

## Developer Certificate of Origin

Contributions are accepted under the Apache License 2.0 of the repository. Sign off every commit
(`git commit -s`) to certify the [Developer Certificate of Origin 1.1](https://developercertificate.org/): that you
wrote the change or otherwise have the right to submit it under that license.

## Code of conduct

Everyone taking part is expected to follow the [code of conduct](https://github.com/gatedtrain/.github/blob/main/CODE_OF_CONDUCT.md).
