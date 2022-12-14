# How to use

Make a commit to a qualifying branch as specified in the config file `.releaserc.json`. The commit message or PR title should be prefixed with any of the tags below

The `Tag` is one of the following:

* `Fix` - for a bug fix.
* `Update` - either for a backwards-compatible enhancement or for a rule change that adds reported problems.
* `New` - implemented a new feature.
* `Breaking` - for a backwards-incompatible enhancement or feature.
* `Docs` - changes to documentation only.
* `Build` - changes to build process only.
* `Upgrade` - for a dependency upgrade.
* `Chore` - for refactoring, adding tests, etc. (anything that isn't user-facing).

## References:

- https://github.com/semantic-release/semantic-release
- https://github.com/conventional-changelog/conventional-changelog/blob/master/packages/conventional-changelog-eslint/README.md
