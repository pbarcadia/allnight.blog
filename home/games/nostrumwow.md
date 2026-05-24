---
title: Nostrum WoW
description: Some helpful things for Nostrum WoW
published: true
date: 2026-05-24T06:38:53.261Z
tags: game, mmo
editor: markdown
dateCreated: 2026-05-24T06:02:20.640Z
---

# ⚔️ NostrumWoW Connection, Media & UI Guide 🛡️
![logo.png](/img/nostrum/logo.png)

# 📺 **[PB Arcadia Live Stream](https://www.youtube.com/@PBQuest_)**

---

## 🌐 How to Connect to NostrumWoW 🧭

Jump into the realm. Follow these steps. Configure your game client.

1. **Visit the Official Website** 🏛️
* Go to [NostrumWoW](https://nostrumwow.com/).
* Register an account.

2. **Locate Your Realmlist File** 📁
* Open your main **World of Warcraft** folder.
* Go to `Data`. Then open `enUS`.

3. **Edit the Realmlist** ✍️
* Open `realmlist.wtf`.
* Use Notepad.
* Delete old lines.
* Add this official address:

```text
set realmlist logon.nostrumwow.com
```

* *Note: Getting a save error? Right-click the file. Click **Properties**. Uncheck **Read-only**. Save it again.*

4. **Launch the Game** 🎮
* Always use **Wow.exe**.
* Find it in your main folder.
* Do not use the Blizzard launcher. It will overwrite your files.

---

## 🎨 High-Definition Textures 🧊

Upgrade your graphics. Do this first. This pack adds modern resolutions. It upgrades Wrath models.

📦 **[Download the WotLK HD Texture Pack](https://bit.ly/3UxNLx6)**

*Installation: Extract the files. Put them in your WoW `Data` folder.*

---

## 🧩 Recommended Addons 🛠️

These work for Wrath of the Lich King. Get them from the main index. Visit [Warperia WotLK Addons](https://warperia.com/wotlk-addons/).

### 🎒 Personal Addon List

Here is my active addon list.

| Addon Name & Link | Description |
| :--- | :--- |
| 📖 [Ackis Recipe List](https://warperia.com/addon-wotlk/ackis-recipe-list/) | Scans professions. Lists missing recipes. Shows where to find them. |
| 💎 [AtlasLoot Enhanced](https://warperia.com/addon-wotlk/atlasloot-enhanced/) | Browse loot tables. Check dungeons and raids in-game. |
| 🪙 [Auctionator](https://warperia.com/addon-wotlk/auctionator/) | Fixes the Auction House. Makes posting items easy. Scans market prices fast. |
| 🍺 [Bartender 4](https://warperia.com/addon-wotlk/bartender-4/) | Replaces action bars. Gives layout control. Customizes keybindings. |
| 🗺️ [Carbonite](https://warperia.com/addon-wotlk/carbonite/) | Quest and map overhaul. Adds an alternate map. Shows fast leveling routes. |
| ⚔️ [Compact Nameplates](https://warperia.com/addon-wotlk/compact-nameplates/) | Replaces default nameplates. Uses clean bars. Improves combat visibility. |
| 📊 [Details! Damage Meter](https://warperia.com/addon-wotlk/details-damagemeter/) | Analyzes combat logs. Tracks DPS in real-time. Shows damage and healing. |
| ⏳ [Elkano's BuffBars](https://warperia.com/addon-wotlk/elkanos-buffbars/) | Replaces buff icons. Uses detailed progress bars. |
| 🟩 [Grid2](https://warperia.com/addon-wotlk/grid2/) | Grid-based unit frames. Great for healers. Shows health clearly. |
| ⏱️ [OmniCC](https://warperia.com/addon-wotlk/omnicc/) | Adds cooldown text. Numbers show on action bars. |
| 🔍 [pfQuest](https://warperia.com/addon-wotlk/pfquest/) | Lightweight quest helper. Includes an in-game database. |
| 💬 [Prat 3.0](https://warperia.com/addon-wotlk/prat/) | Chat frame addon. Adds custom colors. Shows timestamps. Copies URLs easily. |
| ❓ [Questie](https://warperia.com/addon-wotlk/questie/) | Puts quests on your map. Tracks leveling progress. |
| 🗑️ [Scrap](https://warperia.com/addon-wotlk/scrap/) | Sells grey junk automatically. Repairs gear at vendors. |
| ⚓ [Titan Panel](https://warperia.com/addon-wotlk/titanpanel/) | Adds a top info bar. Tracks gold and bag space. Shows XP and durability. |
| ✉️ [WoW Instant Messenger (WIM)](https://warperia.com/addon-wotlk/wowinstantmessenger/) | Isolates whispers. Uses clean pop-up windows. |
| 👤 [X-Perl UnitFrames](https://warperia.com/addon-wotlk/x-perlunitframes/) | Revamps unit frames. Adds 3D portraits. Shows clear health bars. |

### 🔄 Alternative UI

> **Note:** I do not use this. Many people love it. It is included here. ElvUI replaces many addons. It covers all the basics.

| Addon Name & Link | Description |
| :--- | :--- |
| 🖥️ [ElvUI](https://warperia.com/addon-wotlk/elvui/) | Total UI replacement. Overhauls action bars. Changes unit frames and bags. |

---

## ⚠️ Common Problems

### The Black Screen

**Problem:** The game blackscreens. This happens in windowed mode. It happens with desktop gamma. It stops when you press Esc.

**Fix:** Go to the game's `WTF` folder. Open `config.wtf` with Notepad. Add this line:
`SET gxWindow "1"`