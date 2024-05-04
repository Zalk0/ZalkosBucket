# Zalko's Bucket

[![Tests](https://github.com/Zalk0/ZalkosBucket/actions/workflows/ci.yml/badge.svg)](https://github.com/Zalk0/ZalkosBucket/actions/workflows/ci.yml)
[![Excavator](https://github.com/Zalk0/ZalkosBucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/Zalk0/ZalkosBucket/actions/workflows/excavator.yml)

Template bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

## How do I install these manifests?

Add the bucket and you can now install apps from it, like so:

```pwsh
scoop bucket add ZalkosBucket https://github.com/Zalk0/ZalkosBucket
scoop install ZalkosBucket/<manifestname>
```

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.
