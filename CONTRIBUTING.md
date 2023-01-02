# Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change.

Please note we have a code of conduct, please follow it in all your interactions with the project.

## Pull Request Process

1. Update the README.md with details of changes including new [example Dockerfile](./app) if appropriate.
2. Once all outstanding comments and checklist items have been addressed, your contribution will be merged!
3. Merged PRs will be included in the next release. The module maintainers take care of updating the CHANGELOG as they merge.

## Checklists for contributions

- [ ] Add [semantics prefix](#semantic-pull-requests) to your PR or Commits (at least one of your commit groups)
- [ ] CI tests are passing
- [ ] README.md has been updated after any changes.

## Semantic Pull Requests

To generate changelog, Pull Requests or Commits must have semantic and must follow [conventional specs](https://www.conventionalcommits.org/en/v1.0.0/#summary) below:

- `feat:` for new features
- `fix:` for bug fixes
- `perf:` for performance improvements
- `docs:` for documentation and examples
- `style`: for formatting changes
- `refactor:` for refactoring production code
- `test:` for adding missing tests
- `ci:` for CI purpose
- `chore:` for chores stuff
- `build:` for updating build configuration

`chore docs ci build refactor style` prefixes are skipped during changelog generation.

They can be used for `chore: update changelog` commit message by example.
