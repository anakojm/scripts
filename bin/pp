#!/bin/bash
yt-dlp -N 8 --no-part -f "bestaudio" "$1" -o /tmp/ytaudio | yt-dlp -f "bestvideo" "$1" -o - | mpv --audio-file="/tmp/ytaudio" -
rm -rf /tmp/ytaudio
