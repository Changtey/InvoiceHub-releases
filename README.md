# InvoiceHub Downloads

InvoiceHub is an offline-first GST billing and business app for Indian small businesses. This is the official downloads repository.

## Download InvoiceHub

| Platform | Version | Download |
| --- | --- | --- |
| Windows 10/11, 64-bit | 1.1.20 | [Windows installer](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.20/InvoiceHub-Setup-1.1.20.exe) |
| Debian/Ubuntu Linux, 64-bit | 1.1.20 | [Linux installer](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.20/InvoiceHub-1.1.20-linux.deb) |
| Android 7 or newer | 1.1.20 (build 25) | [Android APK](https://github.com/Changtey/InvoiceHub-releases/releases/download/v1.1.20/InvoiceHub-Android-1.1.20.apk) |

See the [InvoiceHub 1.1.20 release](https://github.com/Changtey/InvoiceHub-releases/releases/tag/v1.1.20) for release notes, checksums, and update files.

## Install or update

- **Windows:** open `InvoiceHub-Setup-1.1.20.exe` and follow the installer. The installer is currently unsigned, so Windows may show a security warning. Confirm that it came from this official repository.
- **Linux:** open `InvoiceHub-1.1.20-linux.deb` with Software Install, or run `sudo apt install ./InvoiceHub-1.1.20-linux.deb`. Linux may require administrator approval.
- **Android:** open `InvoiceHub-Android-1.1.20.apk`. Android may ask you to allow installation from your browser or file manager and approve the installation.

Install over the existing app to retain saved business data. Do not uninstall the existing app as part of updating.

InvoiceHub checks for new stable releases when it starts. From 1.1.14 onward:

- **Windows and Linux** download new versions in the background. The update installs when you choose **Restart & update**, or by itself the next time you open InvoiceHub, before you start working. Linux .deb installs ask for the administrator password.
- **Android** downloads new versions by itself on Wi-Fi once you have allowed InvoiceHub to install updates. On mobile data it asks first. Android 12 and newer install later updates without another prompt; older phones show Android's install screen.

Every update is verified before installation. Interrupted downloads and failed installations leave the current working version in place.

## What's new in 1.1.20

- **Sync waits while you edit a bill.** While a sale, purchase or other bill is open, InvoiceHub no longer changes anything on it from the cloud. Changes from your other devices wait, and your bill syncs as soon as you save it.
- **Your saved edits are kept.** Changes made on another device while you edit no longer replace or mix with what you save.
- **Changing a line total no longer changes the quantity.** The quantity stays exactly as you typed it; only the price per item follows the total. You can type the total first and the quantity after.
- A row with an amount but no quantity is no longer left out of the bill without warning. InvoiceHub asks for the quantity instead.
- Windows, Linux and Android all move to 1.1.20.

## What's new in Android 1.1.19

- **Saving on the phone no longer fails.** Two saves at the same moment could break each other ("Cannot delete file … invoicehub_data.json.tmp"), so a bill could be missing later or never reach your other devices. Saves now happen one at a time.
- If the phone switches off in the middle of a save, InvoiceHub restores the last good copy of your data when it opens.
- Windows and Linux stay at 1.1.18; they don't need this fix.

See the [Android 1.1.19 release](https://github.com/Changtey/InvoiceHub-releases/releases/tag/v1.1.19) for its checksum.

## What's new in 1.1.18

- **Sync you can rely on.** Every app now downloads only what changed since its last sync. Before, InvoiceHub could use up Firebase's free daily cloud limit, and then no device synced until 1:30 PM IST.
- **Owners sign in with Google on Windows and Linux** (Settings → Data & sync → Sign in with Google), using the same Google account as their Android phone. Computers that joined with a Workspace Key keep their bills when they switch.
- **Cashiers and assistants** still join with the Workspace Key the owner gives them.
- **Android** shows when it last synced and how many changes are still waiting, and no longer stops syncing without telling you.

## New in 1.1.17

- **Google Play edition** updates quietly in the background instead of showing a full-screen update screen.
- Windows, Linux and the Android APK on this page have no other changes; they move to 1.1.17 so every app shows the same version.

## New in 1.1.16

- **Plan & billing.** Android (Settings → Plan & billing), Windows and Linux show your InvoiceHub plan: launch offer, free trial, free or paid time, the price, any personal discount, a coupon code check, and how to pay by UPI. Desktops and staff phones show the workspace owner's plan.
- **Nobody is charged automatically** and nothing is locked. The launch offer keeps InvoiceHub free until 29 January 2027.
- **Prices, discounts and recorded payments for the developer**, in the Android admin panel or in the browser, protected by Firebase security rules.

## Fixes in 1.1.16

- **Windows and Linux:** the InvoiceHub logo now shows on the taskbar instead of a blank icon.

Use the attached `checksums.json` to verify download sizes and SHA-256 values. Download InvoiceHub only from this official repository.

## About this repository

This repository contains installers, update metadata, checksums, and this download guide. It does not contain InvoiceHub application source code, private signing files, or business data.

GitHub automatically shows **Source code** archives on tagged releases. Those archives contain only this downloads repository and its public metadata.
