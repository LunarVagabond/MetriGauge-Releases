# MetriGauge Releases

This repository hosts **public, signed release artifacts** for the MetriGauge desktop application (Tauri).

- **Purpose**: Distribution of downloadable binaries and update metadata used by the in-app updater  
- **Not included**: Source code, issue tracking, feature requests, or internal documentation  

## Downloads

Visit the **Releases** section of this repository to download the latest version.

- **Linux**: AppImage (recommended)  
- **Windows**: MSI installer  

If you are unsure which file to select, download the installer that matches your operating system.

## Automatic Updates (In-App)

Recent versions of MetriGauge include an in-app update mechanism.

- When an update is available, the application will display a prompt  
- Selecting **Install Update** will download and apply the update  
- A restart may be required to complete installation  

## Updater Metadata

This repository publishes updater metadata alongside each release, including:

- `latest.json` (update manifest)  
- Signature files and packaged update artifacts generated during the build process  

These files are used by the application to securely verify and apply updates.

## Release Authenticity & Signing

All releases are signed as part of the CI pipeline. The application verifies update integrity before installation.

If you obtained the application from a source other than this repository’s Releases page, it should be considered **untrusted**.

## Support

For support, please contact your MetriGauge administrator or your organization’s designated support channel.

MetriGauge is developed and maintained by **MetriCal Laboratories LLC**.
