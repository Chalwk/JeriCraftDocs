# JeriCraft Factions Guide

Welcome to the **JeriCraft Factions System**! This guide will help you understand how to create and manage your faction,
claim land, build power, and raid enemy territories.

---

## 📜 Kingdom Management

> The foundation of any great empire begins with its creation. Establish your own faction, forge alliances, and carve
> your legacy into the lands of JeriCraft. A faction serves as your **kingdom**, a gathering of warriors, builders, and
> rulers under one banner.

| **Action**                  | **Command**        | **Description**                                                              |
|-----------------------------|--------------------|------------------------------------------------------------------------------|
| **Create a faction**        | `/f create <name>` | Establish your own kingdom and take the throne as its ruler.                 |
| **Rename your faction**     | `/f tag <name>`    | Change your kingdom’s official banner (name).                                |
| **View faction details**    | `/f show`          | Display a full overview of your kingdom, including members, power, and land. |
| **Inspect another faction** | `/f who <name>`    | Gather intelligence on another faction, including its members and power.     |
| **List all factions**       | `/f list`          | Discover all known kingdoms that roam these lands.                           |
| **Disband your faction**    | `/f disband`       | Dissolve your kingdom, scattering its people and relinquishing its lands.    |

> Once created, you become the **leader** of your faction, wielding the power to **expand your domain**,
> **recruit allies**, and **command your kingdom’s fate**. You can **manage your faction’s land, power, and members** to
> build an empire that stands the test of time.

---

## 📌 Claiming Land

> A kingdom is nothing without its territory! Factions must **claim land** to establish castles, villages, and
> fortifications.

| **Action**           | **Command**     | **Description**                                    |
|----------------------|-----------------|----------------------------------------------------|
| **Claim land**       | `/f claim`      | Seize control of a chunk of land for your kingdom. |
| **Unclaim land**     | `/f unclaim`    | Relinquish a previously claimed territory.         |
| **Unclaim all land** | `/f unclaimall` | Release all faction-owned land at once.            |

> Each chunk of land requires **power** to maintain, and you can only claim as much land as your
**faction’s total power allows**.

- Your **faction’s power** is determined by the number of members and their individual power levels.
- If a member dies, their power decreases, reducing your faction’s ability to claim land.
- Keep your kingdom strong by **recruiting more members** and **avoiding unnecessary deaths** in battle!

---

## 🏹 Membership & Ranks

> A kingdom thrives on its people! Recruit allies, build a loyal court, and manage your ranks wisely.

| **Action**               | **Command**            | **Description**                                   |
|--------------------------|------------------------|---------------------------------------------------|
| **Join a faction**       | `/f join <name>`       | Swear fealty to a faction and become its subject. |
| **Leave a faction**      | `/f leave`             | Renounce your oath and walk your own path.        |
| **Invite a player**      | `/f invite <player>`   | Extend an invitation to a worthy knight or ally.  |
| **Revoke an invitation** | `/f deinvite <player>` | Retract an invitation before it is accepted.      |
| **Kick a player**        | `/f kick <player>`     | Exile a member from your faction.                 |
| **Promote a player**     | `/f mod <player>`      | Elevate a member to a higher rank of leadership.  |

> As a ruler, it is your duty to **build trust** and **reward loyalty**. Strong factions are forged through camaraderie
> and strategy.

- More members mean **more power**, which allows your faction to **claim more land** and expand its influence.
- Grant **leadership roles** to trusted members to help you manage your growing kingdom.

---

## 🛡️ Communication

> A kingdom must have strong communication among its warriors. Use **faction chat** to strategize, plan attacks, and
> share your vision.

| **Action**       | **Command** | **Description**                            |
|------------------|-------------|--------------------------------------------|
| **Faction chat** | `/f chat`   | Speak privately in your kingdom’s council. |

> Stay connected with your knights and advisors to ensure the prosperity of your realm.

---

## ❓ Additional Help

If you ever need guidance, use these commands to **learn more about faction mechanics**.

| **Action**                | **Command**     | **Description**                              |
|---------------------------|-----------------|----------------------------------------------|
| **View faction commands** | `/f help`       | Show a list of faction-related commands.     |
| **View next help page**   | `/f help 2/3/4` | See additional faction commands and options. |

> May your kingdom rise to power, and may your banner be remembered for generations to come! 🏰

---

## ⚡ Power System

> Power determines how much land your faction can **claim** and **defend**.

- **Starting Power:** `0`
- **Maximum Power per Player:** `150`
- **Minimum Power per Player:** `-10`
- **Power Loss Per Death:** `1`
- **Power Regeneration Rate:** `0.2 per minute` (takes 5 minutes to regain 1 power)
- **Offline Power Loss:** `-1 per day`
- **Offline Power Regeneration:** ❌ *Disabled*
- **Max Faction Power:** Unlimited (0 means no cap, extra power acts as a buffer)

