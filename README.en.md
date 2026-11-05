# Dingding Radio · TingTing Radio

**Internet Radio / Online Radio Player for Android** · Minimalist e-ink style · MP3 / M3U8 streams

[简体中文](README.md) · [繁體中文](README.zh-Hant.md) · [English](README.en.md)

Dingding Radio (TingTing Radio) is a minimalist, e-ink-style internet radio player for Android. MP3 and M3U8 (HLS) live streams play out of the box, playback continues with the screen off, and there is no account and no ads.

> This repository is for the app introduction, user guide and official APK releases only. **Source code is not included.**

<p align="center">
  <img src="screenshots/home.png" width="230" alt="My stations">
  <img src="screenshots/player.png" width="230" alt="Now playing">
  <img src="screenshots/favorites.png" width="230" alt="Favorites">
</p>

## Download

| Item | Details |
|---|---|
| Latest version | [v2026.11.3](https://github.com/haijiang2023/tingting-radio/releases/latest) |
| Package | `dingding-radio-2026.11.3.apk` (~21 MB) |
| Requirements | Android 5.0 (API 21)+, **arm64-v8a** |
| Languages | Simplified Chinese / Traditional Chinese / English |
| Price | Free, no ads, no sign-in required |

**[⬇ Download the latest APK](https://github.com/haijiang2023/tingting-radio/releases/latest)**

SHA-256 (v2026.11.3):

```
2A789F628A766CF767158677FADEE621D7EEBE839019123CBC62AF21D3368FF8
```

Verify the checksum after downloading, then install.

## Features

- **MP3 & M3U8 support** — the stream format is detected from the URL automatically.
- **Keeps playing with the screen off** — foreground media service + wake lock; playback continues when locked or backgrounded.
- **Notification and lock-screen controls** — play, pause, previous, next, stop.
- **Your own station library** — add, edit, move, delete and group stations; bulk import from the clipboard or search an online radio directory.
- **Favorites and resume** — star the stations you use and return to the last one on cold start.
- **Sleep timer** — stop automatically after 15 / 30 / 60 minutes.
- **Auto skip on failure** — when a stream fails, the app offers a clear message and tries the next station.
- **System volume sync** — the volume bar reads and writes Android media volume directly.
- **Paper-and-ink UI** — paper `#F2F2EC` + ink `#16160F`, inverted selection, no colors, gradients or shadows.

## Quick start

1. Download the APK from [Releases](https://github.com/haijiang2023/tingting-radio/releases/latest).
2. Allow “Install unknown apps” on your phone, then install it.
3. Open the app and tap `+` at the top right: add a station manually, import from the clipboard, or search the online radio directory.
4. Tap a station to play. Playback continues after you press the power button, and controls stay available in the notification shade.

Detailed guide (Simplified Chinese): [使用教程](docs/使用教程.md) · FAQ: [常见问题](docs/常见问题.md)

## Three ways to add stations

| Method | Best for |
|---|---|
| Add manually | You already know an MP3 direct link or M3U8 URL |
| Import from clipboard | You have copied several stream URLs and want to parse them in bulk |
| Import from online library | Search a public radio directory and add with one tap |

You can create a group while adding a station. Groups are optional; the home screen shows a mixed list with groups on top and ungrouped stations below.

## Screenshots

| | |
|---|---|
| <img src="screenshots/home.png" width="220"> | <img src="screenshots/add-station.png" width="220"> |
| My stations: group counts and station entries | Add: manual / clipboard / online library / new group |

## About internet radio and online radio

Dingding Radio (TingTing Radio) is a free **internet radio** and **online radio** player for Android, also known as a streaming radio app or web radio client. It supports MP3 direct links and M3U8 (HLS) live streams, which makes it suitable for music stations, city stations and kids' radio programs. No account, no ads, and all your station data stays on your device.

## Notes

- No large built-in station catalog; only 4 AsiaFM sample stations appear on first launch. Add the rest yourself.
- You provide the stream URLs; third-party streams may expire or be region-restricted.
- Stations, groups, favorites and volume are stored on your device only. Uninstalling clears them.
- Only the Android arm64 build is published; the app is not available on any app store.
- Source code is not provided. The app and this repository's content are copyrighted. The APK may be downloaded and installed for personal listening. Do not repackage, modify and redistribute it, or use it commercially.

Official website: <https://www.caicaiapp.com/radio/index.html>

## Feedback

For bugs or feature requests, please open an [Issue](https://github.com/haijiang2023/tingting-radio/issues) and include your phone model, Android version, the station URL (redacted if needed) and steps to reproduce.

**Keywords**: internet radio, online radio, radio player, streaming radio, HLS radio, M3U8 radio, MP3 radio, Android radio app, free radio app, no ads, e-ink radio player, minimalist radio app, Chinese radio app.

中文關鍵字：網路電台、網路收音機、電台 App、線上廣播。中文关键词：网络电台、网络收音机、电台 App、在线广播。
