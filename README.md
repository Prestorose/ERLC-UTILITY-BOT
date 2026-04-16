# ERLC Utility Bot (v1.0.0)

[![GitHub License](https://img.shields.io/github/license/SEJED-DEV/ERLC-UTILITY-BOT?color=green)](https://github.com/SEJED-DEV/ERLC-UTILITY-BOT/blob/main/LICENSE)
[![GitHub Repo Size](https://img.shields.io/github/repo-size/SEJED-DEV/ERLC-UTILITY-BOT)](https://github.com/SEJED-DEV/ERLC-UTILITY-BOT)
[![GitHub Last Commit](https://img.shields.io/github/last-commit/SEJED-DEV/ERLC-UTILITY-BOT)](https://github.com/SEJED-DEV/ERLC-UTILITY-BOT)

A professional, enterprise-grade Discord bot designed for ER:LC Private Servers. Built with modularity, security, and performance in mind.

---

## ✨ Features

- **🚀 ERLC API V2 Integration**: Real-time server info, players, logs, and in-game commands.
- **🛡️ Advanced Security**: Global rate limiting, and private owner management.
- **💾 Local Database**: SQLite integration (`better-sqlite3`) for high-performance settings and log persistence.
- **⚙️ Dynamic Configuration**: Manage every aspect of the bot via `/config` without restarting.
- **👔 Professional Branding**: Dynamic embeds, timestamps, and high-fidelity logging.
- **🎫 Robust Modules**: Ticket systems, Giveaways, Custom Commands, and multi-channel logging.

---

## 🛠️ Quick Start

### 1. Requirements
- Node.js 18.x or higher
- An ER:LC Private Server with an API Key

### 2. Installation
```bash
# Clone the repository
git clone https://github.com/SEJED-DEV/ERLC-UTILITY-BOT
cd ERLC-UTILITY-BOT

# Install dependencies
npm install
```

### 3. Configuration
Rename `.env.example` to `.env` and fill in your credentials:
```env
BOT_TOKEN=your_token
CLIENT_ID=your_id
GUILD_ID=your_guild
SECRET_DEVELOPER_ID=985444871722631199
SERVER_OWNER_ID=your_owner_id
```

### 4. Launch
```bash
# Start the bot
npm start
```

---

## 📦 Project Structure

```text
src/
├── commands/     # Slash & Prefix commands
├── events/       # Discord event listeners
├── handlers/     # Core system loaders
└── utils/        # ERLC API, Database, Security, Embeds
database.db       # Local SQLite storage
```

## 📜 Credits & License
This project is maintained by **SEJED-DEV**.
-   **License**: Custom MIT (Free for all with attribution).
-   **Credits**: Use the `/credits` command in-app to view contributors.

## 🤝 Support
For community support and updates, join our [Discord Server](https://discord.gg/zYvqDB5MWB).

---

© 2026 SEJED-DEV. All Rights Reserved.
