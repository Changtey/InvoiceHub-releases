# InvoiceHub Downloads

InvoiceHub is an offline-first GST billing and business app for Indian small
businesses. This is the official downloads-only repository.

## Download InvoiceHub

| Platform | Version | Download |
| --- | --- | --- |
| Windows 10/11, 64-bit | 1.1.8 | [Download the Windows installer](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.8/InvoiceHub-Setup-1.1.8.exe) |
| Debian/Ubuntu Linux, 64-bit | 1.1.8 | [Download the Linux installer](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.8/InvoiceHub-1.1.8-linux.deb) |
| Android 7 or newer, direct install | 1.1.8 (build 14) | [Download the Android APK](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.8/InvoiceHub-Android-1.1.8.apk) |

See the [InvoiceHub 1.1.8 release](https://github.com/Changtey/InvoiceHub-releases/releases/tag/v1.1.8)
for checksums and release notes.

## Install on Windows

1. Download `InvoiceHub-Setup-1.1.8.exe`.
2. Open the installer and choose the installation folder if needed.
3. Launch InvoiceHub from the desktop or Start menu shortcut.

The Windows installer is not digitally signed yet, so Windows may show a
security warning. Confirm that the file was downloaded from this official
repository before continuing.

## Install on Linux

The Linux installer supports 64-bit Debian and Ubuntu systems.

1. Download `InvoiceHub-1.1.8-linux.deb`.
2. Open it with the system Software Install app, or run
   `sudo apt install ./InvoiceHub-1.1.8-linux.deb` from the download folder.
3. Launch InvoiceHub from the applications menu.

Linux may ask for the computer administrator password. This is required when a
system package is installed or replaced.

## Install on Android

1. Download `InvoiceHub-Android-1.1.8.apk`.
2. Open the APK on the phone.
3. If Android asks, allow installation from the browser or file manager used
   for the download, then finish the Android installation screen.
4. Open InvoiceHub from the app list.

Only install the official signed APK from this repository. Android may show its
required “Allow from this source” and installation confirmation screens.

## Automatic updates

- InvoiceHub checks for a newer stable release whenever the Android, Windows,
  or Linux app starts.
- It does not download an update until the user chooses **Update Now**.
- On Windows, **Update Now** downloads and verifies the installer, installs it
  in the current app location, and automatically reopens InvoiceHub.
- On Android, **Update Now** downloads and verifies the APK. Android then shows
  its required installation approval screen. Newer Android phones may show an
  **InvoiceHub updated** notification that can be tapped to open the app.
- Interrupted downloads and failed installations leave the current working
  version in place and can be tried again.

## What changed in 1.1.8

- Repairs missed sync requests, new-record uploads from Android editors, and
  protection of unsent changes during incoming updates.
- Shows offline, paused, failed, and last successful sync clearly.
- Corrects decimal rounding and discount handling; keeps fixed discounts when
  reopening, copying, or converting invoices.
- Preserves exact entered totals and recorded overpayments.
- Improves A4 page use, text size, continuation headings, and actual-size printing.
- Adds clearer dashboard and invoice lists, readable balances, and a Balance due
  filter that includes partial payments.

Install over the existing app to keep saved data, or reopen InvoiceHub and choose
**Update Now**.

## Verification

- 174 Web checks, 20 desktop checks, and 151 Android checks passed.
- A fictional Rs. 15,000.00 invoice kept its total after saving and reopening.
  A Rs. 5,000.00 payment correctly left Rs. 10,000.00 due.
- Desktop and Android A4 samples were generated and visually inspected.
- Live syncing between signed-in devices, physical printing, and physical Android
  and Linux installation were not tested in this release.
- See the release notes for package checks and the attached `checksums.json` for
  file sizes and SHA-256 values.

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
