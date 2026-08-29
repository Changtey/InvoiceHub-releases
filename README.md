# InvoiceHub Downloads

InvoiceHub is an offline-first GST billing and business app for Indian small
businesses. This is the official downloads-only repository.

## Download InvoiceHub

| Platform | Version | Download |
| --- | --- | --- |
| Windows 10/11, 64-bit | 1.1.5 | [Download the Windows installer](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.5/InvoiceHub-Setup-1.1.5.exe) |
| Debian/Ubuntu Linux, 64-bit | 1.1.2 | [Download the Linux installer](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.2/InvoiceHub-1.1.2-linux.deb) |
| Android 7 or newer, direct install | 1.1.5 (build 11) | [Download the Android APK](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.5/InvoiceHub-Android-1.1.5.apk) |

See the [InvoiceHub 1.1.5 release page](https://github.com/Changtey/InvoiceHub-releases/releases/tag/v1.1.5)
for checksums, verification results, and release notes.

## Install on Windows

1. Download `InvoiceHub-Setup-1.1.5.exe`.
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

1. Download `InvoiceHub-Android-1.1.5.apk`.
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

## What changed in 1.1.5

- Dates now use short, readable month names such as `25 Jan 2025` and
  `04 Sep 2026` across Windows and Android, including forms, lists, details,
  reports, receipts, vouchers, and PDFs.
- Existing payments can now be opened directly from payment history.
- Windows adds payment editing and receipt or voucher printing.
- Android adds receipt or voucher details, printing, and PDF sharing.
- The refreshed packages include the latest payment and report improvements
  from the shared InvoiceHub workspace.
- Unneeded source maps, tests, environment files, application source files, and
  private Android signing files are excluded from the packaged Windows app.

## Verification

- All 143 Windows/Web application tests passed.
- All 18 Windows updater and security tests passed.
- Android analysis found no issues and all 137 Android tests passed.
- Both the production-only and full Windows/Web package audits reported zero
  known vulnerabilities.
- The signed Android APK package name, version 1.1.5, build 11, alignment, size,
  checksum, and signing certificate were verified. Its signing certificate is
  unchanged from version 1.1.4.
- The Windows package embeds version 1.1.5, and its update file matches the exact
  installer and update block map.
- The Windows installer completed successfully on the release laptop, and the
  installed executable reports version 1.1.5.
- No physical Android phone was connected during this release session.

## SHA-256

- Windows installer:
  `1133edd6e3378264301956fe63b1234a6f82da560dfe86f4bd02ebff4087eebf`
- Android APK:
  `8a1de3908ae62afc4a4aaa2829b05a0d71caaed5a651302db06d3fd0164454f8`

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
