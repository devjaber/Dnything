# Dnything

> Download anything. Fast.

Dnything is a fast, precise and self-contained downloader for Windows. It is designed to handle direct files, video and audio downloads in one clean, focused application.

## Logo

The exact product name is **Dnything**.

The black-and-white **Data Stream** logo is built from four unequal data lanes. The lanes represent speed, download queues and support for different file types without relying on the usual download-arrow cliché.

## Features

- Direct HTTP/HTTPS file downloads
- Segmented downloads for faster transfers
- Video and audio downloads through embedded `yt-dlp` and `FFmpeg`
- Quality presets from low resolution to the highest quality available from the source
- Automatic media detection for supported video, audio and social platforms
- Pause, resume, retry and cancel controls
- Download queue and local history
- Duplicate active-download protection
- Clipboard URL detection
- Custom save folder
- Per-file connection settings
- Parallel download control
- Download speed limit
- Progress, speed, file size and status information
- Smooth black-and-white interface
- Outfit typography and Lucide-style interface icons
- Rounded controls and a draggable window surface

## Supported download types

### Direct files

HTTP and HTTPS URLs that point to downloadable files, including archives, installers, documents, images and other binary files.

### Video and audio

Dnything can use supported media pages from services such as YouTube, Vimeo, TikTok, Instagram, Facebook, X/Twitter, Twitch, SoundCloud and Dailymotion. Availability and quality depend on the source service and the media URL.

## Quality options

Depending on the source, Dnything can request:

- Best quality
- 4K / 2160p
- 2K / 1440p
- Full HD / 1080p
- HD / 720p
- SD / 480p
- Low / 360p

## Getting started

1. Download the latest `Dnything.exe` from the [Releases](../../releases) page.
2. Run the executable on a supported Windows computer.
3. Paste a URL into the download field.
4. Choose `Auto Detect`, `Direct File`, `Video` or `Audio`.
5. Select the desired quality when media quality options are available.
6. Choose a save folder if needed, then select **Download**.

## Standalone operation

Dnything is published as a self-contained, single-file Windows x64 application.

You do not need to install:

- .NET Runtime
- FFmpeg
- yt-dlp
- A separate downloader service

The media tools are embedded in the executable. On the first media download, Dnything extracts the required runtime tools automatically into the current user's local application data directory:

```text
%LOCALAPPDATA%\\Dnything\\runtime-tools
```

## System requirements

- Windows 10 or Windows 11
- 64-bit x64 processor
- Internet connection for remote downloads
- Write permission for the selected save folder

The current release is not built for 32-bit Windows, ARM Windows or macOS.

## Privacy and local data

- No account is required to use Dnything.
- Download settings, history and queue data are stored locally on the computer.
- Dnything does not provide or bypass access to private, restricted or protected content.
- The user is responsible for the URLs they enter and the content they download.

## Responsible use

Only download content that you own or have permission to download. Respect the terms of service, copyright and applicable laws for every source you use.

## Troubleshooting

### Windows shows a SmartScreen warning

The standalone executable may be unsigned. If you trust the file source, choose **More info** and then **Run anyway**.

### A media URL does not work

Check that the URL is public and valid, try `Auto Detect`, and make sure the source service is reachable. Media services can change their page formats or restrict downloads.

### The download is slow

Check the source server and your connection, confirm that the save drive has free space, and review the connection and speed-limit settings.

## Release verification

For the current Windows x64 executable:

## Release assets

- `Dnything-v1.0.0-win-x64.exe` — standalone application
- `Dnything-brand-kit-v1.0.0.zip` — optional logo and identity files

## License

The repository license and redistribution terms should be added before distributing modified versions or derivative builds.
