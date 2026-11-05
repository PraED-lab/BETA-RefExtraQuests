# 🎯 BETA  Ref Extra Quests 1.4.0

**68 extra quests for Ref (the Arena trader) in SPT 4.1.x.** A long, level-gated quest line from level 10 to 50, with English and French texts.

![version](https://img.shields.io/badge/version-1.4.0-blue) ![SPT](https://img.shields.io/badge/SPT-4.1.x-green) ![license](https://img.shields.io/badge/license-MIT-lightgrey)

## ✨ What you get
- **68 quests** for Ref: the original 24-quest chain plus **44 new quests** added in 1.4.0.
- **Level 10 to 50.** The first quest is available from level 10, with no Ref prerequisite.
- **One quest line per map** (6 quests each): Customs, Woods, Shoreline, Reserve, Lighthouse and Streets of Tarkov. All lines unlock after the first quest, so you pick the order.
- **8 "special orders"** playable on any map: headshots, long-range kills (50 m+), night kills, repeated extractions and a grand finale.
- **Original chain** (24 quests): Scav, BEAR, USEC and PMC hunts, Ground Zero, Factory and Interchange, extractions.
- Rewards: XP, roubles, dollars or euros, GP coins and Ref reputation, scaled to the quest level.
- **English and French** quest texts.

## 📥 Installation
1. *(Recommended, not required)* Install the **Ref Friendly Quests** mod by acidphantasm (`acidphantasm-reffriendlyquests`): the two mods work well together.
2. **Back up your profile** (`SPT/user/profiles/<your_id>.json`).
3. Copy the `SPT_Runtime` folder from the zip into your SPT folder. It merges with the existing one: `SPT_Runtime/user/mods/RefExtraQuests/`.
4. Start the server. The log shows how many Ref quests were added.

**Update from 1.3.0 or earlier:** delete the old `RefExtraQuests` folder first, then copy the new one. Quest IDs of the original 24 quests are unchanged, so your progress stays valid.

> ⚠️ Once a quest is accepted it is saved in your profile. **Do not remove the mod afterwards.**

## 🆕 Changelog
**1.4.0**
- 44 new quests (Customs, Woods, Shoreline, Reserve, Lighthouse, Streets of Tarkov, special orders).
- First quest available from level 10 (was 15).
- Rouble rewards of the original quests halved.
- Plugin identifier changed to `com.praedlab.refextraquests`.

## ⚠️ Known limitations
- Made for **SPT 4.1.x** only.
- The new quests use standard kill, distance, headshot, night and extract conditions. If an objective never validates in your raid, please report it with the quest name.
- Map filters rely on the map IDs of SPT. A wrong ID would only affect which map the quest is listed under.

## 🐛 Bug or suggestion?
Open an **issue** with the quest name and your server log.

## 👤 Author and license
**PraED_TV** (PraED-lab) · MIT license.
Works great alongside the **Ref Friendly Quests** mod by acidphantasm (optional), all credit to its author.
