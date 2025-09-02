# 🌟 INFINITY Discord Bot

<div align="center">

![Astroz Bot Banner](https://via.placeholder.com/800x200/7289da/ffffff?text=INFINITY+DISCORD+BOT)

[![Discord](https://img.shields.io/discord/YOUR_SERVER_ID?color=7289da&label=Discord&logo=discord&logoColor=white)](https://dsc.gg/astrozhq)
[![Invite New Bot](https://img.shields.io/badge/Invite-Bot-blue?style=for-the-badge)](https://dsc.gg/Astroz-invite)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Node.js](https://img.shields.io/badge/Node.js-v16+-green.svg)](https://nodejs.org/)

**A powerful, feature-rich Discord bot built with Discord.js**

[Invite Bot](https://dsc.gg/Astroz-invite) • [Support Server](https://dsc.gg/astrozhq) • [Documentation](#features) • [Contributing](#contributing)

</div>

## 📋 Table of Contents

- [About](#-about)
- [Features](#-features)
- [Installation](#-installation)
- [Configuration](#-configuration)
- [Commands](#-commands)
- [Events](#-events)
- [Dashboard](#-dashboard)
- [Contributing](#-contributing)
- [Support](#-support)
- [License](#-license)
- [Credits](#-credits)

## 🤖 About

Astroz is a comprehensive Discord bot designed to enhance your server experience with a wide range of features including moderation, entertainment, economy, music, and much more. Built with Discord.js and featuring a modern dashboard, Astroz provides everything you need to manage and entertain your Discord community.

### ✨ Key Highlights

- 🛡️ **Advanced Moderation** - Complete moderation suite with anti-nuke protection
- 🎮 **Fun & Games** - 100+ entertainment commands and interactive games
- 💰 **Economy System** - Full-featured economy with daily rewards, shop, and gambling
- 🎵 **Music Player** - High-quality music streaming with queue management
- 📊 **Comprehensive Logging** - Detailed server activity tracking
- 🌐 **Web Dashboard** - Modern web interface for bot management
- ⚡ **High Performance** - Optimized for speed and reliability
- 🔒 **Security Features** - Anti-spam, anti-raid, and server protection

## 🚀 Features

### 🛡️ Moderation & Security
- **Anti-Nuke Protection** - Prevents server raids and mass deletions
- **Auto Moderation** - Automatic spam and link filtering
- **Comprehensive Mod Tools** - Ban, kick, mute, warn, and more
- **Channel Management** - Lock, unlock, hide channels
- **Role Management** - Create, delete, assign roles
- **Message Management** - Purge, edit, and moderate messages

### 🎮 Entertainment & Fun
- **100+ Fun Commands** - Memes, jokes, games, and interactive content
- **Mini Games** - Tic-tac-toe, Connect 4, Hangman, Wordle, and more
- **Image Manipulation** - Avatar effects, meme generation
- **Random Generators** - Facts, quotes, advice, and more
- **Interactive Features** - Polls, giveaways, trivia

### 💰 Economy System
- **Virtual Currency** - Earn and spend coins
- **Daily Rewards** - Daily coin collection
- **Shop System** - Buy items and upgrades
- **Gambling** - Slots, dice, and other games
- **Work System** - Earn money through various jobs
- **Bank System** - Deposit and withdraw money

### 🎵 Music & Audio
- **High-Quality Streaming** - Crystal clear audio playback
- **Queue Management** - Add, remove, and shuffle songs
- **Playlist Support** - Save and load custom playlists
- **Volume Control** - Adjust playback volume
- **Skip & Stop** - Full playback controls

### 📊 Logging & Analytics
- **Comprehensive Logging** - Track all server activities
- **Member Logs** - Join/leave tracking
- **Message Logs** - Message edit/delete tracking
- **Voice Logs** - Voice channel activity
- **Mod Logs** - Moderation action tracking
- **Role & Channel Logs** - Permission change tracking

### 🌐 Web Dashboard
- **User-Friendly Interface** - Easy-to-use web panel
- **Server Management** - Configure bot settings remotely
- **Real-Time Stats** - Live server statistics
- **Command Management** - Enable/disable commands
- **Custom Settings** - Personalize bot behavior

### 🎯 Utility & Tools
- **Server Information** - Detailed server and user stats
- **Custom Badges** - Create and assign user badges
- **AFK System** - Automatic AFK status management
- **Auto Reactions** - Automatic message reactions
- **Welcome System** - Customizable welcome messages
- **Invite Tracking** - Monitor server invitations

## 🔧 Installation

### Prerequisites
- Node.js v16 or higher
- NPM or Yarn package manager
- Discord Bot Token
- MongoDB Database (optional)

### Quick Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/riyad-123/infinity-bot.git
   cd astroz-discord-bot
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure environment variables**
   ```bash
   cp .env.example .env
   # Edit .env with your bot token and other settings
   ```

4. **Start the bot**
   ```bash
   npm start
   # or
   node index.js
   ```

## ⚙️ Configuration

### Environment Variables

Create a `.env` file in the root directory:

```env
# Bot Configuration
BOT_TOKEN=your_discord_bot_token
CLIENT_ID=your_bot_client_id
GUILD_ID=your_test_server_id

# Database (Optional)
MONGODB_URI=mongodb://localhost:27017/astroz

# Dashboard Configuration
SESSION_SECRET=your_session_secret
DASHBOARD_PORT=3000

# API Keys (Optional)
YOUTUBE_API_KEY=your_youtube_api_key
SPOTIFY_CLIENT_ID=your_spotify_client_id
SPOTIFY_CLIENT_SECRET=your_spotify_client_secret
```

### Bot Configuration

Edit `config.json` to customize bot settings:

```json
{
  "prefix": "!",
  "ownerIds": ["your_discord_user_id"],
  "embedColor": "#7289da",
  "supportServer": "https://dsc.gg/astrozhq",
  "inviteLink": "https://dsc.gg/Astroz-invite"
}
```

## 📚 Commands

### 🛡️ Moderation Commands
- `!ban <user> [reason]` - Ban a user
- `!kick <user> [reason]` - Kick a user
- `!mute <user> [time] [reason]` - Mute a user
- `!warn <user> [reason]` - Warn a user
- `!purge <amount>` - Delete messages
- `!lock [channel]` - Lock a channel
- `!unlock [channel]` - Unlock a channel

### 🎮 Fun Commands
- `!meme` - Get a random meme
- `!joke` - Get a random joke
- `!8ball <question>` - Magic 8-ball
- `!dice [sides]` - Roll dice
- `!coinflip` - Flip a coin
- `!rps <choice>` - Rock Paper Scissors

### 💰 Economy Commands
- `!balance` - Check your balance
- `!daily` - Claim daily reward
- `!work` - Work for money
- `!shop` - View the shop
- `!buy <item>` - Buy an item
- `!slots [amount]` - Play slots

### 🎵 Music Commands
- `!play <song>` - Play a song
- `!skip` - Skip current song
- `!queue` - View music queue
- `!volume <1-100>` - Set volume
- `!stop` - Stop music

### ℹ️ Information Commands
- `!serverinfo` - Server information
- `!userinfo [user]` - User information
- `!botinfo` - Bot statistics
- `!help [command]` - Command help

## 🎯 Events

The bot includes comprehensive event handling for:

- **Message Events** - Command processing, auto-moderation
- **Member Events** - Welcome messages, role assignment
- **Guild Events** - Server join/leave tracking
- **Voice Events** - Voice channel logging
- **Moderation Events** - Anti-nuke protection
- **Interaction Events** - Slash command and button handling

## 🌐 Dashboard

Access the web dashboard at `http://localhost:3000` to:

- Configure bot settings
- View server statistics
- Manage commands and features
- Monitor logs and activities
- Customize welcome messages
- Set up auto-moderation

## 📊 Database

The bot uses SQLite for local data storage:

- **Guild Settings** - Server-specific configurations
- **User Data** - Economy, levels, and preferences
- **Logs** - Activity and moderation logs
- **Blacklists** - User and server blacklists
- **Custom Data** - Badges, roles, and custom features

## 🔒 Security Features

- **Anti-Nuke System** - Prevents mass deletions and raids
- **Rate Limiting** - Command cooldowns and spam protection
- **Permission Checks** - Role-based command access
- **Audit Logging** - Complete action tracking
- **Blacklist System** - Ban malicious users/servers

## 🚀 Performance

- **Optimized Code** - Efficient command handling
- **Memory Management** - Automatic cleanup and sweeping
- **Error Handling** - Comprehensive error management
- **Uptime Monitoring** - 99.9% uptime guarantee
- **Sharding Support** - Scale across multiple processes

## 🤝 Contributing

We welcome contributions to Astroz! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/amazing-feature`)
3. **Commit your changes** (`git commit -m 'Add amazing feature'`)
4. **Push to the branch** (`git push origin feature/amazing-feature`)
5. **Open a Pull Request**

### 📝 Contribution Guidelines

- Follow the existing code style
- Add comments for complex functionality
- Test your changes thoroughly
- Update documentation as needed
- Respect the project's license

## 📞 Support

Need help with Astroz? We're here to assist!

- **Discord Server**: [Join our support server](https://dsc.gg/astrozhq)
- **Bot Invite**: [Invite Astroz to your server](https://dsc.gg/Astroz-invite)
- **Issues**: Open an issue on GitHub
- **Documentation**: Check our wiki (coming soon)

### 🆘 Common Issues

- **Bot not responding**: Check bot permissions and token
- **Commands not working**: Verify prefix and command syntax
- **Music not playing**: Ensure bot has voice permissions
- **Dashboard not loading**: Check port configuration

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🏆 Credits

### 👨‍💻 Development Team

- **Head Developer**: RIYAD (Discord: .17ily)
- **Project Lead**: RIYAD
- **Community**: Astroz Discord Community

### 🙏 Acknowledgments

- **Discord.js** - The amazing Discord library
- **Node.js** - Runtime environment
- **Express.js** - Web framework for dashboard
- **SQLite** - Database management
- **All Contributors** - Thank you for your support!

### 🔗 Links

- **Discord Profile**: .17ily
- **Support Server**: https://dsc.gg/astrozhq
- **Bot Invite**: https://dsc.gg/Astroz-invite
- **GitHub**: https://github.com/RIYAD/astroz-discord-bot

---

<div align="center">

**Made with ❤️ by RIYAD**

*Star ⭐ this repository if you found it helpful!*

</div>

## 📈 Statistics

- **Commands**: 600+ commands across 8 categories
- **Events**: 50+ event handlers
- **Uptime**: 99.9% average uptime
- **Servers**: Growing community of Discord servers
- **Features**: Constantly evolving with new additions

## 🛠️ Tech Stack

- **Language**: JavaScript (Node.js)
- **Framework**: Discord.js v13
- **Database**: SQLite + JSON storage
- **Web Framework**: Express.js
- **Template Engine**: EJS
- **Process Manager**: PM2 (recommended)
- **Hosting**: VPS (production)

## 🎯 Roadmap

- [ ] Slash commands migration
- [ ] Advanced music features
- [ ] Custom command builder
- [ ] API endpoint expansion
- [ ] Mobile dashboard optimization
- [ ] Multi-language support
- [ ] AI integration features
- [ ] Advanced analytics

---

**This bot is open source and free to use. If you appreciate the work, consider starring the repository, adding new bot to your server and joining our community!**
