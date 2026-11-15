# Contributing to DES_tutorial_AHEA

This repository supports an R/simmer tutorial on discrete-event simulation for health-economic modeling in colon cancer. Read [README.txt](README.txt) and preserve the attribution to the tutorial and its original authors.

## Before you start

Search existing issues and pull requests before starting, and discuss substantial changes or new dependencies in an issue. Use an issue template when one is offered. For a bug, include the affected commit or version, environment, a minimal reproduction, and expected versus observed behavior; remove sensitive information from logs and screenshots.

## Development and validation

Open [DES_tutorial_AHEA.Rproj](DES_tutorial_AHEA.Rproj) or set the working directory as described in the README. The actual source directory is `R_scripts`, containing numbered survival-analysis, deterministic-model, and probabilistic-analysis scripts. Inspect their package and input requirements before running them and follow their documented sequence.

For a model change, identify altered time-to-event distributions, competing-risk assumptions, costs, outcomes, or uncertainty settings. Use small synthetic or appropriately reusable examples with independently checkable expected behavior. Record R/package versions, seeds, replications, and the source or saved-object versions used. There is no separate repository-wide automated test command documented here.

Compare affected outputs and explain stochastic variation rather than treating any numerical difference as a defect. Keep teaching material, script behavior, and cited methodology consistent, and preserve existing data-file provenance.

## Pull requests

Work on a focused branch from the current default branch. Open a pull request explaining the problem, the resulting behavior, and any compatibility or data-format changes. Link the relevant issue and complete any existing PR template.

Add focused regression coverage for changed behavior and update affected examples or documentation. Describe the checks actually run, their results, and any checks you could not run. For documentation-only changes, verify links, examples, and rendered formatting. Use the repository's existing checks and review/merge process; preserve required checks and resolve actionable feedback without weakening the checks.

## Security and sensitive information

Follow the [account security policy](https://github.com/edithatogo/.github/blob/main/SECURITY.md). Report vulnerabilities privately through the repository's **Report a vulnerability** option if available; otherwise request a private reporting contact without posting exploit details. Never include credentials, personal information, restricted datasets, or confidential records in issues, commits, fixtures, or diagnostic output.

## Licensing and conduct

The repository's [license](LICENSE) continues to apply. Be respectful and constructive, and follow the [account code of conduct](https://github.com/edithatogo/.github/blob/main/CODE_OF_CONDUCT.md). Preserve attribution and third-party notices. Contribute only material you are entitled to share; resolve unclear permissions before adding third-party content. This guide does not change licensing terms or introduce a CLA or DCO requirement.

## References

- [GitHub contribution guideline conventions](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors)
- [OpenSSF contribution and quality criteria](https://www.bestpractices.dev/en/criteria)
