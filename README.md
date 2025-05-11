# 🧙 ArcaneMobs Wiki

Welcome to the **ArcaneMobs** official wiki! This plugin brings RPG mechanics to Minecraft with dynamic mobs, player progression, quests, and a unique economy.

---

## 📦 Plugin Overview

**ArcaneMobs** is a powerful Minecraft plugin designed to enhance your server with:
- RPG-style leveling and skill trees
- Custom mobs that scale with player level
- An interactive quest system
- A virtual economy powered by Arcane Coins

> 🔄 Current Version: **Alpha**
>  
> 💬 [Join our Discord](https://discord.com/invite/g7wG4MwfJn) to report bugs, suggest features, or get help!

---

## 📈 Player Progression & Skills

Players earn XP by:
- Defeating ArcaneMobs
- Completing quests

As players level up, they gain **skill points** to allocate into:
- ⚔️ **Attack** – Increases damage dealt  
- 🛡️ **Defense** – Reduces damage received  
- 💪 **Strength** – Buffs overall combat performance  
- ❤️ **Health** – Increases max HP  

### Commands
- `/skills` – View current stats  
- `/skills spend <skill>` – Spend a skill point  

---

## 👾 ArcaneMobs System

ArcaneMobs are enhanced versions of vanilla mobs that dynamically scale based on nearby player levels. 

### Features:
- Custom **nameplates** showing mob level
- **Boss bars** with mob HP
- Level-scaled **damage, health, armor, and speed**
- Custom **glowing effects** and **particles**

### Configurable On-Hit Effects (Experimental)
Defined in `mobeffects.yml`:
```yml
Zombie:
  1-10:
    effect: POISON
    chance: 0.2
    duration: 60
    amplifier: 1



📜 Quest System
ArcaneMobs includes a full-featured questing system!

Starting Quests:
Use /quest or /quest list to open the Quest GUI.

Accept or abandon quests via the GUI

Track objectives, rewards, and completion status

Predefined Quests:
Zombie Hunter

Spider Slayer

Witch Hunt

Piglin Patrol

...and more!

Quests reward XP and Arcane Coins.

💰 Arcane Coin Economy
Arcane Coins are custom Gold Nuggets used as currency.

Dropped by ArcaneMobs (scaled by mob level)

Auto-converted into virtual balance on pickup

Player Commands
/am balance – Check your balance

/am pay <player> <amount> – Send coins

Admin Commands
/am eco <give|take|set> <player> <amount> – Manage balances

Absolutely! Here's a clean and structured **Minecraft plugin wiki page** draft for your plugin **ArcaneMobs**, written in Markdown. It’s suitable for GitHub wikis, Modrinth, or SpigotMC documentation.

---

````markdown
# 🧙 ArcaneMobs Wiki

Welcome to the **ArcaneMobs** official wiki! This plugin brings RPG mechanics to Minecraft with dynamic mobs, player progression, quests, and a unique economy.

---

## 📦 Plugin Overview

**ArcaneMobs** is a powerful Minecraft plugin designed to enhance your server with:
- RPG-style leveling and skill trees
- Custom mobs that scale with player level
- An interactive quest system
- A virtual economy powered by Arcane Coins

> 🔄 Current Version: **Alpha**
>  
> 💬 [Join our Discord](https://your-discord-link.com) to report bugs, suggest features, or get help!

---

## 📈 Player Progression & Skills

Players earn XP by:
- Defeating ArcaneMobs
- Completing quests

As players level up, they gain **skill points** to allocate into:
- ⚔️ **Attack** – Increases damage dealt  
- 🛡️ **Defense** – Reduces damage received  
- 💪 **Strength** – Buffs overall combat performance  
- ❤️ **Health** – Increases max HP  

### Commands
- `/skills` – View current stats  
- `/skills spend <skill>` – Spend a skill point  

---

## 👾 ArcaneMobs System

ArcaneMobs are enhanced versions of vanilla mobs that dynamically scale based on nearby player levels. 

### Features:
- Custom **nameplates** showing mob level
- **Boss bars** with mob HP
- Level-scaled **damage, health, armor, and speed**
- Custom **glowing effects** and **particles**

### Configurable On-Hit Effects (Experimental)
Defined in `mobeffects.yml`:
```yml
Zombie:
  1-10:
    effect: POISON
    chance: 0.2
    duration: 60
    amplifier: 1
````

> *(Combat application coming soon)*

---

## 📜 Quest System

ArcaneMobs includes a full-featured questing system!

### Starting Quests:

Use `/quest` or `/quest list` to open the Quest GUI.

* Accept or abandon quests via the GUI
* Track objectives, rewards, and completion status

### Predefined Quests:

* Zombie Hunter
* Spider Slayer
* Witch Hunt
* Piglin Patrol
* ...and more!

Quests reward XP and **Arcane Coins**.

---

## 💰 Arcane Coin Economy

Arcane Coins are custom Gold Nuggets used as currency.

* Dropped by ArcaneMobs (scaled by mob level)
* Auto-converted into virtual balance on pickup

### Player Commands

* `/am balance` – Check your balance
* `/am pay <player> <amount>` – Send coins

### Admin Commands

* `/am eco <give|take|set> <player> <amount>` – Manage balances

---

## ⚙️ Admin Commands & Permissions

### Main Commands

```
/am help  
/am reload  
/am spawn  
/am dungeon  
```

### Permissions

* `arcanemobs.admin` – Access to all commands
* `arcanemobs.eco.admin` – Economy-specific commands

---

## 🔮 Roadmap

### Currently Implemented:

* ✅ Leveling & skills
* ✅ Dynamic mob scaling
* ✅ Quest system with GUI
* ✅ Coin-based economy

### In Progress / Planned:

* ⏳ Combat-triggered mob effects
* 🛍️ Arcane Coin shops
* 🧩 More quests, items, and mob types
* ⚙️ API optimization

