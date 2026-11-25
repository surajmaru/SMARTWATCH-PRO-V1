# Logicsuru Smartwatch Pro V1
<img width="140" height="280" alt="IMG_20261023_220142" src="https://github.com/user-attachments/assets/3eb1cc6b-edda-4624-9ef6-e04950d3ac00" />
<img width="140" height="280" alt="IMG_20261023_211505" src="https://github.com/user-attachments/assets/cb26a073-474d-4c54-b6c6-e5532bb4a4cd" />
<img width="280" height="140" alt="IMG_20261023_160830" src="https://github.com/user-attachments/assets/b60897fc-d548-4f91-82ed-3a87c59ec38f" />



## Components used:-

- ESP32 C3 super mini
- 1.3inch oled display
- Tp4056 charging module
- 3.7v lipo battery
- Push button
- Toggle switch
- Touch sensor module (TTP233)
- Watch strap
- Universal PCB board

## Schematics:-
<img width="500" height="500" alt="c3-smartwatch_bb" src="https://github.com/user-attachments/assets/6e4c127b-2770-48cb-99bc-01d9ffd55d5a" />
<img width="800" height="400" alt="Screenshot 2026-10-24 011615" src="https://github.com/user-attachments/assets/5a4461b6-6774-4692-9d5c-b1cbfa072a77" />

## Features & Specifications

A custom-built smartwatch powered by the **ESP32-C3 SuperMini**, combining everyday smartwatch functionality with custom firmware, interactive mini-games, and a unique virtual companion.

- **Live Date & Time** – Displays the current date and time.
- **Weather Updates** – View temperature, humidity, and UV index.
- **Custom Watch Faces** – Choose from multiple watch faces to personalize your smartwatch.
- **Virtual Companion** – A cute, custom-designed companion built into the watch.
- **Mini-Games** – Play three built-in games: Dino Runner, Hill Climb Racing, and Flappy Bird.
- **Weather Dashboard** – Access a dedicated web dashboard for detailed weather information.
- **Stopwatch** – Time activities directly from your wrist.
- **Flashlight Mode** – Boosts screen brightness to 100% for improved visibility in the dark.
- **Customizable Settings** – Adjust screen timeout, brightness, watch faces, clock settings, and other preferences.
- **System Status** – View detailed information about the watch and its system.
- **Phone Notifications** – See your phone's notifications on the watch using the **LOGICSURU Watch** Android app (see below).
- **Call Alerts** – The watch shows who is calling, and you can decline the call from the watch.
- **Music Controls** – See what's playing and play/pause or skip tracks from your wrist.

## Firmware Flash

Flash the Firmware using the dedicated **LogicSuru Flasher** web interface:-

**[Open LogicSuru Flasher](https://logicsuruflasher.vercel.app/)**

## LOGICSURU Watch Android App

The official companion app connects your phone to the watch over Bluetooth Low Energy and handles everything in one place.

**[⬇️ Download the latest APK](../../releases/latest)**

### What the app does

- **Notifications** – Forward phone notifications to the watch, with a per-app on/off list
- **Calls** – Caller name or number on the watch, and decline from the watch
- **Music** – Now playing info plus play/pause and next track
- **Settings** – Watch face, brightness, screen timeout, Do Not Disturb, 12/24-hour clock, weather city and Wi-Fi
- **Time sync** – Keeps the watch clock correct
- **Stays connected** – Runs in the background, reconnects on its own, and can start again after a reboot

**Requirements:** Android 8.0 or newer with Bluetooth LE. The app has no analytics and makes no network calls. Every permission is optional, and the feature it controls just stays off if you skip it.

### Installing the app

When you open the APK, Android may show **"App blocked to protect your device"**. This is Google Play Protect being extra careful with apps installed outside the Play Store that use **notification access** (needed to show your phone's notifications on the watch).

<img width="250" height="360" alt="install_error" src="https://github.com/user-attachments/assets/50fa54bb-f19e-4a92-ad89-f913e91b1a5f" />

**To install it:**

1. Open the **Google Play Store** app
2. Tap your **profile picture** (top right) → **Play Protect** → tap the **⚙️ settings** icon
3. Turn **off** "Scan apps with Play Protect"
4. Install the APK
5. Go back and turn **"Scan apps with Play Protect"** back **on**

> Menu names can differ slightly between phone brands and Android versions.

**Prefer a computer?** Turn on USB debugging and run:

```
adb install LogicsuruWatch.apk
```

### First-time setup

1. Open the app and follow the setup steps (Bluetooth, notifications, calls, background)
2. Turn on **Notification Access** for LOGICSURU Watch in Android settings so notifications can reach the watch
3. Turn on the watch and tap **Scan** in the app to connect

## Configure your smartwatch with your mobile (bluetooth & wifi):-

You can use the Android app above, or the web version (Android Chrome):

https://logicsuruwatch.vercel.app/

### Battery Life

Approximately **8–10 hours** under normal usage. Actual battery life varies depending on screen brightness, connectivity, and feature usage.

### Project Overview

This project explores **embedded systems, wearable electronics, and custom firmware development**, bringing together practical smartwatch features, interactive entertainment, and personalized software in a compact DIY device.

## Important NOTE:- This firmware only works with the esp32 c3 and with the configured wire connections as i showed in the diagram.

## Build Video:-
https://youtu.be/khXg8iQ5Ihw?si=N-Aul9dYYsl73EUy
