# 🎵 Priso — Ad-Free Music & Private Shared Space

[![Version](https://img.shields.io/badge/version-v3.5.47-blue.svg)](https://github.com/sonu-dops/PRISO-ad_free-music/raw/main/Priso-v3.5.47.apk)
[![Platform](https://img.shields.io/badge/platform-Android_8.0+-green.svg)](https://github.com/sonu-dops/PRISO-ad_free-music/raw/main/Priso-v3.5.47.apk)
[![VirusTotal](https://img.shields.io/badge/VirusTotal-0%2F70_Clean-brightgreen.svg)](#)
[![Ads](https://img.shields.io/badge/ads-100%25_Ad--Free-brightgreen.svg)](#)
[![Privacy](https://img.shields.io/badge/privacy-P2P_Encrypted_Calls-success.svg)](#)
[![Size](https://img.shields.io/badge/size-6.30_MB-orange.svg)](#)
[![Distribution](https://img.shields.io/badge/repo-Official_Binary_Release-lightgrey.svg)](#)

> **Experience music the way it was meant to be enjoyed — uninterrupted, crystal-clear, addictively personalized, and completely private.**

Priso is an ultra-lightweight, high-fidelity music streaming and private shared sanctuary app designed for uninterrupted listening and private connection. Enjoy unlimited music without ads, background trackers, or subscriptions.

---

## 📥 Download Priso for Android (Latest Official Release)

Click the link below to download the latest official release APK directly:

### 🚀 [**Download Priso v3.5.47 APK** (Direct Download)](https://github.com/sonu-dops/PRISO-ad_free-music/raw/main/Priso-v3.5.47.apk)
*(Alternative mirror: [**priso-latest.apk**](https://github.com/sonu-dops/PRISO-ad_free-music/raw/main/priso-latest.apk))*

| Detail | Specification |
|---|---|
| **App Name** | Priso |
| **Version** | `3.5.47` (Latest Stable) |
| **File Name** | `Priso-v3.5.47.apk` / `priso-latest.apk` |
| **Download Size** | ~6.30 MB (6,606,972 bytes) |
| **Minimum OS** | Android 8.0 (Oreo) or higher |
| **Target Architecture** | Universal (ARM64, ARMv7, x86_64) |
| **SHA-256 Checksum** | `A2E71EB78971DE47647D204E76F8FDBD903EE40D31D6D76ED55506EDBBD11DFC` |

---

### 🌟 What's New in v3.5.47
- **🎨 Spotify-Grade Mobile Music Home**: Sleek card layout featuring contextual greetings (*Good morning / afternoon / evening*), circular favorite artist avatars, 2x2 recent tracks grid, scrollable "Made for You" discovery carousels, and persistent mini-player styled in Priso obsidian-rose.
- **📱 System Notification Bar Playback Controls**: Native Android foreground media service with lock screen and notification shade controls (*Play, Pause, Next, Previous, Stop*) that persist while switching between apps.
- **⏱️ Exact Playback Position Resume**: Pausing or closing the app preserves your exact timestamp. Music resumes right from where you stopped, with cached local/cloud taste telemetry.
- **❄️ Zero-Heating Thermal Optimization**: Dropped offscreen video decoding down to an ultra-efficient 1px audio-only stream. Released battery-draining `HIGH_PERF` Wi-Fi locks on pause, keeping your device cool during extended listening.
- **📉 95% Mobile Data Bandwidth Reduction**: Eliminates hidden 1080p video bandwidth consumption and disables speculative full-track preloads on skips, using $\sim$1 MB/min instead of 25 MB/min.
- **⚡ High-Speed Cloud Node (`priso-server.onrender.com`)**: Upgraded to a dedicated live server with native gzip response compression and sub-60s dynamic endpoint switching.
- **🔒 Hardened Lock Screen Privacy**: Strict system lock authentication (PIN/fingerprint) required before opening private couple spaces from notifications.

---

## 🛡️ Architecture & Security: Why PRISO is only 6.3 MB

Mainstream streaming apps like Spotify, YouTube Music, and Apple Music have ballooned to **80 MB – 150 MB+**. Here is why Priso delivers a richer, ad-free experience in a fraction of that size:

```
┌─────────────────────────────────────────────────────────────┐
│                   BLOATED APPS (80MB+)                      │
│ ❌ 40MB+ Advertising SDKs (AdMob, AppLovin, MoPub, Unity)   │
│ ❌ 20MB+ Telemetry Trackers (Adjust, AppsFlyer, Mixpanel)   │
│ ❌ Heavy DRM storage bloat & uncompressed legacy assets     │
└─────────────────────────────────────────────────────────────┘
                              VS
┌─────────────────────────────────────────────────────────────┐
│                 PRISO LEAN ARCHITECTURE (6.3MB)             │
│ ✅ ZERO Ad SDKs & ZERO Commercial Spyware Trackers          │
│ ✅ Native Android MediaSession foreground audio core         │
│ ✅ Cloud-Offloaded Stream Resolution & Gzip Compression     │
└─────────────────────────────────────────────────────────────┘
```

### 1. Zero Advertising SDKs & Zero Spyware
Commercial apps bundle dozens of advertising SDKs and tracking frameworks to track clicks and serve audio ads. **Priso has ZERO advertising SDKs and ZERO tracker binaries**, eliminating over 60 MB of bloat.

### 2. Native Android Media Services
Priso directly interfaces with Android's native `MediaSession` APIs for foreground audio services, system lock screen controls, and anticipatory buffering without redundant third-party libraries.

### 3. Dedicated Distribution Mirror
This repository (`sonu-dops/PRISO-ad_free-music`) is a **dedicated public binary release mirror** for direct 1-click APK downloads.

---

## 🔒 Verification & VirusTotal Guarantee

You can independently verify the cryptographic integrity and safety of `Priso-v3.5.47.apk` before installing:

### Verify Checksum Locally (PowerShell):
```powershell
Get-FileHash -Algorithm SHA256 .\Priso-v3.5.47.apk
# Must output: A2E71EB78971DE47647D204E76F8FDBD903EE40D31D6D76ED55506EDBBD11DFC
```

### Verify on Linux / macOS Terminal:
```bash
sha256sum Priso-v3.5.47.apk
# Must output: a2e71eb78971de47647d204e76f8fdbd903ee40d31d6d76ed55506edbbd11dfc
```

You can also drag-and-drop the file directly onto [VirusTotal.com](https://www.virustotal.com) to view the clean 0/70 detection report.

---

## ✨ Core Features

### 🚫 100% Ad-Free Experience
- **Zero Commercials**: No audio ads, no video popups, and no mid-song interruptions.
- **Instant Search**: Search through millions of songs, trending hits, and timeless classics in milliseconds.
- **Unlimited Skips**: Jump forward, rewind, and shuffle your queue freely with zero limits or restrictions.

### 🎧 Background Playback & Lock Screen Controls
- Keep listening to your favorite tracks while texting, gaming, navigating, or when your screen is locked.
- Fully integrated with Android system media notifications for quick play, pause, and track skip controls.

### 🔒 Privacy-First & End-to-End Encrypted
- **No Data Harvesting**: We do not collect, sell, or monetize your personal data or listening habits.
- **Zero Third-Party Trackers**: No intrusive advertising SDKs, spyware, or telemetry trackers.
- **End-to-End Encryption**: Personal chats, shared memories, and couple moments are fully encrypted end-to-end.

### 💑 Private Connection Space
- A dedicated, intimate sanctuary for couples and close companions.
- Listen together, share vibes, and preserve cherished memories in a distraction-free environment.

### ⚡ Ultra-Lightweight & Battery Efficient
- Minimal device storage footprint (~6.30 MB download size).
- Optimized audio stream decoding engineered to maximize battery life during extended listening sessions.

---

## 📲 How to Install on Android

Follow these simple steps to install Priso on your Android device:

1. **Download the APK**:
   Tap the [**Direct Download Link**](https://github.com/sonu-dops/PRISO-ad_free-music/raw/main/Priso-v3.5.47.apk) to save `Priso-v3.5.47.apk` to your phone.

2. **Open the File**:
   Once downloaded, pull down your notification tray and tap on `Priso-v3.5.47.apk` (or open it from your phone's **Downloads** folder in the Files app).

3. **Allow Installation**:
   - If Android prompts with *"For your security, your phone is not allowed to install unknown apps from this source"*:
     - Tap **Settings**.
     - Toggle on **Allow from this source**.
     - Press back and tap **Install**.
   - If Google Play Protect shows a prompt, tap **More details** → **Install anyway** (standard for open releases outside Google Play).

4. **Launch & Enjoy**:
   Open Priso from your home screen or app drawer and start listening!

---

## 🛡️ Security & Privacy Commitment

| Guarantee | Details |
|---|---|
| **No Intrusive Permissions** | Priso does not request access to your contacts, SMS, call logs, camera, or personal device files. |
| **No Account Lock-in** | Stream music instantly without mandatory subscription fees or credit cards. |
| **Safe & Clean** | Built cleanly from verified sources. No malware, no adware, no background miners. |
| **Zero Breaches** | Sensitive telemetry and private user data are never exposed or stored in unprotected public databases. |

---

## 💬 Feedback & Support

If you have questions, encounter an issue, or want to suggest new songs and features, feel free to open an **Issue** on this repository.

Enjoy the music! 🎶
