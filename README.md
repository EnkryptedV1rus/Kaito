# Kaito

<p align="center">
  <b>A powerful multipurpose Discord bot designed to entertain, protect, and manage communities.</b>
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![Discord.py](https://img.shields.io/badge/Discord.py-Library-5865F2?style=for-the-badge&logo=discord)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Maintained](https://img.shields.io/badge/Maintained-Yes-brightgreen?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-orange?style=for-the-badge)

</p>

---

## Overview

**Kaito** is a feature-rich Discord bot built with **Discord.py** that combines moderation tools, an economy system, and fun commands into one bot.  
It is designed to be **lightweight, customizable, and easy to host**, making it suitable for both small and large communities.

---

# Features

## 💰 Economy System

| Command | Description |
|-------|-------------|
| `balance` | Check your or another user's balance |
| `daily` | Claim daily rewards with streak bonuses |
| `work` | Work to earn coins |
| `shop` | Browse shop items |
| `buy` | Purchase items |
| `inventory` | View your items |
| `give` | Send coins to another user |
| `leaderboard` | View richest users |
| `bank` | Deposit and withdraw coins |
| `steal` | Attempt to rob another user |
| `gamble` | 50/50 double or nothing |
| `fish` | Catch fish with a fishing rod |
| `crime` | High-risk coin reward |
| `slots` | Slot machine gambling |
| `interest` | Passive bank interest |
| `use` | Use items from inventory |

---

## 🛡 Moderation System

| Command | Description |
|-------|-------------|
| `ban` | Ban a member |
| `kick` | Kick a member |
| `purge` | Bulk delete messages |
| `warn` | Warn a member |
| `warnings` | View warnings |
| `clearwarnings` | Clear warnings |
| `mute` | Timeout a user |
| `unmute` | Remove timeout |
| `slowmode` | Set channel slowmode |
| `lock` | Lock a channel |
| `unlock` | Unlock a channel |
| `addrole` | Add a role |
| `removerole` | Remove a role |
| `modlog` | Configure moderation logs |
| `prefix` | Change command prefix |

---

## 🎉 Fun Commands

| Command | Description |
|-------|-------------|
| `8ball` | Ask the magic 8ball a question |
| `coinflip` | Flip a coin |
| `dice` | Roll a customizable dice |
| `rps` | Rock-paper-scissors |
| `meme` | Fetch a random meme |
| `joke` | Get a random joke |

---

## ⚙ Utility

| Command | Description |
|-------|-------------|
| `help` | Display all commands |

---

# Persistent Storage

Kaito stores data using JSON files.

| File | Purpose |
|-----|---------|
| `guildSettings.json` | Server settings such as prefix and modlog channel |
| `economy.json` | Economy balances, inventory, and streaks |
| `warnings.json` | Warning system data |

---

# Command System

Kaito supports both **slash commands** and **prefix commands**.

Default prefix: `,` (changeable)
