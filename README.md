<img src="https://github.com/pbzin/logooriginal.jpg" width="150" height="auto" alt="GooglePhotosMod logo" />

<p align="left">
  <a href="https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fpbzin%2FGooglePhotosMod">
    <img src="https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fpbzin%2FGooglePhotosMod&label=repo%20views&countColor=%230e75b6&style=flat" alt="Repo Views" />
  </a>
  &nbsp;
  <a href="https://github.com/pbzin/GooglePhotosMod/releases">
    <img src="https://img.shields.io/github/downloads/pbzin/GooglePhotosMod/total?style=flat&color=0e75b6&label=downloads" alt="Downloads" />
  </a>
  &nbsp;
  <a href="https://github.com/Xposed-Modules-Repo/io.github.pbzin.googlephotosmod">
    <img src="https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2FXposed-Modules-Repo%2Fio.github.pbzin.googlephotosmod&label=lsposed%20repo%20views&countColor=%230e75b6&style=flat" alt="LSPosed Repo Views" />
  </a>
  &nbsp;
  <a href="https://github.com/Xposed-Modules-Repo/io.github.pbzin.googlephotosmod">
    <img src="https://img.shields.io/github/downloads/Xposed-Modules-Repo/io.github.pbzin.googlephotosmod/total?style=flat&color=0e75b6&label=lsposed%20downloads" alt="LSPosed Downloads" />
  </a>
</p>

# GooglePhotosMod

Mods and enhancements for the Google Photos app via LSPosed. This module adds useful features and technical fixes to improve the media management experience.

## Features (Hooks)

### 🎥 Real Filename Display
Displays the original video filename (e.g., `video_01.mp4`, `vacation.mkv`) directly on the main Google Photos grid.
*   **How it works**: Hooks into `PhotoCellView.draw` and dynamically resolves the media object title, allowing for quick file identification without opening details.

### ⏳ Backup Optimization (Smart Hold)
Prevents the system from prematurely terminating Google Photos backup tasks while data transfer is still active.
*   **How it works**: Monitors network traffic for the app's UID and delays the `jobFinished` call in specific backup services if an upload is still in progress.

## Requirements

*   Android 8.0 (Oreo) or higher.
*   **LSPosed** environment configured and active.
*   Google Photos installed (`com.google.android.apps.photos`).

## Installation

1.  Download the latest APK from the [Releases](https://github.com/pbzin/GooglePhotosMod/releases) tab.
2.  Install the module and enable it in the LSPosed manager, selecting Google Photos as the scope.
3.  Restart Google Photos (Force Stop) for changes to take effect.
4.  Access the module settings to enable or disable the available mods.

---
*Note: This project is an Xposed module and has no official affiliation with Google.*

### 💖 Support My Work

<p align="center">
  <a href="https://buymeacoffee.com/pbzin">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" height="38" align="absmiddle">
  </a>
  <a href="https://github.com/sponsors/pbzin">
    <img src="https://img.shields.io/badge/Sponsor-%F0%9F%92%96-ea4aaa?style=for-the-badge&logo=githubsponsors&logoColor=white" alt="GitHub Sponsors" height="38" align="absmiddle">
  </a>
  <br><br>
  <img src="https://img.shields.io/badge/Pix-%E2%9A%A1-32BCAD?style=for-the-badge&logo=pix&logoColor=white" alt="Pix" height="30" align="absmiddle">
  <img src="https://raw.githubusercontent.com/pbzin/pbzin/main/assets/brasil-badge.png" alt="Brasil" height="30" align="absmiddle">
  <br>
  <code>5198a8b3-6b89-4475-aec1-5adcfcfd12cf</code>
  <br><br>
  <img src="https://img.shields.io/badge/Bitcoin-F7931A?style=for-the-badge&logo=bitcoin&logoColor=white" alt="Bitcoin" height="30" align="absmiddle">
  <br>
  <code>1GkpDZDHYov7WZLs54Nv19f2KUoZPcACs2</code>
  <br>
  <img src="https://raw.githubusercontent.com/pbzin/pbzin/main/assets/bitcoin-qr.png" width="150" alt="Bitcoin donation QR code">
  <br><br>
  <img src="https://img.shields.io/badge/Monero-FF6600?style=for-the-badge&logo=monero&logoColor=white" alt="Monero" height="30" align="absmiddle">
  <br>
  <code>45YtYmxUeXeFdokKPG1KWtMFLByS8nwmtiJjEiZ9LfbkNaSUCvyWWAx3VmtDKKkxPJFdQLSXxodRWMt7EBu5TmA3Qi9dgwT</code>
  <br>
  <img src="https://raw.githubusercontent.com/pbzin/pbzin/main/assets/monero-qr.png" width="150" alt="Monero donation QR code">
</p>
