# Discord Music Bot

A Discord bot that plays music in voice channels using discord.js and discord-player.

## Features

- Play music from YouTube
- Skip current track
- Stop playback
- Queue management
- Volume control

## Setup

1. Clone the repository
```bash
git clone [your-repository-url]
```

2. Install dependencies
```bash
npm install
```

3. Create a `.env` file in the root directory and add your Discord bot token:
```
TOKEN=your_discord_bot_token_here
```

4. Start the bot
```bash
npm start
```

## Commands

- `/play` - Play a song from YouTube
- `/skip` - Skip the current song
- `/stop` - Stop playback and clear the queue
- `/queue` - Show the current queue
- `/volume` - Adjust the volume

## Dependencies

- discord.js
- discord-player
- @discord-player/extractor
- play-dl
