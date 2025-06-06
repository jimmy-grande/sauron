# Release Process

Releases are managed with [Changesets](https://github.com/changesets/changesets).

1. Run `pnpm changeset` and follow the prompts.
2. Commit the generated changeset file.
3. When changes land on `main`, a GitHub workflow will open a release PR.
4. Merge the release PR to publish a new version to npm.
