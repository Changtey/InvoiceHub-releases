# InvoiceHub Downloads

InvoiceHub is an offline-first GST billing and business app for Indian small
businesses. This is the official downloads-only repository.

## Download InvoiceHub 1.1.1

| Platform | Version | Download |
| --- | --- | --- |
| Windows 10/11, 64-bit | 1.1.1 | [Download the Windows installer](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.1/InvoiceHub-Setup-1.1.1.exe) |
| Debian/Ubuntu Linux, 64-bit | 1.1.1 | [Download the Linux installer](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.1/InvoiceHub-1.1.1-linux.deb) |
| Android direct install | 1.1.0 | [Download the current Android APK](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.0/InvoiceHub-Android-1.1.0.apk) |

See the [InvoiceHub 1.1.1 release page](https://github.com/Changtey/InvoiceHub-releases/releases/tag/v1.1.1)
for checksums, verification results, and release notes.

## Install on Windows

1. Download `InvoiceHub-Setup-1.1.1.exe`.
2. Open the installer and choose the installation folder if needed.
3. Launch InvoiceHub from the desktop or Start menu shortcut.

The Windows installer is not digitally signed yet, so Windows may show a
security warning. Confirm that the file was downloaded from this official
repository before continuing.

## Install on Linux

The 1.1.1 Linux installer supports 64-bit Debian and Ubuntu systems.

1. Download `InvoiceHub-1.1.1-linux.deb`.
2. Open it with the system Software Install app, or run
   `sudo apt install ./InvoiceHub-1.1.1-linux.deb` from the download folder.
3. Launch InvoiceHub from the applications menu.

Linux may ask for the computer administrator password. This is a required
operating-system approval for installing or replacing a system package.

## Automatic updates

- InvoiceHub checks for a newer stable release every time the desktop app opens.
- It never downloads a new version until the user chooses **Update Now**.
- After **Update Now**, it downloads and verifies the package, installs it, and
  automatically reopens the latest version.
- Windows installs without extra prompts. Linux may show the required system
  administrator approval.
- Interrupted downloads and failed installations leave the current working
  version in place and can be retried safely.
- The Android direct-install edition has its own verified Android update flow.
  Version 1.1.0 remains the current public Android release.

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
