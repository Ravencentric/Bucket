# Ravencentric's Scoop Bucket

[![Tests](https://github.com/Ravencentric/Bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/Ravencentric/Bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/Ravencentric/Bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/Ravencentric/Bucket/actions/workflows/excavator.yml)

My bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

## Available manifests

- [misaki](https://github.com/Ravencentric/misaki) - Fast, asynchronous link checker with optional FlareSolverr support.

## How do I install these manifests?

After manifests have been committed and pushed, run the following:

```pwsh
scoop bucket add ravencentric https://github.com/Ravencentric/Bucket
scoop install ravencentric/<manifestname>
```

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.
