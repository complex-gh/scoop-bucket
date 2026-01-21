# Scoop Bucket

[![Tests](https://github.com/complex-gh/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/complex-gh/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/complex-gh/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/complex-gh/scoop-bucket/actions/workflows/excavator.yml)

A [Scoop](https://scoop.sh) bucket for installing seedify on Windows.

## Seedify

Seedify is a tool for generating seed phrases from SSH private keys.

## Installation

First, add this bucket to your Scoop installation:

```pwsh
scoop bucket add complex-gh https://github.com/complex-gh/scoop-bucket
```

Then install seedify:

```pwsh
scoop install complex-gh/seedify
```

## Updating

To update seedify to the latest version:

```pwsh
scoop update seedify
```

## Contributing

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.
