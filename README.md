# InvoiceHub Downloads

InvoiceHub is an offline-first GST billing and business app for Indian small
businesses. This is the official downloads-only repository.

## Download InvoiceHub 1.1.2

| Platform | Version | Download |
| --- | --- | --- |
| Windows 10/11, 64-bit | 1.1.2 | [Download the Windows installer](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.2/InvoiceHub-Setup-1.1.2.exe) |
| Debian/Ubuntu Linux, 64-bit | 1.1.2 | [Download the Linux installer](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.2/InvoiceHub-1.1.2-linux.deb) |
| Android direct install | 1.1.0 | [Download the current Android APK](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.0/InvoiceHub-Android-1.1.0.apk) |

See the [InvoiceHub 1.1.2 release page](https://github.com/Changtey/InvoiceHub-releases/releases/tag/v1.1.2)
for checksums, verification results, and release notes.

## Install on Windows

1. Download `InvoiceHub-Setup-1.1.2.exe`.
2. Open the installer and choose the installation folder if needed.
3. Launch InvoiceHub from the desktop or Start menu shortcut.

The Windows installer is not digitally signed yet, so Windows may show a
security warning. Confirm that the file was downloaded from this official
repository before continuing.

## Install on Linux

The 1.1.2 Linux installer supports 64-bit Debian and Ubuntu systems.

1. Download `InvoiceHub-1.1.2-linux.deb`.
2. Open it with the system Software Install app, or run
   `sudo apt install ./InvoiceHub-1.1.2-linux.deb` from the download folder.
3. Launch InvoiceHub from the applications menu.

Linux may ask for the computer administrator password. This is a required
operating-system approval for installing or replacing a system package.

## Automatic updates

- InvoiceHub checks for a newer stable release every time the desktop app opens.
- It never downloads a new version until the user chooses **Update Now**.
- After **Update Now**, it downloads and verifies the package, installs it in
  the existing application location, and automatically reopens the latest version.
- Windows updates are silent for a normal per-user installation. Linux may show
  the required administrator approval for a system package.
- Interrupted downloads and failed installations leave the current working
  version in place and can be retried safely.
- The Android direct-install edition has its own verified Android update flow.
  Version 1.1.0 remains the current public Android release.

## What changed in 1.1.2

- Fixed a timing fault that could leave the updater stuck if the installer
  failed exactly while the download was completing.
- Failed update checks, downloads, and installer starts now report the correct
  step, restore normal app closing, and allow a safe retry.
- Windows updates explicitly reuse the current installation folder.
- Release preparation now works in standard Windows PowerShell.
- Unneeded source maps, tests, environment files, and private signing files are
  excluded from the packaged application.

## Verification

- 98 Web/Desktop application tests passed.
- 18 desktop updater and security tests passed.
- Android analysis found no issues and all 117 Android tests passed.
- Both production and full dependency audits found zero known vulnerabilities.
- Windows 1.1.2 was built and its packaged version and updater were inspected.
- The Debian package structure, version, update metadata, and checksums were
  verified. It was not launched on a real Linux computer in this release check.

## Important

- Download InvoiceHub only from this official repository.
- The Windows installer is currently unsigned.
- Back up important business data before any major application or operating
  system change.
- `checksums.json` on each release can be used to verify downloaded files.

## About this repository

This repository contains only InvoiceHub installers, update metadata,
checksums, and this download guide. It does not contain the InvoiceHub
application source code.

GitHub automatically displays two links named **Source code** on every tagged
release. Those automatic archives contain only this small downloads repository
and its public metadata, not the InvoiceHub application source.
