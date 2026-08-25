# InvoiceHub Downloads

InvoiceHub is an offline-first GST billing and business app for Indian small
businesses. This is the official downloads-only repository.

## Download InvoiceHub 1.1.2

| Platform | Version | Download |
| --- | --- | --- |
| Windows 10/11, 64-bit | 1.1.2 | [Download the Windows installer](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.2/InvoiceHub-Setup-1.1.2.exe) |
| Debian/Ubuntu Linux, 64-bit | 1.1.2 | [Download the Linux installer](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.2/InvoiceHub-1.1.2-linux.deb) |
| Android 7 or newer, direct install | 1.1.2 (build 8) | [Download the Android APK](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.2/InvoiceHub-Android-1.1.2.apk) |

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

## Install on Android

1. Download `InvoiceHub-Android-1.1.2.apk`.
2. Open the APK on the phone.
3. If Android asks, allow installation from the browser or file manager used
   for the download, then finish the system installation screen.
4. Open InvoiceHub from the app list.

Only install the official signed APK from this repository. Android may show its
required “Allow from this source” or installation confirmation screens.

## Automatic updates

- InvoiceHub checks for a newer stable release every time the desktop app opens.
- It never downloads a new version until the user chooses **Update Now**.
- After **Update Now**, it downloads and verifies the package, installs it in
  the existing application location, and automatically reopens the latest version.
- Windows updates are silent for a normal per-user installation. Linux may show
  the required administrator approval for a system package.
- Interrupted downloads and failed installations leave the current working
  version in place and can be retried safely.
- The Android direct-install edition checks its verified feed every time it
  opens. After **Update Now**, it requests any required Android installation
  approval before downloading and continues automatically when the user
  returns. It verifies the APK size, checksum, package, version, and signing
  certificate before installation. Android 10 and newer then show an
  **InvoiceHub updated** notification; tap it once to open the latest version.
  Older Android versions reopen it automatically when the system permits it.

## What changed in 1.1.2

- Fixed a timing fault that could leave the updater stuck if the installer
  failed exactly while the download was completing.
- Failed update checks, downloads, and installer starts now report the correct
  step, restore normal app closing, and allow a safe retry.
- Windows updates explicitly reuse the current installation folder.
- Release preparation now works in standard Windows PowerShell.
- Added the signed Android 1.1.2 build and its verified automatic-update feed.
- Fixed the first direct-update approval handoff so the update resumes
  automatically after the user returns from Android Settings.
- Added a reliable completion notification for Android versions that block
  apps from forcing themselves into the foreground after installation.
- Added a package-replacement fallback so the newly installed APK can report
  completion even when the previous updater process has already stopped.
- Unneeded source maps, tests, environment files, and private signing files are
  excluded from the packaged application.

## Verification

- 98 Web/Desktop application tests passed.
- 18 desktop updater and security tests passed.
- Android analysis found no issues and all 117 Android tests passed.
- The signed Android 1.1.2 APK package, version, build number, updater
  permissions, alignment, contents, size, and checksum were verified.
- Both production and full dependency audits found zero known vulnerabilities.
- Windows 1.1.2 was built and its packaged version and updater were inspected.
- The Debian package structure, version, update metadata, and checksums were
  verified. It was not launched on a real Linux computer in this release check.
- A live Android 15 emulator updated from build 7 to build 8 using the public
  GitHub download. The completion notification opened the latest dashboard and
  no fatal update error occurred. A physical phone was not used for this check.

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
