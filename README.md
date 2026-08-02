# homebrew-tap

Homebrew tap for [enplace](https://github.com/djcp/enplace) — a CLI recipe manager powered by Claude AI.

## Install

```sh
brew install djcp/tap/enplace
```

Or add the tap explicitly, then install:

```sh
brew tap djcp/tap
brew install enplace
```

Upgrade with `brew upgrade enplace`.

## About this repo

The cask in `Casks/` is generated and published automatically by
[GoReleaser](https://goreleaser.com) whenever a non-prerelease `enplace` release
is tagged. Don't edit it by hand — changes will be overwritten on the next release.
