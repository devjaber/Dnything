<div align="center">

<img src="./dnything.png" alt="Dnything — Data Stream logo and wordmark" width="520">

### Download anything. Fast.

**One powerful downloader for files, videos, and audio on Windows.**  
Fast transfers. Smart media detection. Flexible controls. One clean app.

<p>
  <a href="https://github.com/devjaber/Dnything/releases/latest"><img src="https://img.shields.io/github/v/release/devjaber/Dnything?style=for-the-badge&label=Latest%20Release&color=181818" alt="Latest GitHub release"></a>
  <img src="https://img.shields.io/badge/Windows-10%20%2F%2011-181818?style=for-the-badge&logo=windows11&logoColor=white" alt="Windows 10 and 11">
  <img src="https://img.shields.io/badge/Architecture-x64-181818?style=for-the-badge" alt="Windows x64">
  <img src="https://img.shields.io/badge/Build-Standalone-181818?style=for-the-badge" alt="Standalone build">
</p>

**[⬇ Download Dnything for Windows](https://github.com/devjaber/Dnything/releases/latest)** &nbsp;·&nbsp; [Screenshots](#screenshots) &nbsp;·&nbsp; [Features](#features) &nbsp;·&nbsp; [Supported Platforms](#supported-platforms) &nbsp;·&nbsp; [Quick Start](#quick-start)

</div>

---

<div align="center">
  <a href="./DataStream.png"><img src="./DataStream.png" alt="Dnything download manager showing completed media transfer" width="960"></a>
  <p><sub>Simple, focused, and designed to keep your downloads under control.</sub></p>
</div>

## Why Dnything?

**Dnything** brings direct file downloads and online media downloads together in a single, self-contained **Windows 10/11 x64** application. Paste a link, choose the download type and available quality, and let Dnything handle the rest.

| ⚡ Fast transfers | 🎬 Video & audio | 🗂️ Full control |
|:---|:---|:---|
| Segmented HTTP/HTTPS downloads with adjustable connections when supported by the server. | Media downloads powered by bundled `yt-dlp` and `FFmpeg` tools. | Pause, resume, retry, cancel, manage the queue, and track local history. |

No separate .NET Runtime, `yt-dlp`, or `FFmpeg` installation is required for the published self-contained build.

## Screenshots

### Quality selection & direct downloads

See the two main download experiences **side by side**. Click either image to view it at full size.

<table>
  <tr>
    <th align="center" width="50%">🎞️ Video & Audio Quality</th>
    <th align="center" width="50%">📁 Direct File Downloads</th>
  </tr>
  <tr>
    <td align="center" valign="top" width="50%">
      <a href="./Qualityoptions.png"><img src="./Qualityoptions.png" alt="Dnything video and audio quality options" width="100%"></a>
    </td>
    <td align="center" valign="top" width="50%">
      <a href="./Directfiles.png"><img src="./Directfiles.png" alt="Dnything HTTP and HTTPS direct file downloading" width="100%"></a>
    </td>
  </tr>
  <tr>
    <td align="center">Choose an available format and resolution.</td>
    <td align="center">Download files with transfer progress and controls.</td>
  </tr>
</table>

## Features

| Downloading | Media & detection | Productivity & control |
|:---|:---|:---|
| Direct HTTP/HTTPS files | Video and audio downloads | Pause, resume, retry, cancel |
| Segmented transfers | Embedded `yt-dlp` and `FFmpeg` | Download queue and local history |
| Per-file connection settings | Automatic URL type detection | Duplicate active-download protection |
| Parallel download control | Quality presets when available | Clipboard URL detection |
| Configurable speed limit | Video or audio mode selection | Custom save folder |
| Live download speed and progress | Source-dependent format selection | File size and status information |

**Designed for focus:** a smooth black-and-white interface with Outfit typography, Lucide-style icons, rounded controls, and a draggable window surface.

## Supported Platforms

### Download from popular social media, video & music services

Dnything can process **compatible public media URLs** using `yt-dlp`. Supported examples include:

| Category | Platforms |
|:---|:---|
| **Social networks** | **YouTube**, **TikTok**, **Instagram**, **Facebook**, **X / Twitter**, **Reddit**, **Pinterest**, **Bluesky**, **Tumblr**, **LinkedIn**, **VK**, **Likee** |
| **Video & streaming** | **Vimeo**, **Twitch**, **Dailymotion**, **Rumble**, **Bilibili**, **PeerTube** |
| **Music & audio** | **SoundCloud**, **Bandcamp**, **Mixcloud** |
| **Direct files** | Publicly accessible **HTTP/HTTPS** URLs, including ZIP, EXE, PDF, images, archives, and other files |

**Popular formats:** YouTube videos and Shorts, Instagram Reels, TikTok clips, Facebook videos, X posts with media, live-stream recordings, audio tracks, and direct files—**where the source and extractor support them**.

> [!IMPORTANT]
> Compatibility depends on the source website, URL, network availability, and the bundled `yt-dlp` version. Not every video, account, or link is downloadable. Private, restricted, and DRM-protected content is not unlocked or bypassed.

Explore the [official yt-dlp supported sites](https://github.com/yt-dlp/yt-dlp/blob/master/supportedsites.md) for additional services and extractor details.

## Quality Options

Choose the best source quality or request a preferred resolution when offered:

| Best Available | 4K UHD | 2K QHD | Full HD | HD | SD | Low |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Highest available | 2160p | 1440p | 1080p | 720p | 480p | 360p |

Audio-only downloads use source-dependent streams and compatible processing options. Quality presets do not create resolutions unavailable at the source.

## Download

<div align="center">

### Windows 10 / 11 · x64 · Standalone

**[⬇ Get the latest Dnything.exe](https://github.com/devjaber/Dnything/releases/latest)**

No installer or separate .NET, FFmpeg, or yt-dlp setup required.

</div>

Download `Dnything.exe` from the **Assets** section of the latest [GitHub Release](https://github.com/devjaber/Dnything/releases). Use only releases from sources you trust.

## Quick Start

1. Open the [latest release](https://github.com/devjaber/Dnything/releases/latest) and download `Dnything.exe`.
2. Run it on a supported Windows x64 computer.
3. Paste a file URL or a supported video/audio link.
4. Choose **Auto Detect**, **Direct File**, **Video**, or **Audio**.
5. Select an available quality preset for media downloads.
6. Choose a save folder and click **Download**.
7. Monitor progress and manage your download queue.

<div align="center">
  <a href="./Openapp.png"><img src="./Openapp.png" alt="Dnything application ready to receive a URL" width="900"></a>
  <p><sub>Open Dnything, paste a URL, and start your next download.</sub></p>
</div>

## Standalone by Design

Dnything is distributed as a **self-contained, single-file Windows x64 executable**:

- **.NET Runtime included** — no separate runtime installation needed.
- **yt-dlp bundled** — media extraction tools are included with the release build.
- **FFmpeg bundled** — required media processing tools are included.
- **Local operation** — the app manages its own settings, transfers, queue, and history.

On the first media download, the necessary bundled tools are extracted to:

```text
%LOCALAPPDATA%\Dnything\runtime-tools
```

### System Requirements

| | Requirement |
|:---|:---|
| **OS** | Windows 10 or Windows 11 |
| **CPU** | x64 (64-bit) |
| **Internet** | Required for remote downloads |
| **Storage** | Free disk space and write permission in your chosen folder |

The current build is not intended for 32-bit Windows, Windows on ARM, or macOS.

## Privacy & Responsible Use

- **No Dnything account required.**
- Download settings, queue data, and history are stored locally on your device.
- Downloaded files are saved to the destination you select.
- Online downloads connect to the source websites or servers you choose.
- Only download content you own or have permission to save. Respect copyright, applicable law, and the terms of each platform.

## Troubleshooting

<details>
<summary><strong>Windows SmartScreen shows a warning</strong></summary>

The standalone executable may be unsigned. Check the publisher, release source, and any available file verification information before deciding whether to run it.

</details>

<details>
<summary><strong>A social media or video URL does not work</strong></summary>

Confirm that the URL is valid, publicly accessible, and compatible with the included version of `yt-dlp`. Try **Auto Detect**. Platform changes, authentication requirements, and content restrictions can prevent downloads.

</details>

<details>
<summary><strong>The download is slower than expected</strong></summary>

Check your connection, source server, destination drive, speed limit, and connection settings. Segmented transfers help only when the remote server supports range requests.

</details>

<details>
<summary><strong>The resolution I want is missing</strong></summary>

Available quality levels are determined by the source and the media extractor. Try **Best Available** or another offered preset.

</details>

## Credits & License

- **Dnything:** [github.com/devjaber/Dnything](https://github.com/devjaber/Dnything)
- **Data Stream design:** four unequal data lanes symbolizing speed, transfer queues, and different file types.
- **Media extraction:** [yt-dlp](https://github.com/yt-dlp/yt-dlp)
- **Media processing:** [FFmpeg](https://ffmpeg.org/)

**License:** A repository license has not yet been specified. Add a `LICENSE` file to define permissions for reuse, modification, and redistribution.

---

<div align="center">

**Dnything — Download anything. Fast.**

Built for Windows. Made for downloads.

[Back to top](#download-anything-fast) · [Latest Release](https://github.com/devjaber/Dnything/releases/latest)

</div>
