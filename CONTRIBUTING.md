# Contributing

Thank you for considering contributing to **sauron**!

## Getting Started

1. Fork and clone the repository.
2. Run `pnpm install` to install dependencies.
3. Create a new branch for your change.

## Scripts

- `pnpm lint` - run ESLint
- `pnpm test` - run tests
- `pnpm format` - format files with Prettier
- `pnpm changeset` - create a changeset for releases

## Conventional Commits

This project uses [Conventional Commits](https://www.conventionalcommits.org) for
commit messages. Please follow this format when committing your changes.

Example commit message:

```
feat: add new tracing exporter
```

## Pull Requests

1. Ensure `pnpm lint` and `pnpm test` pass.
2. Run `pnpm changeset` to document your change.
3. Open a pull request with a clear description of your change.
