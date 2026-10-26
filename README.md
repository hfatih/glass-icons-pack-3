<div align="center">
  <img src="assets/cover.png" alt="Glass Icons Pack 3 (Fresh & Mint Glass) Logo" width="104" height="104">
  <h1>Glass Icons Pack 3 (Fresh & Mint Glass)</h1>
  <p><strong>1,000 fresh frosted glass squircle icons in Teal & Vibrant Green palettes for Stream Deck & Evoxdeck.</strong></p>

  <p>
    <strong>Language:</strong> <a href="README.md"><strong>EN</strong></a> | <a href="README.tr.md"><strong>TR</strong></a>
    &nbsp;•&nbsp;
    <a href="https://github.com/Hfatih/glass-icons-pack-3/releases/latest">Download .evoxpack</a> ·
    <a href="https://hfatih.github.io/glass-icons-pack-3/">Live Interactive Gallery</a> ·
    <a href="#quick-installation">Installation Guide</a>
  </p>

  <p>
    <img src="https://img.shields.io/badge/Language-EN%20%7C%20TR-blue?style=flat-square" alt="EN | TR">
    <img src="https://img.shields.io/badge/Total%20Icons-1,000-26b2aa?style=flat-square" alt="1,000 Icons">
    <img src="https://img.shields.io/badge/Platforms-Stream%20Deck%20%7C%20Evoxdeck-0078D6?style=flat-square" alt="Platforms">
    <img src="https://img.shields.io/badge/Format-Retina%20128x128%20PNG-10B981?style=flat-square" alt="Format">
    <img src="https://img.shields.io/badge/Package-.evoxpack%20v1.0.0-a855f7?style=flat-square" alt="Package">
    <img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square" alt="License MIT">
  </p>
  <p align="center">
    <img src="https://hits.sh/github.com/hfatih/glass-icons-pack-3.svg?style=flat-square&label=views&color=26b2aa" alt="Views">
    <a href="https://github.com/hfatih/glass-icons-pack-3/releases"><img src="https://img.shields.io/github/downloads/hfatih/glass-icons-pack-3/total?style=flat-square&label=downloads&color=26b2aa" alt="Downloads"></a>
    <a href="https://github.com/hfatih/glass-icons-pack-3/releases/latest"><img src="https://img.shields.io/github/v/release/hfatih/glass-icons-pack-3?style=flat-square&label=version&color=dba8c2" alt="Version"></a>
    <a href="https://github.com/hfatih/glass-icons-pack-3/stargazers"><img src="https://img.shields.io/github/stars/hfatih/glass-icons-pack-3?style=flat-square&label=stars&color=26b2aa" alt="Stars"></a>
    <a href="https://github.com/hfatih/glass-icons-pack-3/commits"><img src="https://img.shields.io/github/last-commit/hfatih/glass-icons-pack-3?style=flat-square&label=last%20commit&color=bca4dd" alt="Last Commit"></a>
  </p>
</div>

---

## Overview

**Glass Icons Pack 3 (Fresh & Mint Glass)** is a premium physical frosted glass icon collection handcrafted for **Stream & Macro Decks**, **Evoxdeck**, **Loupedeck**, and **Touch Portal** controllers.

Every icon is precision-rendered at Retina $128\times 128$ resolution using an advanced superellipse squircle formula ($p=3.65, r=53$), top-left diffuse light refraction (*specular bloom*), internal bottom rim lighting, and tactile 3D embossed glyphs.

### 🌐 Live Interactive Gallery & Deck Simulator
Browse all 1,000 icons, search keywords, switch colors, and test keys live in your browser:
👉 **[Open Live Gallery on GitHub Pages](https://hfatih.github.io/glass-icons-pack-3/)**

---

## Showcase Preview

| Stream Deck Hardware Showcase |
| :---: |
| ![Showcase](assets/showcase.png) |
| *Frosted glass tiles with pure white embossed vectors and 3D depth shadows.* |

---

## Color Palettes Included

| Palette Name | Slug | Top-Left RGB | Bottom-Right RGB | Hex Gradient |
| :--- | :--- | :--- | :--- | :--- |
| **Deniz Mavisi (Teal)** | `teal` | `rgb(158, 240, 209)` | `rgb(58, 208, 198)` | `#9ef0d1` ➔ `#3ad0c6` |
| **Canlı Yeşil (Green)** | `green` | `rgb(206, 255, 206)` | `rgb(176, 222, 52)` | `#ceffce` ➔ `#b0de34` |

---

## Icon Categories (500 Symbols × 2 Themes)

1. **🎙️ Audio & Voice:** Mic, Headphones, Volume Levels (0-1-2-Mute), Sound Waves, Mixer, Radio.
2. **🎵 Media & Playback:** Play, Pause, Record, Fast-Forward, Rewind, Shuffle, Repeat, Camera, Video, 4K, HD.
3. **⭐ Streamer Badges:** REC, LIVE, Game Audio, Mic On, Mute, AFK, GG, VIP, MOD, Clutch, Sub, Chat.
4. **🎮 Gaming & Esports:** Minecraft, Valorant, League of Legends, Steam, OBS, Discord, Twitch, Gamepad, Joystick.
5. **📱 Apps & Socials:** YouTube, Twitch, Spotify, TikTok, Twitter/X, Instagram, Kick, Reddit, Telegram, WhatsApp.
6. **⚙️ Hardware & System:** CPU, GPU, RAM, Monitor, Laptop, Keyboard, Mouse, Bluetooth, WiFi, Power, Settings.

---

## Quick Installation

```mermaid
flowchart TD
    A["Download .evoxpack from Releases"] --> B{"Your Hardware / Software"}
    B -->|"Evoxdeck"| C["One-Click Import<br/>Double-click file or drag into Evoxdeck"]
    B -->|"Stream & Macro Decks"| D["Extract icons/ folder<br/>Drag PNG directly to key slot"]
    C --> E["1,000 Icons Ready Instantly"]
    D --> E
```

### 1. Evoxdeck (Recommended)
1. Download `Glass Icons Pack 3.evoxpack` from [Latest Releases](https://github.com/Hfatih/glass-icons-pack-3/releases/latest).
2. Double-click the file or navigate to **Evoxdeck** ➔ **Settings** ➔ **Icon Packs** ➔ **Import Pack**.
3. All 1,000 icons appear instantly with full search and tags.

### 2. Stream & Macro Decks
1. Extract the `icons/` folder from the repository or `.evoxpack` container.
2. Drag and drop any PNG onto your Stream Deck key slot.

---

## Package Specification (`manifest.json`)

The `.evoxpack` conforms strictly to the **Evoxdeck Package Specification v1**:
- `schemaVersion`: `1`
- `packageType`: `icon_pack`
- `coverImage`: `cover.png` (512×512 Retina squircle)
- `assets/icons/`: 1,000 individual PNG icons ($128\times 128$ px, 32-bit RGBA)

---

## License

Distributed under the **MIT License**. Free for personal and commercial stream setups.
Authored with 💖 by **[Fatih Han](https://github.com/Hfatih)**.
