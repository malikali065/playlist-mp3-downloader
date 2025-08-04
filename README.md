# 🎵 YouTube MP3 Downloader

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Windows](https://img.shields.io/badge/Platform-Windows-blue.svg)](https://www.microsoft.com/windows)
[![Batch](https://img.shields.io/badge/Language-Batch-green.svg)](https://en.wikipedia.org/wiki/Batch_file)

A simple yet powerful batch script for automatically downloading music from YouTube as high-quality MP3 files, complete with embedded cover art and metadata.

## ✨ Features

- 🎧 **High-Quality MP3s** - Downloads in the best available audio quality
- 🖼️ **Album Art** - Automatically embeds YouTube thumbnails as cover art
- 📝 **Rich Metadata** - Includes title, artist, and additional track information
- 📦 **Batch Processing** - Download multiple songs from a simple text list
- 📊 **Progress Tracking** - Real-time download status and completion indicators
- ⚠️ **Error Handling** - Clear reporting of successful and failed downloads
- 🔄 **Easy Setup** - Minimal configuration required

## 🚀 Quick Start

### Prerequisites

1. **Windows Operating System** (Windows 7 or later)
2. **Internet Connection** for downloading

### Download & Setup

1. **Download the latest release** from the [Releases](../../releases) page
2. **Extract** the ZIP file to your desired location
3. **Edit** `songs.txt` with your desired tracks (see format below)
4. **Run** `download.bat`

### Song List Format

Open `songs.txt` and add your songs using this format:

```
Artist - Title
```

**Examples:**
```
Adele - Hello
Ed Sheeran - Shape of You
The Beatles - Hey Jude
```

**For collaborations:**
```
Akon,Eminem - Smack That
Jay-Z,Alicia Keys - Empire State of Mind
```

## 📁 Project Structure

```
youtube-mp3-downloader/
├── 📄 download.bat          # Main download script
├── 📄 songs.txt             # Your song list (editable)
├── 📄 yt-dlp.exe           # YouTube downloader (included)
├── 📄 ffmpeg.exe           # Audio converter (included)
├── 📄 README.md            # This file
└── 📂 downloads/           # Output folder (created automatically)
    ├── 🎵 Song1.mp3
    ├── 🎵 Song2.mp3
    └── ...
```

## 🛠️ Usage

1. **Prepare Your List**: Edit `songs.txt` with desired tracks
2. **Run the Script**: Double-click `download.bat`
3. **Monitor Progress**: Watch the download progress in the console
4. **Collect Your Music**: Find MP3s in the `downloads/` folder

### Example Output
```
====== YouTube MP3 Downloader mit Cover und Metadaten ======

[1/3] Lade: Adele - Hello
✅ Erfolgreich: Adele - Hello

[2/3] Lade: Ed Sheeran - Shape of You  
✅ Erfolgreich: Ed Sheeran - Shape of You

[3/3] Lade: The Beatles - Hey Jude
✅ Erfolgreich: The Beatles - Hey Jude

====== Alle Downloads abgeschlossen ======
```

## 🔧 Dependencies

This project includes all necessary dependencies:

- **[yt-dlp](https://github.com/yt-dlp/yt-dlp)** - YouTube video/audio downloader
- **[FFmpeg](https://ffmpeg.org/)** - Audio processing and conversion

*No additional downloads required!*

## ❓ Troubleshooting

### Common Issues

| Issue | Solution |
|-------|----------|
| "yt-dlp.exe not found" | Ensure `yt-dlp.exe` is in the same folder as `download.bat` |
| "ffmpeg.exe not found" | Ensure `ffmpeg.exe` is in the same folder as `download.bat` |
| "songs.txt not found" | Create `songs.txt` and add at least one song |
| Song not found | Check spelling, try English titles, or alternative versions |
| Download fails | Check your internet connection and try again |

### Getting Help

- 📧 **Discord**: `rali2628`
- 🐛 **Issues**: [Open an issue](../../issues) on GitHub
- 💬 **Discussions**: Use the [Discussions](../../discussions) tab

## 📋 System Requirements

- **OS**: Windows 7/8/10/11
- **RAM**: 1GB minimum
- **Storage**: 100MB + space for downloaded music
- **Network**: Stable internet connection

## 🚨 Legal Disclaimer

This tool is intended for **personal use only**. Users are responsible for:

- ✅ Respecting copyright laws in their jurisdiction
- ✅ Following YouTube's Terms of Service
- ✅ Only downloading content they have permission to download
- ✅ Using downloaded content for personal, non-commercial purposes

**The author is not liable for any misuse of this software.**

## 🤝 Contributing

Contributions are welcome! Please feel free to:

1. 🍴 Fork the repository
2. 🌟 Create a feature branch
3. 💻 Make your changes
4. 📝 Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⭐ Show Your Support

If this project helped you, please consider:

- ⭐ **Starring** this repository
- 🐛 **Reporting** any bugs you find
- 💡 **Suggesting** new features
- 📢 **Sharing** with friends who might find it useful

## 📊 Stats

![GitHub stars](https://img.shields.io/github/stars/yourusername/youtube-mp3-downloader?style=social)
![GitHub forks](https://img.shields.io/github/forks/yourusername/youtube-mp3-downloader?style=social)
![GitHub issues](https://img.shields.io/github/issues/yourusername/youtube-mp3-downloader)
![GitHub downloads](https://img.shields.io/github/downloads/yourusername/youtube-mp3-downloader/total)

---

**Made with ❤️ by [Rali](https://github.com/yourusername)**

*Enjoy your music! 🎵*