> You gain power over time while online, but **death and inactivity** will reduce it!

---

## ⚔️ Raiding & Warfare

> If your faction’s **claimed land exceeds its power**, **your land becomes vulnerable to raids**!

- **Raidability:** ✅ *Enabled*
- **Raid Triggers:** If a faction’s land is **greater than or equal to** their power.
- **WarZone & Wilderness Power Loss:** ✅ *Enabled* (You lose power when dying in warzones and wilderness.)
- **Power Stealing on Kill:** `50%` (Attackers gain half of the power lost by the victim.)

> Once raidable, **enemy factions can break blocks, loot chests, and take control of your land**! Be strategic and
> manage your faction’s power wisely.

---

## 🏰 Faction Commands Reference

| Command              | Description                                 |
|----------------------|---------------------------------------------|
| `/f create <name>`   | Create a faction                            |
| `/f invite <player>` | Invite a player to your faction             |
| `/f join <faction>`  | Join a faction                              |
| `/f leave`           | Leave your current faction                  |
| `/f disband`         | Disband your faction (leader only)          |
| `/f claim`           | Claim land for your faction                 |
| `/f unclaim`         | Unclaim the current land chunk              |
| `/f unclaimall`      | Unclaim all faction land                    |
| `/f power`           | View your power stats                       |
| `/f map`             | See the land claimed by factions around you |
| `/f top`             | View the top factions by power              |

---

## ⚠️ Tips for Survival

- **Keep your power high!** Avoid dying and stay online to regenerate power.
- **Don’t overclaim!** If your land exceeds your power, your faction can be raided.
- **Strategic alliances** can help protect your land from powerful enemies.
- **Set faction homes** (`/f sethome`) to quickly regroup with your allies.

---

## 🎨 Faction Colors and Relations

- **Faction Colors:**
    - **Safezone:** `GOLD`
    - **Warzone:** `DARK_RED`
    - **Wilderness:** `GRAY`
- **Relation Colors:**
    - **Ally:** `LIGHT_PURPLE`
    - **Enemy:** `RED`
    - **Member:** `GREEN`
    - **Neutral:** `WHITE`
    - **Peaceful:** `GOLD`
    - **Truce:** `DARK_PURPLE`

- The colors help identify faction territories and relationships at a glance.
- For example, if you see `DARK_RED`, you’re in a **Warzone**, where PvP is enabled and factions can raid each other.

---

## 💰 Economy and Faction Banks

- **Faction Bank:** Enabled
    - Factions can store money to pay for land claims and other costs.
    - Members with the `moderator` rank or higher can withdraw money.
- **Costs:**
    - **Create a Faction:** `$100`
    - **Claim Land:** `$30` per chunk
    - **~~Set Home~~:** `$30`
    - **~~Set Warp~~:** `$0` (free)
- Use the faction bank to pool resources and fund expansions.
- Be mindful of the costs associated with managing your faction.

---

## 🛡️ Protection and PvP

- **Safe Zones:**
    - No PvP or building allowed.
    - Protected from explosions and mob damage.
- **War Zones:**
    - PvP is always enabled.
    - No building or usage permissions for non-members.
- **Wilderness:**
    - No protections; players can build and PvP freely.
- Safe zones are ideal for new players or trading.
- War zones are high-risk areas for PvP and raiding.

---

## 🏠 Faction Homes and Warps

- **Faction Homes:**
    - Enabled
    - Must be set in claimed territory.
    - Players can teleport to the faction home using `/f home`.
- **Warps:**
    - Maximum of `5` warps per faction.
    - Warps can be set using `/f setwarp`.

**What Players Need to Know:**

- Set a faction home (`/f sethome`) to regroup quickly with allies.
- Use warps to create strategic locations for your faction.

---

## 🛠️ Advanced Features

- **TNT Banking:** Disabled
- **Portals:**
    - Portals can only be created in territory with a minimum relation of `MEMBER`.
- **Spawning:**
    - Certain mobs (e.g., hostile mobs) are prevented from spawning in safe zones and war zones.
- Use portals and spawning rules to your advantage when defending or raiding.

---

## 📊 Scoreboard and UI

- **Constant Scoreboard:** Enabled
    - Displays faction information, power, and territory status.
    - Updates in real-time as players move between territories.
- The scoreboard provides essential information about your faction and its status.

---

🛡️ **Defend your kingdom, forge alliances, and become the most powerful faction in JeriCraft!** 🏆