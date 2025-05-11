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
