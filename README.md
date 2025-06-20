# Riot Roleplay Ticket Bot

A powerful, customizable Discord ticket bot designed for Riot Roleplay servers. Easily manage support, applications, and roleplay requests with advanced ticketing features.

## Features

- Slash and text command support
- Customizable ticket panels and questions
- Role-based permissions
- Ticket claim, close, pin, move, and more
- Logging and transcripts
- Multi-language support
- Easy configuration via JSON files

## Getting Started

### Prerequisites

- Node.js (v16 or higher recommended)
- npm or yarn
- A Discord bot token

### Installation

1. **Clone the repository:**
   ```bash
   git clone <repo-url>
   cd open-ticket-main
   ```
2. **Install dependencies:**
   ```bash
   npm install
   # or
   yarn install
   ```
3. **Configure your bot token:**

   - Create a `.env` file in the project root:
     ```env
     DISCORD_TOKEN=your-bot-token-here
     ```
   - Or set `tokenFromENV` to `false` in `config/general.json` and put your token there (not recommended for production).

4. **Configure your server settings:**
   - Edit `config/general.json` and other files in the `config/` folder to match your server's needs (IDs, permissions, language, etc).

### Running the Bot

```bash
npm start
# or
node index.js
```

### Docker Support

You can use the provided `dockerfile` and `docker-compose.yml` for containerized deployment.

## Usage

- Use `/help` or the configured prefix (default: `!ticket `) for a list of commands.
- Set up ticket panels and permissions in the config files.
- Manage tickets directly from Discord with buttons and commands.

## Support & Documentation

- [Support Server](https://discord.dj-dj.be)
- [Documentation](https://otdocs.dj-dj.be)

## License

MIT
