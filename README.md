<p align="center">
  <img src="https://img.shields.io/badge/platform-Windows%2010%2F11%20(64--bit)-0078D6?style=flat-square" alt="Platform" />
  <img src="https://img.shields.io/badge/type-Portable-4caf50?style=flat-square" alt="Portable" />
  <img src="https://img.shields.io/badge/runtime-None%20required-607d8b?style=flat-square" alt="Runtime" />
  <img src="https://img.shields.io/badge/sites-1000%2B-9c27b0?style=flat-square" alt="Supported sites" />
</p>

<h1 align="center">Lunox</h1>
<p align="center">
  <strong>A portable video &amp; audio downloader for Windows</strong><br />
  Powered by <a href="https://github.com/yt-dlp/yt-dlp">yt-dlp</a> and <a href="https://ffmpeg.org/">FFmpeg</a>.
</p>

---

## Overview

Lunox is a no-install Windows desktop application for downloading video and audio from
YouTube and 1000+ other sites. It bundles its own `yt-dlp.exe` and `ffmpeg.exe`, so no
Python, Node.js, or any other runtime is required.

---

## Features

| Category          | Details                                                                       |
| ----------------- | ----------------------------------------------------------------------------- |
| **Formats**       | MP4, MP3, M4A, video-only, best quality, subtitles                            |
| **Quality**       | 144p to 2160p (4K)                                                            |
| **Playlists**     | Full download or specific item ranges                                         |
| **Cookies**       | Reuse a logged-in browser session                                             |
| **Options**       | Embedded subtitles/thumbnail/metadata, section download, speed limit, custom output folder |
| **Compatibility** | Windows 10 / 11, 64-bit                                                       |

---

## Installation

### Prerequisites

- Windows 10 or 11 (64-bit)
- An internet connection

### Steps

1. **Download** the release archive and extract it to a folder of your choice.
2. **Verify** that the following files are in the same folder:

   ```
   Lunox.exe
   yt-dlp.exe
   ffmpeg.exe
   ffplay.exe
   ffprobe.exe
   ```

3. **Run** the application:

   ```powershell
   .\Lunox.exe
   ```

No further setup is required.

---

## Usage

1. Paste a video or playlist URL into the input box.
2. Select a **format**, **quality**, and any additional options.
3. Click **Download**.
4. Finished files are saved to the `downloads` folder next to the application.

---

## License

Copyright © 2026 Lunox. All rights reserved.
