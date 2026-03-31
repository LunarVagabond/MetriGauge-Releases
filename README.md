# MetriGauge Releases

This repository hosts **public, signed release artifacts** for the MetriGauge desktop application (Tauri).

- **What this repo is for**: downloadable installers/AppImages and update metadata used by the in-app updater.
- **What this repo is not for**: source code, issue tracking, feature requests, or internal documentation.

## Downloads

Go to the **Releases** section of this repository and download the latest build for your OS.

- **Linux**: AppImage (recommended) and `.deb` when available
- **Windows**: installer (`.exe`) and/or `.msi` when available

If you are unsure which file to pick, choose the installer for your operating system with the most recent version number.

## Automatic updates (in-app)

Newer versions of MetriGauge include an in-app updater.

- When an update is available, the app will show an update prompt.
- Clicking **Install update** will download and apply the update.
- You may need to **restart the app** after installation.

### Updater metadata

This repo publishes updater metadata files alongside each release, for example:

- `latest-<target>.json` (update manifest)
- signature files and packaged update artifacts created during the build

These files are consumed by the MetriGauge application to securely verify and apply updates.

## Release authenticity / signing

Releases are signed during CI. The application verifies updates before installing them.

If you obtained the app from somewhere other than this repository’s Releases page, you should treat it as untrusted.

## Support

For support, contact your MetriGauge administrator / your organization’s support contact.

(Internal: source code and issue tracking are maintained privately.)
