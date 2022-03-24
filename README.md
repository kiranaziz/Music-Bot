# Music Bot

This Discord bot plays user's specified music, either by entering key words or a YouTube URL.

### Commands:
- /help - Displays all the available commands.
- /p <insert keywords or URL here> - Finds the song on YouTube and plays it in your current channel. The bot will resume playing the current song if it was paused.
- /q - Displays the current music queue.
- /skip - Skips the current song being played
- /clear - Stops the music and clears the queue
- /leave - Disconnected the bot from the voice channel
- /pause - Pauses the current song being played or resumes if already paused
- /resume - Resumes playing the current song

## Installation:
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the following before running and must 
download FFmpeg first from here: [](https://ffmpeg.org/download.html)

```bash
pip install discord.py
pip install ffmpeg
pip install youtube_dl
```
