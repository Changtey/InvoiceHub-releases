# InvoiceHub Downloads

InvoiceHub is an offline-first GST billing and business app for Indian small
businesses. This is the official downloads-only repository.

## Download InvoiceHub

| Platform | Version | Download |
| --- | --- | --- |
| Windows 10/11, 64-bit | 1.1.4 | [Download the Windows installer](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.4/InvoiceHub-Setup-1.1.4.exe) |
| Debian/Ubuntu Linux, 64-bit | 1.1.2 | [Download the Linux installer](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.2/InvoiceHub-1.1.2-linux.deb) |
| Android 7 or newer, direct install | 1.1.4 (build 10) | [Download the Android APK](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.4/InvoiceHub-Android-1.1.4.apk) |

See the [InvoiceHub 1.1.4 release page](https://github.com/Changtey/InvoiceHub-releases/releases/tag/v1.1.4)
for checksums, verification results, and release notes.

## Install on Windows

1. Download `InvoiceHub-Setup-1.1.4.exe`.
2. Open the installer and choose the installation folder if needed.
3. Launch InvoiceHub from the desktop or Start menu shortcut.

The Windows installer is not digitally signed yet, so Windows may show a
security warning. Confirm that the file was downloaded from this official
repository before continuing.

## Install on Linux

The latest Linux installer remains version 1.1.2 and supports 64-bit Debian and
Ubuntu systems.

1. Download `InvoiceHub-1.1.2-linux.deb`.
2. Open it with the system Software Install app, or run
   `sudo apt install ./InvoiceHub-1.1.2-linux.deb` from the download folder.
3. Launch InvoiceHub from the applications menu.

Linux may ask for the computer administrator password. This is required when a
system package is installed or replaced.

## Install on Android

1. Download `InvoiceHub-Android-1.1.4.apk`.
2. Open the APK on the phone.
3. If Android asks, allow installation from the browser or file manager used
   for the download, then finish the Android installation screen.
4. Open InvoiceHub from the app list.

Only install the official signed APK from this repository. Android may show its
required “Allow from this source” and installation confirmation screens.

## Automatic updates

- InvoiceHub checks for a newer stable release whenever the Android or Windows
  app starts.
- It does not download an update until the user chooses **Update Now**.
- On Windows, **Update Now** downloads and verifies the installer, installs it
  in the current app location, and automatically reopens InvoiceHub.
- On Android, **Update Now** downloads and verifies the APK. Android then shows
  its required installation approval screen. Newer Android phones may show an
  **InvoiceHub updated** notification that can be tapped to open the app.
- Interrupted downloads and failed installations leave the current working
  version in place and can be tried again.

## What changed in 1.1.4

- Android reports now generate clean multi-page PDF files that can be previewed,
  printed, and shared.
- Added printable receipts for Money In and Payment In.
- Added printable vouchers for Payment Out.
- Fixed sales total editing so the decimal part can be removed, for example
  from 2,500.11 to 2,500.
- Invoice dates now use a clear format such as 03 March 2026 in forms, lists,
  details, and PDF documents.
- Confirmed startup update checks and the **Update Now** flow for Android and
  Windows.
- Unneeded source maps, tests, environment files, and private signing files are
  excluded from the packaged application.

## Verification

- 128 Windows/Web application tests passed.
- 18 Windows updater and security tests passed.
- Android analysis found no issues and all 137 Android tests passed.
- The signed Android APK package name, version 1.1.4, build 10, permissions,
  alignment, size, checksum, and signing certificate were verified.
- The Windows package embeds version 1.1.4, and its update file matches the
  exact installer.
- No physical Android phone was connected, and the Windows installer was not
  installed during this release session.

## SHA-256

- Windows installer:
  `7051b9972efe0c2e67a114777ee5bf2b0eb60434bc4c4dd28163fc82f9126a45`
- Android APK:
  `ef58ec02a3f2e00f62432c9974fbd0664f189dd873b151096edae001b84394a3`

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
