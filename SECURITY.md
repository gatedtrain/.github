# Security policy

gatedtrain and its recipes are prototypes. They run training and evaluation code in containers, load checkpoints,
and execute model-generated programs in sandboxes, so security reports are welcome.

## Reporting a vulnerability

Please do not open a public issue. Report privately through GitHub: open the affected repository's **Security** tab
and choose **Report a vulnerability** (GitHub private vulnerability reporting). Include the repository, the commit,
what an attacker controls, and what they gain; a minimal reproduction helps.

We aim to acknowledge a report within seven days and to agree a disclosure date with the reporter once a fix is
ready. There is no bug bounty.

## Scope

In scope: the code in the gatedtrain repositories (the framework, its launcher and sandboxes, and the recipes).

Out of scope: third-party projects the recipes use (training frameworks, models, datasets, container images); report
those to their maintainers. Running checkpoints, datasets, or containers from untrusted sources is outside the
threat model: the recipes load only artifacts their own runs produced or that are pinned by hash.

## Supported versions

Only the latest commit of each repository's default branch is supported.
