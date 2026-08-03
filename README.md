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
| **Formats**       | MP4, WebM, MP3, M4A, video-only, best quality, subtitles                      |
| **Quality**       | 144p to 2160p (4K)                                                            |
| **Playlists**     | Full download or specific item ranges                                         |
| **Cookies**       | Reuse a logged-in browser session                                             |
| **Options**       | Embedded subtitles/thumbnail/metadata, section download, speed limit, custom output folder |
| **Download Log**  | Download history is tracked automatically and stored locally                  |
| **Compatibility** | Windows 10 / 11, 64-bit                                                       |

---

## Installation

### Prerequisites

- Windows 10 or 11 (64-bit)

### Steps

1. **Download** `Lunox.exe` and place it in a folder of your choice.
2. **Run** the application:

   ```powershell
   .\Lunox.exe
   ```

That's it. On first launch, Lunox automatically downloads everything it needs
(`yt-dlp.exe`, `ffmpeg.exe`, `ffplay.exe`, `ffprobe.exe`) into the same folder.
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
