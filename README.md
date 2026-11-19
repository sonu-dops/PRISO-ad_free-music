# 🎵 Priso — Ad-Free Music & Private Shared Space

[![Version](https://img.shields.io/badge/version-v3.5.53-blue.svg)](https://github.com/sonu-dops/PRISO-ad_free-music/raw/main/Priso-v3.5.53.apk)
[![Platform](https://img.shields.io/badge/platform-Android_8.0+-green.svg)](https://github.com/sonu-dops/PRISO-ad_free-music/raw/main/Priso-v3.5.53.apk)
[![VirusTotal](https://img.shields.io/badge/VirusTotal-0%2F70_Clean-brightgreen.svg)](#)
[![Ads](https://img.shields.io/badge/ads-100%25_Ad--Free-brightgreen.svg)](#)
[![Privacy](https://img.shields.io/badge/privacy-P2P_Encrypted_Calls-success.svg)](#)
[![Size](https://img.shields.io/badge/size-6.29_MB-orange.svg)](#)
[![Distribution](https://img.shields.io/badge/repo-Official_Binary_Release-lightgrey.svg)](#)

> **Experience music the way it was meant to be enjoyed — uninterrupted, crystal-clear, addictively personalized, and completely private.**

Priso is an ultra-lightweight, high-fidelity music streaming and private shared sanctuary app designed for uninterrupted listening and private connection. Enjoy unlimited music without ads, background trackers, or subscriptions.

---

## 📥 Download Priso for Android (Latest Official Release)

Click the link below to download the latest official release APK directly:

### 🚀 [**Download Priso v3.5.53 APK** (Direct Download)](https://github.com/sonu-dops/PRISO-ad_free-music/raw/main/Priso-v3.5.53.apk)
*(Alternative mirror: [**priso-latest.apk**](https://github.com/sonu-dops/PRISO-ad_free-music/raw/main/priso-latest.apk))*

| Detail | Specification |
|---|---|
| **App Name** | Priso |
| **Version** | `3.5.53` (Latest Stable) |
| **File Name** | `Priso-v3.5.53.apk` / `priso-latest.apk` |
| **Download Size** | ~6.29 MB (6,597,943 bytes) |
| **Minimum OS** | Android 8.0 (Oreo) or higher |
| **Target Architecture** | Universal (ARM64, ARMv7, x86_64) |
| **SHA-256 Checksum** | `71b9a7795aed4051269d0d92f6b72fc0351a131c14e5ec63f4057dd17007f88d` |

---

### 🌟 What's New in v3.5.53
- **⚡ Rock-Solid Partner Pairing & Auto-Healing**: Resilient cold-start retry and auto-recovery for partner invitation generation. Eliminates transient "Failed to fetch" errors during server spin-up with automatic fallback and transparent session healing.
- **🚀 Complete Google Drive Elimination**: 100% of relational records, user profiles, invitations, and chat message history now dual-write to Supabase PostgreSQL, while all media and audio streams live on Cloudflare R2 with cascade deletion.
- **🔄 Silent Background OTA v3.5.53**: High-speed, seamless over-the-air bundle updates without disrupting active playback or user workflows.
- **✨ Tactile Micro-Animations**: Enhanced tactile spring animations across the sanctuary dashboard, video call controls, chat reactions, and pairing flows.
- **📱 System Notification Bar Playback Controls**: Native Android foreground media service with lock screen and notification shade controls (*Play, Pause, Next, Previous, Stop*).
- **🔑 Direct Google OAuth Sign-In**: Connected native OAuth bridge via Chrome Custom Tabs for instant, seamless login.

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

You can independently verify the cryptographic integrity and safety of `Priso-v3.5.53.apk` before installing:

### Verify Checksum Locally (PowerShell):
```powershell
Get-FileHash -Algorithm SHA256 .\Priso-v3.5.53.apk
# Must output: 71B9A7795AED4051269D0D92F6B72FC0351A131C14E5EC63F4057DD17007F88D
```

### Verify on Linux / macOS Terminal:
```bash
sha256sum Priso-v3.5.53.apk
# Must output: 71b9a7795aed4051269d0d92f6b72fc0351a131c14e5ec63f4057dd17007f88d
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
   Tap the [**Direct Download Link**](https://github.com/sonu-dops/PRISO-ad_free-music/raw/main/Priso-v3.5.51.apk) to save `Priso-v3.5.51.apk` to your phone.

2. **Open the File**:
   Once downloaded, pull down your notification tray and tap on `Priso-v3.5.51.apk` (or open it from your phone's **Downloads** folder in the Files app).

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
