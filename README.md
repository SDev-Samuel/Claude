# Claude

Practice repository for learning software development workflows with
[Claude Code](https://claude.com/claude-code): branching, conventional
commits and pull requests.

## Workflow

1. Create a feature branch from `main`.
2. Make small, focused commits using
   [Conventional Commits](https://www.conventionalcommits.org/)
   (e.g. `docs: ...`, `feat: ...`, `fix: ...`).
3. Open a pull request against `main` and review the diff before merging.

## Security

Never commit secrets (API keys, passwords, tokens). Keep them in a local
`.env` file and make sure it is listed in `.gitignore`.
