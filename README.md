# Touchline

A personal Android companion app for football coaching, match tracking and garage training, built for Lloyd's Waveshare device.

This is a small family project, shared publicly for convenient downloads. It is designed for the **Waveshare ESP32-S3-Touch-AMOLED-1.75C** running the matching **Touchline/Lloyd firmware**. The ordinary Waveshare demonstration firmware will not work with it. Without the matching device and firmware, the app has limited usefulness: you can prepare plans, but cannot sync or collect device records.

## Download

**[Download Android 0.3.2](https://github.com/reflectingme/touchline/releases/download/android-v0.3.2/Touchline-0.3.2.apk)** · [Release notes and all downloads](https://github.com/reflectingme/touchline/releases)

The installed app is currently called **Lloyd Touchline** and has a red football icon. Touchline is the public project name.

## What it does

- Saves match results, timelines, weather and season statistics received from the device.
- Creates and edits team, match, coaching and gym plans, including copies, search and upcoming fixtures.
- Sends individual plans or all pending changes to a paired device over local Wi-Fi.
- Keeps imported gym and coaching session history on the phone.

## Install or update

1. Open the download link on your Android phone and download the **APK** file.
2. Open the file. If Android asks, allow installation from the browser or file app you used.
3. Confirm **Install** or **Update**. For future versions, update the existing app rather than uninstalling it, to retain its local data.

Requires **Android 8 or newer**; tested on a Samsung Galaxy A12 running Android 12. Use matching device firmware **0.4.22** for the full feature set. The APK installs only the Android app; it does not update Waveshare firmware.

To connect for the first time, put both devices on the same local Wi-Fi. Open **Phone sync → Pair phone** on the Waveshare and follow the Android app's **Device** instructions. Pairing is remembered. For later transfers, wake the Waveshare, finish any running activity before sending a plan, and transfer from the phone. Received plans are reviewed and loaded separately on the device.

**From version 0.3.1:** open **Device → App updates** to check manually. Automatic checks run when due on opening/returning and approximately every two hours; Android may delay background checks. New versions appear as a Home notice. Downloading and installing are your choice, with Android confirmation. No Waveshare firmware is installed by this updater. Users on 0.3.0 need to install 0.3.1 manually once.

## Your data

The download contains no saved match records, personal training history, Wi-Fi credentials or device pairing keys. Records are stored locally; publishing this APK does not publish anyone's records. GitHub hosts the download, not the app's match history.

This repository contains download information and release packages. It does not contain the app's source code or the matching device firmware. This is a personal project under active development, with no commitment to support other hardware.
