# Tpwer

Tpwer is a registration-free, local-first Git client for macOS.

## Downloads

Download packaged builds from [Releases](https://github.com/emeacham/Tpwer/releases). Each release includes a ZIP, SHA-256 checksums, a release manifest, and release notes.

The initial distribution targets Apple Silicon Macs running macOS 13 or newer. Build manifests identify the exact architecture and minimum system version.

## Credits

**Author: Ed Meacham ([goldshorts.com](https://goldshorts.com))**

Big thanks to the [Tower team](https://www.git-tower.com/) for the UI inspiration.

## Distribution and privacy

This repository hosts distribution documentation and release assets. Source development and build workflows are maintained in a private repository. Packaged Electron applications contain the runtime resources needed to run the app; the private repository and its history are not mirrored here.

Tpwer has no registration gate, telemetry, automatic update checker, crash uploader, or background remote refresh. Git remote, hosting, service, and AI requests run only through explicit app actions. A completely offline setting blocks those requests too.

## Signing and verification

The initial builds are ad-hoc signed and are not Apple notarized. macOS may require manual approval before opening them. Verify the published SHA256SUMS against the downloaded ZIP. The release manifest records signature status and the accepted application archive hash.

## Third-party components

Component notices are included inside the app under Contents/Resources, including Electron, Chromium, and the bundled runtime libraries.
