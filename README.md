# Lunox — Video & Audio Downloader

A portable Windows GUI downloader for YouTube and hundreds of other sites, powered by
[yt-dlp](https://github.com/yt-dlp/yt-dlp) and [FFmpeg](https://ffmpeg.org/). No installation
required — just run `Lunox.exe`.

## Features

- **Multiple formats**
  - Video (with audio) — merged to MP4 via FFmpeg
  - Video (best quality)
  - Video only (no sound)
  - Audio only (MP3)
  - Audio only (M4A)
  - Audio only (best quality)
  - Subtitles only
- **Quality selection** — Best, 2160p (4K), 1440p (2K), 1080p, 720p, 480p, 360p, 240p, 144p
- **Playlist support** — full download or specific item ranges
- **Cookie support** — select a browser to reuse its logged-in session
- **Options** — embed subtitles/thumbnail/metadata, download a section of a video (start/end
  time), speed limit, custom output folder and file-name template
- **1000+ sites** supported through yt-dlp (YouTube, Vimeo, Twitch, TikTok, and more)
- Portable: ships with its own `yt-dlp.exe`, `ffmpeg.exe`, `ffprobe.exe`, and `ffplay.exe`

## Requirements

- Windows 10 / 11 (64-bit)
- Internet connection

No Python or other runtime is required. All binaries are bundled inside the app folder.

## Installation

1. Download and extract the release archive.
2. Make sure `Lunox.exe`, `yt-dlp.exe`, and `ffmpeg.exe` are all in the **same folder**.
3. Run `Lunox.exe`.

That's it.

## Usage

1. Paste a video/playlist URL into the box.
2. Pick a **format**, **quality**, and any extra options.
3. Click download. Progress is shown in the log panel.
4. Finished files are saved into the `downloads` subfolder next to the app
   (changeable in the UI).

### File naming

The default output template is `%(title)s.%(ext)s`. You can supply your own yt-dlp output
template (for example `%(channel)s/%(title)s.%(ext)s`) in the UI.

## Tech notes

- Built with PyInstaller (Python 3.13), single `--onefile` executable.
- Downloads are handled by `yt-dlp.exe`; video/audio muxing uses the bundled `ffmpeg.exe`.
- The app stores no history files and writes no logs to the app folder.

## Changelog

**v2.1.0.0** (this build)
- Fixed: crash on download start (a `NameError` in the download thread).
- Fixed: files were saved to the wrong location because the output folder was misused as the
  file-name template.
- Fixed: the download now writes its output into the selected folder correctly.

## License

Copyright (c) 2026 Lunox. All rights reserved.
