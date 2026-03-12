# Kaito - Advanced Discord Bot

A powerful, feature‑rich Discord bot with economy and moderation systems, written in JavaScript using discord.js v14.  
Includes persistent storage, cooldowns, and a wide range of commands for fun, economy, and server management.

---

## Features

### 💰 Economy System

Complete economy with balance, daily rewards, work, shop, inventory, bank, gambling, and more:

- `balance` - Check your or another user's balance  
- `daily` - Claim daily rewards with streak bonuses  
- `work` - Work to earn coins (1 hour cooldown)  
- `shop` - Browse available items  
- `buy` - Purchase items from the shop  
- `inventory` - View your items  
- `give` - Transfer coins to another user  
- `leaderboard` - View the richest users  
- `bank` - Deposit, withdraw, and check bank balance  
- `steal` - Attempt to rob another user (30 min cooldown)  
- `gamble` - 50/50 double or nothing (5 min cooldown)  
- `fish` - Go fishing (requires fishing rod, 1 min cooldown)  
- `crime` - Commit a crime for high risk/reward (1 hour cooldown)  
- `slots` - Play the slot machine (30 sec cooldown)  
- `interest` - Earn interest on bank savings (0.1% per hour)  
- `use` - Use items from your inventory  

### 🛡️ Moderation

Complete moderation toolkit:

- `ban` - Ban a user from the server  
- `kick` - Kick a user from the server  
- `purge` - Delete multiple messages at once  
- `warn` - Warn a user  
- `warnings` - List warnings for a user  
- `clearwarnings` - Clear all warnings for a user  
- `mute` - Timeout a user (temporary mute)  
- `unmute` - Remove timeout from a user  
- `slowmode` - Set slowmode in the current channel  
- `lock` - Lock the current channel  
- `unlock` - Unlock the current channel  
- `addrole` - Add a role to a user  
- `removerole` - Remove a role from a user  
- `modlog` - Set the channel for moderation logs  
- `prefix` - Change the command prefix  

### 🎉 Fun Commands

Entertainment features:

- `8ball` - Ask the magic 8ball a question  
- `coinflip` - Flip a coin  
- `dice` - Roll a dice (customizable sides)  
- `rps` - Play rock-paper-scissors  
- `meme` - Fetch a random meme from Reddit  
- `joke` - Get a random joke  

### ℹ️ Utility

- `help` - Show all available commands  

### 📊 Persistent Storage

All data saved in JSON files:

- `guildSettings.json` - Server settings (prefix, modlog channel)  
- `economy.json` - Economy data (balances, inventory, streaks)  
- `warnings.json` - Warning system (per user per guild)  

### ⚡ Dual Command System

Both slash commands and prefix commands:

- Slash commands - Registered globally, accessible via `/`  
- Prefix commands - Customizable per-server prefix (default: `?`)  

---

## What You Need

- Node.js v16.9.0 or higher  
- A Discord bot token (Discord Developer Portal)  
- Git (optional)  
- Visual Studio Code or any code editor  

---

## Installation

1. **Clone the repository**

```bash
git clone https://github.com/EnkryptedV1rus/kaito-bot.git
cd kaito-bot
```
2. **Install dependencies**
```bash
npm install
```

---

## Configuration

1. Create a config.json file in the root directory with the following structure:
```bash
{
  "token": "YOUR_BOT_TOKEN",
  "clientId": "YOUR_CLIENT_ID",
  "defaultPrefix": "?"
}
```
`token`: Your bot token
`clientId`: Your bot

