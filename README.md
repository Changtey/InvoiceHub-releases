# InvoiceHub Downloads

InvoiceHub is an offline-first GST billing and business app for Indian small businesses. This is the official downloads repository.

## Download InvoiceHub

| Platform | Version | Download |
| --- | --- | --- |
| Windows 10/11, 64-bit | 1.1.9 | [Windows installer](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.9/InvoiceHub-Setup-1.1.9.exe) |
| Debian/Ubuntu Linux, 64-bit | 1.1.9 | [Linux installer](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.9/InvoiceHub-1.1.9-linux.deb) |
| Android 7 or newer | 1.1.9 (build 15) | [Android APK](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.9/InvoiceHub-Android-1.1.9.apk) |

See the [InvoiceHub 1.1.9 release](https://github.com/Changtey/InvoiceHub-releases/releases/tag/v1.1.9) for release notes, checksums, and update files.

## Install or update

- **Windows:** open `InvoiceHub-Setup-1.1.9.exe` and follow the installer. The installer is currently unsigned, so Windows may show a security warning. Confirm that it came from this official repository.
- **Linux:** open `InvoiceHub-1.1.9-linux.deb` with Software Install, or run `sudo apt install ./InvoiceHub-1.1.9-linux.deb`. Linux may require administrator approval.
- **Android:** open `InvoiceHub-Android-1.1.9.apk`. Android may ask you to allow installation from your browser or file manager and approve the installation.

Install over the existing app to retain saved business data. Do not uninstall the existing app as part of updating.

InvoiceHub checks for new stable releases when it starts. Downloads begin after **Update Now**. The app verifies the update before installation. Interrupted downloads and failed installations leave the current working version in place. Newer Android phones may show an **InvoiceHub updated** notification that can be tapped to reopen the app.

## What changed in 1.1.9

- Simpler home screens and navigation on desktop and Android.
- Clearer sales, purchases, quotations, orders, returns, payments, expenses, and account transfers.
- Essential entry fields first, with extra details in labelled sections that preserve edits.
- All 20 invoice templates adapt to large sheets, A4, A5, and receipt rolls.
- Better wrapping, repeated headings, compact totals, and less wasted receipt paper.
- Correct payment information for invoices and document-only summaries for quotations and orders.
- Calculation and report fixes for discounts, taxable charges, included GST, returns, payments, customer statements, and date-aware TDS/TCS estimates.

## Verification

- 222 web checks, 20 desktop checks, and 209 Android checks passed.
- 350 fictional print samples were checked for clipped or overlapping text and correct quotation/order payment labels.
- Package identities, versions, update metadata, and file checksums were verified. Android signing and alignment were checked against the existing trusted certificate.
- Physical-device installation, physical printing, and live sync between signed-in devices were not verified for this release.

Use the attached `checksums.json` to verify download sizes and SHA-256 values. Download InvoiceHub only from this official repository.

## About this repository

This repository contains installers, update metadata, checksums, and this download guide. It does not contain InvoiceHub application source code, private signing files, or business data.

GitHub automatically shows **Source code** archives on tagged releases. Those archives contain only this downloads repository and its public metadata.
