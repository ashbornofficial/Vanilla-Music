<div align="center">

<img src="docs/assets/banner.svg" alt="Vanilla Music - Music that moves with you" width="100%">

<br>

<img src="docs/assets/typing.svg" alt="Full-screen synced lyrics · mini player · library + YouTube" width="720">

<br><br>

[![Download](https://img.shields.io/badge/⬇_Download-latest_release-ff8a2b?style=for-the-badge&labelColor=1a1a1f)](../../releases/latest)
[![Discord](https://img.shields.io/badge/Discord-join_the_server-5865F2?style=for-the-badge&logo=discord&logoColor=white&labelColor=1a1a1f)](https://discord.gg/weRFDT6Ppf)
[![Website](https://img.shields.io/badge/Website-visit-8b5cff?style=for-the-badge&labelColor=1a1a1f)](https://vanilla-music.netlify.app)

![Windows](https://img.shields.io/badge/Windows-0078D4?style=flat-square&logo=windows11&logoColor=white)
![macOS](https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![React](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Capacitor](https://img.shields.io/badge/Capacitor_8-119EFF?style=flat-square&logo=capacitor&logoColor=white)
![Version](https://img.shields.io/badge/version-1.6-ff8a2b?style=flat-square)
![Free](https://img.shields.io/badge/price-free-34d399?style=flat-square)

<img src="docs/assets/stats.svg" alt="3 platforms, 17 looks, 0 ads, 100% free" width="760">

</div>

<img src="docs/assets/divider.svg" alt="" width="100%">

## ✨ See it in action

<div align="center">
  <img src="docs/assets/demo.gif" alt="Vanilla Music demo: desktop app, full-screen lyrics and mini player" width="640">
  <br>
  <sub>Desktop app → full-screen lyrics → mini player (cut from the 44-second promo video)</sub>
</div>

<br>

<div align="center">
  <img src="docs/screenshots/d-home.png" width="88%" alt="Home screen">
</div>

<table>
  <tr>
    <td width="50%"><img src="docs/screenshots/d-library.png" alt="Library"><br><sub><b>Library</b> - your files and every download, with a Now Playing card</sub></td>
    <td width="50%" align="center"><img src="docs/screenshots/mini.png" alt="Mini player" width="92%"><br><sub><b>Mini player</b> - tiny, always on top (Windows &amp; Mac)</sub></td>
  </tr>
</table>

<div align="center">
  <img src="docs/screenshots/m-home.png" width="22%" alt="Android home">
  <img src="docs/screenshots/m-player.png" width="22%" alt="Android library">
  <img src="docs/screenshots/m-playing.png" width="22%" alt="Android now playing">
  <br><sub><b>Android</b> - white &amp; orange by default, background play with lock-screen controls</sub>
</div>

<img src="docs/assets/divider.svg" alt="" width="100%">

## 🚀 Features

| | Feature | What you get |
|:-:|---|---|
| 🎵 | **Library + YouTube** | Add songs or folders (drag & drop works) or search any song on YouTube and play it instantly. |
| 🎤 | **Full-screen lyrics** | Big synced lines that glow with the song, cover-colour backdrop, tap a line to seek. Press <kbd>L</kbd>. |
| 🔎 | **Lyrics almost everywhere** | Smart title cleaning, then LRCLIB → NetEase → lyrics.ovh, so far fewer "not found". |
| 🪟 | **Mini player** | The whole app shrinks into a small always-on-top player with seek, volume and controls. |
| ⬇️ | **Downloads → library** | Save a YouTube song and it lands in **Library → Local files** automatically, ready offline. |
| 🔥 | **A busy Home** | *Because you listened*, *Trending now*, *Hot in India*, mood mixes, radio. |
| ✨ | **AI DJ & mixes** | Local smart shuffle and mood mixes - nothing is sent to an AI service. |
| 🎨 | **17 looks** | AMOLED, Midnight, Ocean, Forest, Rose, Sunset, Mocha, Nord, Dracula, Neon, Paper, Cream, Mint, Sky, Lavender, Peach + 17 accent colours. |
| 🔋 | **Android background play** | Foreground service, wake & Wi-Fi locks, lock-screen controls, battery-optimisation helper. |
| 🔒 | **Private by design** | No account, no ads, no analytics. Your library stays on your device. |

<details>
<summary><b>🎹 Keyboard shortcuts</b></summary>
<br>

| Key | Action | Key | Action |
|---|---|---|---|
| <kbd>Space</kbd> | Play / pause | <kbd>L</kbd> | Full-screen lyrics |
| <kbd>←</kbd> <kbd>→</kbd> | Seek 5 s | <kbd>Shift</kbd>+<kbd>←</kbd>/<kbd>→</kbd> | Previous / next |
| <kbd>↑</kbd> <kbd>↓</kbd> | Volume | <kbd>M</kbd> | Mute |
| <kbd>S</kbd> | Shuffle | <kbd>Ctrl</kbd>+<kbd>K</kbd> | Search |

</details>

<img src="docs/assets/divider.svg" alt="" width="100%">

## ⬇️ Download

| Platform | File | Notes |
|:-:|---|---|
| 🪟 **Windows** | `Vanilla-Music-<version>-Windows-x64.exe` · `...-Windows-Portable.exe` | Windows 10/11, 64-bit. Custom setup wizard. |
| 🤖 **Android** | `Vanilla-Music-<version>-Android.apk` | Android 8+. Allow *Install unknown apps* when asked. |
| 🍎 **macOS** | `...-macOS-arm64.dmg` · `...-macOS-x64.dmg` | Coming soon - or build it yourself, see below. |

👉 **Get them from the [Releases page](../../releases/latest).**

👉 **Get them from the [Website](https://vanilla-music.netlify.app/).**

> [!NOTE]
> The apps are not code-signed yet. Windows shows a SmartScreen notice once - click **More info → Run anyway**. On a Mac, right-click the app → **Open** (or run `xattr -cr "/Applications/Vanilla Music.app"`).

<img src="docs/assets/divider.svg" alt="" width="100%">


## 🗺️ Roadmap

- [x] Full-screen synced lyrics
- [x] Mini player (Windows & Mac)
- [x] Downloads added to the library automatically
- [x] Multi-source lyrics + smart title cleaning
- [x] 17 looks, Trending & "Because you listened"
- [x] Rebuilt Android background play
- [ ] Ready-made macOS `.dmg` on the Releases page
- [ ] Code-signed Windows installer
- [ ] iOS
- [ ] Manual lyrics (paste / `.lrc` file)
- [ ] Sleep timer & equalizer

Have an idea? Tell us on **[Discord](https://discord.gg/weRFDT6Ppf)** or open an issue.

## ❓ FAQ

<details><summary><b>Where do my downloads go?</b></summary>
<br>Windows/Mac: <code>Music\Vanilla Music</code>. Android: <code>Music/Vanilla Music</code>. They are also added to <b>Library → Local files</b> automatically.
</details>

<details><summary><b>Music stops with the screen off on Android</b></summary>
<br>Open <b>Settings → Background play → Allow</b> and, on phones with strict battery savers (Xiaomi, Oppo, Vivo, Samsung), set the app's battery to "No restrictions".
</details>

<details><summary><b>Lyrics are missing for a song</b></summary>
<br>The app searches LRCLIB, NetEase and lyrics.ovh. If none has it you will see "No lyrics found".
</details>

<details><summary><b>Is it really free? Where does the music come from?</b></summary>
<br>Yes - free, no ads. Vanilla Music plays files you own and public YouTube content you choose. It does not host any music.
</details>

## 🔐 Privacy

No accounts, no ads, no analytics. The library, playlists and settings stay on your device. The app goes online only for YouTube and lyrics. Full details: [Privacy Policy](https://vanilla-music.netlify.app/privacy.html).

## 📜 Licence & credits

Proprietary - free for personal, non-commercial use (see [`LICENSE`](LICENSE)). Built with Electron, React, Vite, Capacitor, [NewPipe Extractor](https://github.com/TeamNewPipe/NewPipeExtractor), [yt-dlp](https://github.com/yt-dlp/yt-dlp), Lucide icons and music-metadata. Lyrics from [LRCLIB](https://lrclib.net). YouTube is a trademark of Google LLC; this project is not affiliated with YouTube or Google.

<div align="center">

<img src="docs/assets/divider.svg" alt="" width="60%">

**Made with ♥ by [Ashborn](https://github.com/ashbornofficial)** · [Discord](https://discord.gg/weRFDT6Ppf)

<sub>If you like it, drop a ⭐ on the repo - it really helps.</sub>

</div>
