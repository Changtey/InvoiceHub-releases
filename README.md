# InvoiceHub Downloads

InvoiceHub is an offline-first GST billing and business app for Indian small businesses. This is the official downloads repository.

## Download InvoiceHub

| Platform | Version | Download |
| --- | --- | --- |
| Windows 10/11, 64-bit | 1.1.15 | [Windows installer](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.15/InvoiceHub-Setup-1.1.15.exe) |
| Debian/Ubuntu Linux, 64-bit | 1.1.15 | [Linux installer](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.15/InvoiceHub-1.1.15-linux.deb) |
| Android 7 or newer | 1.1.15 (build 20) | [Android APK](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.15/InvoiceHub-Android-1.1.15.apk) |

See the [InvoiceHub 1.1.15 release](https://github.com/Changtey/InvoiceHub-releases/releases/tag/v1.1.15) for release notes, checksums, and update files.

## Install or update

- **Windows:** open `InvoiceHub-Setup-1.1.15.exe` and follow the installer. The installer is currently unsigned, so Windows may show a security warning. Confirm that it came from this official repository.
- **Linux:** open `InvoiceHub-1.1.15-linux.deb` with Software Install, or run `sudo apt install ./InvoiceHub-1.1.15-linux.deb`. Linux may require administrator approval.
- **Android:** open `InvoiceHub-Android-1.1.15.apk`. Android may ask you to allow installation from your browser or file manager and approve the installation.

Install over the existing app to retain saved business data. Do not uninstall the existing app as part of updating.

InvoiceHub checks for new stable releases when it starts. From 1.1.14 onward:

- **Windows and Linux** download new versions in the background. The update installs when you choose **Restart & update**, or by itself the next time you open InvoiceHub, before you start working. Linux .deb installs ask for the administrator password.
- **Android** downloads new versions by itself on Wi-Fi once you have allowed InvoiceHub to install updates. On mobile data it asks first. Android 12 and newer install later updates without another prompt; older phones show Android's install screen.

Every update is verified before installation. Interrupted downloads and failed installations leave the current working version in place.

## What's new in 1.1.15

- **Account record.** After Google sign-in on Android, InvoiceHub keeps your name, email, app version and when you last used the app, so the developer can support you and give free access. See the privacy policy.
- **Clear "account closed" message.** If an account is closed, Android and desktop stop syncing and say so. Bills already on your devices stay there.
- **Admin panel for the developer**, protected by Firebase security rules.

## Fixes in 1.1.15

- Desktop no longer retries sync every 15 seconds when an account is closed.

Use the attached `checksums.json` to verify download sizes and SHA-256 values. Download InvoiceHub only from this official repository.

## About this repository

This repository contains installers, update metadata, checksums, and this download guide. It does not contain InvoiceHub application source code, private signing files, or business data.

GitHub automatically shows **Source code** archives on tagged releases. Those archives contain only this downloads repository and its public metadata.
