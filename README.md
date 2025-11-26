# STOW - Video Downloader and Converter

A modern Electron application for downloading videos from 1000+ websites and converting videos between multiple formats.

## Features

- **Video Downloads**: Download videos from YouTube, Vimeo, Dailymotion, Instagram, TikTok, Threads, X (Twitter), and 1000+ other websites
- **Playlist Support**: Download entire playlists from supported platforms
- **Video Conversion**: Convert videos between multiple formats (MP4, WebM, AVI, MOV, MKV, FLV, WMV)
- **Audio Extraction**: Extract audio in various formats (MP3, WAV, AAC, OGG)
- **Drag & Drop**: Easy file selection with drag-and-drop interface
- **Quality Selection**: Choose video quality for downloads
- **Modern UI**: Dark theme with macOS-style window controls

## Supported Platforms

- YouTube
- Vimeo
- Dailymotion
- Instagram
- TikTok
- Threads
- X (Twitter)
- And 1000+ more websites supported by yt-dlp

## Installation

1. Install dependencies:
```bash
npm install
```

2. Run the application:
```bash
npm start
```

## Building

Build for your platform:
```bash
npm run build
```

## Requirements

- Node.js 16+ 
- FFmpeg (needs to be installed separately)

### Installing FFmpeg

**macOS:**
```bash
brew install ffmpeg
```

**Windows:**
Download from [FFmpeg website](https://ffmpeg.org/download.html) or use:
```bash
choco install ffmpeg
```

**Linux:**
```bash
sudo apt-get install ffmpeg  # Debian/Ubuntu
sudo yum install ffmpeg       # CentOS/RHEL
```

**Note:** yt-dlp is automatically downloaded by yt-dlp-wrap on first run.

## Usage

### Downloading Videos

1. Switch to the "Download" tab
2. Paste a video URL
3. Select quality and options
4. Click "Download"

### Converting Videos

1. Switch to the "Convert" tab
2. Drag and drop videos or click "Choose Files"
3. Select output format and quality
4. Click "Convert"

## Technologies

- Electron
- yt-dlp-wrap (for video downloads)
- fluent-ffmpeg (for video conversion)

## License

MIT

# stow
