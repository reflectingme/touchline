# Touchline

An Android companion app for football coaching, match tracking and training, designed for the **Waveshare ESP32-S3-Touch-AMOLED-1.75C** with matching Touchline firmware.

## Download

**[Download Android 0.4.3](https://github.com/reflectingme/touchline/releases/download/android-v0.4.3/Touchline-0.4.3.apk)** · [All releases](https://github.com/reflectingme/touchline/releases)

Requires **Android 8 or newer**. The installed app is called **Lloyd Touchline**, with a red football icon.

## Features

- Match history, goal timelines, weather and season statistics.
- Team, match, coaching and gym plans, with search, duplication and upcoming fixtures.
- Send plans to the paired device and receive match and training records over local Wi-Fi.
- Separate update controls for the Android app and Waveshare firmware.
- Offline illustrated guides, page help and a clear transfer summary.
- Preview and share match scorecards with optional dates, venue, weather and timelines.

## Install and pair

1. Download and open the **APK** on your phone. Allow installation from that source if Android asks, then confirm installation.
2. Connect the phone and Waveshare to the same local Wi-Fi network. Waveshare needs **2.4 GHz**.
3. On Waveshare, open **Settings → Wi-Fi → Phone sync → Pair phone**.
4. In the Android app's **Device** tab, enter the displayed address and all four code groups, then tap **Pair and get history**.

The first-use guide walks through these steps; reopen it under **Device → Pairing help**. Pairing is remembered. For later transfers, wake the device on the same Wi-Fi and use **Get history** or send a plan from the phone. Received plans are reviewed and loaded on the device.

The ordinary Waveshare demonstration firmware is not compatible. Without the matching device and firmware, plans can be prepared on the phone, but device records and sync are unavailable.

## Updates

**Android app:** use **Device → App updates**. Automatic checks are also available; Android may delay background checks. Download and installation require your approval. Update the existing app without uninstalling to keep its local records and pairing.

**Waveshare device:** Android 0.4.0 includes **Device → App updates → Waveshare updates**. First install **device 0.4.23 by USB** to add its update receiver. Future compatible updates can then be sent over Wi-Fi. Keep Waveshare on USB power, finish active activities/timers and keep the phone app open until the restarted version is confirmed.

[Waveshare firmware 0.4.24](https://github.com/reflectingme/touchline/releases/tag/waveshare-v0.4.24) is for the aluminium **1.75C** board only. Phone releases use `.apk` files; device releases use `.bin` files and independent version numbers. Bootloader/partition changes and recovery beyond the built-in updater require USB.

## About this repository

This is a personal project shared publicly for convenient downloads. The repository holds documentation, update information and release packages; it does not contain the application source code.

Downloads contain no saved match records, training history, Wi-Fi credentials or pairing keys. App records stay on the phone and device; GitHub hosts the updates, not your history.
