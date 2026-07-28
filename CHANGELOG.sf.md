# StreamingFast Changelog

Changelog for the StreamingFast fork of [monad-bft](https://github.com/category-labs/monad-bft).
It tracks only the fork's own releases (the `*-fh*` tags); upstream changes are covered by
the [upstream releases](https://github.com/category-labs/monad-bft/releases).

Kept in `CHANGELOG.sf.md` rather than `CHANGELOG.md` so it never conflicts with an upstream
changelog. The release workflow looks up the section matching the tag being released and
publishes it as the GitHub release notes, so rename `## Unreleased` to the tag name (for
example `## v0.15.3-fh3.0`) before tagging — the release job fails if no section matches.

## Unreleased

* Build and publish `monad-node` / `monad-rpc` images on `release/**` branches and on
  `v*-fh*` tags, and create a GitHub release from this changelog on tag builds.

## v0.15.2-fh3.0

* Bumped to [v0.15.2](https://github.com/category-labs/monad-bft/releases/tag/v0.15.2).

## v0.15.1-fh

* Bumped to [v0.15.1](https://github.com/category-labs/monad-bft/releases/tag/v0.15.1).
