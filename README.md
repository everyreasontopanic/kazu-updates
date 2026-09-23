# KAZU updates and downloads

[Download the latest KAZU release](https://github.com/everyreasontopanic/kazu-updates/releases/latest).

Release packages are publicly downloadable without a GitHub account:

- macOS: signed and notarized universal AU/VST3 installer.
- Windows: x64 VST3 installer and a portable VST3 ZIP with installation instructions.
- Linux: x86_64 VST3 archive with installation instructions.

Each release includes `SHA256SUMS.txt` for package verification. Choose the package
for your operating system under the release's Assets list.

Installed plugins read `latest.json` at its existing public URL. The manifest
links to the public GitHub release page and direct platform downloads. Automatic
checks retain the existing 24-hour cache; **Check for Updates** refreshes immediately.

## Release order

1. Build and verify every platform package, including macOS signing and notarization.
2. Upload the packages and checksums to a GitHub release.
3. Verify all downloads without authentication.
4. Update `latest.json` after download verification passes.

Keep credentials, license data, and access tokens out of this public repository.
