# YouTube Playlist to Podcast Automation

## Overview
This project automates the process of converting YouTube playlist videos into MP3 audio files, ready for podcast hosting on platforms like Spotify. It was used to process over 5000+ videos from our Raja Yoga Meditation YouTube channel and repurpose them into podcasts.

## Features
- Downloads audio directly from YouTube playlists
- Converts videos to MP3 format
- Supports batch processing of large playlists (1000+ videos)
- Outputs structured files ready for volunteers to upload to Spotify or other podcast platforms

## Example Podcasts
- [Raja Yoga 7 Days Course](https://creators.spotify.com/pod/profile/jaishree-k/)  
- [Raja Yoga Meditation Classes in Tamil](https://creators.spotify.com/pod/profile/selvasoniyalourduxavier/)  
- [Raja Yoga Q&A Series](https://creators.spotify.com/pod/profile/sethupathi-sekar/)  
- [Raja Yoga Commentary](https://creators.spotify.com/pod/profile/lourdu-xavier-ambrose/)  
- [Bedtime Stories in Tamil](https://creators.spotify.com/pod/profile/kayal-lekha/)  
- [Miscellaneous Topics](https://creators.spotify.com/pod/profile/sethupathi-sekar3/)  

## How It Works
1. Provide a YouTube playlist link as input.
2. The script downloads and converts each video to MP3.
3. MP3 files are stored locally for further curation or upload.

## Technologies Used
- **Python**
- `pytube` or `yt-dlp` for YouTube downloads
- `ffmpeg` for audio conversion
- Standard Python libraries for file handling

## Usage
```bash
# Install dependencies
pip install yt-dlp ffmpeg-python

# Run the script
python playlist_to_podcast.py "https://www.youtube.com/playlist?list=YOUR_PLAYLIST_ID"
