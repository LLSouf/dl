# Media Downloader GUI Script 🎬

A Bash script with YAD GUI for downloading YouTube videos/audio with format selection, quality options, and clip cutting features. 🖥️🔧

## Features ✨
- 🖱️ URL input from clipboard or command line
- 🎚️ Multiple download options:
  - Best Video/MP4/720p/480p/Best Audio/M4A
  - Custom format selection
  - Video clipping with timecodes
- 📁 Automatic organization in `~/Downloads/ydl/`
- 🔐 Chrome cookie integration
- 📊 Progress notifications with `notify-send`
- 📝 Smart filename truncation

## Prerequisites 📦
```bash
sudo apt install yad yt-dlp ffmpeg xclip # For Debian/Ubuntu
```
## Installation ⚙️
```bash
git clone https://github.com/LLSouf/dl
cd dl
chmod +x dl
```
## Usage 🚀
```bash
./dl [URL]  
```
CLI Optional : if you bind a keyboard shortcut to the script, clipboarded URL is processed

## Troubleshooting 🚨
Missing Cookies: Ensure Chrome is installed

Cut Errors: Verify timecode format (HHMMSS)

Format Issues: Check available formats with yt-dlp -F [URL]
