# Contributing

How we work in every Explo-Gen repository.

## Branches

`main` is always working. Never push straight to it. Branch off `main`:

- `feature/short-name` for new features
- `fix/short-name` for bug fixes
- `docs/short-name` for documentation
- `chore/short-name` for maintenance

## Commits

Use clear messages in the form `type: what changed`:

- `feat: add template picker`
- `fix: correct email validation`
- `docs: update setup guide`

## Pull requests

1. Open a pull request into `main` and fill in the template.
2. Get one review.
3. Fix any comments.
4. Merge, then delete the branch.

Keep pull requests small: one change, one pull request.

## Issues and labels

Use the standard labels: `bug`, `feature`, `design`, `docs`, `infra`.

## Secrets

Never commit passwords, tokens, keys or `.env` files. Keep a `.env.example` with variable names only.

## More

The full guide lives in the private handbook: `processes/git-workflow.md`.
