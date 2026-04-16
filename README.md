# ERLC Utility Bot (v1.0.0)

[![GitHub License](https://img.shields.io/github/license/SEJED-DEV/ERLC-UTILITY-BOT?color=blue)](https://github.com/SEJED-DEV/ERLC-UTILITY-BOT/blob/main/LICENSE.md)
[![GitHub Repo Size](https://img.shields.io/github/repo-size/SEJED-DEV/ERLC-UTILITY-BOT?color=blue)](https://github.com/SEJED-DEV/ERLC-UTILITY-BOT)
[![GitHub Last Commit](https://img.shields.io/github/last-commit/SEJED-DEV/ERLC-UTILITY-BOT?color=blue)](https://github.com/SEJED-DEV/ERLC-UTILITY-BOT)
[![Discord Support](https://img.shields.io/badge/Discord-Support-7289DA?logo=discord&logoColor=white)](https://discord.gg/zYvqDB5MWB)

A professional, enterprise-grade Discord bot designed for ER:LC Private Servers. Built with modularity, security, and the latest **ERLC API V2** at its core.

---

## 🎧 Support & Community

Need real-time assistance or want to join the community?
**[Join our Discord Support Server](https://discord.gg/zYvqDB5MWB)**

---

## ✨ Features

- **🚀 ERLC API V2 (Optimized)**: Real-time status, postal location tracking, wanted-star detection, and vehicle plate lookups—all via a single-endpoint polling system for maximum efficiency.
- **🛡️ Secure Persistence**: High-performance local SQLite database (`better-sqlite3`) ensures your data stays on your machine, not in the cloud.
- **⚙️ Dynamic Management**: A powerful `/config` command system allows owners to update API keys, channel IDs, and role permissions without reboots.
- **👔 Executive Branding**: High-fidelity embeds, auto-updating SSU counters, and professional console logging.
- **🎫 Feature Suite**: Advanced Ticket transcripts, Button-based Giveaways, and comprehensive forensic logging.

---

## 🛠️ Quick Start

### 1. Requirements
- Node.js 18.x or higher
- An ER:LC Private Server API Key

### 2. Installation
```bash
# Clone the repository
git clone https://github.com/SEJED-DEV/ERLC-UTILITY-BOT
cd ERLC-UTILITY-BOT

# Install dependencies
npm install
```

### 3. Configuration
Rename `.env.example` to `.env` and enter your IDs. The rest can be configured via `/config` once the bot is live.

### 4. Launch
```bash
npm start
```

---

## 📦 Project Structure

```text
src/
├── commands/     # Slash & Prefix commands
├── events/       # Discord event listeners
├── handlers/     # Loaders (Command, Slash, Events)
└── utils/        # Core Utilities (DB, API, Security, Branding)
database.db       # Local SQLite storage
```

## 📜 Credits & License
Maintained and authored by **SEJED-DEV**.
-   **License**: [MIT License](LICENSE.md) (Free for use with attribution).
-   **Attribution**: Maintain the `/credits` and `/support` commands visible.

---

© 2026 SEJED-DEV. All Rights Reserved.
