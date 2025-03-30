# Discord AI Buddy 🤖

A powerful Discord bot powered by AI that helps manage your server and interact with users in a smart way. Features a beautiful web dashboard for easy configuration and monitoring.

## 🌟 Features

- **AI-Powered Conversations**: Engage in natural conversations using advanced language models
- **Smart Command System**: Built-in commands for various functionalities
  - `!ask` - Ask the AI any question
  - `!help` - Get help with commands
  - `!ping` - Check bot latency
- **Web Dashboard**: Modern UI for managing bot settings and monitoring activity
- **Context Memory**: Bot remembers conversation context for more natural interactions
- **Moderation**: Built-in content moderation to keep conversations appropriate
- **Real-time Statistics**: Monitor bot performance, usage, and server statistics

## 🚀 Tech Stack

- **Frontend**: React, TypeScript, Tailwind CSS, Shadcn UI
- **Backend**: Node.js, Express
- **Database**: PostgreSQL with Drizzle ORM
- **AI Integration**: OpenAI GPT models
- **Real-time Updates**: WebSocket for live dashboard updates
- **Authentication**: Session-based auth with Passport.js

## 📋 Prerequisites

Before you begin, ensure you have:
- Node.js (v16 or higher)
- PostgreSQL database
- Discord Bot Token
- OpenAI API Key

## 🛠️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/AIDiscordBuddy.git
   cd AIDiscordBuddy
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a `.env` file in the root directory with:
   ```env
   DISCORD_TOKEN=your_discord_bot_token
   DATABASE_URL=your_postgresql_database_url
   ```

4. **Initialize database**
   ```bash
   npm run db:push
   ```

5. **Start the development server**
   ```bash
   npm run dev
   ```

## 🎮 Usage

1. **Invite the bot to your server**
   - Use the Discord Developer Portal to generate an invite link
   - Select required permissions (Send Messages, Read Messages, etc.)

2. **Basic Commands**
   - `!ask [question]` - Ask the AI a question
   - `!help` - Display available commands
   - `!ping` - Check bot's response time

3. **Web Dashboard**
   - Access at `http://localhost:5000` (in development)
   - Configure bot settings
   - View analytics and logs
   - Manage server-specific settings

## 🔧 Configuration

The bot can be configured through:
- Web dashboard interface
- Environment variables
- `config.json` file (for advanced settings)

## 📊 Dashboard Features

- Real-time statistics
- Command usage analytics
- Server management
- User interaction logs
- Configuration settings
- Theme customization

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with [Discord.js](https://discord.js.org/)
- UI components from [shadcn/ui](https://ui.shadcn.com/)
- Powered by OpenAI's GPT models

## 📞 Support

If you need help or have questions:
- Open an issue on GitHub
- Join our Discord server (coming soon)
- Check the documentation (coming soon)

---
Made with ❤️ by [Your Name]