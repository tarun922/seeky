<div align="center">

<img src="assets/icon.png" alt="Seeky" width="120"/>

# Seeky

**One free desktop player for your local files, YouTube playlists, and Spotify imports.**

[![Latest Release](https://img.shields.io/github/v/release/tarun922/seeky?style=for-the-badge&color=8B5CF6&label=Download)](https://github.com/tarun922/seeky/releases/latest)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-blue?style=for-the-badge)](#-installation)
[![Discord](https://img.shields.io/badge/Discord-Join%20us-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/Tjv3pa3PU9)
[![GitHub Stars](https://img.shields.io/github/stars/tarun922/seeky?style=for-the-badge&color=yellow)](https://github.com/tarun922/seeky/stargazers)

<br/>

> Spotify imports. YouTube playlists. Local files. Live lyrics. Song ID. Discord RPC.
> All in one gorgeous desktop app. **Free, no ads, no account.**

<br/>

[**⬇️ Download**](https://github.com/tarun922/seeky/releases/latest) &nbsp;·&nbsp;
[Installation](#-installation) &nbsp;·&nbsp;
[Features](#-features) &nbsp;·&nbsp;
[Roadmap](#%EF%B8%8F-roadmap) &nbsp;·&nbsp;
[Discord](https://discord.gg/Tjv3pa3PU9)

<br/>

<!-- Replace with a short GIF of theme switching + Now Playing (ScreenToGif / Peek / Kap) -->
<!-- ![Seeky demo](assets/screenshots/demo.gif) -->

| Home | Now Playing |
|:----:|:-----------:|
| ![Home](assets/screenshots/home.png) | ![Now Playing](assets/screenshots/nowplaying.png) |

</div>

---

## ✨ Why Seeky?

Most music apps make you pick a lane: *local only* or *streaming only*. Seeky does both. It's a free, offline-first desktop music hub that pulls everything into one library without the monthly bill.

- **Zero effort listening**: play one song and the Smart Feed keeps the music going
- **No account required**
- **No ads, no upsells**
- **Private by default**: your library and listening data stay on your machine

---

## 🎯 Features

| | |
|---|---|
| 🌊 **Smart Feed** | Play one song and let Seeky do the rest. The feed generator builds an endless queue from your first pick, so you never have to curate a playlist. |
| 🎵 **Play everything** | Local files, YouTube streams, and Spotify-imported playlists in one library. Supports `mp3`, `flac`, `opus`, `ogg`, `wav` and more. |
| 📥 **Spotify import** | Bring your playlists over, subscription or not. |
| 📺 **YouTube playlists** | Paste a playlist URL and play it like a local playlist, with caching for skip-free listening. |
| 🎤 **Live synced lyrics** | Scrolling lyrics on the Now Playing screen. |
| 🕵️ **Song ID** | Press `R` anywhere in the player. Seeky records 8 seconds from your mic and identifies the track via ACRCloud. |
| 📊 **Wrapped, all year** | Top artists, top tracks, listening streaks, total hours. Any time, not just December. |
| 🎮 **Gamer Mode** | Auto-ducks music volume when game audio kicks in. |
| 💬 **Discord Rich Presence** | Shows song, artist, album art, and play state on your profile. |
| 📱 **Mobile remote** | Open Seeky's remote URL on your phone (same Wi-Fi) to control playback. |
| 🪟 **Mini player** | Always-on-top compact controls. |
| ↔️ **Crossfade & visualizer** | Smooth transitions and a real-time visualizer. |
| 🔌 **Plugin system** | Gamer Mode ships built in, with community plugins planned. |

### 🎨 11 Hand-Crafted Themes

Every theme is hand-crafted, not just a color swap.

<div align="center">

| 🌌 Midnight Aurora | 🕳️ Cosmic Void | 🔴 Molten Obsidian |
|:------------------:|:--------------:|:------------------:|
| ![Midnight Aurora](assets/screenshots/themes/1.png) | ![Cosmic Void](assets/screenshots/themes/2.png) | ![Molten Obsidian](assets/screenshots/themes/3.png) |

| 🔵 Powder Blue | 🌅 Golden Hour | ⬜ Arctic Pearl |
|:--------------:|:--------------:|:---------------:|
| ![Powder Blue](assets/screenshots/themes/4.png) | ![Golden Hour](assets/screenshots/themes/5.png) | ![Arctic Pearl](assets/screenshots/themes/6.png) |

| 🖼️ Toon Dark | 🎉 Toob Pop | 🌸 Cute Dark |
|:------------:|:-----------:|:------------:|
| ![Toon Dark](assets/screenshots/themes/7.png) | ![Toob Pop](assets/screenshots/themes/8.png) | ![Cute Dark](assets/screenshots/themes/9.png) |

| 🍬 Cute Light | 💎 Crystal ✨ |
|:-------------:|:-------------:|
| ![Cute Light](assets/screenshots/themes/10.png) | ![Crystal](assets/screenshots/themes/11.png) |

> 💎 **Crystal** is Seeky's signature theme, with a custom **live animated background** that reacts to your music in real time.

</div>

---

## 📦 Installation

Grab the latest build from the [Releases page](https://github.com/tarun922/seeky/releases/latest).

### Windows
1. Download the `.exe` installer
2. Run it. Done.

### macOS
1. Download the `.dmg`
2. Drag Seeky to Applications
3. First launch: right-click → **Open** to get past Gatekeeper

### Linux

**AppImage**
```bash
chmod +x Seeky-x.x.x.AppImage
./Seeky-x.x.x.AppImage
```

**deb**
```bash
sudo dpkg -i seeky_x.x.x_amd64.deb
```

> Seeky checks for updates on launch and installs them silently.

---

## 🔧 Setup Guides

### Song ID
1. Create a free account at [ACRCloud](https://www.acrcloud.com/)
2. Create a project and copy the **Host**, **Key**, and **Secret**
3. In Seeky: **Settings → Integrations → ACRCloud**

Free tier: 1,000 identifications per day.

### Discord Rich Presence
1. Open the [Discord Developer Portal](https://discord.com/developers/applications) and create a **New Application**
2. Copy the **Application ID**
3. In Seeky: **Settings → Discord** and paste it as the Client ID

---

## 🗺️ Roadmap

- [ ] Last.fm scrobbling
- [ ] Equalizer
- [ ] Sleep timer
- [ ] Plugin marketplace
- [ ] Collaborative playlists
- [ ] Tidal / Apple Music import

Have an idea? [Open an issue](https://github.com/tarun922/seeky/issues) or suggest it on [Discord](https://discord.gg/Tjv3pa3PU9).

---

## 🐛 Found a bug?

[Open an issue](https://github.com/tarun922/seeky/issues/new) and include your OS, Seeky version, and what you were doing when it happened. Screenshots help.

---

## ❓ FAQ

**Is it really free?**
Yes. No ads, no subscription, no account needed for core features.

**Does it work offline?**
Fully, for local files. YouTube playback and Spotify import need internet.

**Is my data private?**
Seeky doesn't send your library or listening data anywhere. Song ID and Discord RPC only activate when you enable them.

**Where's the source code?**
Seeky is currently closed-source. A plugin API and community extensions are planned.

---

<div align="center">

Made with ❤️ and way too many late nights.

**[⭐ Star this repo if Seeky made your day better](https://github.com/tarun922/seeky)**

*Seeky is not affiliated with Spotify, YouTube, Discord, or ACRCloud.*

</div>
