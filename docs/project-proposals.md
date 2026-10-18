# Propose and lead a project

Members are welcome to propose research or development ideas and coordinate the work. A short proposal is enough to begin a discussion.

Open the [Project proposal issue form](https://github.com/AGH-Quant-Finance/.github/issues/new?template=project-proposal.yml) and describe:

- The problem or research question.
- The expected outcome and a small first milestone.
- The skills needed.
- Interested contributors (share other people's usernames only with their agreement).
- A proposed coordinator, or a request for help finding one.

For example, several members could propose **Information Diffusion**: investigate how public information reaches prices, agree on a dataset and a first experiment, and volunteer a coordinator. It does not need to be one of the initial four ideas.

A track maintainer discusses feasibility with the contributors. Leadership or designated maintainers confirm the scope, coordinator, resources, and any access decisions. Record a short outcome in the issue: accepted, needs revision, parked, or declined. Keep applicant records, private contacts, credentials, and restricted data out of public issues.

For accepted work:

1. Confirm the coordinator, interested contributors, and a realistic first milestone.
2. Decide whether the work belongs in an existing repository. Create a new one only after a separate approval, when a team and reasonable scope exist.
3. Grant contributor Write and lead Maintain only on the assigned repository. Track-team access is suitable only when its membership matches the approved project contributors; otherwise use explicit project grants or a project team when that access boundary is necessary.
4. Open a few implementation issues with a clear outcome and reviewer, and link them to the proposal. Use PRs for changes to code, experiments, or shared documentation.
5. Track progress on one organization board, if approved, with **Proposed → Planned → In Progress → In Review → Completed**. Check for an existing board before creating another.
6. If the project becomes inactive, discuss its status with the coordinator. Record a short summary and archive only after the team and owners approve; remove obsolete write access separately after reviewing who still needs it.

The initial research proposals can use `volatility-forecasting` and `volatility-hedging`. The development work can start in `market-engine`, with separate Order Book and Matching Engine modules. These are proposed boundaries; no repositories are created by submitting an issue.
