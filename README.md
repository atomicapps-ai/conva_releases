# Conva releases

This public repository contains official Conva desktop downloads, update
manifests, and user-facing release notes. The application source remains in a
separate private repository.

## Download

- [Latest stable release](https://github.com/atomicapps-ai/conva_releases/releases/latest)
- [All releases](https://github.com/atomicapps-ai/conva_releases/releases)

Each stable release is expected to include Windows MSI and NSIS installers, a
macOS disk image, signed updater archives, and a cross-platform `latest.json`
manifest. Release notes summarize the important product changes rather than
listing internal commits.

Releases are created as drafts by the private build pipeline, checked for a
complete asset set, reviewed by the owner, and only then published. Do not use
an unpublished draft as an updater source.
