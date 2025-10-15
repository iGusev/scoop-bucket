# Scoop Bucket for iGusev's Tools

This is a [Scoop](https://scoop.sh/) bucket for iGusev's command-line tools.

## Installation

First, make sure you have Scoop installed. Then add this bucket and install the tools:

```powershell
# Add the bucket
scoop bucket add igusev https://github.com/igusev/scoop-bucket

# Install glf
scoop install igusev/glf
```

## Available Tools

### glf

Fast CLI tool for instant fuzzy search across self-hosted GitLab projects.

- **Homepage**: https://github.com/igusev/glf
- **Installation**: `scoop install igusev/glf`
- **Update**: `scoop update glf`

#### Features

- Instant fuzzy search across all your GitLab projects
- Fast navigation to projects, files, and merge requests
- Terminal-based user interface
- Self-hosted GitLab support

## Updating

To update any installed tool:

```powershell
# Update Scoop itself
scoop update

# Update glf
scoop update glf
```

## Uninstallation

```powershell
# Uninstall glf
scoop uninstall glf

# Remove the bucket (optional)
scoop bucket rm igusev
```

## About This Bucket

This bucket is automatically maintained by [GoReleaser](https://goreleaser.com/). Manifests are updated automatically when new releases are published.

## Support

For issues with the tools themselves, please visit their respective GitHub repositories. For bucket-related issues, please open an issue in this repository.
