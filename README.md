# 🌌 Galaxy Theme Patcher

A professional desktop automation tool designed to make Samsung Galaxy Store trial themes permanent. Compatible with all versions from One UI 1.0 to the latest One UI 8.0.

## ✨ Features
- **Universal Support:** Works across all Samsung One UI versions (Android 9 to Android 16).
- **Infinity Timer:** Injects a custom value into the system database to set trial duration to 4,000+ years.
- **Watchdog Killer:** Automatically detects and freezes background security services like `Dressroom` that trigger theme reverts.
- **Safe & Reversible:** One-click 'Restore' button to return your device to stock settings instantly.
- **No Root Required:** Operates entirely through ADB (Android Debug Bridge).

## 🛠️ How It Works
The patcher uses a multi-layer bypass strategy:
1. **Database Layer:** Modifies `theme_trial_time` in the Secure Settings.
2. **Permission Layer:** Revokes `START_FOREGROUND` rights for theme services.
3. **Service Layer:** Suspends the "Watchdog" packages that monitor trial status.

## 🚀 Getting Started

### Prerequisites
- Windows or Linux PC.
- Samsung device with **USB Debugging** enabled in Developer Options.
- [ADB Drivers](https://developer.android.com/tools/adb) installed on your PC.

### Installation
1. Download the latest `GalaxyThemePatcher-Release.zip` from the [**Releases Page**](https://github.com/Varun7009/Galaxy-Theme-Patcher/releases).
   > **Note:** Do NOT download the "Source Code" zip. Use the file under "Assets" in the Release section.
2. Connect your phone to your PC via USB.

### Usage
1. Open the **Galaxy Store** on your phone.
2. Download and **Apply** your desired Trial Theme or Icons.
3. Close the Store app.
4. Open **Galaxy Theme Patcher** on your PC and click **"Apply Permanent Patch"**.
5. Wait for the "Success" message. You're done!

> **Note:** Do NOT fully disable Developer Options after patching, as it may trigger a system security sweep and reset your theme.

## ⚠️ Disclaimer
This tool is for educational and personal customization purposes only. Use it at your own risk. We are not responsible for any issues caused to your device.
