# Contributing to Quant Finance AGH

Start with the [onboarding guide](https://github.com/AGH-Quant-Finance/.github/blob/main/docs/onboarding.md) and the repository README. Each repository describes its own environment, tests, and release conventions.

## Choose a task

Discuss an existing issue with its maintainer before starting substantial work. If the task has no issue, write a short description of the problem, intended result, and how you will check it. Small documentation corrections can go straight to a focused pull request.

New project ideas belong in the [project-proposal process](https://github.com/AGH-Quant-Finance/.github/blob/main/docs/project-proposals.md). Proposing an idea does not require repository administration rights.

## Make a contribution

1. Create a feature branch. If you do not have Write access, fork the repository and submit a pull request from your fork.
2. Keep the change focused and preserve unrelated work.
3. Run the repository's documented checks. Add tests when behavior changes; explain anything you could not verify.
4. Open a pull request describing the problem, the change, and validation. Link the related issue. Use a draft PR when early feedback would help.
5. Ask an appropriate maintainer to review. Address feedback and keep checks passing before a maintainer merges.

C++ infrastructure repositories use `[MAJOR]`, `[MINOR]`, or `[PATCH]` PR-title prefixes. Keep the prefix in the final merge commit subject so the existing release automation can determine its version bump. Follow each repository's README rather than applying this convention indiscriminately to every project.

## Research and engineering standards

Document data sources, assumptions, methods, results, and limitations. Make experiments reproducible, keep comparisons fair, and distinguish measured results from expectations. Explain how to build and test engineering changes; performance claims should include the benchmark conditions.

Respect copyright, data-use restrictions, and confidentiality. Do not commit credentials, applicant information, private contact lists, restricted datasets, or large generated outputs. Discuss a suitable storage location with the project lead.

Reviews should help improve the work and help contributors learn. Follow the [Code of Conduct](https://github.com/AGH-Quant-Finance/.github/blob/main/CODE_OF_CONDUCT.md). English is preferred for shared project records; Polish is welcome when useful, with a short English summary for wider collaboration.
