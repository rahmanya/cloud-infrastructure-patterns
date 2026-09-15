# Contributing

This repository is a practical platform engineering and cloud
infrastructure lab.

Changes should be small, reviewable and introduced through pull requests.

## Development workflow

1. Create a feature branch from `main`.
2. Make the required changes.
3. Validate changes locally where applicable.
4. Commit using a clear, descriptive commit message.
5. Push the feature branch.
6. Raise a pull request into `main`.
7. Review the proposed changes and validation evidence.
8. Merge only when the required repository controls have passed.

## Branch naming

Use descriptive branch names such as:

- `feature/<description>`
- `fix/<description>`
- `docs/<description>`
- `chore/<description>`

## Commit messages

Use concise commit messages that describe the purpose of the change.

Examples:

`feat: add reusable GCP network module`

`fix: correct Terraform variable validation`

`docs: document GitHub to GitLab migration`

`chore: add repository governance baseline`

## Pull requests

Pull requests should:

- describe what is changing and why;
- identify relevant validation performed;
- remain focused on a single logical change;
- avoid committing credentials, secrets or sensitive information;
- pass required automated checks before merge where configured.

## Infrastructure changes

Infrastructure code should be formatted, validated and documented before
merge.

Additional automated validation will be introduced as the repository evolves.