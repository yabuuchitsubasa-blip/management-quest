# Management Quest

Management Quest is an AI management agent that visualizes employee workload as HP, predicts future HP, and supports managers with concrete actions such as workload redistribution, meeting reduction, and recovery support.

> Core principle: not an AI that monitors employees, but an AI that protects employees and supports managerial decision-making.

## Current baseline

- Vanilla HTML / CSS / JavaScript
- Main flows: Team Dashboard, Member Detail, AI Analysis / Future HP, Management Action, Member / My Status, Recovery Marketplace
- Development priority: preserve the working demo while splitting responsibilities so 3–4 people can develop in parallel.

## Development rules

1. Do not push feature work directly to `main`.
2. Create one branch per issue: `feature/<scope>` or `fix/<scope>`.
3. Open a pull request before merging.
4. Keep shared data structures stable. Changes to the member / HP / workload model require review.
5. Prefer small PRs that can be reviewed quickly.

## Branch naming

- `feature/dashboard`
- `feature/member-detail`
- `feature/hp-prediction`
- `feature/ai-analysis`
- `feature/management-actions`
- `feature/recovery`
- `fix/<scope>`

## Product framing

HP represents an estimated work-condition / workload state. It must not be treated as an employee ability score or a surveillance score.
