# InvoiceHub Downloads

InvoiceHub is an offline-first GST billing and business app for Indian small
businesses. This is the official downloads-only repository.

## Download InvoiceHub

| Platform | Version | Download |
| --- | --- | --- |
| Windows 10/11, 64-bit | 1.1.6 | [Download the Windows installer](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.6/InvoiceHub-Setup-1.1.6.exe) |
| Debian/Ubuntu Linux, 64-bit | 1.1.6 | [Download the Linux installer](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.6/InvoiceHub-1.1.6-linux.deb) |
| Android 7 or newer, direct install | 1.1.6 (build 12) | [Download the Android APK](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.6/InvoiceHub-Android-1.1.6.apk) |

See the [InvoiceHub 1.1.6 release page](https://github.com/Changtey/InvoiceHub-releases/releases/tag/v1.1.6)
for checksums, verification results, and release notes.

## Install on Windows

1. Download `InvoiceHub-Setup-1.1.6.exe`.
2. Open the installer and choose the installation folder if needed.
3. Launch InvoiceHub from the desktop or Start menu shortcut.

The Windows installer is not digitally signed yet, so Windows may show a
security warning. Confirm that the file was downloaded from this official
repository before continuing.

## Install on Linux

The Linux installer supports 64-bit Debian and Ubuntu systems.

1. Download `InvoiceHub-1.1.6-linux.deb`.
2. Open it with the system Software Install app, or run
   `sudo apt install ./InvoiceHub-1.1.6-linux.deb` from the download folder.
3. Launch InvoiceHub from the applications menu.

Linux may ask for the computer administrator password. This is required when a
system package is installed or replaced.

## Install on Android

1. Download `InvoiceHub-Android-1.1.6.apk`.
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

## What changed in 1.1.6

- Entering a line total of **₹15,000** now keeps it at **₹15,000.00**.
- Selling price, taxable value, and GST are adjusted together so their sum
  matches the exact amount entered.
- Amounts with paise, such as **₹15,000.01**, also stay exact.
- Entered totals survive saving, reopening, description edits, copying, and
  converting documents across Windows, Linux, and Android.
- Changing quantity, price, discount, or tax recalculates the line from those
  changed values.
- The desktop updater's YAML library includes its latest security fix.
- The Linux installer includes the package information needed by its updater.

## Verification

- All 151 Windows/Web application checks passed.
- All 18 desktop updater and security checks passed.
- All 141 Android checks passed.
- Web lint and Android analysis completed without errors. Existing style
  warnings and older-library notices remain.
- The production desktop dependency audit reports zero known vulnerabilities.
  The full development workspace audit reports 24 findings.
- The signed Android APK package name, version 1.1.6, build 12, alignment,
  size, checksum, and trusted signing certificate were verified.
- Windows and Linux packages embed version 1.1.6. Their update files match
  the exact installers.
- The Linux package structure, executable permissions, and update identity
  were verified.
- A fresh installation was not manually checked during this release.
  No physical Android phone or Linux computer was used for installation checks.

## SHA-256

- Windows installer:
  `53137d757318cdb0c33f19222b0c7a0876cfc5fb67d690fd39ae3a0f9803d466`
- Linux installer:
  `e87a3131b1f5aae9bed1152c9f96cc33b79465bcf9c099169fd089e6bde6ed6d`
- Android APK:
  `58612905060e9852ed3a1dfcf538593e541fbf267f3ddce22218bdf5e21dedcb`

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
