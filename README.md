# InvoiceHub Downloads

InvoiceHub is an offline-first GST billing and business app for Indian small businesses. This is the official downloads repository.

## Download InvoiceHub

| Platform | Version | Download |
| --- | --- | --- |
| Windows 10/11, 64-bit | 1.1.11 | [Windows installer](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.11/InvoiceHub-Setup-1.1.11.exe) |
| Debian/Ubuntu Linux, 64-bit | 1.1.11 | [Linux installer](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.11/InvoiceHub-1.1.11-linux.deb) |
| Android 7 or newer | 1.1.12 (build 17) | [Android APK](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.12/InvoiceHub-Android-1.1.12.apk) |

See [desktop 1.1.11](https://github.com/Changtey/InvoiceHub-releases/releases/tag/v1.1.11) and [Android 1.1.12](https://github.com/Changtey/InvoiceHub-releases/releases/tag/v1.1.12) for release notes, checksums, and update files.

## Install or update

- **Windows:** open `InvoiceHub-Setup-1.1.11.exe` and follow the installer. The installer is currently unsigned, so Windows may show a security warning. Confirm that it came from this official repository.
- **Linux:** open `InvoiceHub-1.1.11-linux.deb` with Software Install, or run `sudo apt install ./InvoiceHub-1.1.11-linux.deb`. Linux may require administrator approval.
- **Android:** open `InvoiceHub-Android-1.1.12.apk`. Android may ask you to allow installation from your browser or file manager and approve the installation.

Install over the existing app to retain saved business data. Do not uninstall the existing app as part of updating.

InvoiceHub checks for new stable releases when it starts. Downloads begin after **Update Now**. The app verifies the update before installation. Interrupted downloads and failed installations leave the current working version in place. Newer Android phones may show an **InvoiceHub updated** notification that can be tapped to reopen the app.

## Android update repair in 1.1.12

Android 1.1.11 could install successfully but keep offering the same update because its checker reported an older cached build number. Version 1.1.12 reads the installed version directly from Android and stops offering a version that is already installed. It retains the 1.1.11 invoice and PDF fixes.

If the old app keeps offering 1.1.11, close it fully and reopen it, or download the 1.1.12 APK above and install over the existing app. Keep the existing app installed to retain its saved data.

Windows and Linux remain on version 1.1.11.

## What changed in 1.1.11

- Invoice headings, quantities, rates, tax values, and amounts align consistently across all 20 templates.
- Column widths account for the selected font and actual values, keeping large amounts together in the reviewed cases.
- Receipt headers stay inside the paper, and continuation pages keep the complete invoice reference.
- Android Heritage invoices align wrapped numeric headings and the tax summary correctly.
- Desktop Save, Save Draft, Save & Preview, and Save & New now explain missing company setup and keep entered document details.
- Company state is optional when creating a company from a desktop document.
- Desktop View, Edit, and More actions stay visible when transaction tables scroll. View and Edit have text labels.
- Desktop Reports has five categories, search, short descriptions, and favorites.
- The desktop app logo and favicon are bundled correctly for installed apps.

## Verification

- 251 web checks, 20 desktop checks, and 211 Android checks passed. One Android check was intentionally skipped.
- 430 fictional PDFs across 530 pages were checked, including 4,420 measured table text positions. No clipping, overlapping text, missing glyphs, or table alignment errors were detected in those samples.
- Package identities, versions, update metadata, and file checksums were verified. Android signing and alignment were checked against the existing trusted certificate.
- Windows 1.1.11 was installed and its files verified locally. Physical Android/Linux installation, physical printing, and live sync between signed-in devices were not verified for this release.

Use the attached `checksums.json` to verify download sizes and SHA-256 values. Download InvoiceHub only from this official repository.

## About this repository

This repository contains installers, update metadata, checksums, and this download guide. It does not contain InvoiceHub application source code, private signing files, or business data.

GitHub automatically shows **Source code** archives on tagged releases. Those archives contain only this downloads repository and its public metadata.
