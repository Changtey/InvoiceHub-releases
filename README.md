# InvoiceHub Downloads

InvoiceHub is an offline-first GST billing and business app for Indian small businesses. This is the official downloads repository.

## Download InvoiceHub

| Platform | Version | Download |
| --- | --- | --- |
| Windows 10/11, 64-bit | 1.1.14 | [Windows installer](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.14/InvoiceHub-Setup-1.1.14.exe) |
| Debian/Ubuntu Linux, 64-bit | 1.1.14 | [Linux installer](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.14/InvoiceHub-1.1.14-linux.deb) |
| Android 7 or newer | 1.1.14 (build 19) | [Android APK](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.14/InvoiceHub-Android-1.1.14.apk) |

See the [InvoiceHub 1.1.14 release](https://github.com/Changtey/InvoiceHub-releases/releases/tag/v1.1.14) for release notes, checksums, and update files.

## Install or update

- **Windows:** open `InvoiceHub-Setup-1.1.14.exe` and follow the installer. The installer is currently unsigned, so Windows may show a security warning. Confirm that it came from this official repository.
- **Linux:** open `InvoiceHub-1.1.14-linux.deb` with Software Install, or run `sudo apt install ./InvoiceHub-1.1.14-linux.deb`. Linux may require administrator approval.
- **Android:** open `InvoiceHub-Android-1.1.14.apk`. Android may ask you to allow installation from your browser or file manager and approve the installation.

Install over the existing app to retain saved business data. Do not uninstall the existing app as part of updating.

InvoiceHub checks for new stable releases when it starts. From 1.1.14 onward:

- **Windows and Linux** download new versions in the background. The update installs when you choose **Restart & update**, or by itself the next time you open InvoiceHub, before you start working. Linux .deb installs ask for the administrator password.
- **Android** downloads new versions by itself on Wi-Fi once you have allowed InvoiceHub to install updates. On mobile data it asks first. Android 12 and newer install later updates without another prompt; older phones show Android's install screen.

Every update is verified before installation. Interrupted downloads and failed installations leave the current working version in place.

## What's new in 1.1.14

- **Group by customer or supplier.** Sales, Purchases and Payments can show bills grouped under each party, with totals and balance due.
- **Party page.** Click a customer or supplier to see all their invoices, quotations, orders, bills and payments together, and what they owe.
- **Search by amount.** Find a bill by number, name, or total, for example `6372` or `₹6,372`.
- **Product pictures.** Up to six pictures per product, resized automatically.
- **New Home screen** with a getting-started checklist, quick actions, and "Who owes you".
- **Help & about** with a step-by-step tutorial, the app version, and developer contact.
- **Keyboard shortcuts** on desktop, and a more compact bill screen.
- **Automatic updates** on Windows, Linux and Android, as described above.

## Fixes in 1.1.14

- New bills, payments and expenses use today's date in India (work between midnight and 5:30 AM was dated the previous day).
- Desktop quotations, orders and purchase documents get their own number prefix (QT-, SO-, PB- …) instead of the invoice prefix; wrongly saved prefixes are repaired automatically.
- Customer and supplier balances include bills with hand-typed names, and match on every page.
- Payment totals count returns correctly; several desktop navigation issues are fixed.

Use the attached `checksums.json` to verify download sizes and SHA-256 values. Download InvoiceHub only from this official repository.

## About this repository

This repository contains installers, update metadata, checksums, and this download guide. It does not contain InvoiceHub application source code, private signing files, or business data.

GitHub automatically shows **Source code** archives on tagged releases. Those archives contain only this downloads repository and its public metadata.
